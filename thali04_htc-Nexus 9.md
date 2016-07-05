#### Test 7214543196063dc_thali04_htc-Nexus 9 Logs


```
--------- beginning of main
07-05 14:04:16.656   994  1093 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-05 14:04:16.656   994  1093 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:04:17.119  2331  2331 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:04:17.123  2331  2331 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:17.155  2331  2331 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:04:17.189  2331  2331 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:04:17.213  2331  2331 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 14:04:17.218   534  1160 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:04:17.233  2331  2331 D AndroidRuntime: Shutting down VM
07-05 14:04:17.243  1078  1090 W SearchService: Abort, client detached.
07-05 14:04:17.258   534   552 I ActivityManager: Start proc 2340:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-05 14:04:17.258  1078  1297 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ef7bc67
07-05 14:04:17.259  1078  1311 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-05 14:04:17.258  1078  1078 I HotwordDetector: Closing mic
07-05 14:04:17.280   223   646 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-05 14:04:17.286  1078  1310 I MicroRecognitionRnrImpl: Detection finished
07-05 14:04:17.292  1078  1299 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-05 14:04:17.307  1078  1078 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-05 14:04:17.377  2340  2340 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-05 14:04:17.510  2340  2340 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-05 14:04:17.533  2340  2340 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 6161-6175)
,07-05 14:04:17.533  2340  2340 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:04:17.578  2340  2340 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bc49357}
07-05 14:04:17.579  2340  2340 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:17.579  2340  2340 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:17.584  2340  2340 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:17.585  2340  2340 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 14:04:17.615  2340  2356 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-05 14:04:17.622  2340  2340 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 14:04:17.641  2340  2340 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:17.641  2340  2340 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:17.905   534   577 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9fb386f:true
07-05 14:04:17.958  2340  2340 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 14:04:17.976  2340  2340 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
07-05 14:04:18.031  2340  2380 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-05 14:04:18.046  2340  2367 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-05 14:04:18.078  2340  2380 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:04:18.169   534   578 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +924ms
07-05 14:04:18.172   994   994 I Keyboard.Facilitator: onFinishInput()
07-05 14:04:18.238  2340  2340 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2340
07-05 14:04:18.250   534   755 I ActivityManager: Killing 2016:com.google.android.youtube/u0a81 (adj 15): empty #17
07-05 14:04:18.293   534   755 I ActivityManager: Killing 1967:com.google.android.gm.exchange/u0a70 (adj 15): empty #18
07-05 14:04:18.353  2340  2340 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-05 14:04:18.531  2340  2381 D jxcore_app_log: JniHelper::setJavaVM(0xab1847b8), pthread_self() = -557209296
07-05 14:04:18.539  2340  2381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:18.539  2340  2381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:18.539  2340  2381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:18.539  2340  2381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:18.539  2340  2381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 14:04:18.539  2340  2381 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d46687a added. We now have 1 listener(s)
07-05 14:04:18.545  2340  2381 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
07-05 14:04:18.547  2340  2381 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-05 14:04:18.547  2340  2381 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:04:18.548  2340  2381 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:18.550  2340  2381 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2179e21 added. We now have 1 listener(s)
07-05 14:04:18.550  2340  2381 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 14:04:18.555   534   665 D WifiService: New client listening to asynchronous messages
07-05 14:04:18.555  2340  2381 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:18.556  2340  2381 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-05 14:04:18.559  2340  2381 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 14:04:18.559  2340  2381 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 14:04:18.559  2340  2381 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 14:04:18.560  2340  2381 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-05 14:04:18.561  2340  2381 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 14:04:18.561  2340  2381 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
07-05 14:04:18.563  2340  2381 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:18.564  2340  2381 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:18.564  2340  2381 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:18.564  2340  2381 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 14:04:18.564  2340  2381 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 14:04:18.594  2340  2340 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:19.159  2340  2390 W jxcore-log: Initializing JXcore engine
,07-05 14:04:19.160  2340  2390 W jxcore-log: JXcore engine is ready
,07-05 14:04:19.206  2390  2390 W Thread-50: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9975 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-05 14:04:19.206  2390  2390 W Thread-50: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10620]" dev="sockfs" ino=10620 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 14:04:19.206  2390  2390 W Thread-50: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1032 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:04:19.206  2390  2390 W Thread-50: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17885]" dev="sockfs" ino=17885 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-05 14:04:19.219  2340  2390 W jxcore-log: Starting JXcore engine
,07-05 14:04:19.699   534  1243 I ActivityManager: Killing 1473:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,07-05 14:04:20.949  2340  2390 W jxcore-log: Platform android
07-05 14:04:20.949  2340  2390 W jxcore-log: 
,07-05 14:04:20.950  2340  2390 W jxcore-log: Process ARCH arm
07-05 14:04:20.950  2340  2390 W jxcore-log: 
,07-05 14:04:21.083  2340  2390 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:21.083  2340  2390 I jxcore-log: 
,07-05 14:04:21.084  2340  2390 W jxcore-log: JXcore engine is started
,07-05 14:04:21.090  2340  2381 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:04:21.092  2340  2340 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:21.735  1095  1095 I ConfigService: onDestroy
,07-05 14:04:26.489  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:26.489  2340  2390 I jxcore-log: 
,07-05 14:04:26.492  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:26.492  2340  2390 I jxcore-log: 
,07-05 14:04:26.493  2340  2390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:26.493  2340  2390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:26.493  2340  2390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:04:26.493  2340  2390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-05 14:04:26.495  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:26.495  2340  2390 I jxcore-log: 
,07-05 14:04:26.496  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:26.496  2340  2390 I jxcore-log: 
,07-05 14:04:27.730  2340  2390 I jxcore-log: Unit Test app is loaded
07-05 14:04:27.730  2340  2390 I jxcore-log: 
,07-05 14:04:27.737  2340  2340 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:27.738  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-05 14:04:27.738  2340  2390 I jxcore-log: 
,07-05 14:04:27.777   534  1160 D WifiService: setWifiEnabled: true pid=2340, uid=10000
,07-05 14:04:27.777   534  1160 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-05 14:04:27.792   219   635 D SoftapController: Softap fwReload - Ok
,07-05 14:04:27.829  2340  2390 I jxcore-log: My device name is: htc-Nexus 9
07-05 14:04:27.829  2340  2390 I jxcore-log: 
,07-05 14:04:27.834   534   577 I ActivityManager: Start proc 2415:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-05 14:04:27.858   219   635 D CommandListener: Setting iface cfg
07-05 14:04:27.859   219   635 D CommandListener: Trying to bring down wlan0
,07-05 14:04:27.860   219   635 D CommandListener: Clearing all IP addresses on wlan0
,07-05 14:04:27.862   534   664 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-05 14:04:27.970  2415  2415 D AdapterServiceConfig: Adding HeadsetService
,07-05 14:04:27.971  2415  2415 D AdapterServiceConfig: Adding A2dpService
,07-05 14:04:27.971  2415  2415 D AdapterServiceConfig: Adding HidService
07-05 14:04:27.971  2415  2415 D AdapterServiceConfig: Adding HealthService
07-05 14:04:27.971  2415  2415 D AdapterServiceConfig: Adding PanService
07-05 14:04:27.971  2415  2415 D AdapterServiceConfig: Adding GattService
,07-05 14:04:28.013   534   577 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad745ba:true
,07-05 14:04:28.016  2415  2415 D BluetoothAdapterState: make() - Creating AdapterState
,07-05 14:04:28.032  2415  2415 I bt_bluedroid: init
,07-05 14:04:28.032  2415  2429 I BluetoothAdapterState: Entering OffState
,07-05 14:04:28.048  2415  2430 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-05 14:04:28.050  2415  2430 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-05 14:04:28.051  2415  2430 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-05 14:04:28.051  2415  2430 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-05 14:04:28.053  2415  2415 I bt_bluedroid: get_profile_interface socket
,07-05 14:04:28.054  2415  2415 I bt_bluedroid: get_profile_interface sdp
,07-05 14:04:28.058  2415  2426 I bt_bluedroid: config_hci_snoop_log
,07-05 14:04:28.061  2415  2433 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-05 14:04:28.063  2415  2433 D BluetoothAdapterProperties: Name is: Nexus 9
07-05 14:04:28.063   534   577 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-05 14:04:28.066  2415  2429 D BluetoothAdapterState: Current state: OFF, message: 0
07-05 14:04:28.066  2415  2429 D BluetoothAdapterProperties: Setting state to 14
07-05 14:04:28.066  2415  2429 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-05 14:04:28.067  2415  2429 D BluetoothBondStateMachine: make
,07-05 14:04:28.072  2415  2415 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-05 14:04:28.077  2415  2429 I BluetoothAdapterState: Entering PendingCommandState
,07-05 14:04:28.077  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
,07-05 14:04:28.077  2415  2435 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-05 14:04:28.077  2415  2415 D BtGatt.DebugUtils: handleDebugAction() action=null
07-05 14:04:28.078  2415  2415 D BtGatt.GattService: Received start request. Starting profile...
07-05 14:04:28.078  2415  2415 D BtGatt.GattService: start()
,07-05 14:04:28.078  2415  2415 I bt_bluedroid: get_profile_interface gatt
,07-05 14:04:28.078  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
07-05 14:04:28.078  2415  2415 D BtGatt.AdvertiseManager: advertise manager created
07-05 14:04:28.083  2415  2415 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:28.083  2415  2415 V BluetoothAdapterState: isTurningOn()=false
07-05 14:04:28.083  2415  2415 V BluetoothAdapterState: isBleTurningOn()=true
,07-05 14:04:28.083  2415  2415 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:28.084  2415  2429 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-05 14:04:28.084  2415  2429 I bt_bluedroid: enable
,07-05 14:04:28.084  2415  2430 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-05 14:04:28.084  2415  2430 I bt_hci  : start_up
07-05 14:04:28.091  2415  2430 I bt_vendor: alloc value 0xf3fd0889
,07-05 14:04:28.091  2415  2430 I bt_vendor: init
,07-05 14:04:28.091  2415  2430 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-05 14:04:28.297  2415  2430 D bt_hci  : start_up starting async portion
,07-05 14:04:28.297  2415  2439 I bt_hci  : event_finish_startup
,07-05 14:04:28.297  2415  2439 I bt_hci_h4: hal_open
07-05 14:04:28.297  2415  2439 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
07-05 14:04:28.299  2415  2439 I bt_userial_vendor: device fd = 49 open
,07-05 14:04:28.311  2415  2439 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-05 14:04:28.343  2415  2439 D bt_hwcfg: Chipset BCM4350C0
07-05 14:04:28.343  2415  2439 D bt_hwcfg: Target name = [BCM4350C0]
07-05 14:04:28.343  2415  2439 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-05 14:04:28.617   534   664 D wifi    : set interface wlan0 flags (UP)
,07-05 14:04:28.617   534   664 I WifiHAL : Initializing wifi
,07-05 14:04:28.617   534   664 I WifiHAL : Creating socket
,07-05 14:04:28.624   534   664 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-05 14:04:28.624   534   664 D wifi    : Did set static halHandle = 0x558c9905f0
07-05 14:04:28.624   534   664 D wifi    : halHandle = 0x558c9905f0, mVM = 0x558c0c6c30, mCls = 0x1014fa
07-05 14:04:28.624   534   664 D wifi    : array field set
07-05 14:04:28.625   534   664 I WifiNative-HAL: interface[0] = wlan0
07-05 14:04:28.629   534  2443 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=367431058928
07-05 14:04:28.629   534  2443 D wifi    : waitForHalEvents called, vm = 0x558c0c6c30, obj = 0x1014fa, env = 0x558c379640
,07-05 14:04:28.631   534   664 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-05 14:04:28.633   534   664 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-05 14:04:28.634  2340  2340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:28.642   534   567 I ActivityManager: Start proc 2445:com.google.android.apps.gcs/u0a83 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
07-05 14:04:28.754  2444  2444 I wpa_supplicant: Successfully initialized wpa_supplicant
07-05 14:04:28.833  2444  2444 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-05 14:04:28.878  2415  2439 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-05 14:04:28.878  2415  2439 D bt_hwcfg: Settlement delay -- 100 ms
07-05 14:04:28.878  2415  2439 I bt_hwcfg: Setting fw settlement delay to 100 
07-05 14:04:28.888  2445  2445 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
07-05 14:04:28.923  2445  2445 W InstanceID/Rpc: Found 10007
07-05 14:04:28.933  2445  2445 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-05 14:04:28.985  2415  2439 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-05 14:04:28.985  2415  2439 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-05 14:04:28.995  2444  2444 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-05 14:04:28.996  2444  2444 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-05 14:04:29.011  2415  2439 I bt_hwcfg: vendor lib fwcfg completed
,07-05 14:04:29.011  2415  2439 I bt_vendor: firmware callback
,07-05 14:04:29.011  2415  2439 I bt_hci  : firmware_config_callback
,07-05 14:04:29.014  2415  2471 I bt_btu  : btu_task pending for preload complete event
,07-05 14:04:29.014  2415  2471 I bt_btu_task: Bluetooth chip preload is complete
,07-05 14:04:29.014  2415  2471 I bt_btu  : btu_task received preload complete event
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_HCI
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_AVDT
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_AVRC
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_A2D
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_BNEP
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_BTM
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_GAP
,07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_PAN
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_SDP
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_GATT
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_SMP
,07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-05 14:04:29.017  2415  2471 I         : BTE_InitTraceLevels -- TRC_BTIF
07-05 14:04:29.049  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:29.053  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:29.055  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:29.069  1095  1105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-05 14:04:29.069  1095  1105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:04:29.069  1095  1105 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:29.069  1095  1105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:29.080  1715  1715 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:04:29.080  1715  1715 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:04:29.080  1715  1715 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-05 14:04:29.094   534  1163 I ActivityManager: Killing 1803:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-05 14:04:29.229  2415  2471 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f4ea31
,07-05 14:04:29.230  2415  2471 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f4ea31 
07-05 14:04:29.341  2415  2433 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
07-05 14:04:29.354  2415  2433 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-05 14:04:29.354  2415  2433 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-05 14:04:29.355  2415  2433 D BluetoothAdapterProperties: Name is: Nexus 9
07-05 14:04:29.356  2415  2433 D BluetoothAdapterProperties: Scan Mode:20
07-05 14:04:29.356  2415  2433 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:29.356  2415  2433 D bt_hci  : do_postload posting postload work item
07-05 14:04:29.356  2415  2439 I bt_hci  : event_postload
07-05 14:04:29.356  2415  2439 I bt_vendor: sco_config_cb
,07-05 14:04:29.356  2415  2439 I bt_hci  : sco_config_callback postload finished.
07-05 14:04:29.357  2340  2340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:29.361  2415  2433 D bt_bte_conf: Device ID record 1 : primary
07-05 14:04:29.361  2415  2433 D bt_bte_conf:   vendorId            = 000f
07-05 14:04:29.361  2415  2433 D bt_bte_conf:   vendorIdSource      = 0001
07-05 14:04:29.362  2415  2433 D bt_bte_conf:   product             = 1200
,07-05 14:04:29.362  2415  2433 D bt_bte_conf:   version             = 1436
07-05 14:04:29.362  2415  2433 D bt_bte_conf:   clientExecutableURL = 
07-05 14:04:29.362  2415  2433 D bt_bte_conf:   serviceDescription  = 
07-05 14:04:29.362  2415  2433 D bt_bte_conf:   documentationURL    = 
07-05 14:04:29.362  2415  2433 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-05 14:04:29.362  2415  2430 D bt_stack_manager: event_start_up_stack finished
07-05 14:04:29.362  2415  2429 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-05 14:04:29.362  2415  2429 D BluetoothAdapterProperties: Setting state to 15
07-05 14:04:29.362  2415  2429 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-05 14:04:29.363  2415  2429 I BluetoothAdapterState: Entering BleOnState
07-05 14:04:29.367  2415  2429 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-05 14:04:29.367  2415  2429 D BluetoothAdapterProperties: Setting state to 11
,07-05 14:04:29.367  2415  2429 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-05 14:04:29.370  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
,07-05 14:04:29.377  2415  2439 I bt_vendor: low_power_mode_cb
,07-05 14:04:29.381  2415  2415 D HeadsetService: Received start request. Starting profile...
07-05 14:04:29.384   534   567 I ActivityManager: Start proc 2477:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-05 14:04:29.388  2415  2429 I BluetoothAdapterState: Entering PendingCommandState
07-05 14:04:29.389  2415  2415 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-05 14:04:29.389  2415  2415 D HeadsetStateMachine: make
07-05 14:04:29.404  2415  2415 D HeadsetStateMachine: max_hf_connections = 1
07-05 14:04:29.405  2415  2415 I bt_bluedroid: get_profile_interface handsfree
07-05 14:04:29.405  2415  2433 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-05 14:04:29.405  2415  2433 E bt_btif : btif_hf_upstreams_evt: Invalid index 28520
07-05 14:04:29.407  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
07-05 14:04:29.407   534   534 D BluetoothA2dp: Proxy object connected
,07-05 14:04:29.409  2415  2415 D A2dpService: Received start request. Starting profile...
07-05 14:04:29.409  2415  2415 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-05 14:04:29.409  2415  2415 I bt_bluedroid: get_profile_interface avrcp
,07-05 14:04:29.444  2415  2415 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-05 14:04:29.444  2415  2415 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-05 14:04:29.444  2415  2415 D A2dpStateMachine: make
,07-05 14:04:29.445  2415  2415 I bt_bluedroid: get_profile_interface a2dp
07-05 14:04:29.446  2415  2433 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-05 14:04:29.461  2415  2415 I BluetoothHidServiceJni: classInitNative: succeeds
,07-05 14:04:29.462  2415  2491 D A2dpStateMachine: Enter Disconnected: -2
07-05 14:04:29.464  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
07-05 14:04:29.465   716   716 D BluetoothInputDevice: Proxy object connected
,07-05 14:04:29.465  2415  2415 D HidService: Received start request. Starting profile...
07-05 14:04:29.465  2415  2415 I bt_bluedroid: get_profile_interface hidhost
07-05 14:04:29.465  2415  2415 D HidService: setHidService(): set to: null
07-05 14:04:29.465  2415  2433 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f30099
07-05 14:04:29.465  2415  2433 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-05 14:04:29.466  2415  2415 I BluetoothHealthServiceJni: classInitNative: succeeds
07-05 14:04:29.467  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
07-05 14:04:29.468  2415  2415 D HealthService: Received start request. Starting profile...
07-05 14:04:29.470  2415  2415 I bt_bluedroid: get_profile_interface health
07-05 14:04:29.470  2415  2415 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-05 14:04:29.471  2415  2415 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@628fd29
07-05 14:04:29.473  2415  2415 D PanService: Received start request. Starting profile...
07-05 14:04:29.473  2415  2415 D BluetoothPanServiceJni: initializeNative(L110): pan
07-05 14:04:29.473  2415  2415 I bt_bluedroid: get_profile_interface pan
07-05 14:04:29.473  2415  2433 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-05 14:04:29.502   716   716 D HidProfile: Bluetooth service connected
07-05 14:04:29.504   716   716 D BluetoothPan: BluetoothPAN Proxy object connected
07-05 14:04:29.504   716   716 D PanProfile: Bluetooth service connected
07-05 14:04:29.548  2415  2415 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:29.548  2415  2415 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:29.548  2415  2415 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:29.548  2415  2415 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:29.548  2415  2482 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:29.549  2415  2415 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:29.550  2415  2415 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:29.550  2415  2415 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:29.550  2415  2415 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:29.550  2415  2429 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-05 14:04:29.550  2415  2429 D BluetoothAdapterProperties: ScanMode =  20
07-05 14:04:29.550  2415  2429 D BluetoothAdapterProperties: State =  11
07-05 14:04:29.550  2415  2429 D BluetoothAdapterProperties: Setting state to 12
07-05 14:04:29.550  2415  2429 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-05 14:04:29.551   716   728 D BluetoothPan: onBluetoothStateChange on: true
07-05 14:04:29.552  2340  2340 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 14:04:29.554  2415  2433 D BluetoothAdapterProperties: Scan Mode:21
07-05 14:04:29.554  2415  2433 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:29.555   534   577 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:29.555   534   577 D BluetoothA2dp: onBluetoothStateChange: up=true
07-05 14:04:29.556  1026  1038 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:29.557  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:29.558  2340  2340 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:29.558  2415  2429 I BluetoothAdapterState: Entering OnState
07-05 14:04:29.559   716  1076 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-05 14:04:29.559   716   908 D BluetoothPbap: onBluetoothStateChange: up=true
07-05 14:04:29.560   716   903 D BluetoothMap: onBluetoothStateChange: up=true
07-05 14:04:29.560   716   903 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-05 14:04:29.560   534   577 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:29.560   534   577 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:29.562   534   534 I Telecom : BluetoothPhoneService: queryPhoneState
,07-05 14:04:29.577   716   930 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-05 14:04:29.596   716   716 D BluetoothA2dp: Proxy object connected
,07-05 14:04:29.596   716   930 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-05 14:04:29.600  2477  2477 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:29.656  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-05 14:04:29.656   534   577 D BluetoothHeadset: Proxy object connected
,07-05 14:04:29.657  2340  2340 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:29.659  1026  1046 D BluetoothHeadset: Proxy object connected
07-05 14:04:29.659   534   664 D WifiConfigStore: Loading config and enabling all networks 
07-05 14:04:29.661   534   577 D BluetoothHeadset: Proxy object connected
07-05 14:04:29.661   534   577 D BluetoothHeadset: Proxy object connected
07-05 14:04:29.676   534   552 I ActivityManager: Killing 1943:com.google.android.gm/u0a71 (adj 15): empty #17
,07-05 14:04:29.709  1095  1095 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:29.720   716   903 D BluetoothHeadset: Proxy object connected
,07-05 14:04:29.721   716   716 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:29.723   534   664 D WifiConfigStore: loaded 0 passpoint configs
07-05 14:04:29.726   534  1148 I ActivityManager: Start proc 2500:com.google.android.apps.maps/u0a60 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
07-05 14:04:29.728   534   664 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-05 14:04:29.729   534   664 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-05 14:04:29.729   534   664 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-05 14:04:29.730   534   664 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-05 14:04:29.730   534   664 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-05 14:04:29.730   534   664 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-05 14:04:29.735  1537  1537 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:04:29.736   534   664 D WifiNative-HAL: Setting external_sim to 1
,07-05 14:04:29.737   534   664 D wifi    : setting dfs flag to true, 0x558c98ec20
07-05 14:04:29.738   534   664 D WifiStateMachine: Setting OUI to DA-A1-19
07-05 14:04:29.738   534   664 D wifi    : setting scan oui 0x558c98ec20
,07-05 14:04:29.739   534   664 D WifiHAL : Sending mac address OUI
,07-05 14:04:29.760   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:29.763   534   534 D RttService: SCAN_AVAILABLE : 3
07-05 14:04:29.764   534   679 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-05 14:04:29.764   219   635 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
07-05 14:04:29.764   534   664 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-05 14:04:29.765   219   635 D CommandListener: Setting iface cfg
07-05 14:04:29.766   534   663 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '29 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 29 Failed to set address (No such device)'
07-05 14:04:29.766   534   663 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-05 14:04:29.770   534   663 D WifiNative-HAL: p2pGetDeviceAddress
07-05 14:04:29.771   534   663 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-05 14:04:29.795   534   664 E native  : do suspend false,
,07-05 14:04:29.801   534   664 D WifiConfigStore: No blacklist allowed without epno enabled,
07-05 14:04:29.802   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:29.829  2500  2500 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.e.b(PG:170)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.k.d(PG:583)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.e.b(PG:170)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=38 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=37 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.940  2500  2500 D StrictMode: StrictMode policy violation; ~duration=37 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:29.940  2500  2500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:29.951  2477  2477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-05 14:04:29.960  1095  1095 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-05 14:04:29.966   716   716 D BluetoothPbap: Proxy object connected
07-05 14:04:29.967   716   716 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:29.983   534   577 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba63c7a:true
,07-05 14:04:29.985  2415  2526 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:29.995  2415  2530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-05 14:04:30.001  2415  2530 I BtOppRfcommListener: Accept thread started.
,07-05 14:04:30.089  2477  2477 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-05 14:04:30.093  2477  2477 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-05 14:04:30.102  2477  2477 D LocalBluetoothProfileManager: Adding local MAP profile
,07-05 14:04:30.103  2477  2477 D BluetoothMap: Create BluetoothMap proxy object
,07-05 14:04:30.104  2477  2477 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-05 14:04:30.108  2477  2477 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-05 14:04:30.113  2477  2477 D DockEventReceiver: finishStartingService: stopping service
,07-05 14:04:30.115  2477  2477 D BluetoothA2dp: Proxy object connected
,07-05 14:04:30.118  2477  2477 D BluetoothInputDevice: Proxy object connected
,07-05 14:04:30.119  2477  2477 D HidProfile: Bluetooth service connected
,07-05 14:04:30.124  2477  2477 D BluetoothPan: BluetoothPAN Proxy object connected
,07-05 14:04:30.125  2477  2477 D PanProfile: Bluetooth service connected
,07-05 14:04:30.125  2477  2477 D BluetoothPbap: Proxy object connected
,07-05 14:04:30.126  2477  2477 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:30.128   534  1160 I ActivityManager: Killing 2097:com.google.android.music:main/u0a61 (adj 15): empty #17
,07-05 14:04:30.196  2477  2490 D BluetoothHeadset: Proxy object connected
,07-05 14:04:30.197  2477  2477 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:30.275  2500  2516 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:30.298   534   577 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f0da501:true
,07-05 14:04:30.540   534   664 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-05 14:04:30.543   534   664 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-05 14:04:30.543   534   664 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:30.551   534   664 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-05 14:04:30.608   534   664 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-05 14:04:30.609  2444  2444 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-05 14:04:31.030  2444  2444 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-05 14:04:31.044  2444  2444 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-05 14:04:31.044  2444  2444 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-05 14:04:31.046   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:31.055   534   664 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-05 14:04:31.055   534   664 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-05 14:04:31.056   534   666 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-05 14:04:31.065   534   664 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:31.076   219   635 D CommandListener: Setting iface cfg
,07-05 14:04:31.080   534   664 D WifiStateMachine: Start Dhcp Watchdog 1
,07-05 14:04:31.091   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:31.091   534   666 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,07-05 14:04:31.092   534   664 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-05 14:04:31.100   534  2541 D DhcpClient: Receive thread started
,07-05 14:04:31.177   534   664 E native  : do suspend false
,07-05 14:04:31.185   534  2540 D DhcpClient: Broadcasting DHCPDISCOVER
,07-05 14:04:32.869  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:32.869  2340  2390 I jxcore-log: 
,07-05 14:04:32.950   534  2541 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,07-05 14:04:32.953   534  2540 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-05 14:04:32.954   534  2540 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-05 14:04:32.961   534  2541 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-05 14:04:32.963   534  2540 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-05 14:04:32.964   219   635 D CommandListener: Setting iface cfg
,07-05 14:04:32.966   534   664 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
,07-05 14:04:32.969   534  2540 D DhcpClient: Scheduling renewal in 86399s
,07-05 14:04:32.976   534   664 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-05 14:04:32.977   534   664 D WifiConfigStore: No blacklist allowed without epno enabled
07-05 14:04:32.977   534   666 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-05 14:04:32.978   534   666 D ConnectivityService: Adding iface wlan0 to network 100
07-05 14:04:32.983   534   664 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-05 14:04:33.024   534   666 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-05 14:04:33.024   534   666 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-05 14:04:33.026   534   666 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,07-05 14:04:33.027   534   666 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-05 14:04:33.029   534   666 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-05 14:04:33.044   534   666 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:33.047   534   666 D ConnectivityService: scheduleUnvalidatedPrompt 100
,07-05 14:04:33.048   534   666 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-05 14:04:33.048   534   666 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:33.048   534   666 D ConnectivityService:    accepting network in place of null
07-05 14:04:33.048   534   664 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-05 14:04:33.049   534   664 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-05 14:04:33.049   534   666 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-05 14:04:33.061   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=101703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:04:33.088   219   635 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:04:33.120  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:33.120  2340  2390 I jxcore-log: 
07-05 14:04:33.121   219   635 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:04:33.124   534   666 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,07-05 14:04:33.132   534  2538 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:814::200e
,07-05 14:04:33.135   534   666 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-05 14:04:33.141   534   666 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-05 14:04:33.142   534   577 D Tethering: MasterInitialState.processMessage what=3
,07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:33.147  2340  2340 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 14:04:33.149  2340  2340 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:33.152   534   666 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:33.199   534  1011 D AlarmManagerService: Setting time of day to sec=1467720269
,07-05 14:04:29.710   534  2538 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jul 2016 12:04:29 GMT], X-Android-Received-Millis=[1467720269691], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467720273189]}
07-05 14:04:29.712   534   666 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-05 14:04:29.712   534   666 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-05 14:04:29.712   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:29.713   534   666 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-05 14:04:29.728   534   766 I ActivityManager: Start proc 2560:com.google.android.youtube/u0a81 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:04:29.744  1078  1078 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-05 14:04:29.794  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:29.794  2340  2390 I jxcore-log: 
,07-05 14:04:29.801  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:29.801  2340  2390 I jxcore-log: 
,07-05 14:04:29.805  2560  2560 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,07-05 14:04:29.821  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:29.821  2340  2390 I jxcore-log: 
,07-05 14:04:29.830  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:29.830  2340  2390 I jxcore-log: 
,07-05 14:04:29.909  1223  2573 I CheckinService: Checking schedule, now: 1467720269909 next: 1467314901924
07-05 14:04:29.909  1223  2573 I CheckinService: active receiver: enabled
,07-05 14:04:29.936  2560  2577 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:29.942  1223  2573 I CheckinService: Preparing to send checkin request
,07-05 14:04:30.038  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,07-05 14:04:30.038  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud.
07-05 14:04:30.038  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:30.038  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:30.049  1223  2579 I GcmGroups: Failed to subscribe to group.
07-05 14:04:30.049  1223  2579 I GcmGroups: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:350)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:444)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:334)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:241)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:48)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:30.049  1223  2579 I GcmGroups: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:30.051  1223  2579 I GcmGroups: Groups upload failed, retrying in 24000:00:00
07-05 14:04:30.063  2560  2577 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
07-05 14:04:30.092  2560  2577 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:30.140  1223  1223 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-05 14:04:30.141  1223  1223 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-05 14:04:30.153  1223  2593 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
07-05 14:04:30.153  1223  2593 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:04:30.161  1223  2593 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
07-05 14:04:30.162  1223  1223 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-05 14:04:30.164  1223  1223 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-05 14:04:30.175   534  1160 I ActivityManager: Start proc 2598:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-05 14:04:30.205  2560  2560 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 14:04:30.228  1223  2595 I iu.SyncManager: SYNC; picasa accounts
,07-05 14:04:29.942  1223  2573 I EventLogService: Accumulating logs since 1467719152260
,07-05 14:04:30.261  2445  2454 W art     : Suspending all threads took: 6.232ms
,07-05 14:04:30.322  1223  2595 I iu.UploadsManager: num queued entries: 0
,07-05 14:04:30.397   534   565 I UsageStatsService: Time changed in UsageStats by -3 seconds
07-05 14:04:30.397   534   565 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:04:30.398  1223  2595 I iu.UploadsManager: num updated entries: 0
,07-05 14:04:30.450  2445  2574 V GoogleAuthProtoRequest: [214] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:04:30.468  1223  2595 I iu.SyncManager: NEXT; no task
,07-05 14:04:30.483  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-05 14:04:30.488  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,07-05 14:04:30.533  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:30.534  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:30.554  1095  2627 I GCM     : Ack for not saved message 122
07-05 14:04:30.564  2560  2560 W InstanceID/Rpc: Found 10007
,07-05 14:04:30.574   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:30.601   737  2622 D DownloadManager: [114] Starting
,07-05 14:04:30.611  1223  2593 E MDM     : [173] SitrepService.a: Error sending sitrep.
,07-05 14:04:30.626   737  2622 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 14:04:30.627  1095  1105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:04:30.629  1095  1105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-05 14:04:30.629  1095  1105 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:30.629  1095  1105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: [214] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: [214] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:04:30.646  2445  2574 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:04:30.734  2560  2640 W YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1035 Unknown task tag innertube_config_fetch_charging; aborting...
,07-05 14:04:30.754   534  1243 I ActivityManager: Start proc 2659:com.google.android.apps.magazines/u0a62 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-05 14:04:30.766  1095  2627 I GCM     : GCM message com.google.android.gms 0:1467616626996379%136ddda6f9fd7ecd
,07-05 14:04:30.794  1095  2627 I GCM     : GCM message com.google.android.gms 0:1467620259860159%136ddda6f9fd7ecd
,07-05 14:04:30.845  1223  2592 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:04:30.943  1537  2664 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-05 14:04:30.963  1223  2573 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:04:30.985   534   665 D WifiService: New client listening to asynchronous messages
,07-05 14:04:30.987  1223  2573 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 14:04:31.006   534   755 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1223 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:04:31.113  1223  2621 W DriveInitializer: Awaiting to be initialized
,07-05 14:04:31.122  1223  2689 W DriveInitializer: Background init thread started
,07-05 14:04:31.154  2659  2659 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm64
,07-05 14:04:31.173  2675  2675 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads877340184.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads877340184.dex
,07-05 14:04:31.254  1223  2623 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:04:31.360  2675  2675 I dex2oat : dex2oat took 214.347ms (threads: 2) arena alloc=170KB java alloc=33KB native alloc=758KB free=65KB
,07-05 14:04:31.454  1223  2689 W DriveInitializer: Background init thread ended
,07-05 14:04:31.559   737  2622 D DownloadManager: [114] Finished with status SUCCESS
,07-05 14:04:31.606  2659  2659 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-05 14:04:31.606  2659  2659 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:31.606  2659  2659 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:31.617  2659  2659 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:31.625  2659  2659 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:31.641  2659  2715 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:31.712   534   565 I UsageStatsDatabase: Time changed by -3s522ms. files deleted: 0 files moved: 33
,07-05 14:04:31.718   534   565 I UsageStatsService: User[0] Rollover scheduled @ 2016-07-06 02:00:00(1467763200000)
,07-05 14:04:31.856  2659  2659 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-05 14:04:31.879  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-05 14:04:31.879  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-05 14:04:31.879  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:31.879  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:31.973  2659  2659 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-05 14:04:31.978  1223  2573 W CheckinRequestBuilder: awaiting user notification for token
,07-05 14:04:31.986  2659  2659 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4148-4150)
,07-05 14:04:31.987  2659  2659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:04:32.019   534  2736 D GpsLocationProvider: NTP server returned: 1467720269678 (Tue Jul 05 14:04:29 GMT+02:00 2016) reference: 101841 certainty: 7 system time offset: -2339
,07-05 14:04:32.028  2659  2659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ecda458}
,07-05 14:04:32.037  2659  2659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:04:32.041  1223  2735 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,07-05 14:04:32.075  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:32.092  2659  2659 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 14:04:32.096  2659  2659 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 14:04:32.107  2659  2659 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 14:04:32.142   534  1575 D libgps  : proxy_gps_xtra_inject_xtra_data: called.
,07-05 14:04:32.142   231   231 D gpsd    : WakeLock(Acquire,GPSD)
,07-05 14:04:32.158   231   231 D gpsd    : WakeLock(Release,GPSD)
,07-05 14:04:32.257   534  1163 I ActivityManager: Start proc 2745:com.google.android.gms.unstable/u0a7 for service com.google.android.gms/.droidguard.DroidGuardService
,07-05 14:04:32.300   231   231 D gpsd    : WakeLock(Acquire,GPSD)
,07-05 14:04:32.300   231   231 D gpsd    : WakeLock(Release,GPSD)
,07-05 14:04:32.324  2659  2659 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 14:04:32.332  2659  2659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 14:04:32.332  2659  2659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 14:04:32.368  2745  2745 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:32.415  2745  2745 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:04:32.415  2745  2745 I MultiDex: install
07-05 14:04:32.415  2745  2745 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:32.483  1223  2623 I PeopleSync: Setting subscription: result=true [5005f081]
,07-05 14:04:32.517  1223  2623 I PeopleSync: Starting sync, feed=null [5005f081]
,07-05 14:04:32.521  2745  2745 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:32.594  2745  2745 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:32.603  2659  2771 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-05 14:04:32.689  2659  2659 I NSApplication: Starting up...
,07-05 14:04:32.719   534   755 I ActivityManager: Start proc 2778:com.google.android.apps.photos/u0a66 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-05 14:04:32.720   534   755 I ActivityManager: Killing 1594:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-05 14:04:32.734   223   886 D WVCdm   : Instantiating CDM.
,07-05 14:04:32.736   223   223 I WVCdm   : CdmEngine::OpenSession
,07-05 14:04:32.737   223   223 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:04:32.743   223   223 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:04:32.744   223   223 D oemcrypto_cenc: >> OEMCrypto_Initialize: modular drm 5.00  Jul 20 2015  05:40:21
,07-05 14:04:32.746   223   223 D oemcrypto_cenc: << OEMCrypto_Initialize
,07-05 14:04:32.746   223   223 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-05 14:04:32.747   223   223 D oemcrypto_cenc: >> OEMCrypto_IsKeyboxValid
07-05 14:04:32.747   223   223 D oemcrypto_cenc: << OEMCrypto_IsKeyboxValid
,07-05 14:04:32.747   223   223 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:32.747   223   223 D oemcrypto_cenc: >> OEMCrypto_OpenSession
07-05 14:04:32.747   223   223 D oemcrypto_cenc: bool AddSessionHandle(OEMCrypto_SESSION): session:0xabcc3b20, status: 1
07-05 14:04:32.747   223   223 D oemcrypto_cenc: << OEMCrypto_OpenSession
07-05 14:04:32.747   223   223 D oemcrypto_cenc: >> OEMCrypto_GetRandom
,07-05 14:04:32.754   223   223 D oemcrypto_cenc: << OEMCrypto_GetRandom
,07-05 14:04:32.754   223   223 E oemcrypto_cenc: OEMCrypto_SecurityLevel
,07-05 14:04:32.758   223   223 D oemcrypto_cenc: >> OEMCrypto_LoadDeviceRSAKey
,07-05 14:04:32.759   223   223 D oemcrypto_cenc: << OEMCrypto_LoadDeviceRSAKey
07-05 14:04:32.759   223   223 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:04:32.762   223   893 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-05 14:04:32.762   223   893 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:32.762   223   893 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:32.762   223   893 D oemcrypto_cenc: >> OEMCrypto_GetDeviceID
07-05 14:04:32.763   223   893 D oemcrypto_cenc: << OEMCrypto_GetDeviceID
07-05 14:04:32.763   223   893 D oemcrypto_cenc: >> OEMCrypto_SupportsUsageTable
,07-05 14:04:32.786  2745  2775 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,07-05 14:04:32.790  2560  2569 W art     : Suspending all threads took: 401.504ms
,07-05 14:04:32.802   223   893 D oemcrypto_cenc: << OEMCrypto_SupportsUsageTable
,07-05 14:04:32.802   223   893 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-05 14:04:32.802   223   893 D oemcrypto_cenc: OEMCrypto_GetHDCPCapability
07-05 14:04:32.802   223   893 D oemcrypto_cenc: >> OEMCrypto_GenerateNonce
,07-05 14:04:32.803   223   893 D oemcrypto_cenc: << OEMCrypto_GenerateNonce
,07-05 14:04:32.803   223   893 D WVCdm   : PrepareKeyRequest: nonce=2445149460
07-05 14:04:32.803   223   893 D oemcrypto_cenc: >> OEMCrypto_GenerateRSASignature
,07-05 14:04:32.885   223   893 D oemcrypto_cenc: << OEMCrypto_GenerateRSASignature
,07-05 14:04:32.886   223   647 I WVCdm   : CdmEngine::CloseSession
07-05 14:04:32.886   223   647 D oemcrypto_cenc: >> OEMCrypto_CloseSession
07-05 14:04:32.886   223   647 D oemcrypto_cenc: bool RemoveSessionHandle(OEMCrypto_SESSION): session: 0xabcc3b20, status: 1
07-05 14:04:32.887   223   647 D oemcrypto_cenc: << OEMCrypto_CloseSession
07-05 14:04:32.887   223   647 D oemcrypto_cenc: >> OEMCrypto_Terminate
07-05 14:04:32.888   223   647 D oemcrypto_cenc: << OEMCrypto_Terminate
07-05 14:04:32.889  2745  2755 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 14:04:32.891  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:32.891  2340  2390 I jxcore-log: 
07-05 14:04:32.901  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:32.901  2340  2390 I jxcore-log: 
,07-05 14:04:32.909  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:32.909  2340  2390 I jxcore-log: 
,07-05 14:04:32.948  1223  2623 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:32.951  1223  2623 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:32.962  1223  2623 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:32.964  1223  2623 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,07-05 14:04:33.048  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:33.048  2340  2390 I jxcore-log: 
,07-05 14:04:33.073  2778  2778 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-05 14:04:33.114  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:33.114  2340  2390 I jxcore-log: 
,07-05 14:04:33.156  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:33.156  2340  2390 I jxcore-log: 
,07-05 14:04:33.164  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:33.164  2340  2390 I jxcore-log: 
,07-05 14:04:33.229   534   552 I ActivityManager: Killing 947:android.process.acore/u0a3 (adj 15): empty #17
,07-05 14:04:33.339  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:33.339  2340  2390 I jxcore-log: 
,07-05 14:04:33.360  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:33.360  2340  2390 I jxcore-log: 
,07-05 14:04:33.366  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:33.366  2340  2390 I jxcore-log: 
,07-05 14:04:33.376  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:33.376  2340  2390 I jxcore-log: 
,07-05 14:04:33.387  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:33.387  2340  2390 I jxcore-log: 
,07-05 14:04:33.405  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:33.405  2340  2390 I jxcore-log: 
,07-05 14:04:33.416  1223  1223 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-05 14:04:33.445  1095  1095 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:33.449  1223  2800 I ConfigFetchService: running network task: configservice_periodic
,07-05 14:04:33.450  1223  2800 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
07-05 14:04:33.450  1223  2800 E WakeLock: java.lang.IllegalArgumentException
07-05 14:04:33.450  1223  2800 E WakeLock: 	at com.google.android.gms.stats.d.<init>(SourceFile:135)
07-05 14:04:33.450  1223  2800 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:341)
07-05 14:04:33.450  1223  2800 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:159)
07-05 14:04:33.450  1223  2800 E WakeLock: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:33.455  1223  2800 I ConfigFetchService: launchTask
,07-05 14:04:33.456  1095  1095 I ConfigService: onCreate
,07-05 14:04:33.471  1223  1223 I ConfigFetchService: service connected
,07-05 14:04:33.473  1223  1223 D ConfigFetchService: ConfigApi connection successful.
,07-05 14:04:33.505  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:33.505  2340  2390 I jxcore-log: 
,07-05 14:04:33.510  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:33.510  2340  2390 I jxcore-log: 
,07-05 14:04:33.539  2799  2799 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_dg_cache/39A8A382160AEDAB93CB98DA523134BE833487FA/the.apk --oat-file=/data/user/0/com.google.android.gms/app_dg_cache/39A8A382160AEDAB93CB98DA523134BE833487FA/opt/the.dex
,07-05 14:04:33.592  2799  2799 I dex2oat : dex2oat took 53.150ms (threads: 2) arena alloc=46KB java alloc=21KB native alloc=472KB free=87KB
07-05 14:04:33.658  2340  2390 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:33.658  2340  2390 I jxcore-log: 
07-05 14:04:33.670  2340  2390 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
07-05 14:04:33.672  2340  2390 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-05 14:04:33.672  2340  2390 I jxcore-log: 
07-05 14:04:33.720  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
07-05 14:04:33.720  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud.
,07-05 14:04:33.720  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:33.720  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:33.729  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-05 14:04:33.729  2340  2390 I jxcore-log: 
07-05 14:04:33.729  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-05 14:04:33.729  2340  2390 I jxcore-log: 
,07-05 14:04:33.730  2340  2390 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:33.730  2340  2390 I jxcore-log: 
,07-05 14:04:33.752  1223  2801 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XQOeOLp2Qnvt_3L8Cxm6z7DTHM3znI5KpW-Ssxusf1J9xgPzHykO3DMgzeLrSUzjFYKC4EfAhQsA5x83HZbIY_HJfvd6PtJU6WpvCe14fg3Kwfkg_Xaxdaw4KE4aW8-fW4NvrhcexRqC5xYiPmO4Ze0xNbs9NPGpanXHVaR8c_SbDckzVCRYxZMSdOqkQxVSRVlEDJ25xjncO20CRf2GT-z5_-ftmBiso3nDRQPrqemOJWNpQ
,07-05 14:04:33.796  1223  2801 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:33.807  1095  2802 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-05 14:04:33.809  2812  2812 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-05 14:04:33.928  2445  2818 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:04:33.936  2812  2812 I dex2oat : dex2oat took 127.160ms (threads: 2) arena alloc=66KB java alloc=48KB native alloc=782KB free=57KB
,07-05 14:04:33.944  1223  2623 I PeopleSync: Sync finished, successful=false, took 949ms
,07-05 14:04:33.945  2745  2755 W System  : ClassLoader referenced unknown path: 
,07-05 14:04:33.972  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:04:33.972  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:04:33.972  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:33.972  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:33.986  2445  2818 W ExperimentUpdateService: [215] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: [215] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:04:33.987  2445  2818 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:04:34.073   534   565 I ActivityManager: Start proc 2820:com.google.android.apps.books/u0a28 for service com.google.android.apps.books/.service.SyncService
,07-05 14:04:34.141  1223  2623 I PeopleSync: Cannot authenticate [5005f081]
07-05 14:04:34.141  1223  2623 I PeopleSync: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.people.service.g.b(SourceFile:171)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1190)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.people.sync.aa.g(SourceFile:1085)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.people.sync.aa.a(SourceFile:240)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:274)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:189)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:91)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
07-05 14:04:34.141  1223  2623 I PeopleSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,07-05 14:04:34.195  2820  2820 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm64,
,07-05 14:04:34.219  1223  2623 I PeopleSync: ***Sync finished***, duration: 2952 [5005f081]
,07-05 14:04:34.228  1223  2801 I ConfigFetchTask: updating config table for com.google.android.gms
,07-05 14:04:34.299   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 31652, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:34.301   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 138518, reason: Periodic
,07-05 14:04:34.630   534   766 I ActivityManager: Start proc 2843:com.google.android.calendar/u0a31 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-05 14:04:34.686  2820  2820 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:34.719  2820  2820 I BooksApp: Created application version: 3.6.9 (30609)
,07-05 14:04:34.763   223   223 D WVCdm   : Instantiating CDM.
07-05 14:04:34.765   223   893 I WVCdm   : CdmEngine::OpenSession
07-05 14:04:34.765   223   893 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
07-05 14:04:34.767   223   893 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-05 14:04:34.767   223   893 D oemcrypto_cenc: >> OEMCrypto_Initialize: modular drm 5.00  Jul 20 2015  05:40:21
07-05 14:04:34.768   223   893 D oemcrypto_cenc: << OEMCrypto_Initialize
07-05 14:04:34.768   223   893 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-05 14:04:34.768   223   893 D oemcrypto_cenc: >> OEMCrypto_IsKeyboxValid
07-05 14:04:34.768   223   893 D oemcrypto_cenc: << OEMCrypto_IsKeyboxValid
07-05 14:04:34.768   223   893 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:34.768   223   893 D oemcrypto_cenc: >> OEMCrypto_OpenSession
07-05 14:04:34.768   223   893 D oemcrypto_cenc: bool AddSessionHandle(OEMCrypto_SESSION): session:0xabcbe330, status: 1
07-05 14:04:34.769   223   893 D oemcrypto_cenc: << OEMCrypto_OpenSession
07-05 14:04:34.769   223   893 D oemcrypto_cenc: >> OEMCrypto_GetRandom
07-05 14:04:34.769   223   893 D oemcrypto_cenc: << OEMCrypto_GetRandom
07-05 14:04:34.770   223   893 E oemcrypto_cenc: OEMCrypto_SecurityLevel
,07-05 14:04:34.770   223   893 D oemcrypto_cenc: >> OEMCrypto_LoadDeviceRSAKey
07-05 14:04:34.771   223   893 D oemcrypto_cenc: << OEMCrypto_LoadDeviceRSAKey
07-05 14:04:34.771   223   893 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:04:34.778   223   223 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:04:34.778   223   223 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:34.778   223   223 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-05 14:04:34.778   223   223 D oemcrypto_cenc: >> OEMCrypto_GetDeviceID
07-05 14:04:34.778   223   223 D oemcrypto_cenc: << OEMCrypto_GetDeviceID
,07-05 14:04:34.778   223   223 D oemcrypto_cenc: >> OEMCrypto_SupportsUsageTable
,07-05 14:04:34.787   223   223 D oemcrypto_cenc: << OEMCrypto_SupportsUsageTable
07-05 14:04:34.787   223   223 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-05 14:04:34.787   223   223 D oemcrypto_cenc: OEMCrypto_GetHDCPCapability
07-05 14:04:34.787   223   223 D oemcrypto_cenc: >> OEMCrypto_GenerateNonce
07-05 14:04:34.787   223   223 D oemcrypto_cenc: << OEMCrypto_GenerateNonce
07-05 14:04:34.787   223   223 D WVCdm   : PrepareKeyRequest: nonce=3907687497
07-05 14:04:34.787   223   223 D oemcrypto_cenc: >> OEMCrypto_GenerateRSASignature
07-05 14:04:34.826   223   223 D oemcrypto_cenc: << OEMCrypto_GenerateRSASignature
07-05 14:04:34.828   223   893 I WVCdm   : CdmEngine::CloseSession
,07-05 14:04:34.828   223   893 D oemcrypto_cenc: >> OEMCrypto_CloseSession
,07-05 14:04:34.828   223   893 D oemcrypto_cenc: bool RemoveSessionHandle(OEMCrypto_SESSION): session: 0xabcbe330, status: 1
07-05 14:04:34.829   223   893 D oemcrypto_cenc: << OEMCrypto_CloseSession
07-05 14:04:34.829   223   893 D oemcrypto_cenc: >> OEMCrypto_Terminate
07-05 14:04:34.830   223   893 D oemcrypto_cenc: << OEMCrypto_Terminate
,07-05 14:04:35.005  1223  1223 I ConfigFetchService: fetch service done; releasing wakelock
,07-05 14:04:35.006  1223  1223 I ConfigFetchService: stopping self
,07-05 14:04:35.021  2173  2183 W art     : Suspending all threads took: 40.831ms
,07-05 14:04:35.138  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:35.174  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
07-05 14:04:35.175  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
07-05 14:04:35.175  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-05 14:04:35.175  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:35.195  1223  2861 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:35.201  1095  2862 I VacuumService: Vacuum at: now=1467720275201 tag=VacuumService
,07-05 14:04:35.318  2843  2843 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm64
,07-05 14:04:35.568  1986  2842 V KeepSync: Connecting to GoogleApiClient
,07-05 14:04:35.573   534   766 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-05 14:04:35.647   534  1160 I ActivityManager: Start proc 2865:com.android.providers.calendar/u0a2 for content provider com.android.providers.calendar/.CalendarProvider2
,07-05 14:04:35.735  1223  2573 I CheckinRequestBuilder: Classify the device as Tablet.
,07-05 14:04:35.736  1095  1347 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:04:35.736  1095  1347 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:04:35.736  1095  1347 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:35.736  1095  1347 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:35.770  1095  1095 W GCM-DMM : Force release of GOOGLE_C2DM lock
07-05 14:04:35.773  1223  2878 V BaseAuthAsyncOperation: access token request failed
07-05 14:04:35.774  1986  2842 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:04:35.776  2865  2865 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm64
,07-05 14:04:35.796  1095  1095 W GCM-DMM : Force release of GOOGLE_C2DM lock
,07-05 14:04:35.873   534  1117 I ActivityManager: Start proc 2888:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-05 14:04:35.875   534  1117 I ActivityManager: Killing 2242:com.android.musicfx/u0a14 (adj 15): empty #17
,07-05 14:04:35.896  2865  2865 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@5a6bdaa(com.android.providers.calendar.CalendarProvider2@144bd9b)
,07-05 14:04:35.908   534  1117 I ActivityManager: Killing 2227:com.google.android.partnersetup/u0a11 (adj 15): empty #18
,07-05 14:04:35.940  2843  2843 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-05 14:04:35.984  2888  2888 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,07-05 14:04:35.994  2820  2902 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:04:36.057  2888  2888 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:04:36.057  2888  2888 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:36.057  2888  2888 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:36.067  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:04:36.067  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:04:36.068  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:36.068  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:36.069  2888  2888 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:36.073  2888  2888 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:36.083  1986  2842 E KeepSync: IOException
07-05 14:04:36.083  1986  2842 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:36.083  1986  2842 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:04:36.083  1986  2842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:04:36.083  1986  2842 E KeepSync: 	... 10 more
,07-05 14:04:36.091  1986  2842 W KeepSync: Sync result 2
,07-05 14:04:36.093  2888  2909 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:36.102   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 26825, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:04:36.122  1223  2573 W System.err: java.lang.Exception: Error converting session
,07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
,07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
07-05 14:04:36.122  1223  2573 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
,07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
,07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-05 14:04:36.123  1223  2573 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
,07-05 14:04:36.124  1223  2573 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
07-05 14:04:36.124  1223  2573 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
07-05 14:04:36.124  1223  2573 W System.err: 	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
07-05 14:04:36.124  1223  2573 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
07-05 14:04:36.124  1223  2573 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:04:36.124  1223  2573 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:04:36.124  1223  2573 W System.err: Caused by: java.io.IOException: Invalid session data
07-05 14:04:36.124  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
07-05 14:04:36.124  1223  2573 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
,07-05 14:04:36.124  1223  2573 W System.err: 	... 25 more
,07-05 14:04:36.163  1095  1428 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,07-05 14:04:36.169  1223  1223 I GCM     : Message from 745476177629 null
,07-05 14:04:36.172  1223  1223 I GCM     : Message from 745476177629 null
,07-05 14:04:36.186   534  1160 I ActivityManager: Killing 1278:com.google.android.gms.wearable/u0a7 (adj 15): empty #17
,07-05 14:04:36.208  2820  2916 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-05 14:04:36.240   994  2917 I DictionaryProvider:UpdateHandler: downloadFinished() : DownloadId = 114
,07-05 14:04:36.265  1095  1448 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 14:04:36.266  1095  1095 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 14:04:36.274  1095  1219 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:04:36.274  1095  1219 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-05 14:04:36.274  1095  1219 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:36.274  1095  1219 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:36.286  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:36.288  1223  1223 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 14:04:36.312   534  1117 I ActivityManager: Start proc 2924:com.google.android.gms.wearable/u0a7 for service com.google.android.gms/.wearable.service.WearableService
,07-05 14:04:36.362  1223  2936 D LocationInitializer: Restart initialization of location
,07-05 14:04:36.385  2924  2924 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:36.396  1095  2919 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-05 14:04:36.400  1095  2919 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:36.428  2924  2924 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:04:36.428  2924  2924 I MultiDex: install
07-05 14:04:36.428  2924  2924 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 14:04:36.440  1095  1105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 14:04:36.441  1095  1105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:04:36.441  1095  1105 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:36.441  1095  1105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:36.444  1058  1230 W GCoreFlp: No location to return for getLastLocation()
07-05 14:04:36.444  1095  2938 W FusedLocationProvider: location=null
07-05 14:04:36.455  2820  2916 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:36.457  2820  2902 E BooksSync: Soft error
07-05 14:04:36.457  2820  2902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:36.457  2820  2902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:04:36.457  2820  2902 E BooksSync: Sync error
07-05 14:04:36.457  2820  2902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:36.457  2820  2902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:04:36.467  2820  2902 I BooksSync: Finished books sync
,07-05 14:04:36.494  2924  2924 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...,
07-05 14:04:36.501  1223  1223 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,07-05 14:04:36.505  1223  1223 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-05 14:04:36.505  1223  1223 I ConfigFetchService: GmsCore config value changed; rescheduling
07-05 14:04:36.506  1223  1223 I ConfigFetchService: service connected
,07-05 14:04:36.509  1223  1223 D ConfigFetchService: ConfigApi connection successful.
07-05 14:04:36.520  1223  2945 I ConfigFetchService: self-hosted config:fetch_interval = 43200
07-05 14:04:36.531  2924  2924 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:36.538  1223  2945 I ConfigFetchService: stopping self
,07-05 14:04:36.545  1095  1095 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 14:04:36.556   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26825, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
07-05 14:04:36.566  1095  1461 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 14:04:36.570  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:36.574  1223  1223 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
07-05 14:04:36.579  2924  2924 D WearableService: callingUid 10007, callindPid: 2924
07-05 14:04:36.628  1223  2952 D LocationInitializer: Restart initialization of location
,07-05 14:04:36.633  2924  2948 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,07-05 14:04:36.636  1058  1452 E MDM     : [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 14:04:36.640  1058  1452 E MDM     : [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-05 14:04:36.655  1095  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.me
07-05 14:04:36.655  1095  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me without consulting the cloud.
,07-05 14:04:36.655  1095  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:36.655  1095  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:36.658  1058  1230 W GCoreFlp: No location to return for getLastLocation()
07-05 14:04:36.658  1095  2953 W FusedLocationProvider: location=null
,07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: Failed to update the notification(s) read state.
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:60)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:403)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:284)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:262)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.notifications.a.a(SourceFile:45)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsService.a(SourceFile:199)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsService.onHandleIntent(SourceFile:73)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:36.665  1095  2947 W GnotsSRSOperation: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:36.665  1095  2947 W WakefulBroadcastReceiver: No active wake lock id #8
07-05 14:04:36.674  1095  2947 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
07-05 14:04:36.687  1095  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.me
07-05 14:04:36.687  1095  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me without consulting the cloud.
07-05 14:04:36.687  1095  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:36.687  1095  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: Failed to fetch notification by identifer.
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:60)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:403)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:284)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:262)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.notifications.c.a(SourceFile:45)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.notifications.GunsService.a(SourceFile:228)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at com.google.android.gms.notifications.GunsService.onHandleIntent(SourceFile:86)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:36.695  1095  2947 D GnotsFetchOperation: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.696  1095  2947 W WakefulBroadcastReceiver: No active wake lock id #9
07-05 14:04:36.711  1095  2954 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
07-05 14:04:36.711  1095  2954 W WakefulBroadcastReceiver: No active wake lock id #10
,07-05 14:04:36.721   534  1163 I ActivityManager: Killing 2267:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,07-05 14:04:36.727  1223  2573 I CheckinTask: Sending checkin request (9602 bytes)
,07-05 14:04:36.809   534   565 I ActivityManager: Start proc 2956:com.google.android.gm/u0a71 for service com.google.android.gm/.provider.MailSyncAdapterService
,07-05 14:04:36.810  1095  2919 W Uploader:  no longer exists, so no auth token.
,07-05 14:04:36.839  2956  2956 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm64
,07-05 14:04:36.874  1095  2919 W Uploader: SMS no longer exists, so no auth token.
,07-05 14:04:36.886  2956  2971 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-05 14:04:36.894  2956  2970 I Gmail   : getAccountsCursor
,07-05 14:04:36.901  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:36.936  2956  2956 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:36.964   534  1244 I ActivityManager: Start proc 2979:com.google.android.gm.exchange/u0a70 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,07-05 14:04:37.000   534   766 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 14:04:37.010  2956  2992 I Gmail   : Observing account changes for notifications
,07-05 14:04:37.032  2865  2865 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-05 14:04:37.034  2865  2865 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 14:04:37.036  2979  2979 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm64
,07-05 14:04:37.036   534   553 I ActivityManager: Killing 2210:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-05 14:04:37.052  1223  2573 I CheckinResponseProcessor: From server: 2 gservices updates and 1 deletes
,07-05 14:04:37.072  2956  2970 I Gmail   : getAccountsCursor
,07-05 14:04:37.073  2956  2993 E Gmail   : Error finding the version of the Email provider.....
07-05 14:04:37.073  2956  2993 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 14:04:37.073  2956  2993 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-05 14:04:37.073  2956  2993 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-05 14:04:37.073  2956  2993 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 14:04:37.073  2956  2993 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:37.073  2956  2993 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:37.073  2956  2993 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:37.073  2956  2993 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:37.074  2956  2993 W EmailMigration: We do not support migrating this version of the Email provider.
,07-05 14:04:37.077  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:37.119  2979  2979 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:37.131  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:37.152  2979  2979 I Exchange: EasService.onCreate
,07-05 14:04:37.153  2659  3006 I SyncAdapterService: Ignoring sync request for non-current account
,07-05 14:04:37.187  1095  2919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:37.187  1095  2919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:37.187  1095  2919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:37.187  1095  2919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:37.197  1095  2919 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:37.197  1095  2919 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:37.197  1095  2919 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-05 14:04:37.197  2979  3008 I Exchange: RestartPingTask
,07-05 14:04:37.200  2956  3005 W Gmail   : Sync started for account: account:61035162
,07-05 14:04:37.229   534   565 I ActivityManager: Start proc 3012:com.google.process.gapps/u0a85 for service com.google.android.syncadapters.contacts/.ContactsSyncAdapterService
,07-05 14:04:37.266  2979  2979 I Exchange: RestartPingsTask did not start any pings.
,07-05 14:04:37.267  2979  2979 I Exchange: PSS stopIfIdle
,07-05 14:04:37.267  2979  2979 I Exchange: PSS has no active accounts; stopping service.
07-05 14:04:37.268  2979  2979 I Exchange: onDestroy
,07-05 14:04:37.275  3012  3012 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm64
,07-05 14:04:37.290  3012  3012 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:04:37.304  1095  2919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:37.304  1095  2919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:37.304  1095  2919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:37.304  1095  2919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:37.313  1095  2919 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:37.313  1095  2919 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:37.313  1095  2919 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:37.336   534  1148 I ActivityManager: Start proc 3028:android.process.acore/u0a3 for content provider com.android.providers.contacts/.ContactsProvider2
,07-05 14:04:37.353  2956  3009 I Gmail   : notifyAccountChanged
,07-05 14:04:37.357  2956  2970 I Gmail   : getAccountsCursor
07-05 14:04:37.359  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:37.396  2956  3009 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:04:37.412  2956  3009 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:04:37.425  3028  3028 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,07-05 14:04:37.428  2956  3005 I Gmail   : notifyAccountChanged
,07-05 14:04:37.447  2956  3009 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:04:37.452  2956  3009 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:04:37.532   534   666 D ConnectivityService: handlePromptUnvalidated 100
,07-05 14:04:37.533  1095  2919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:37.533  1095  2919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:37.533  1095  2919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:37.533  1095  2919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:37.543  1095  2919 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:37.543  1095  2919 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:37.543  1095  2919 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:37.557  2956  2971 I Gmail   : getAccountsCursor,
,07-05 14:04:37.561  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:37.567  3028  3028 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,07-05 14:04:37.580  3012  3026 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,07-05 14:04:37.586  1095  1105 I GservicesProvider: main difference update completed
,07-05 14:04:37.603   534   567 I ActivityManager: Start proc 3045:com.google.android.configupdater/u0a36 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,07-05 14:04:37.618  1223  2573 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:04:37.630  1223  2573 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 14:04:37.650  3012  3026 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:04:37.700  3045  3045 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm64
,07-05 14:04:37.772  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
07-05 14:04:37.772  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-05 14:04:37.772  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:37.772  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:37.782  2956  3005 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4343, normalSync: true
,07-05 14:04:37.790  3045  3045 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,07-05 14:04:37.799   994  2917 I DictionaryProvider:UpdateHandler: downloadFinished() : Success = true
07-05 14:04:37.800   994  2917 I DictionaryProvider:UpdateHandler: downloadFinished() : Metadata Success
,07-05 14:04:37.801   994   994 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-05 14:04:37.805   994  3065 I Keyboard.Facilitator.DecoderInitializer: run()
,07-05 14:04:37.815   994  3065 I Decoder : createOrResetDecoder
,07-05 14:04:37.818  3045  3045 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,07-05 14:04:37.821  3045  3045 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,07-05 14:04:37.824  3045  3045 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,07-05 14:04:37.829  3045  3045 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,07-05 14:04:37.830  1095  2919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:37.830  1095  2919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,07-05 14:04:37.830  1095  2919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:37.830  1095  2919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:37.834  1223  2573 W CheckinRequestBuilder: awaiting user notification for token
07-05 14:04:37.838  1095  2919 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:37.838  1095  2919 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:37.838  1095  2919 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:37.866   534  1244 I ActivityManager: Start proc 3074:com.google.android.partnersetup/u0a11 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,07-05 14:04:37.867   534  1244 I ActivityManager: Killing 1715:com.android.vending/u0a16 (adj 15): empty #17
,07-05 14:04:37.890   994  3065 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-05 14:04:37.923  1223  2573 I CheckinRequestBuilder: Classify the device as Tablet.
,07-05 14:04:37.944   994  3065 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-05 14:04:37.948   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,07-05 14:04:37.948   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-05 14:04:37.951   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,07-05 14:04:37.951   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-05 14:04:37.956   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-05 14:04:37.956   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,07-05 14:04:37.957   994  3065 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-05 14:04:37.957   994  3065 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,07-05 14:04:37.958   994  3065 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-05 14:04:37.958   994  3065 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-05 14:04:37.958   994  3065 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-05 14:04:37.958   994  3065 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-05 14:04:37.962  3074  3074 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,07-05 14:04:37.969  1223  2573 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-05 14:04:37.986  1223  2573 I CheckinService: Checking schedule, now: 1467720277985 next: 1467762422969
07-05 14:04:37.986  1223  2573 I CheckinService: active receiver: disabled
,07-05 14:04:38.073  2956  3005 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:38.135   534  2901 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,07-05 14:04:38.169  1223  1223 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,07-05 14:04:38.179  1223  3099 I CheckinService: Checking schedule, now: 1467720278179 next: 1467762422969
,07-05 14:04:38.179  1223  3099 I CheckinService: active receiver: disabled
,07-05 14:04:38.187  1223  1223 D SystemUpdateService: onCreate
,07-05 14:04:38.191  1223  1223 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-05 14:04:38.207  1095  1428 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:04:38.213  1223  1223 D OcrModelManager: Updating downloaded model state (gservices changed)
,07-05 14:04:38.217  1223  1223 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
07-05 14:04:38.218  1223  1223 I OcrUtils: Updating ocr activity enabled=false
,07-05 14:04:38.224  1223  3100 I SystemUpdateService: cancelUpdate (empty URL)
,07-05 14:04:38.224  1223  3100 I SystemUpdateService: active receiver: disabled
,07-05 14:04:38.256  1223  1223 D SystemUpdateService: onDestroy
,07-05 14:04:38.257  1058  1058 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,07-05 14:04:38.270  1058  1058 I GCoreUlr: DispatchingService.onCreate()
,07-05 14:04:38.290  2956  3005 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:38.340   534   766 I ActivityManager: Killing 1078:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
07-05 14:04:38.356  3028  3041 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-05 14:04:38.404   534   665 D WifiService: Client connection lost with reason: 4
,07-05 14:04:38.427  2956  3005 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:38.431  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:38.448  1095  1219 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail,
,07-05 14:04:38.448  1095  1219 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
,07-05 14:04:38.448  1095  1219 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:38.448  1095  1219 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:38.460  1095  1219 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:38.460  1095  1219 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:38.460  1095  1219 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:38.460  1095  1219 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:38.460  1095  1219 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:38.460  1095  1219 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:38.460  1095  1219 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:38.488  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:38.501  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
07-05 14:04:38.501  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:04:38.501  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:38.502  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:38.510  1095  1164 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:38.510  1095  1164 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:38.510  1095  1164 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:38.510  1095  1164 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:38.510  1095  1164 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:38.510  1095  1164 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:38.510  1095  1164 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:04:38.513  1223  1233 E System  : Uncaught exception thrown by finalizer
07-05 14:04:38.515  1223  1233 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:04:38.515  1223  1233 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:04:38.515  1223  1233 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-05 14:04:38.515  1223  1233 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:04:38.515  1223  1233 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:04:38.515  1223  1233 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:04:38.551  1058  3106 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:04:38.569  1223  1320 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,07-05 14:04:38.590  2956  3005 I Gmail   : notifyAccountChanged
,07-05 14:04:38.595  2956  2978 I Gmail   : getAccountsCursor
,07-05 14:04:38.608   534  1148 I ActivityManager: Start proc 3112:com.google.android.googlequicksearchbox:search/u0a22 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,07-05 14:04:38.633  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:38.675   534   766 I ActivityManager: Killing 2477:com.android.settings/1000 (adj 15): empty #17
,07-05 14:04:38.682  2956  2967 W Gmail   : MailSyncAdapterService#onSyncCanceled Thread[SyncAdapterThread-1,5,main]
,07-05 14:04:38.682  2956  2967 W Gmail   : MailEngine != null account: account:61035162
,07-05 14:04:38.710  2956  3005 I Gmail   : notifyAccountChanged
,07-05 14:04:38.712  2956  3005 W Gmail   : Sync complete for account: account:61035162
07-05 14:04:38.712  2956  2970 I Gmail   : getAccountsCursor
,07-05 14:04:38.715  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:38.833  1058  3106 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 14:04:38.840  1058  3106 I GCoreUlr: Unbound from all location providers
,07-05 14:04:38.856  1058  1058 I GCoreUlr: DispatchingService.onDestroy()
,07-05 14:04:38.856  1058  1058 I GCoreUlr: Stopping handler for UlrDispSvcFast
07-05 14:04:38.859  1058  1058 I GCoreUlr: Unbound from all location providers
,07-05 14:04:38.971   534  3107 I ActivityManager: Killing 2500:com.google.android.apps.maps/u0a60 (adj 15): empty #17
,07-05 14:04:39.035  1223  1223 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 14:04:39.038  1223  1223 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-05 14:04:39.043  1095  1448 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 14:04:39.050  1095  1448 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 14:04:39.052  1223  1223 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 14:04:39.053  1223  1223 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-05 14:04:39.068  3112  3145 I GservicesUpdateTask: Updating Gservices keys
,07-05 14:04:39.078  3028  3041 D ContactDirectoryManager: Found com.google.contacts.gal.provider
07-05 14:04:39.078  3028  3041 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-05 14:04:39.099  3028  3041 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-05 14:04:39.119  2956  3147 W Gmail   : Sync started for account: account:61035162
,07-05 14:04:39.121  2956  3147 I Gmail   : notifyAccountChanged
,07-05 14:04:39.126  2956  2971 I Gmail   : getAccountsCursor
,07-05 14:04:39.129  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:39.138  3028  3041 I ContactDirectoryManager: Discovered 0 contact directories in 257ms
,07-05 14:04:39.151   994  2917 I DictionaryProvider:UpdateHandler: downloadFinished() : Success = true
,07-05 14:04:39.151   994  2917 I DictionaryProvider:UpdateHandler: downloadFinished() : Metadata Success
,07-05 14:04:39.153   994   994 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-05 14:04:39.169  3112  3145 I GStaticConfiguration: #getNewConfigurationUrl [pref=2016_04_08_14_33_37, gservice=2016_06_27_18_09_34]
,07-05 14:04:39.176   994  3149 I Keyboard.Facilitator.DecoderInitializer: run()
,07-05 14:04:39.184  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:39.202  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,07-05 14:04:39.202  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> cp without consulting the cloud.
07-05 14:04:39.202  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:39.202  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:39.210  1095  1841 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:39.210  1095  1841 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:39.210  1095  1841 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:39.210  1095  1841 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:39.210  1095  1841 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:39.210  1095  1841 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:39.210  1095  1841 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:39.221   737  3150 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/metadata.json#14674147872064.1.23104.2862625.json via provider delete
,07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: innerSync failed
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:269)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:169)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:128)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:04:39.226  3012  3026 D ContactsSyncAdapter: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:39.232   994  3149 I Decoder : createOrResetDecoder
,07-05 14:04:39.247   994  3149 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-05 14:04:39.263  2956  3147 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4343, normalSync: true
,07-05 14:04:39.271   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 26827, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:39.273   994  3149 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-05 14:04:39.273   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 143766, reason: Periodic
,07-05 14:04:39.276   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,07-05 14:04:39.276   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-05 14:04:39.278   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-05 14:04:39.278   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-05 14:04:39.278   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,07-05 14:04:39.278   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-05 14:04:39.280   994  3149 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-05 14:04:39.280   994  3149 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,07-05 14:04:39.280   994  3149 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-05 14:04:39.281   994  3149 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-05 14:04:39.281   994  3149 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-05 14:04:39.281   994  3149 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-05 14:04:39.289  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:39.302  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
,07-05 14:04:39.302  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:04:39.302  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:39.302  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:39.311  1095  1109 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:39.311  1095  1109 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:39.311  1095  1109 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:39.311  1095  1109 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:39.311  1095  1109 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:39.311  1095  1109 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:39.311  1095  1109 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:39.317  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:39.320   534   665 D WifiService: New client listening to asynchronous messages
,07-05 14:04:39.340  1095  1105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
,07-05 14:04:39.340  1095  1105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:04:39.340  1095  1105 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:39.340  1095  1105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:39.352  1095  1105 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:39.352  1095  1105 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:39.352  1095  1105 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:39.352  1095  1105 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:39.352  1095  1105 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:39.352  1095  1105 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:39.352  1095  1105 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:39.370  2843  2843 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-05 14:04:39.375  2956  3147 I Gmail   : notifyAccountChanged
,07-05 14:04:39.375  2956  3147 W Gmail   : Sync complete for account: account:61035162
07-05 14:04:39.376  2956  2978 I Gmail   : getAccountsCursor
,07-05 14:04:39.379  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:39.385   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 26827, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:39.386   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 144532, reason: Periodic
,07-05 14:04:39.434  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:39.442  2843  3160 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:39.447  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:39.453  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:39.460  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:39.464  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:04:39.468  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:04:39.477  1223  1223 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:39.543  2843  3160 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:39.568  2843  3160 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:39.569  2843  3160 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:39.580   534   565 I ActivityManager: Start proc 3166:com.google.android.music:main/u0a61 for service com.google.android.music/.sync.SyncAdapterService
,07-05 14:04:39.650  3166  3166 W System  : ClassLoader referenced unknown path: /system/app/Music2/lib/arm64
,07-05 14:04:39.657  3166  3166 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:04:39.657  3166  3166 I MultiDex: install
,07-05 14:04:39.657  3166  3166 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:39.674  1095  3124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,07-05 14:04:39.674  1095  3124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud.
07-05 14:04:39.675  1095  3124 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:39.675  1095  3124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:39.686  2820  2848 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:39.689  3166  3166 I MusicStore: Database version: 121
,07-05 14:04:39.705   534  1160 I ActivityManager: Killing 2598:com.android.chrome/u0a34 (adj 15): empty #17
,07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: Exception in onPerformLoggedSync 
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:153)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:90)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:859)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:419)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:352)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:469)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.Utils.executeAndLog(Utils.java:555)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2853)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:2301)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffsForAccount(CalendarSyncAdapterApiary.java:2182)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:623)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:473)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.android.emailcommon.syncadapter.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:49)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.zzb(Unknown Source)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:141)
07-05 14:04:39.710  2843  3160 E CalendarSyncAdapter: 	... 13 more
,07-05 14:04:39.740   534  2901 I ActivityManager: Killing 2560:com.google.android.youtube/u0a81 (adj 15): empty #17
,07-05 14:04:39.763   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 26827, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:39.774   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 143011, reason: Periodic
,07-05 14:04:39.787  3166  3166 D MusicLifecycle: com.google.android.music.MusicApplication generated event: Application created
,07-05 14:04:39.803   534   565 I ActivityManager: Start proc 3190:com.google.android.apps.cloudprint:sync/u0a35 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,07-05 14:04:39.813  3166  3166 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:39.876  3190  3190 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm64
,07-05 14:04:39.878  3166  3166 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:39.898  3166  3166 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:39.898  3166  3166 D AndroidMusic: GMSCore installation verified
,07-05 14:04:39.910  3166  3166 I ConfigStore: Config Database version: 1
,07-05 14:04:39.934   534  1243 I ActivityManager: Start proc 3203:com.google.android.apps.cloudprint/u0a35 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,07-05 14:04:39.968  3203  3203 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm64
,07-05 14:04:39.980  3166  3166 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Tablet, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-05 14:04:39.983  3190  3215 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,07-05 14:04:39.985   534   755 I ActivityManager: Killing 2173:com.google.android.apps.plus/u0a68 (adj 15): empty #17
,07-05 14:04:40.009   534  3107 I ActivityManager: Killing 2888:com.google.android.deskclock/u0a38 (adj 15): empty #17
,07-05 14:04:40.109  1223  3219 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:04:40.109  3166  3166 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 14:04:40.113  3166  3166 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:40.167  3166  3166 D MusicLifecycle: com.google.android.music.net.NetworkMonitor generated event: Service created
,07-05 14:04:40.168  3166  3166 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:40.174  3166  3221 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,07-05 14:04:40.194  3166  3166 D MusicLifecycle: com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,07-05 14:04:40.195  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,07-05 14:04:40.199  3166  3166 D MusicLifecycle: com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,07-05 14:04:40.209  1223  3222 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:40.214  3166  3166 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2a924fb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-05 14:04:40.214  3166  3166 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:40.217  3166  3166 D MusicLifecycle: com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,07-05 14:04:40.219  3166  3166 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
07-05 14:04:40.221  3166  3166 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:40.228  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service created
,07-05 14:04:40.240  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,07-05 14:04:40.260  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:40.274  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: mail
,07-05 14:04:40.274  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:04:40.274  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:40.274  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:40.289  1095  1164 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:40.289  1095  1164 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:40.289  1095  1164 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:40.289  1095  1164 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:40.289  1095  1164 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:40.289  1095  1164 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:40.289  1095  1164 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:40.290  1223  3222 W SubscribedFeeds: Hard error
,07-05 14:04:40.301  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:40.315  1095  1219 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.music, service: sj
,07-05 14:04:40.315  1095  1219 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> sj without consulting the cloud.
07-05 14:04:40.316  1095  1219 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:40.316  1095  1219 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:40.327  1095  1219 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:40.327  1095  1219 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:40.327  1095  1219 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:40.327  1095  1219 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:40.327  1095  1219 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:40.327  1095  1219 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:40.327  1095  1219 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:04:40.335  3166  3166 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@de84bb7 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:04:40.338   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 26827, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:40.345   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 143148, reason: Periodic
,07-05 14:04:40.345  3166  3221 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
,07-05 14:04:40.346  3166  3221 W MusicSyncAdapter: Sync failed due to an authentication issue.
,07-05 14:04:40.346  3166  3166 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:04:40.400   534   565 I ActivityManager: Start proc 3230:com.google.android.apps.inputmethod.zhuyin/u0a54 for service com.google.android.apps.inputmethod.zhuyin/.preference.SyncService
,07-05 14:04:40.404  3166  3166 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:04:40.406  3166  3166 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@de84bb7 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:04:40.412  3166  3166 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:40.418  3166  3229 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 14:04:40.418  3166  3229 I MusicLeanback: Stop autocaching.
07-05 14:04:40.419  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:04:40.422   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 26827, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:40.426  3166  3166 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,07-05 14:04:40.427  3166  3166 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
,07-05 14:04:40.427  3166  3166 D MusicLifecycle: com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
07-05 14:04:40.427   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 144282, reason: Periodic
07-05 14:04:40.429  3230  3230 W System  : ClassLoader referenced unknown path: /system/app/GoogleZhuyinIME/lib/arm64
,07-05 14:04:40.440  3166  3166 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:40.441  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:04:40.492  1223  1223 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,07-05 14:04:40.518  3166  3166 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@de84bb7 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:04:40.521  3166  3166 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,07-05 14:04:40.527  3166  3166 D MusicLifecycle: com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,07-05 14:04:40.532  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:04:40.538  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@de84bb7 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:04:40.553  3166  3166 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:40.559  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:04:40.560  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:04:40.562  1223  3248 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=233:priority=5:group=main]
,07-05 14:04:40.578  3166  3166 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:40.583  3166  3166 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:04:40.584  3166  3252 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:04:40.585  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:04:40.598  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:04:40.599   534  2901 I ActivityManager: Killing 1986:com.google.android.keep/u0a72 (adj 15): empty #17
,07-05 14:04:40.715   534  1148 I ActivityManager: Killing 1537:com.google.android.talk/u0a56 (adj 15): empty #17
,07-05 14:04:40.747  1058  3259 I GCoreUlr: Uploading GCM registration ID for account#2#
,07-05 14:04:40.765  1058  3259 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:40.776  1058  3259 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,07-05 14:04:40.781  1058  3259 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,07-05 14:04:40.791  2843  2880 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:40.804  1095  1105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,07-05 14:04:40.804  1095  1105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud.
07-05 14:04:40.804  1095  1105 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:40.804  1095  1105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:40.822  1058  3259 E GCoreUlr: 
07-05 14:04:40.822  1058  3259 E GCoreUlr: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.location.reporting.d.c.a(SourceFile:164)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.location.reporting.d.g.a(SourceFile:94)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.location.reporting.service.u.b(SourceFile:220)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.location.reporting.service.u.a(SourceFile:173)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.location.reporting.service.t.a(SourceFile:151)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
07-05 14:04:40.822  1058  3259 E GCoreUlr: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,07-05 14:04:40.832   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 26827, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:40.833   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 143558, reason: Periodic
,07-05 14:04:40.889  3230  3257 E AndroidIME: com.google.android.apps.inputmethod.libs.hmm.sync.UserDictSyncTask: SyncUserDict
07-05 14:04:40.889  3230  3257 E AndroidIME: dj
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at dA.a(SourceFile:1280)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at dA.download(SourceFile:94)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at com.google.android.apps.inputmethod.libs.hmm.sync.UserDictSyncTask.downloadNewWords(SourceFile:176)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at com.google.android.apps.inputmethod.libs.hmm.sync.UserDictSyncTask.doInBackground(SourceFile:150)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at com.google.android.apps.inputmethod.libs.hmm.sync.UserDictSyncTask.doInBackground(SourceFile:31)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:04:40.889  3230  3257 E AndroidIME: 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:04:40.929   534   565 I ActivityManager: Start proc 3272:com.google.android.apps.docs.editors.docs/u0a41 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,07-05 14:04:40.937   534  1163 I ActivityManager: Killing 2820:com.google.android.apps.books/u0a28 (adj 15): empty #17
,07-05 14:04:40.987  3272  3272 W System  : ClassLoader referenced unknown path: /system/app/EditorsDocs/lib/arm64
,07-05 14:04:41.136  1095  1347 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,07-05 14:04:41.137  1095  1347 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud.
07-05 14:04:41.137  1095  1347 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:41.137  1095  1347 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:41.147  1223  3286 E RemindersSync: AuthError [T SyncAdapterThread-2:id=234:priority=5:group=main]
,07-05 14:04:41.177   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 31669, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:41.180   534   565 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 145339, reason: Periodic
,07-05 14:04:41.196   534   565 I ActivityManager: Start proc 3291:com.google.android.apps.docs/u0a40 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,07-05 14:04:41.253  3291  3291 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm64
,07-05 14:04:41.294   534   664 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,07-05 14:04:41.396  3272  3289 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:04:41.396  3272  3289 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:41.396  3272  3289 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:41.409  3291  3304 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:04:41.409  3291  3304 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:41.409  3291  3304 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:41.413  3272  3289 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:41.419  3272  3289 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:41.421  3291  3304 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:41.428  3291  3304 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:41.434  3272  3316 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:41.449  3272  3289 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.322.09.44
,07-05 14:04:41.444  3291  3318 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:41.489  3291  3304 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.44
,07-05 14:04:41.641   534   766 I ActivityManager: Killing 2659:com.google.android.apps.magazines/u0a62 (adj 15): empty #17
,07-05 14:04:41.716   534  3107 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@31817ad}
,07-05 14:04:41.731  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:41.768  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:41.779   534  1243 I ActivityManager: Killing 3045:com.google.android.configupdater/u0a36 (adj 15): empty #17
,07-05 14:04:41.824  3291  3335 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:41.893  3272  3325 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:41.929  3291  3335 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:41.950   534   565 I ActivityManager: Start proc 3349:com.google.android.apps.docs.editors.sheets/u0a42 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,07-05 14:04:41.983  2956  2975 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:41.990  3272  3325 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:41.993  3291  3335 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:42.011  3272  3325 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:42.190  2979  3000 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:42.220   534  1148 I ActivityManager: Killing 2445:com.google.android.apps.gcs/u0a83 (adj 15): empty #17
,07-05 14:04:42.238  3291  3340 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
,07-05 14:04:42.239  3291  3340 E BaseSyncManager: ClientFlagSyncException
07-05 14:04:42.239  3291  3340 E BaseSyncManager: cfk$a: IO Exception opening: https://ssl.gstatic.com/docs/android/drive/client_flags?1467720281801= stream was reset: PROTOCOL_ERROR
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cfk.a(PG:1108)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at dpe.a(PG:18060)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at dph.run(PG:9612)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at dpf.run(PG:3031)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: Caused by: java.io.IOException: stream was reset: PROTOCOL_ERROR
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hun.b(PG:145)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at htk.b(PG:104)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hsx.d(PG:917)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hsx.a(PG:95)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hsx$a.a(PG:902)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hrj.a(PG:50089)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hrj$a.a(PG:230)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at hrj.a(PG:3201)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cpx.a(PG:156)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnk.a(PG:47)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnj.a(PG:22)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnl.a(PG:69)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnp.b(PG:96)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnp.a(PG:84)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnn.b(PG:5140)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cnn.a(PG:1096)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	at cfk.a(PG:2062)
07-05 14:04:42.239  3291  3340 E BaseSyncManager: 	... 3 more
,07-05 14:04:42.353  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:42.366  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
07-05 14:04:42.367  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud.
07-05 14:04:42.367  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:42.367  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:42.375  1095  1348 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:42.375  1095  1348 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:42.375  1095  1348 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:42.375  1095  1348 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:42.375  1095  1348 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:42.375  1095  1348 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:42.375  1095  1348 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:42.377  3291  3340 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
07-05 14:04:42.377  3291  3340 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
,07-05 14:04:42.379  3291  3340 E BaseSyncManager: AuthenticatorException
07-05 14:04:42.379  3291  3340 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:04:42.379  3291  3340 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:04:42.379  3291  3340 E BaseSyncManager: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:04:42.379  3291  3340 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:04:42.379  3291  3340 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:04:42.379  3291  3340 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:42.382   534  3107 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@31817ad}
,07-05 14:04:42.390   534  1148 I ActivityManager: Killing 3074:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-05 14:04:42.487  3349  3364 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:04:42.487  3349  3364 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:42.487  3349  3364 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:42.502  3349  3364 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:42.506  3349  3364 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:42.521  3349  3364 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.44
,07-05 14:04:42.523  3349  3381 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:42.660  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:42.688   534  3107 I ActivityManager: Killing 2778:com.google.android.apps.photos/u0a66 (adj 15): empty #17
,07-05 14:04:42.749  3349  3386 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:04:42.781  3349  3386 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:42.801  3349  3386 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:44.284  1095  1095 I ConfigService: onDestroy,
,07-05 14:04:45.011  3166  3166 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@de84bb7 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:04:45.021  3166  3166 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:04:45.030  3166  3166 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:04:45.032  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@de84bb7 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:04:45.039  3166  3399 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 14:04:45.039  3166  3399 I MusicLeanback: Stop autocaching.
07-05 14:04:45.040  3166  3166 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:45.047  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:04:45.054  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:04:45.055  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:04:45.061  3166  3166 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-05 14:04:45.062  3166  3166 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
07-05 14:04:45.063  3166  3166 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:04:45.071  3166  3402 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:04:45.073  3166  3166 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:04:45.720   534  1243 I ActivityManager: Killing 3112:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,07-05 14:04:45.758   534   665 D WifiService: Client connection lost with reason: 4
,07-05 14:04:48.091   534   656 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:04:48.095   534   567 I ActivityManager: Start proc 3405:com.google.android.googlequicksearchbox:search/u0a22 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,07-05 14:04:48.207   534   591 W PackageSettings: Skipping PackageSetting{beeeb92 com.example.hello/10095} due to missing metadata
,07-05 14:04:48.258  1058  1058 V GmsNetworkLocationProvi: DISABLE
,07-05 14:04:48.264  1058  1058 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 14:04:48.307   534   565 D ActivityRecognitionProxy: AR HW instance not available, binding will be a no-op.
,07-05 14:04:48.374   534  3107 I ActivityManager: Start proc 3425:com.google.android.partnersetup/u0a11 for content provider com.google.android.partnersetup/.RlzAppProvider
,07-05 14:04:48.392   534  1160 I ActivityManager: Start proc 3436:com.google.android.talk/u0a56 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,07-05 14:04:48.406   534  1243 I ActivityManager: Killing 2979:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,07-05 14:04:48.455  3425  3425 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,07-05 14:04:48.473  3436  3436 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-05 14:04:48.643  3436  3457 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-05 14:04:48.643  3436  3457 I Babel_SMS: MmsConfig.loadMmsSettings
,07-05 14:04:48.664  3436  3457 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=, mUaProfUrl=
,07-05 14:04:48.665  3436  3457 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 14:04:48.682  3436  3457 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-05 14:04:48.682  3436  3457 I Babel_SMS: MmsConfig.loadFromResources
07-05 14:04:48.683  3436  3457 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 14:04:48.685  3436  3457 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Hangouts/4.1.102314611, mUaProfUrl=https://ssl.gstatic.com/android/hangouts/hangouts_mms_ua_profile.xml
,07-05 14:04:48.686  3436  3436 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:04:48.701  3436  3436 I Babel_Crash: startup - clean
,07-05 14:04:48.745   534   755 I ActivityManager: Start proc 3460:com.android.vending/u0a16 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,07-05 14:04:48.801  3460  3460 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm64
,07-05 14:04:48.859  3436  3436 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-05 14:04:48.886  3436  3436 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 14:04:48.890  3436  3436 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-05 14:04:48.892  3436  3436 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-05 14:04:48.894  3436  3436 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-05 14:04:48.898  3436  3436 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-05 14:04:48.926  3436  3436 I vclib   : onServiceConnected
,07-05 14:04:48.938  3460  3460 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-05 14:04:48.946  3436  3479 I Babel   : deleted: false for 0
,07-05 14:04:49.008  3460  3460 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,07-05 14:04:49.013  3436  3436 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:04:49.016  3460  3460 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 14:04:49.017  3460  3460 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 14:04:49.055  3460  3460 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-05 14:04:49.055  3460  3460 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,07-05 14:04:49.056  3460  3498 D Ads     : Skipping gmscore version check
,07-05 14:04:49.062  3460  3498 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186446
,07-05 14:04:49.097   534  1117 I ActivityManager: Killing 3012:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-05 14:04:49.122  3460  3460 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-05 14:04:49.127  1223  3500 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:04:49.131  1223  3500 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-05 14:04:49.139  3405  3501 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 14:04:49.147   534   755 I ActivityManager: Start proc 3503:com.google.android.apps.plus/u0a68 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-05 14:04:49.168  1223  1320 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-05 14:04:49.183  3460  3460 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-05 14:04:49.213  3503  3503 W System  : ClassLoader referenced unknown path: /system/app/PlusOne/lib/arm
,07-05 14:04:49.256  3436  3436 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:49.306  3436  3436 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:49.345  3405  3501 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
,07-05 14:04:49.500   534   664 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-05 14:04:49.508   534   755 I ActivityManager: Killing 2865:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-05 14:04:53.306   534  3107 I ActivityManager: Killing 2956:com.google.android.gm/u0a71 (adj 15): empty #17
,07-05 14:04:54.024  3460  3460 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-05 14:04:54.084  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:54.091  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:54.092  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:54.114  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-05 14:04:54.114  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:04:54.114  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:54.114  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.150  3460  3460 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:04:54.155  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:54.166  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:04:54.166  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:04:54.166  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:54.166  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.186  3460  3529 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186446
,07-05 14:04:54.188  3460  3460 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,07-05 14:04:54.189  3460  3460 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,07-05 14:04:54.220  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:54.233  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:04:54.233  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:04:54.233  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:54.233  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.241  3460  3460 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:04:54.241  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:04:54.242  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-05 14:04:54.253  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:04:54.253  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:04:54.253  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:54.253  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.262  3460  3460 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:04:54.304  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:54.314  1095  3124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-05 14:04:54.314  1095  3124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:04:54.314  1095  3124 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:54.314  1095  3124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.322  3460  3460 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:04:54.323  3460  3460 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-05 14:04:54.324  3460  3460 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-05 14:04:54.327  3460  3530 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186446,
07-05 14:04:54.329  3460  3460 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,07-05 14:04:54.332  3460  3460 D Finsky  : [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,07-05 14:04:54.347  3460  3460 D Finsky  : [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,07-05 14:04:54.365  3460  3499 D Finsky  : [336] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.earth for verification
,07-05 14:04:54.377  3460  3529 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186446
,07-05 14:04:54.649  3460  3484 I qtaguid : Failed write_ctrl(u 29) res=-1 errno=22
,07-05 14:04:54.652  3460  3484 I qtaguid : Untagging socket 29 failed errno=-22
,07-05 14:04:54.652  3460  3484 W NetworkManagementSocketTagger: untagSocket(29) failed with errno -22
,07-05 14:04:54.676   534   755 I ActivityManager: Killing 2843:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-05 14:05:12.770   534   565 I ActivityManager: Start proc 3533:com.google.android.keep/u0a72 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,07-05 14:05:12.815   534   565 I ActivityManager: Start proc 3543:com.google.android.apps.books/u0a28 for service com.google.android.apps.books/.service.SyncService
,07-05 14:05:12.894  3533  3533 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm64
,07-05 14:05:12.931  3543  3543 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm64
,07-05 14:05:13.238  3533  3561 V KeepSync: Connecting to GoogleApiClient
,07-05 14:05:13.239   534  3107 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-05 14:05:13.264  3543  3543 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:05:13.274  3543  3543 I BooksApp: Created application version: 3.6.9 (30609)
,07-05 14:05:13.280  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:05:13.280  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:13.295  1095  1105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:05:13.295  1095  1105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-05 14:05:13.295  1095  1105 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.295  1095  1105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.308  1223  3571 V BaseAuthAsyncOperation: access token request failed
,07-05 14:05:13.310  3533  3561 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:05:13.329  3543  3575 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:05:13.396  1095  1347 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:05:13.396  1095  1347 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:05:13.396  1095  1347 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.396  1095  1347 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.433  3533  3561 E KeepSync: IOException
07-05 14:05:13.433  3533  3561 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:05:13.433  3533  3561 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:05:13.433  3533  3561 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:05:13.433  3533  3561 E KeepSync: 	... 10 more
,07-05 14:05:13.433  3533  3561 W KeepSync: Sync result 2
,07-05 14:05:13.437   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 139021, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:05:13.451  3543  3581 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-05 14:05:13.477  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:05:13.477  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:05:13.477  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.477  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.500  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:05:13.500  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:05:13.500  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.500  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.512  3543  3581 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:05:13.513  3543  3575 E BooksSync: Soft error
07-05 14:05:13.513  3543  3575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:05:13.513  3543  3575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:05:13.513  3543  3575 E BooksSync: Sync error
07-05 14:05:13.513  3543  3575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:05:13.513  3543  3575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:05:13.513  3543  3575 I BooksSync: Finished books sync
,07-05 14:05:13.516   534   766 I ActivityManager: Killing 3203:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
,07-05 14:05:13.517   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140059, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:05:13.840   534  2901 I ActivityManager: Killing 3190:com.google.android.apps.cloudprint:sync/u0a35 (adj 15): empty #17
,07-05 14:05:14.351   534  1163 I ActivityManager: Start proc 3584:com.google.android.apps.gcs/u0a83 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,07-05 14:05:14.398   534  1244 I ActivityManager: Start proc 3596:com.google.android.youtube/u0a81 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:05:14.440  3584  3584 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,07-05 14:05:14.494  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:14.508  3596  3596 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,07-05 14:05:14.519  3584  3584 W InstanceID/Rpc: Found 10007
,07-05 14:05:14.520  1095  1219 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-05 14:05:14.520  1095  1219 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:05:14.520  1095  1219 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:14.520  1095  1219 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:05:14.534  3584  3584 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-05 14:05:14.540  3460  3460 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:05:14.540  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:05:14.540  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-05 14:05:14.584  3596  3620 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-05 14:05:14.598  3584  3619 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:05:14.636  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:05:14.636  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:05:14.636  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:14.637  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:14.665  3596  3620 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:14.695  3596  3620 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:14.700  3584  3619 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:05:14.703  3584  3619 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:05:14.706   534  3107 I ActivityManager: Killing 2745:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,07-05 14:05:14.767  3596  3596 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 14:05:14.879  3632  3632 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1045426031.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1045426031.dex
,07-05 14:05:14.886  3596  3596 W InstanceID/Rpc: Found 10007
,07-05 14:05:14.952  3584  3679 V GoogleAuthProtoRequest: [338] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:05:14.968  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-05 14:05:14.968  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:05:14.968  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:14.968  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:05:14.980  3584  3679 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:05:14.983   534  2901 I ActivityManager: Killing 3230:com.google.android.apps.inputmethod.zhuyin/u0a54 (adj 15): empty #17
,07-05 14:05:15.004  3632  3632 I dex2oat : dex2oat took 125.287ms (threads: 2) arena alloc=177KB java alloc=33KB native alloc=758KB free=65KB
,07-05 14:05:17.908  3533  3540 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@21fe6e1)
,07-05 14:05:18.264  3543  3569 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:05:18.461   534   580 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:05:18.468   534   580 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:05:18.479   994   994 I Keyboard.Facilitator: onFinishInput()
,07-05 14:05:18.490   171   176 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (608 us)
,07-05 14:05:18.622  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:05:18.624  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:05:18.652  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ab42e5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@cc00d63, 16908290=android.view.AbsSavedState$1@cc00d63}, android:focusedViewId=100}]}]
,07-05 14:05:18.652  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:05:18.653  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:05:18.653  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:05:19.208   534   580 V KeyguardServiceDelegate: onScreenTurnedOff(),
,07-05 14:05:19.228   534   580 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-05 14:05:19.229   534   578 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-05 14:05:19.229   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55922aa430
07-05 14:05:19.240   171   171 D hwcomposer: hwc_blank: display 0: blank
07-05 14:05:19.240   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-05 14:05:19.543   534   683 D SurfaceControl: Excessive delay in setPowerMode(): 314ms
,07-05 14:05:19.621   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:05:19.637   534   664 E native  : do suspend false
,07-05 14:05:19.644   534   664 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:05:19.841   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:05:19.844   534   664 E native  : do suspend true
,07-05 14:05:20.127   534   664 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,07-05 14:05:22.000  1058  1472 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:05:23.341  3460  3471 D Finsky  : [313] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-05 14:05:23.356  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:23.366  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:23.369  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:23.401  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:05:23.401  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:05:23.401  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:23.402  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:23.426  3460  3471 D Finsky  : [313] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-05 14:05:29.511   534   664 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,07-05 14:05:34.667  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:34.673  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:34.675  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:34.696  1095  3124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:05:34.697  1095  3124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:05:34.697  1095  3124 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:34.697  1095  3124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:34.713  3460  3460 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:05:34.714  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:05:34.714  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-05 14:05:54.904  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:54.910  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:54.911  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:54.932  1095  3124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:05:54.932  1095  3124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:05:54.932  1095  3124 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:54.932  1095  3124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:54.948  3460  3460 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:05:54.949  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:05:54.949  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-05 14:05:57.563  2415  2482 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-05 14:06:12.687   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:06:15.072  3533  3698 V KeepSync: Connecting to GoogleApiClient
,07-05 14:06:15.073   534  1117 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-05 14:06:15.131  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:15.134  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:15.149  3584  3700 V GoogleAuthProtoRequest: [339] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:06:15.158  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:06:15.158  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-05 14:06:15.158  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:15.158  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:15.177  1223  3701 V BaseAuthAsyncOperation: access token request failed
,07-05 14:06:15.180  3533  3698 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:06:15.187  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-05 14:06:15.187  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:06:15.187  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:15.187  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:15.210  3584  3700 W ExperimentUpdateService: [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:06:15.211  3584  3700 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:06:15.236  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:15.265  1095  1219 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:06:15.266  1095  1219 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:06:15.266  1095  1219 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:15.266  1095  1219 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:15.278  1095  3124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:06:15.279  1095  3124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:06:15.279  1095  3124 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:06:15.280  1095  3124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:15.283  3460  3460 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:06:15.283  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:06:15.283  3460  3460 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-05 14:06:15.304  3533  3698 E KeepSync: IOException
07-05 14:06:15.304  3533  3698 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:06:15.304  3533  3698 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:06:15.304  3533  3698 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:06:15.304  3533  3698 E KeepSync: 	... 10 more
,07-05 14:06:15.304  3533  3698 W KeepSync: Sync result 2
,07-05 14:06:15.308   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 207110, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:06:18.489   994  3149 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-05 14:06:18.490   994  3149 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:06:18.517  1095  1095 I ConfigService: onCreate
,07-05 14:06:23.600  1095  1095 I ConfigService: onDestroy
,07-05 14:06:37.287   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:06:45.611  3543  3703 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:06:45.663  3543  3704 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-05 14:06:45.690  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:45.696  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:45.717  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:06:45.717  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:06:45.717  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:45.717  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:45.739  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:45.741  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:45.760  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:06:45.760  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:06:45.760  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:45.761  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:45.775  3543  3704 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:45.776  3543  3703 E BooksSync: Soft error
07-05 14:06:45.776  3543  3703 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:45.776  3543  3703 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:06:45.776  3543  3703 E BooksSync: Sync error
07-05 14:06:45.776  3543  3703 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:45.776  3543  3703 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:06:45.776  3543  3703 I BooksSync: Finished books sync
,07-05 14:06:45.783   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 208357, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:07:07.087   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=259251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:07:13.346  1095  1242 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:08:15.257  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:15.260  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:15.274  3584  3706 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:08:15.301  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:08:15.301  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:08:15.302  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:15.302  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:15.318  3584  3706 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:08:15.319  3584  3706 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:08:18.402  3533  3707 V KeepSync: Connecting to GoogleApiClient
,07-05 14:08:18.403   534  1160 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-05 14:08:18.478  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:08:18.478  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:08:18.478  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:18.479  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:18.497  1223  3708 V BaseAuthAsyncOperation: access token request failed
,07-05 14:08:18.498  3533  3707 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:08:18.554  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:08:18.555  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:08:18.555  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:18.555  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:18.570  3533  3707 E KeepSync: IOException
07-05 14:08:18.570  3533  3707 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:08:18.570  3533  3707 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:08:18.570  3533  3707 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:08:18.570  3533  3707 E KeepSync: 	... 10 more
,07-05 14:08:18.570  3533  3707 W KeepSync: Sync result 2
,07-05 14:08:18.576   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 330491, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:08:34.874   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:08:51.353  3543  3710 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:08:51.399  3543  3711 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-05 14:08:51.423  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:51.427  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:51.470  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:08:51.471  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:08:51.471  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:51.471  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:51.520  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:51.525  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:51.569  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:08:51.569  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:08:51.570  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:51.570  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:51.591  3543  3711 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:08:51.592  3543  3710 E BooksSync: Soft error
07-05 14:08:51.592  3543  3710 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:08:51.592  3543  3710 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:08:51.593  3543  3710 E BooksSync: Sync error
07-05 14:08:51.593  3543  3710 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:08:51.593  3543  3710 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:08:51.593  3543  3710 I BooksSync: Finished books sync
,07-05 14:08:51.599   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 363299, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:09:04.634   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=376798, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:09:34.727   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=406890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:09:49.154  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:49.174  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:49.179  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:49.228  1095  3124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:09:49.228  1095  3124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:09:49.228  1095  3124 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:09:49.229  1095  3124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:09:49.264  1095  3124 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:09:49.264  1095  3124 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:09:49.264  1095  3124 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:09:49.264  1095  3124 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:09:49.264  1095  3124 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:09:49.264  1095  3124 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:09:49.264  1095  3124 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:09:49.274  3460  3494 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:09:49.274  3460  3494 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:09:49.274  3460  3494 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:09:49.274  3460  3494 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:09:49.274  3460  3494 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:09:49.274  3460  3494 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:09:49.274  3460  3494 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:11:11.567   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=503730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:12:15.389  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:15.391  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:15.402  3584  3759 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:12:15.424  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:12:15.424  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:12:15.424  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:12:15.424  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:12:15.439  3584  3759 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:12:15.440  3584  3759 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:12:24.692  3533  3760 V KeepSync: Connecting to GoogleApiClient
07-05 14:12:24.694   534  1148 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-05 14:12:24.760  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:24.762  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:24.783  1095  1347 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:12:24.783  1095  1347 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:12:24.783  1095  1347 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:12:24.783  1095  1347 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:12:24.797  1223  3761 V BaseAuthAsyncOperation: access token request failed
,07-05 14:12:24.798  3533  3760 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:12:24.847  1095  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:12:24.847  1095  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 14:12:24.847  1095  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:12:24.847  1095  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:12:24.863  3533  3760 E KeepSync: IOException
07-05 14:12:24.863  3533  3760 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:12:24.863  3533  3760 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:12:24.863  3533  3760 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:12:24.863  3533  3760 E KeepSync: 	... 10 more
07-05 14:12:24.863  3533  3760 W KeepSync: Sync result 2
,07-05 14:12:24.867   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 576773, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:13:02.540  3543  3762 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:13:02.559  3543  3763 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-05 14:13:02.568  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:13:02.571  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:13:02.596  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:13:02.596  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:13:02.596  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:13:02.596  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:13:02.617  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:13:02.619  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:13:02.638  1095  1347 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 14:13:02.638  1095  1347 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-05 14:13:02.638  1095  1347 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:13:02.638  1095  1347 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:13:02.657  3543  3763 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:13:02.657  3543  3762 E BooksSync: Soft error
07-05 14:13:02.657  3543  3762 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:13:02.657  3543  3762 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:13:02.657  3543  3762 E BooksSync: Sync error
07-05 14:13:02.657  3543  3762 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:13:02.657  3543  3762 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:13:02.658  3543  3762 I BooksSync: Finished books sync
,07-05 14:13:02.665   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 614468, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:13:54.742   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=666905, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:14:24.527   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=696691, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:14:46.634   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=718797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:15:12.527   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=744690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:15:35.891   534   656 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-05 14:15:35.893   534   534 V KeyguardServiceDelegate: onStartedWakingUp()
,07-05 14:15:35.901   534   580 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 14:15:35.925   534   580 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@bd51c36)
07-05 14:15:35.925  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 14:15:35.926  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 14:15:35.926  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-05 14:15:35.926  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-05 14:15:35.945   171   171 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x55922aa430
07-05 14:15:35.945   171   171 D hwcomposer: hwc_blank: display 0: unblank
07-05 14:15:35.945   171   171 D hwcomposer: hwc_blank_display: display 0: [1 -> 0]
,07-05 14:15:35.945   171   171 D hwcomposer: Display 0 layer clip is 1536 x 2048
,07-05 14:15:35.945   171   171 D hwcomposer: Display 0 device clip is 1536 x 2048
07-05 14:15:35.945   534   578 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-05 14:15:35.954   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
07-05 14:15:35.960   534   755 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 14:15:35.983   534   664 E native  : do suspend false
07-05 14:15:35.988   994   994 I Keyboard.Facilitator: onFinishInput()
07-05 14:15:35.992   534   664 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:15:36.016   534   568 I CwMcuSensor: CwMcuSensor::flush: fd = 198, sensors_id = 0, path = /sys/class/htc_sensorhub/sensor_hub/flush, err = 0
,07-05 14:15:36.017   534   580 I DisplayPowerController: Unblocked screen on after 115 ms
07-05 14:15:36.017   534   580 V KeyguardServiceDelegate: onScreenTurnedOn()
07-05 14:15:36.019  1058  1058 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,07-05 14:15:36.035   534  1148 I ActivityManager: Start proc 3783:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-05 14:15:36.094  3783  3783 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm64
,07-05 14:15:36.204   534  2901 I ActivityManager: Start proc 3796:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-05 14:15:36.204   534  2901 I ActivityManager: Killing 3272:com.google.android.apps.docs.editors.docs/u0a41 (adj 15): empty #17
,07-05 14:15:36.255   534   683 D SurfaceControl: Excessive delay in setPowerMode(): 310ms
,07-05 14:15:36.265  3796  3796 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,07-05 14:15:36.321  3796  3796 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:15:36.321  3796  3796 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:15:36.321  3796  3796 I GAv4    :   adb logcat -s GAv4
,07-05 14:15:36.330  3796  3796 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:36.334  3796  3796 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:36.342  3796  3811 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:36.385   534   766 I ActivityManager: Killing 3349:com.google.android.apps.docs.editors.sheets/u0a42 (adj 15): empty #17
,07-05 14:15:39.000   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:15:41.006   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=773170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:15:42.021   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:16:06.180   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=798344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:16:27.350   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:16:30.377   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:16:36.029   994  3149 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-05 14:16:36.029   994  3149 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:16:36.064  1095  1095 I ConfigService: onCreate
,07-05 14:16:36.419   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:16:39.443   534   666 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:16:41.153  1095  1095 I ConfigService: onDestroy
,07-05 14:17:36.026  1058  1472 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:17:36.842   534   580 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 14:17:36.845   534   580 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:17:36.919   994   994 I Keyboard.Facilitator: onFinishInput()
,07-05 14:17:36.941  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:17:36.941  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:17:36.965  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ab42e5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@cc00d63, 16908290=android.view.AbsSavedState$1@cc00d63}, android:focusedViewId=100}]}]
07-05 14:17:36.965  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:17:36.965  2340  2340 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:17:36.965  2340  2340 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:17:37.406   534   580 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 14:17:37.420   534   578 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:17:37.420   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55922aa430
07-05 14:17:37.421   171   171 D hwcomposer: hwc_blank: display 0: blank
07-05 14:17:37.421   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-05 14:17:37.742   534   683 D SurfaceControl: Excessive delay in setPowerMode(): 321ms
,07-05 14:17:37.768   534   664 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:17:37.784   534   664 E native  : do suspend true
,07-05 14:18:12.847   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=925011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:18:29.220   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=941384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:18:36.921   994  3149 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-05 14:18:36.921   994  3149 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:18:36.966  1095  1095 I ConfigService: onCreate
,07-05 14:18:42.064  1095  1095 I ConfigService: onDestroy
,07-05 14:19:25.868  2415  2432 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 14:20:15.470  1223  3819 I EventLogService: Aggregate from 1467720270809 (log), 1467719152260 (data)
,07-05 14:20:15.559  1223  1223 I GCM     : Message from null null
,07-05 14:20:15.559  1223  1223 E GCM     : Dropping message from null
,07-05 14:20:15.575  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:15.578  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:15.590  3584  3822 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:20:15.621  1095  1348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:20:15.622  1095  1348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:20:15.622  1095  1348 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:15.622  1095  1348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:15.636  3584  3822 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:20:15.637  3584  3822 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:20:20.434   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1052597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:20:31.886   534  2539 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1064050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:20:37.031  3533  3823 V KeepSync: Connecting to GoogleApiClient
,07-05 14:20:37.032   534   553 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-05 14:20:37.137  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:37.143  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:37.193  1095  1841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:20:37.194  1095  1841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:20:37.194  1095  1841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:37.195  1095  1841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:37.234  1223  3824 V BaseAuthAsyncOperation: access token request failed
,07-05 14:20:37.239  3533  3823 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:20:37.353  1095  1219 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-05 14:20:37.353  1095  1219 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 14:20:37.353  1095  1219 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:37.353  1095  1219 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:37.369  3533  3823 E KeepSync: IOException
07-05 14:20:37.369  3533  3823 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:20:37.369  3533  3823 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:20:37.369  3533  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:20:37.369  3533  3823 E KeepSync: 	... 10 more
07-05 14:20:37.369  3533  3823 W KeepSync: Sync result 2
,07-05 14:20:37.374   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1069098, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:21:24.378  3543  3825 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:21:24.413  3543  3826 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-05 14:21:24.428  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:24.432  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:24.470  1095  1347 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:21:24.471  1095  1347 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:21:24.471  1095  1347 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:24.471  1095  1347 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:24.504  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:24.508  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:24.533  1095  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:21:24.533  1095  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:21:24.534  1095  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:24.534  1095  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:24.551  3543  3826 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:21:24.553  3543  3825 E BooksSync: Soft error
07-05 14:21:24.553  3543  3825 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:21:24.553  3543  3825 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:21:24.553  3543  3825 E BooksSync: Sync error
07-05 14:21:24.553  3543  3825 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:21:24.553  3543  3825 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:21:24.554  3543  3825 I BooksSync: Finished books sync
,07-05 14:21:24.561   534   565 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1116238, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:23:07.499   534   565 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms)
```
