#### Test 7214543196063dc_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
,07-05 14:04:09.783  2545  2580 I Finsky  : [222] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
07-05 14:04:09.937  2545  2580 I Finsky  : [222] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
07-05 14:04:09.937  2545  2545 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
07-05 14:04:10.356  3163  3163 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:04:10.360  3163  3163 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:10.394  3163  3163 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:04:10.429  3163  3163 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:04:10.448  3163  3163 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 14:04:10.451   789   972 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:04:10.478   789   972 I ActivityManager: Start proc 3179:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-05 14:04:10.481  3163  3163 D AndroidRuntime: Shutting down VM
07-05 14:04:10.562  3179  3179 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-05 14:04:10.591  3179  3179 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3062-3064)
07-05 14:04:10.591  3179  3179 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:10.609  3179  3179 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a635ebe}
07-05 14:04:10.610  3179  3179 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:10.610  3179  3179 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:10.615  3179  3179 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:10.616  3179  3179 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 14:04:10.621  3179  3194 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-05 14:04:10.625  3179  3179 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 14:04:10.629  3179  3179 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:10.629  3179  3179 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:10.630  3179  3179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-05 14:04:10.685   789   809 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a480c88:true
,07-05 14:04:10.750  3179  3179 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 14:04:10.760  3179  3179 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-05 14:04:10.804  3179  3216 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-05 14:04:10.823  3179  3203 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-05 14:04:10.856  3179  3216 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:04:10.881  1225  1225 I Keyboard.Facilitator: onFinishInput()
07-05 14:04:10.899   789   810 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +390ms (total +432ms)
07-05 14:04:10.984  3179  3179 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3179
07-05 14:04:11.067  3179  3179 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-05 14:04:11.183  3179  3219 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1641363152
07-05 14:04:11.188  3179  3219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:11.188  3179  3219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:11.188  3179  3219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:11.188  3179  3219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:11.188  3179  3219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 14:04:11.188  3179  3219 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8190ead added. We now have 1 listener(s)
07-05 14:04:11.191  3179  3219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
07-05 14:04:11.193  3179  3219 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-05 14:04:11.194  3179  3219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:04:11.194  3179  3219 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:11.197  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:11.198  3179  3219 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb9430 added. We now have 1 listener(s)
07-05 14:04:11.198  3179  3219 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 14:04:11.208   789   895 D WifiService: New client listening to asynchronous messages
07-05 14:04:11.208  3179  3219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:11.209  3179  3219 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-05 14:04:11.210  3179  3219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 14:04:11.210  3179  3219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 14:04:11.210  3179  3219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 14:04:11.210  3179  3219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-05 14:04:11.212  3179  3219 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 14:04:11.212  3179  3219 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
07-05 14:04:11.214  3179  3219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:11.215  3179  3219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:11.215  3179  3219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:11.215  3179  3219 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 14:04:11.215  3179  3219 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 14:04:11.232  3179  3179 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:11.914  3179  3226 W jxcore-log: Initializing JXcore engine
07-05 14:04:11.914  3179  3226 W jxcore-log: JXcore engine is ready
07-05 14:04:11.938  3226  3226 W Thread-257: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8453]" dev="sockfs" ino=8453 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 14:04:11.938  3226  3226 W Thread-257: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:04:11.938  3226  3226 W Thread-257: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20817]" dev="sockfs" ino=20817 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 14:04:11.963  3179  3226 W jxcore-log: Starting JXcore engine
07-05 14:04:12.043  3179  3226 W jxcore-log: Platform android
07-05 14:04:12.043  3179  3226 W jxcore-log: 
07-05 14:04:12.043  3179  3226 W jxcore-log: Process ARCH arm
07-05 14:04:12.043  3179  3226 W jxcore-log: 
07-05 14:04:12.236  3179  3226 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:12.236  3179  3226 I jxcore-log: 
07-05 14:04:12.236  3179  3226 W jxcore-log: JXcore engine is started
07-05 14:04:12.238  3179  3219 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-05 14:04:12.240  3179  3179 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:21.919  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:21.919  3179  3226 I jxcore-log: 
,07-05 14:04:21.921  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:21.921  3179  3226 I jxcore-log: 
,07-05 14:04:21.923  3179  3226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:21.923  3179  3226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:21.923  3179  3226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:21.923  3179  3226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-05 14:04:21.924  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:21.924  3179  3226 I jxcore-log: 
07-05 14:04:21.926  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:21.926  3179  3226 I jxcore-log: 
,07-05 14:04:22.291  3179  3226 I jxcore-log: Unit Test app is loaded
07-05 14:04:22.291  3179  3226 I jxcore-log: 
,07-05 14:04:22.298  3179  3179 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:22.298  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-05 14:04:22.298  3179  3226 I jxcore-log: 
,07-05 14:04:22.303   789   974 D WifiService: setWifiEnabled: true pid=3179, uid=10000
07-05 14:04:22.303   789   974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-05 14:04:22.312   194   655 D SoftapController: Softap fwReload - Ok
07-05 14:04:22.317  3179  3226 I jxcore-log: My device name is: LGE-Nexus 5
07-05 14:04:22.317  3179  3226 I jxcore-log: 
07-05 14:04:22.318   194   655 D CommandListener: Setting iface cfg
07-05 14:04:22.318   194   655 D CommandListener: Trying to bring down wlan0
07-05 14:04:22.321   194   655 D CommandListener: Clearing all IP addresses on wlan0
07-05 14:04:22.323   789   894 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-05 14:04:22.324   789   809 I ActivityManager: Start proc 3230:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-05 14:04:22.438  3230  3230 D AdapterServiceConfig: Adding HeadsetService
07-05 14:04:22.438  3230  3230 D AdapterServiceConfig: Adding A2dpService
,07-05 14:04:22.439  3230  3230 D AdapterServiceConfig: Adding HidService
07-05 14:04:22.439  3230  3230 D AdapterServiceConfig: Adding HealthService
07-05 14:04:22.439  3230  3230 D AdapterServiceConfig: Adding PanService
07-05 14:04:22.439  3230  3230 D AdapterServiceConfig: Adding GattService
07-05 14:04:22.439  3230  3230 D AdapterServiceConfig: Adding BluetoothMapService
,07-05 14:04:22.456   789   809 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@be46ee8:true
,07-05 14:04:22.457  3230  3230 D BluetoothAdapterState: make() - Creating AdapterState
,07-05 14:04:22.459  3230  3230 I bt_bluedroid: init
,07-05 14:04:22.459  3230  3254 I BluetoothAdapterState: Entering OffState
,07-05 14:04:22.469  3230  3255 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-05 14:04:22.469  3230  3255 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-05 14:04:22.469  3230  3255 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-05 14:04:22.469  3230  3255 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-05 14:04:22.470  3230  3230 I bt_bluedroid: get_profile_interface socket
,07-05 14:04:22.474  3230  3258 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-05 14:04:22.475  3230  3258 D BluetoothAdapterProperties: Name is: Nexus 5
,07-05 14:04:22.475  3230  3230 I bt_bluedroid: get_profile_interface sdp
,07-05 14:04:22.478  3230  3240 I bt_bluedroid: config_hci_snoop_log
,07-05 14:04:22.479   789   809 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,07-05 14:04:22.483  3230  3254 D BluetoothAdapterState: Current state: OFF, message: 0
,07-05 14:04:22.484  3230  3254 D BluetoothAdapterProperties: Setting state to 14
,07-05 14:04:22.484  3230  3254 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-05 14:04:22.486  3230  3254 D BluetoothBondStateMachine: make
,07-05 14:04:22.488  3230  3259 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-05 14:04:22.489  3230  3254 I BluetoothAdapterState: Entering PendingCommandState
07-05 14:04:22.490  3230  3230 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-05 14:04:22.492  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
,07-05 14:04:22.492  3230  3230 D BtGatt.DebugUtils: handleDebugAction() action=null
07-05 14:04:22.492  3230  3230 D BtGatt.GattService: Received start request. Starting profile...
07-05 14:04:22.492  3230  3230 D BtGatt.GattService: start()
,07-05 14:04:22.494  3230  3230 I bt_bluedroid: get_profile_interface gatt
,07-05 14:04:22.494  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
07-05 14:04:22.494  3230  3230 D BtGatt.AdvertiseManager: advertise manager created
,07-05 14:04:22.499  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:22.499  3230  3230 V BluetoothAdapterState: isTurningOn()=false
07-05 14:04:22.499  3230  3230 V BluetoothAdapterState: isBleTurningOn()=true
,07-05 14:04:22.500  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
,07-05 14:04:22.502  3230  3254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-05 14:04:22.502  3230  3254 I bt_bluedroid: enable
07-05 14:04:22.502  3230  3255 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-05 14:04:22.503  3230  3255 I bt_hci  : start_up
,07-05 14:04:22.508  3230  3255 I bt_vendor: alloc value 0xb39a5631
,07-05 14:04:22.508  3230  3255 I bt_vendor: init
07-05 14:04:22.509  3230  3255 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-05 14:04:22.509  3230  3255 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-05 14:04:22.548  3230  3255 D bt_hci  : start_up starting async portion
07-05 14:04:22.548  3230  3262 I bt_hci  : event_finish_startup
,07-05 14:04:22.548  3230  3262 I bt_hci_h4: hal_open
07-05 14:04:22.548  3230  3262 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-05 14:04:22.552  3230  3262 I bt_userial_vendor: device fd = 49 open
,07-05 14:04:22.633  3230  3262 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-05 14:04:22.660  3230  3262 D bt_hwcfg: Chipset BCM4335C0
,07-05 14:04:22.660  3230  3262 D bt_hwcfg: Target name = [BCM4335C0]
07-05 14:04:22.661  3230  3262 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-05 14:04:23.009  3230  3262 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-05 14:04:23.009  3230  3262 D bt_hwcfg: Settlement delay -- 100 ms
07-05 14:04:23.009  3230  3262 I bt_hwcfg: Setting fw settlement delay to 100 
,07-05 14:04:23.114   789   894 D wifi    : set interface wlan0 flags (UP)
07-05 14:04:23.114   789   894 I WifiHAL : Initializing wifi
07-05 14:04:23.114   789   894 I WifiHAL : Creating socket
,07-05 14:04:23.116   789   809 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-05 14:04:23.117   789   894 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-05 14:04:23.117   789   894 D wifi    : Did set static halHandle = 0x9b587d20
,07-05 14:04:23.117   789   894 D wifi    : halHandle = 0x9b587d20, mVM = 0xb4cfc000, mCls = 0x736
,07-05 14:04:23.117   789   894 D wifi    : array field set
,07-05 14:04:23.117   789   894 I WifiNative-HAL: interface[0] = p2p0
,07-05 14:04:23.117   789   894 I WifiNative-HAL: interface[1] = wlan0
07-05 14:04:23.123   789   894 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-05 14:04:23.124  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:23.124   789   894 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-05 14:04:23.124   789  3270 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1688699616
,07-05 14:04:23.125   789  3270 D wifi    : waitForHalEvents called, vm = 0xb4cfc000, obj = 0x736, env = 0x9b585580
07-05 14:04:23.125  3230  3262 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-05 14:04:23.125  3230  3262 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
07-05 14:04:23.132   789   805 I ActivityManager: Start proc 3272:com.android.settings/1000 for broadcast com.android.settings/.widget.SettingsAppWidgetProvider
,07-05 14:04:23.155  3230  3262 I bt_hwcfg: vendor lib fwcfg completed
,07-05 14:04:23.155  3230  3262 I bt_vendor: firmware callback
07-05 14:04:23.155  3230  3262 I bt_hci  : firmware_config_callback
,07-05 14:04:23.167  3230  3284 I bt_btu  : btu_task pending for preload complete event
,07-05 14:04:23.167  3230  3284 I bt_btu_task: Bluetooth chip preload is complete
07-05 14:04:23.167  3230  3284 I bt_btu  : btu_task received preload complete event
,07-05 14:04:23.173  3230  3284 I         : BTE_InitTraceLevels -- TRC_HCI
,07-05 14:04:23.173  3230  3284 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_AVDT
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_AVRC
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_A2D
,07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_BNEP
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_BTM
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_GAP
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_PAN
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_SDP
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_GATT
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_SMP
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-05 14:04:23.174  3230  3284 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-05 14:04:23.192  3272  3272 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-05 14:04:23.196  3271  3271 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-05 14:04:23.205   789   809 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@47b61fb:true
,07-05 14:04:23.224  3272  3272 D LocalBluetoothProfileManager: Adding local MAP profile
,07-05 14:04:23.226  3272  3272 D BluetoothMap: Create BluetoothMap proxy object
,07-05 14:04:23.231  3272  3272 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-05 14:04:23.238  3271  3271 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-05 14:04:23.251   789  1310 I ActivityManager: Start proc 3298:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-05 14:04:23.253   789  1310 I ActivityManager: Killing 2209:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-05 14:04:23.299  3271  3271 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-05 14:04:23.387  3230  3284 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39239b5
,07-05 14:04:23.388  3230  3284 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39239b5 
,07-05 14:04:23.393  3230  3258 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-05 14:04:23.394  3230  3258 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-05 14:04:23.394  3230  3258 D BluetoothAdapterProperties: Name is: Nexus 5
07-05 14:04:23.395  3230  3258 D BluetoothAdapterProperties: Scan Mode:20
07-05 14:04:23.395  3230  3258 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:23.395  3230  3258 D bt_hci  : do_postload posting postload work item
07-05 14:04:23.395  3230  3262 I bt_hci  : event_postload
07-05 14:04:23.395  3230  3262 I bt_vendor: sco_config_cb
07-05 14:04:23.395  3230  3262 I bt_hci  : sco_config_callback postload finished.
,07-05 14:04:23.397  3298  3298 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-05 14:04:23.397  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:23.398  3230  3262 I bt_vendor: low_power_mode_cb
07-05 14:04:23.399  3230  3258 D bt_bte_conf: Device ID record 1 : primary
07-05 14:04:23.399  3230  3258 D bt_bte_conf:   vendorId            = 000f
07-05 14:04:23.399  3230  3258 D bt_bte_conf:   vendorIdSource      = 0001
,07-05 14:04:23.399  3230  3258 D bt_bte_conf:   product             = 1200
,07-05 14:04:23.399  3230  3258 D bt_bte_conf:   version             = 1436
,07-05 14:04:23.399  3230  3258 D bt_bte_conf:   clientExecutableURL = 
,07-05 14:04:23.399  3230  3258 D bt_bte_conf:   serviceDescription  = 
,07-05 14:04:23.399  3230  3258 D bt_bte_conf:   documentationURL    = 
,07-05 14:04:23.399  3230  3258 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-05 14:04:23.399  3230  3255 D bt_stack_manager: event_start_up_stack finished
,07-05 14:04:23.399  3230  3254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-05 14:04:23.399  3230  3254 D BluetoothAdapterProperties: Setting state to 15
07-05 14:04:23.399  3230  3254 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-05 14:04:23.400  3230  3254 I BluetoothAdapterState: Entering BleOnState
,07-05 14:04:23.402  3230  3254 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-05 14:04:23.402  3230  3254 D BluetoothAdapterProperties: Setting state to 11
07-05 14:04:23.402  3230  3254 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-05 14:04:23.408  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
07-05 14:04:23.409  3230  3230 D HeadsetService: Received start request. Starting profile...
,07-05 14:04:23.411  3230  3230 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-05 14:04:23.413  3230  3230 D HeadsetStateMachine: make
07-05 14:04:23.414  3230  3254 I BluetoothAdapterState: Entering PendingCommandState
,07-05 14:04:23.424  3230  3230 D HeadsetStateMachine: max_hf_connections = 1
,07-05 14:04:23.424  3230  3230 I bt_bluedroid: get_profile_interface handsfree
07-05 14:04:23.425  3230  3258 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-05 14:04:23.425  3230  3258 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
,07-05 14:04:23.427  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
,07-05 14:04:23.428   789   789 D BluetoothA2dp: Proxy object connected
,07-05 14:04:23.428  3230  3230 D A2dpService: Received start request. Starting profile...
,07-05 14:04:23.429  3230  3230 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-05 14:04:23.429  3230  3230 I bt_bluedroid: get_profile_interface avrcp
,07-05 14:04:23.436  3230  3230 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-05 14:04:23.436  3230  3230 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-05 14:04:23.436  3230  3230 D A2dpStateMachine: make
,07-05 14:04:23.437  3230  3230 I bt_bluedroid: get_profile_interface a2dp
,07-05 14:04:23.438  3230  3258 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-05 14:04:23.439  3230  3319 D A2dpStateMachine: Enter Disconnected: -2
,07-05 14:04:23.439  3230  3230 I BluetoothHidServiceJni: classInitNative: succeeds
,07-05 14:04:23.444  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
,07-05 14:04:23.445  3230  3230 D HidService: Received start request. Starting profile...
,07-05 14:04:23.445  3230  3230 I bt_bluedroid: get_profile_interface hidhost
07-05 14:04:23.445  3230  3230 D HidService: setHidService(): set to: null
07-05 14:04:23.445  3230  3230 I BluetoothHealthServiceJni: classInitNative: succeeds
07-05 14:04:23.446  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
,07-05 14:04:23.446   930   930 D BluetoothInputDevice: Proxy object connected
07-05 14:04:23.446   930   930 D HidProfile: Bluetooth service connected
07-05 14:04:23.447  3230  3258 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3905099
07-05 14:04:23.447  3230  3258 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-05 14:04:23.447  3230  3230 D HealthService: Received start request. Starting profile...
07-05 14:04:23.447  3272  3272 D BluetoothInputDevice: Proxy object connected
07-05 14:04:23.448  3272  3272 D HidProfile: Bluetooth service connected
07-05 14:04:23.448  3230  3230 I bt_bluedroid: get_profile_interface health
,07-05 14:04:23.449  3230  3230 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-05 14:04:23.456  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
,07-05 14:04:23.457   930   930 D BluetoothPan: BluetoothPAN Proxy object connected
,07-05 14:04:23.457  3272  3272 D BluetoothPan: BluetoothPAN Proxy object connected
07-05 14:04:23.457   930   930 D PanProfile: Bluetooth service connected
07-05 14:04:23.457  3230  3230 D PanService: Received start request. Starting profile...
07-05 14:04:23.457  3230  3230 D BluetoothPanServiceJni: initializeNative(L110): pan
07-05 14:04:23.457  3230  3230 I bt_bluedroid: get_profile_interface pan
07-05 14:04:23.457  3230  3258 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-05 14:04:23.458  3272  3272 D PanProfile: Bluetooth service connected
,07-05 14:04:23.463  3230  3230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@740d558
,07-05 14:04:23.464   930   930 D BluetoothMap: Proxy object connected
07-05 14:04:23.464   930   930 D MapProfile: Bluetooth service connected
07-05 14:04:23.464   930   930 D BluetoothMap: getConnectedDevices()
07-05 14:04:23.465   930   930 D BluetoothMap: Bluetooth is Not enabled
07-05 14:04:23.465  3230  3230 D BluetoothMapService: Received start request. Starting profile...
07-05 14:04:23.465  3230  3230 D BluetoothMapService: start()
07-05 14:04:23.466  3272  3272 D BluetoothMap: Proxy object connected
07-05 14:04:23.467  3272  3272 D MapProfile: Bluetooth service connected
07-05 14:04:23.467  3230  3230 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-05 14:04:23.467  3272  3272 D BluetoothMap: getConnectedDevices()
07-05 14:04:23.467  3230  3230 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-05 14:04:23.467  3230  3230 D BluetoothMapAppObserver: createReceiver()
07-05 14:04:23.468  3230  3230 D BluetoothMapAppObserver: initObservers()
07-05 14:04:23.468  3230  3230 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-05 14:04:23.468  3272  3272 D BluetoothMap: Bluetooth is Not enabled
07-05 14:04:23.474  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:23.474  3230  3230 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:23.474  3230  3230 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:23.474  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:23.475  3298  3298 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:23.475  3230  3230 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:23.476  3230  3254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-05 14:04:23.476  3230  3254 D BluetoothAdapterProperties: ScanMode =  20
07-05 14:04:23.476  3230  3254 D BluetoothAdapterProperties: State =  11
07-05 14:04:23.476  3230  3315 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-05 14:04:23.476  3230  3254 D BluetoothAdapterProperties: Setting state to 12
07-05 14:04:23.476  3230  3254 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-05 14:04:23.477   789   809 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:23.477  3230  3254 I BluetoothAdapterState: Entering OnState
07-05 14:04:23.478   930   943 D BluetoothPan: onBluetoothStateChange on: true
07-05 14:04:23.478  3230  3258 D BluetoothAdapterProperties: Scan Mode:21
07-05 14:04:23.478  3230  3258 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:23.479  3272  3283 D BluetoothPan: onBluetoothStateChange on: true
07-05 14:04:23.479  3272  3282 D BluetoothPbap: onBluetoothStateChange: up=true
07-05 14:04:23.480   930  1344 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-05 14:04:23.481  3179  3179 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 14:04:23.483   789   809 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:23.483   930   949 D BluetoothPbap: onBluetoothStateChange: up=true
07-05 14:04:23.485   789  2167 I ActivityManager: Killing 2343:com.google.android.gm/u0a70 (adj 15): empty #17
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:23.486  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:23.486   930   943 D BluetoothMap: onBluetoothStateChange: up=true
07-05 14:04:23.486  3272  3283 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-05 14:04:23.486   789   809 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:23.487   789   809 D BluetoothA2dp: onBluetoothStateChange: up=true
07-05 14:04:23.487  1289  1429 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:23.487  3272  3282 D BluetoothMap: onBluetoothStateChange: up=true
07-05 14:04:23.488  3179  3179 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:23.492  3230  3230 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-05 14:04:23.492  3230  3230 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-05 14:04:23.645   789   809 D BluetoothHeadset: Proxy object connected
,07-05 14:04:23.645   789   809 D BluetoothHeadset: Proxy object connected
07-05 14:04:23.645   789   809 D BluetoothHeadset: Proxy object connected
07-05 14:04:23.646   789   789 I Telecom : BluetoothPhoneService: queryPhoneState
07-05 14:04:23.646  1289  1430 D BluetoothHeadset: Proxy object connected
,07-05 14:04:23.652  3230  3230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-05 14:04:23.652  3272  3272 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-05 14:04:23.656  3230  3230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:23.657  3230  3230 D ObexServerSockets: Succeed to create listening sockets 
07-05 14:04:23.657  3230  3230 D ObexServerSockets0: startAccept()
,07-05 14:04:23.657  3230  3230 D ObexServerSockets0: prepareForNewConnect()
07-05 14:04:23.658   930  1157 D LocalBluetoothProfileManager: Adding local A2DP profile
07-05 14:04:23.659  3230  3230 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-05 14:04:23.659  3272  3272 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-05 14:04:23.659  3230  3230 D BluetoothSdpJni: SDP Create record success - handle: 0
07-05 14:04:23.659  3230  3230 D BluetoothMapService: onReceive
07-05 14:04:23.659  3230  3230 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-05 14:04:23.659  3230  3230 D BluetoothMapService: STATE_ON
,07-05 14:04:23.660  3230  3335 D ObexServerSockets0: Accepting socket connection...
07-05 14:04:23.660  3230  3336 D ObexServerSockets0: Accepting socket connection...
,07-05 14:04:23.663   930   930 D BluetoothA2dp: Proxy object connected
,07-05 14:04:23.663   930  1157 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-05 14:04:23.667  3272  3272 D BluetoothA2dp: Proxy object connected
,07-05 14:04:23.679  3230  3230 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-05 14:04:23.679  3230  3230 D ObexServerSockets0: prepareForNewConnect()
,07-05 14:04:23.690   789   975 I ActivityManager: Start proc 3337:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-05 14:04:23.763  3272  3282 D BluetoothHeadset: Proxy object connected
,07-05 14:04:23.764  3272  3272 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:23.766   930  1344 D BluetoothHeadset: Proxy object connected
,07-05 14:04:23.766   930   930 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:23.902  3337  3337 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-05 14:04:23.902  3337  3337 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.902  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.903  3337  3337 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.903  3337  3337 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.e.b(PG:170)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.903  3337  3337 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.k.d(PG:583)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.e.b(PG:170)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.903  3337  3337 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.903  3337  3337 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.903  3337  3337 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:23.903  3337  3337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:23.905   789  1310 I ActivityManager: Killing 2610:com.google.android.music:main/u0a60 (adj 15): empty #17
,07-05 14:04:23.946  3337  3354 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-05 14:04:23.954   789   809 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@df6fe4a:true
,07-05 14:04:24.010  1737  1737 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:24.016  1737  1737 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-05 14:04:24.024  3272  3272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-05 14:04:24.043   930   930 D BluetoothPbap: Proxy object connected
,07-05 14:04:24.043   930   930 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:24.045  3230  3368 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:24.049  3272  3272 D DockEventReceiver: finishStartingService: stopping service
,07-05 14:04:24.055  3272  3272 D BluetoothPbap: Proxy object connected
,07-05 14:04:24.056  3272  3272 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:24.080  1737  1737 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:24.086  1737  3375 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-05 14:04:24.088  1737  1737 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-05 14:04:24.094  3230  3376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:24.096  3230  3376 I BtOppRfcommListener: Accept thread started.
,07-05 14:04:24.107  1737  3375 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-05 14:04:24.130   789   894 D WifiConfigStore: Loading config and enabling all networks 
,07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:24.132  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-05 14:04:24.134  3179  3179 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-05 14:04:24.136   789   895 D WifiService: New client listening to asynchronous messages
,07-05 14:04:24.142   789   894 D WifiConfigStore: loaded 0 passpoint configs
07-05 14:04:24.142   789   894 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-05 14:04:24.143   789   894 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-05 14:04:24.143   789   894 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-05 14:04:24.144   789   894 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-05 14:04:24.144   789   894 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-05 14:04:24.144   789   894 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-05 14:04:24.144   789   894 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-05 14:04:24.150  2277  2277 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 14:04:24.150   789   894 D WifiNative-HAL: Setting external_sim to 1
,07-05 14:04:24.151   789   894 D wifi    : setting dfs flag to true, 0x9b65be68
07-05 14:04:24.151   789   894 D WifiStateMachine: Setting OUI to DA-A1-19
07-05 14:04:24.151   789   894 D wifi    : setting scan oui 0x9b65be68
07-05 14:04:24.151   789   894 D WifiHAL : Sending mac address OUI
,07-05 14:04:24.163   789   894 E native  : do suspend true
,07-05 14:04:24.167   789   894 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-05 14:04:24.168   789   789 D RttService: SCAN_AVAILABLE : 3
07-05 14:04:24.168   789   907 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-05 14:04:24.170   194   655 D CommandListener: Setting iface cfg
,07-05 14:04:24.170   194   655 D CommandListener: Trying to bring up p2p0
07-05 14:04:24.170   789   894 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-05 14:04:24.170   789   893 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-05 14:04:24.178   789   893 D WifiNative-HAL: p2pGetDeviceAddress
07-05 14:04:24.178   789   893 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-05 14:04:26.377  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:26.377  3179  3226 I jxcore-log: 
,07-05 14:04:26.773  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:26.773  3179  3226 I jxcore-log: 
,07-05 14:04:26.797  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:26.797  3179  3226 I jxcore-log: 
,07-05 14:04:26.801  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:26.801  3179  3226 I jxcore-log: 
,07-05 14:04:26.817  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:26.817  3179  3226 I jxcore-log: 
,07-05 14:04:26.821  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:26.821  3179  3226 I jxcore-log: 
,07-05 14:04:27.627   789   975 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1596 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:04:27.666  1596  3395 W DriveInitializer: Background init thread started
,07-05 14:04:27.718  1596  3395 W DriveInitializer: Background init thread ended
,07-05 14:04:28.827  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:28.827  3179  3226 I jxcore-log: 
,07-05 14:04:28.837  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:28.837  3179  3226 I jxcore-log: 
,07-05 14:04:28.845  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:28.845  3179  3226 I jxcore-log: 
,07-05 14:04:28.996  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:28.996  3179  3226 I jxcore-log: 
,07-05 14:04:29.078  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:29.078  3179  3226 I jxcore-log: 
,07-05 14:04:29.134  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:29.134  3179  3226 I jxcore-log: 
,07-05 14:04:29.140  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:29.140  3179  3226 I jxcore-log: 
,07-05 14:04:29.328  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:29.328  3179  3226 I jxcore-log: 
,07-05 14:04:29.349  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:29.349  3179  3226 I jxcore-log: 
,07-05 14:04:29.353  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:29.353  3179  3226 I jxcore-log: 
,07-05 14:04:29.358  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:29.358  3179  3226 I jxcore-log: 
,07-05 14:04:29.374  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:29.374  3179  3226 I jxcore-log: 
,07-05 14:04:29.392  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:29.392  3179  3226 I jxcore-log: 
,07-05 14:04:29.475  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:29.475  3179  3226 I jxcore-log: 
,07-05 14:04:29.480  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:29.480  3179  3226 I jxcore-log: 
,07-05 14:04:29.505  3179  3226 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:29.505  3179  3226 I jxcore-log: 
,07-05 14:04:29.514  3179  3226 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-05 14:04:29.516  3179  3226 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 14:04:29.516  3179  3226 I jxcore-log: 
,07-05 14:04:29.560  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-05 14:04:29.560  3179  3226 I jxcore-log: 
,07-05 14:04:29.561  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-05 14:04:29.561  3179  3226 I jxcore-log: 
,07-05 14:04:58.635  1737  1888 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:04:59.497   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:59.537   789   894 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-05 14:05:10.898  1225  1351 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-05 14:05:10.898  1225  1351 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:05:29.842  1737  1737 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=27e20bf0-94dd-41fd-8e66-76129ddc4c40
,07-05 14:05:29.843  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 14:05:29.844  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:05:29.956  1737  1799 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:05:29.959  1596  3419 D UdcContextInitService: registered all accounts: true
,07-05 14:05:29.963  1737  1784 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 14:05:30.031  1737  1784 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,07-05 14:05:30.033  1737  1737 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,07-05 14:05:30.119  1737  3431 I VacuumService: Vacuum at: now=1467720330119 tag=VacuumService
,07-05 14:05:40.708   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c4a030
,07-05 14:05:40.708   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,07-05 14:05:40.708   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
,07-05 14:05:40.709   192   508 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229715152)
,07-05 14:05:40.830   192   508 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-05 14:05:40.830   192   508 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,07-05 14:05:40.831   192   508 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229715152) wakelock released: 1, error no: 0
07-05 14:05:40.831   192   508 I rmt_storage: 
,07-05 14:05:40.833   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c4a030
,07-05 14:06:01.322   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:06:01.343   789   894 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-05 14:06:30.168  1737  1784 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-05 14:06:30.169  1737  1784 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-05 14:06:30.169  1737  1784 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
07-05 14:06:30.169  1737  1784 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-05 14:06:30.190  1737  1784 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
,07-05 14:06:30.191  1737  1784 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-05 14:07:03.028   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:07:03.054   789   894 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-05 14:07:58.443  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:58.471  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:58.472  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:12:58.558  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:12:58.573  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 14:12:58.573  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:13:04.731   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:13:04.743   789   894 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-05 14:15:29.431   789   885 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-05 14:15:29.432   789   789 V KeyguardServiceDelegate: onStartedWakingUp()
,07-05 14:15:29.440   789   812 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 14:15:29.449   789   805 I ActivityManager: Start proc 3457:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-05 14:15:29.459   789   812 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@27e5731)
07-05 14:15:29.461  3179  3179 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 14:15:29.461  3179  3179 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 14:15:29.463   198  1102 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:15:29.464   789  1343 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 14:15:29.469  1270  1381 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,07-05 14:15:29.469  1270  1381 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-05 14:15:29.470  1270  1381 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-05 14:15:29.470  1270  1613 D BrcmNfcJni: RoutingManager::commitRouting
07-05 14:15:29.470  1270  1381 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-05 14:15:29.473  3179  3179 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-05 14:15:29.473  3179  3179 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 14:15:29.481   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:15:29.489   789   894 E native  : do suspend false
,07-05 14:15:29.496  3457  3457 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-05 14:15:29.498   789   894 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:15:29.518   789   974 I ActivityManager: Killing 2037:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-05 14:15:29.540  1962  1978 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
07-05 14:15:29.540   191   191 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
07-05 14:15:29.540   191   191 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 14:15:29.568   789   810 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-05 14:15:29.582  1737  1737 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-05 14:15:29.712   789   812 I DisplayPowerController: Unblocked screen on after 272 ms
,07-05 14:15:29.712   789   812 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-05 14:15:29.770   191   191 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-05 14:15:29.770   789   910 D SurfaceControl: Excessive delay in setPowerMode(): 229ms
,07-05 14:15:29.989   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:15:30.294  1270  1636 D NfcService: Discovery configuration equal, not updating.
,07-05 14:15:31.453   789   894 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-05 14:15:31.457   789   894 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-05 14:15:31.457   789   894 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:15:31.467   789   894 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-05 14:15:31.499   789   894 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-05 14:15:31.501  3271  3271 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-05 14:15:31.654  3271  3271 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-05 14:15:31.681  3271  3271 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-05 14:15:31.681  3271  3271 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-05 14:15:31.683   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:15:31.693   789   894 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-05 14:15:31.694   789   894 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-05 14:15:31.694   789   896 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-05 14:15:31.706   789   894 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:15:31.716   194   655 D CommandListener: Setting iface cfg
,07-05 14:15:31.725   789   894 D WifiStateMachine: Start Dhcp Watchdog 1
,07-05 14:15:31.730   789  3498 D DhcpClient: Receive thread started
,07-05 14:15:31.736   789   896 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:15:31.736   789   896 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,07-05 14:15:31.738   789   894 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-05 14:15:31.821   789   894 E native  : do suspend false
,07-05 14:15:31.828   789  3497 D DhcpClient: Broadcasting DHCPDISCOVER
,07-05 14:15:32.847   789  3498 D DhcpClient: Received packet: 50:55:27:f0:fd:0b OFFER, ip /192.168.1.118, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,07-05 14:15:32.849   789  3497 D DhcpClient: Got pending lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-05 14:15:32.853   789  3497 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.118 serverid=192.168.1.1
,07-05 14:15:32.863   789  3498 D DhcpClient: Received packet: 50:55:27:f0:fd:0b ACK: your new IP /192.168.1.118, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
07-05 14:15:32.864   789  3497 D DhcpClient: Confirmed lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-05 14:15:32.870   194   655 D CommandListener: Setting iface cfg
07-05 14:15:32.881   789   894 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
07-05 14:15:32.899   789  3497 D DhcpClient: Scheduling renewal in 86399s
07-05 14:15:32.914   789   894 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-05 14:15:32.921   789   894 D WifiConfigStore: No blacklist allowed without epno enabled
07-05 14:15:32.924   789   896 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-05 14:15:32.930   789   896 D ConnectivityService: Adding iface wlan0 to network 100
07-05 14:15:32.941   789   894 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-05 14:15:32.975   789   896 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-05 14:15:32.975   789   896 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-05 14:15:32.976   789   896 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-05 14:15:32.977   789   896 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-05 14:15:32.978   789   896 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-05 14:15:32.986   789   896 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-05 14:15:32.990   789   896 D ConnectivityService: scheduleUnvalidatedPrompt 100
07-05 14:15:32.990   789   896 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-05 14:15:32.990   789   894 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-05 14:15:32.991   789   894 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-05 14:15:32.991   789   896 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-05 14:15:32.991   789   896 D ConnectivityService:    accepting network in place of null
07-05 14:15:32.992   789   896 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.118/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -72]}  Score{16}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 14:15:33.007   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=785466, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:15:33.037   194   655 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:15:33.055   194   655 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:15:33.057   789   896 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,07-05 14:15:33.059   789   896 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-05 14:15:33.060   789   896 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-05 14:15:33.060   789   896 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-05 14:15:33.061   789   809 D Tethering: MasterInitialState.processMessage what=3
,07-05 14:15:33.069  1382  1382 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-05 14:15:33.078   789   974 I ActivityManager: Start proc 3534:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-05 14:15:33.080   789  3495 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:816::200e
,07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:15:33.081  3179  3179 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:15:33.084  3179  3179 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:15:33.085  3179  3226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:15:33.085  3179  3226 I jxcore-log: 
,07-05 14:15:33.111   789  1265 D AlarmManagerService: Setting time of day to sec=1467720935
,07-05 14:15:35.634   789  1265 W AlarmManagerService: Unable to set rtc to 1467720935: Invalid argument
,07-05 14:15:35.638   789  1319 I ActivityManager: Start proc 3550:com.google.android.youtube/u0a80 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:15:35.665   789  3495 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jul 2016 12:15:35 GMT], X-Android-Received-Millis=[1467720935664], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467720935634]}
,07-05 14:15:35.665   789   896 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-05 14:15:35.665   789   896 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-05 14:15:35.665   789   896 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-05 14:15:35.666   789   896 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-05 14:15:35.672   944  3563 D DownloadManager: [105] Starting
,07-05 14:15:35.676   944  3563 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 14:15:35.697   789  3570 D GpsLocationProvider: NTP server returned: 1467720935638 (Tue Jul 05 14:15:35 GMT+02:00 2016) reference: 785574 certainty: 8 system time offset: -59
,07-05 14:15:35.697   789  3570 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,07-05 14:15:35.698  1596  3572 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-05 14:15:35.716   789   804 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 23051, reason: UserStart, SyncResult: databaseError: true stats []
,07-05 14:15:35.718   789   804 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 817198, reason: UserStart
,07-05 14:15:35.734   789   804 I UsageStatsService: Time changed in UsageStats by 2 seconds
07-05 14:15:35.734   789   804 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:15:35.753  3550  3573 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:35.768  3550  3573 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:15:35.768  3550  3573 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:35.777  3550  3573 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:35.792  1596  3569 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:15:35.812  3550  3573 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:35.818  3550  3574 D ChimeraCfgMgr: Reading stored module config
,07-05 14:15:35.828   789   804 I UsageStatsDatabase: Time changed by +2s523ms. files deleted: 0 files moved: 15
,07-05 14:15:35.853   789   804 I UsageStatsService: User[0] Rollover scheduled @ 2016-07-06 02:00:00(1467763200000)
,07-05 14:15:35.865  3550  3574 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
,07-05 14:15:35.869  3550  3574 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:15:35.873  3550  3550 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 14:15:35.880  3550  3574 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:15:35.899  3550  3574 D DynamitePackage: Instantiated singleton DynamitePackage.
,07-05 14:15:35.900  3550  3574 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,07-05 14:15:35.941   789   799 I ActivityManager: Start proc 3612:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-05 14:15:35.974  3612  3612 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-05 14:15:36.021   944  3563 D DownloadManager: [105] Finished with status SUCCESS
,07-05 14:15:36.030  3550  3550 W InstanceID/Rpc: Found 10008
,07-05 14:15:36.041  2277  3611 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-05 14:15:36.049  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:36.049  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:36.062  3631  3631 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/1459442732877.jar --oat-file=/data/user/0/com.google.android.youtube/cache/1459442732877.dex
,07-05 14:15:36.124  3298  3635 V GoogleAuthProtoRequest: [258] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:15:36.128  3631  3631 I dex2oat : dex2oat took 66.995ms (threads: 4) arena alloc=350KB java alloc=38KB native alloc=1706KB free=1621KB
,07-05 14:15:36.513   789   804 I ActivityManager: Start proc 3691:com.google.android.gm/u0a70 for service com.google.android.gm/.provider.MailSyncAdapterService
,07-05 14:15:36.528  3691  3691 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,07-05 14:15:36.545  1596  3707 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:15:36.545  1596  3707 I CheckinChimeraService: Checking schedule, now: 1467720936545 next: 1466528445134
07-05 14:15:36.545  1596  3707 I CheckinChimeraService: active receiver: enabled
,07-05 14:15:36.546  1596  3707 I CheckinChimeraService: Preparing to send checkin request
,07-05 14:15:36.546  1596  3707 I EventLogChimeraService: Accumulating logs since 1467719258697
,07-05 14:15:36.561  1596  3714 I iu.SyncManager: SYNC; picasa accounts
,07-05 14:15:36.572  3691  3717 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-05 14:15:36.574  1596  1596 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-05 14:15:36.575  1596  1596 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-05 14:15:36.585  3691  3716 I Gmail   : getAccountsCursor
,07-05 14:15:36.607  1596  3714 I iu.UploadsManager: num queued entries: 0
,07-05 14:15:36.613  1596  3714 I iu.UploadsManager: num updated entries: 0
07-05 14:15:36.614  1596  3714 I iu.SyncManager: NEXT; no task
,07-05 14:15:36.631   789   971 I ActivityManager: Start proc 3721:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-05 14:15:36.665  3691  3691 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:15:36.685  3721  3721 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-05 14:15:36.699  3691  3742 W Gmail   : Sync started for account: account:61035162
,07-05 14:15:36.704   789   974 I ActivityManager: Start proc 3743:com.google.android.gm.exchange/u0a69 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,07-05 14:15:36.708  3691  3749 E Gmail   : Error finding the version of the Email provider.....
07-05 14:15:36.708  3691  3749 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 14:15:36.708  3691  3749 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-05 14:15:36.708  3691  3749 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-05 14:15:36.708  3691  3749 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 14:15:36.708  3691  3749 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:15:36.708  3691  3749 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:15:36.708  3691  3749 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-05 14:15:36.708  3691  3749 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:15:36.708  3691  3749 W EmailMigration: We do not support migrating this version of the Email provider.
,07-05 14:15:36.723  1737  3703 I GCM     : GCM config loaded
,07-05 14:15:36.730   789  2167 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 14:15:36.740  3743  3743 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-05 14:15:36.762  3691  3760 I Gmail   : Observing account changes for notifications
,07-05 14:15:36.773  3743  3743 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:15:36.785  3743  3743 I Exchange: EasService.onCreate
,07-05 14:15:36.790  3743  3767 I Exchange: RestartPingTask
,07-05 14:15:36.800  3721  3721 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-05 14:15:36.800  3721  3721 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:15:36.800  3721  3721 I GAv4    :   adb logcat -s GAv4
,07-05 14:15:36.810  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:36.815  3743  3743 I Exchange: RestartPingsTask did not start any pings.
07-05 14:15:36.816  3743  3743 I Exchange: PSS stopIfIdle
07-05 14:15:36.816  3743  3743 I Exchange: PSS has no active accounts; stopping service.
,07-05 14:15:36.818  1596  3737 V AccountUtils: 0 accounts found with uca feature
,07-05 14:15:36.818  1596  3737 I GamesSyncAdapter: Starting sync for 3a3529a
,07-05 14:15:36.818  3691  3716 I Gmail   : getAccountsCursor
07-05 14:15:36.818  3721  3721 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:36.822  3743  3743 I Exchange: onDestroy
07-05 14:15:36.822  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:36.832   789  1333 I ActivityManager: Killing 2940:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-05 14:15:36.832  3721  3721 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:36.833  1596  3707 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:15:36.836  3721  3776 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:36.837   789   895 D WifiService: New client listening to asynchronous messages
,07-05 14:15:36.848  3691  3759 I Gmail   : notifyAccountChanged
,07-05 14:15:36.850  3691  3759 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:15:36.852  3691  3759 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:15:36.857  3691  3759 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:15:36.858  3691  3759 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:15:36.861  1596  3707 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 14:15:36.880  3691  3742 I Gmail   : notifyAccountChanged
,07-05 14:15:36.978  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:36.983  3691  3741 I Gmail   : getAccountsCursor
,07-05 14:15:36.988  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:36.998  3691  3717 I Gmail   : getAccountsCursor
,07-05 14:15:37.004  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:37.010  3298  3635 V ExperimentUpdateService: [258] ExperimentUpdateService.a: Empty/null config in valid experiment update response.
,07-05 14:15:37.019  3691  3742 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24101, normalSync: true
,07-05 14:15:37.023  3721  3721 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-05 14:15:37.025  1596  3707 V CheckinRequestBuilder: No Subscriptions found on the device
,07-05 14:15:37.032   789   971 I ActivityManager: Start proc 3800:com.google.android.play.games.ui/u0a66 for service com.google.android.play.games/com.google.android.gms.games.service.PlayGamesBridgeService
,07-05 14:15:37.041  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:37.078  3550  3814 W YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1035 Unknown task tag innertube_config_fetch_charging; aborting...
,07-05 14:15:37.095  3721  3721 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 7036-7046)
,07-05 14:15:37.095  3721  3721 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:15:37.119  3721  3721 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cf46960}
,07-05 14:15:37.120  3721  3721 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:15:37.121  3721  3721 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 14:15:37.131  3721  3721 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 14:15:37.132  3721  3721 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 14:15:37.133  1596  3737 I GamesSyncAdapter: Sync duration for 3a3529a: 316
,07-05 14:15:37.145  3721  3721 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 14:15:37.150  3721  3721 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:15:37.150  3721  3721 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:15:37.151  3721  3721 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:37.165  3691  3742 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:37.175   789   800 I ActivityManager: Killing 3030:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-05 14:15:37.192  3691  3742 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:15:37.192  3691  3742 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:37.196  3721  3834 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-05 14:15:37.198  3691  3742 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:37.224  3691  3742 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:37.255  3721  3721 I NSApplication: Starting up...
,07-05 14:15:37.256  1596  3737 E PopupManager: No content view usable to display popups. Popups will not be displayed in response to this client's calls. Use setViewForPopups() to set your content view.
,07-05 14:15:37.260   789   971 I ActivityManager: Killing 3057:com.android.musicfx/u0a15 (adj 15): empty #17
,07-05 14:15:37.262   789   896 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:15:37.311   789  1318 I ActivityManager: Killing 1382:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,07-05 14:15:37.323   789   895 D WifiService: Client connection lost with reason: 4
,07-05 14:15:37.424   789   896 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,07-05 14:15:37.426   789   805 W BroadcastQueue: Failure sending broadcast Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 (has extras) }
07-05 14:15:37.426   789   805 W BroadcastQueue: android.os.DeadObjectException
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1128)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:453)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:594)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:667)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:15:37.426   789   805 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,07-05 14:15:37.442  1596  3847 W GamesServiceBroker: Client connected with SDK 8487000, Services 9083438, and Games 37230038
,07-05 14:15:37.522   789   800 I ActivityManager: Start proc 3856:com.google.android.calendar/u0a31 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-05 14:15:37.544  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:37.567  3856  3856 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,07-05 14:15:37.576   789  1343 I ActivityManager: Start proc 3868:com.google.android.gms.unstable/u0a8 for service com.google.android.gms/.droidguard.DroidGuardService
,07-05 14:15:37.585  1737  3880 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:37.650  3868  3868 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:15:37.650  3868  3868 I MultiDex: install
07-05 14:15:37.650  3868  3868 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:15:37.673   789  1319 I ActivityManager: Start proc 3891:com.android.providers.calendar/u0a2 for content provider com.android.providers.calendar/.CalendarProvider2
,07-05 14:15:37.690  1596  1596 D PlayCommon: [1] DfeRequest.deliverResponse: Not delivering second response for request=[[ ] https://android.clients.google.com/fdfe/api/experiments 0xe8d195d1 NORMAL 1]
,07-05 14:15:37.693  3868  3868 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:37.699  1737  3880 D GoogleSignatureVerifier: Package manager can't find package null, defaulting to false
,07-05 14:15:37.706  1737  3880 I GLSUser : Method not found getActionBar
,07-05 14:15:37.710  3891  3891 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-05 14:15:37.718  3868  3868 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:15:37.718  3868  3868 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:37.722  3868  3868 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:37.741  3891  3891 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@a635ebe(com.android.providers.calendar.CalendarProvider2@8216b1f)
,07-05 14:15:37.764  3868  3868 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:37.769   789  1343 I ActivityManager: Start proc 3908:com.qualcomm.timeservice/u0a76 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,07-05 14:15:37.779  3856  3856 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-05 14:15:37.793  3908  3908 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-05 14:15:37.800  3908  3908 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467720937800
07-05 14:15:37.800  3908  3908 D         : TimeServiceNative: User Time to be set is 1467720937800
07-05 14:15:37.800  3908  3908 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-05 14:15:37.800  3908  3908 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-05 14:15:37.800  3908  3908 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467720937800
07-05 14:15:37.800   212   639 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-05 14:15:37.800  3908  3908 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467720937800
07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467720937800, operation = 0
,07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/20/70 5:45:9
07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:Value read from RTC seconds = 1662309000
07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:new time 1467720937800 
07-05 14:15:37.801   212  3925 D QC-time-services: Daemon: delta 1466058628800 genoff 1466058628800 
,07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466058628800 to memory
07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
,07-05 14:15:37.801   212  3925 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-05 14:15:37.803  3868  3868 D ChimeraCfgMgr: Reading stored module config
,07-05 14:15:37.807   212  3925 D QC-time-services: Updating the TOD offset
07-05 14:15:37.807   212  3925 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466058628800 to memory
07-05 14:15:37.807   212  3925 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
07-05 14:15:37.807   212  3925 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-05 14:15:37.810   212  3925 D QC-time-services: Daemon:Update to modem bit set
07-05 14:15:37.810   212  3925 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-05 14:15:37.810   212  3925 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1151756137800
,07-05 14:15:37.810  3908  3908 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-05 14:15:37.813   212   639 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-05 14:15:37.813   212   637 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-05 14:15:37.828   789  3843 I ActivityManager: Start proc 3926:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-05 14:15:37.830   789  3843 I ActivityManager: Killing 3078:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,07-05 14:15:37.865  3868  3924 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:15:37.891  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-05 14:15:37.914   789   800 I ActivityManager: Killing 1197:android.process.acore/u0a4 (adj 15): empty #17
,07-05 14:15:37.919  3926  3926 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:15:37.919  3926  3926 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:15:37.919  3926  3926 I GAv4    :   adb logcat -s GAv4
,07-05 14:15:37.964  3926  3926 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:37.971  3926  3926 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:37.977  1737  1737 D WearableService: callingUid 10008, callindPid: 1737
,07-05 14:15:37.980  3926  3946 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:38.015   198  1102 D WVCdm   : Instantiating CDM.
,07-05 14:15:38.016   198   198 I WVCdm   : CdmEngine::OpenSession
07-05 14:15:38.016   198   198 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:15:38.037   198   198 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:15:38.042   198   198 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-05 14:15:38.042   198   198 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:15:38.042   198   198 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:15:38.042   198   198 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:15:38.044   789   975 I ActivityManager: Killing 2993:com.android.defcontainer/u0a5 (adj 15): empty #17
,07-05 14:15:38.048  1737  3948 I CheckinUtil: Classify the device as Phone.
,07-05 14:15:38.064   198   198 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:15:38.065   198   198 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:15:38.065   198   198 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
07-05 14:15:38.065   198   198 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
,07-05 14:15:38.082   198   198 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:15:38.082   198   198 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:15:38.087   198   198 D DrmWidevineDash: hlos api version =  10
,07-05 14:15:38.087   198   198 D DrmWidevineDash: tz api version =  10
07-05 14:15:38.087   198   198 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:15:38.087   198   198 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:15:38.112   198   198 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:15:38.112   198   198 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:15:38.112   198   198 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbed9a214
,07-05 14:15:38.117   198   198 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-05 14:15:38.117   198   198 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:15:38.117   198   198 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb600bda8, dataLength=8
,07-05 14:15:38.123   198   198 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:15:38.131   198   198 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb5fc7600, wrapped_rsa_key_length=1280
,07-05 14:15:38.138   198   198 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 14:15:38.138   198   198 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:15:38.139   198  1102 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:15:38.139   198  1102 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:15:38.139   198  1102 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:15:38.139   198  1102 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb33dd120, idLength=0xb357ef2c
,07-05 14:15:38.149   198  1102 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:15:38.149   198  1102 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:15:38.156   198  1102 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 14:15:38.156   198  1102 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:15:38.156   198  1102 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:15:38.156   198  1102 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:15:38.161   198  1102 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-05 14:15:38.161   198  1102 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:15:38.167   198  1102 D DrmWidevineDash: hlos api version =  10
,07-05 14:15:38.167   198  1102 D DrmWidevineDash: tz api version =  10
07-05 14:15:38.167   198  1102 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:15:38.167   198  1102 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:15:38.173   198  1102 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-05 14:15:38.173   198  1102 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:15:38.173   198  1102 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:15:38.180   198  1102 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-05 14:15:38.180   198  1102 D WVCdm   : PrepareKeyRequest: nonce=2706979495
07-05 14:15:38.180   198  1102 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb33e4000
07-05 14:15:38.180   198  1102 D DrmWidevineDash: message_length=1639, signature=0xb35af000, signature_length=3008884740
,07-05 14:15:38.293   198  1102 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:15:38.294   198   828 I WVCdm   : CdmEngine::CloseSession
07-05 14:15:38.294   198   828 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:15:38.299   198   828 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 14:15:38.299   198   828 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:15:38.304   198   828 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 14:15:38.305   198   828 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:15:38.305   198   828 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:15:38.305   198   828 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:15:38.305   198   828 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:15:38.335  1225  3956 I DictionaryProvider:UpdateHandler: downloadFinished() : DownloadId = 105
,07-05 14:15:38.353  1596  3922 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
,07-05 14:15:38.353  1596  3922 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,07-05 14:15:38.405  1596  1596 I GCM     : Message from 745476177629 null
,07-05 14:15:38.416  1596  1596 I GCM     : Message from 745476177629 null
,07-05 14:15:38.426  1596  1596 I GCM     : Message from 745476177629 null
,07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
,07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
07-05 14:15:38.448  3868  3879 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,07-05 14:15:38.454  3868  3879 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 14:15:38.454  3868  3879 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:15:38.461  3868  3879 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
,07-05 14:15:38.462  3868  3879 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-05 14:15:38.463  3868  3879 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:15:38.465  3868  3879 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:15:38.513  1596  3962 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,07-05 14:15:38.535  3868  3879 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:15:38.642  1737  1737 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:38.664  1737  3982 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
,07-05 14:15:38.665  1737  3981 I PhenotypeConfigurator: Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,07-05 14:15:38.701  1737  1744 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@af19105)
,07-05 14:15:38.721  3983  3983 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/the.apk --oat-file=/data/user/0/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/opt/the.dex
,07-05 14:15:38.769  3983  3983 I dex2oat : dex2oat took 51.067ms (threads: 4) arena alloc=41KB java alloc=21KB native alloc=928KB free=863KB
,07-05 14:15:38.789  3891  3891 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-05 14:15:38.789  3891  3891 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 14:15:38.903   198   828 I WVCdm   : CdmEngine::OpenSession
07-05 14:15:38.903   198   828 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:15:38.905   198   828 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:15:38.906   198   828 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-05 14:15:38.906   198   828 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:15:38.906   198   828 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:15:38.906   198   828 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:15:38.918   198   828 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:15:38.918   198   828 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:15:38.918   198   828 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
07-05 14:15:38.918   198   828 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
,07-05 14:15:38.931   198   828 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:15:38.931   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:15:38.937   198   828 D DrmWidevineDash: hlos api version =  10
,07-05 14:15:38.937   198   828 D DrmWidevineDash: tz api version =  10
07-05 14:15:38.937   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:15:38.937   198   828 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:15:38.948   198   828 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-05 14:15:38.948   198   828 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:15:38.948   198   828 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb36ff134
,07-05 14:15:38.953   198   828 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-05 14:15:38.953   198   828 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:15:38.953   198   828 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb600bda8, dataLength=8
,07-05 14:15:38.958   198   828 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:15:38.960   198   828 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb5fc8e00, wrapped_rsa_key_length=1280
,07-05 14:15:38.968   198   828 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-05 14:15:38.968   198   828 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:15:38.969   198   828 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-05 14:15:38.969   198   828 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:15:38.969   198   828 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:15:38.969   198   828 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb482dfa0, idLength=0xb36fef2c
,07-05 14:15:38.980   198   828 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 14:15:38.980   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:15:38.986   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 14:15:38.986   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:15:38.986   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:15:38.986   198   828 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:15:38.992   198   828 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-05 14:15:38.992   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:15:38.997   198   828 D DrmWidevineDash: hlos api version =  10
07-05 14:15:38.997   198   828 D DrmWidevineDash: tz api version =  10
,07-05 14:15:38.997   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:15:38.997   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:15:39.002   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-05 14:15:39.002   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:15:39.002   198   828 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:15:39.008   198   828 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-05 14:15:39.008   198   828 D WVCdm   : PrepareKeyRequest: nonce=2445146325
,07-05 14:15:39.008   198   828 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb33e4700
07-05 14:15:39.008   198   828 D DrmWidevineDash: message_length=1670, signature=0xb6036840, signature_length=3010457604
,07-05 14:15:39.035  3721  4001 I SyncAdapterService: Ignoring sync request for non-current account
,07-05 14:15:39.086   198   828 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:15:39.086   198   198 I WVCdm   : CdmEngine::CloseSession
07-05 14:15:39.086   198   198 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:15:39.092   198   198 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-05 14:15:39.092   198   198 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:15:39.097   198   198 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:15:39.097   198   198 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:15:39.097   198   198 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:15:39.098   198   198 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:15:39.098   198   198 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:15:39.169   789   804 I ActivityManager: Start proc 4014:com.google.process.gapps/u0a85 for service com.google.android.syncadapters.contacts/.ContactsSyncAdapterService
,07-05 14:15:39.183  4014  4014 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-05 14:15:39.200  4014  4014 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:15:39.205   789   800 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.phenotype.service.PhenotypeCommitChimeraService (has extras) } U=0: not found
,07-05 14:15:39.222   789  1319 I ActivityManager: Start proc 4032:android.process.acore/u0a4 for content provider com.android.providers.contacts/.ContactsProvider2
,07-05 14:15:39.250  4032  4032 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-05 14:15:39.253  4027  4027 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-05 14:15:39.268  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:39.286  3691  3742 I Gmail   : checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^f]), all([^b, userlabel:93982, userlabel:90242001, userlabel:2914615, userlabel:90242029, userlabel:2914456, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, userlabel:-1492383895, ^f, userlabel:94076, userlabel:823616170, userlabel:-1492276994, userlabel:-1492276990, userlabel:3026, userlabel:-1492276991, ^u, ^t, ^smartlabel_group, ^s, ^smartlabel_personal, userlabel:-812318908, ^smartlabel_social, userlabel:2914593, ^p_mtunsub, ^sq_ig_i_personal, ^g, ^r, ^punsub, ^smartlabel_promo, userlabel:-1497452393, ^i, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, userlabel:2907326, userlabel:93692, userlabel:-244132349, ^sq_ig_i_social, userlabel:90241971, userlabel:3011, userlabel:1123230114, ^p_abs])
,07-05 14:15:39.299  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-05 14:15:39.310  4014  4031 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
07-05 14:15:39.310  4027  4027 I dex2oat : dex2oat took 58.566ms (threads: 4) arena alloc=233KB java alloc=51KB native alloc=1534KB free=1537KB
07-05 14:15:39.311  4014  4031 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:15:39.318  3868  3879 W System  : ClassLoader referenced unknown path: 
,07-05 14:15:39.335  4032  4049 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-05 14:15:39.337  3868  3879 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:39.402  1596  4053 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
,07-05 14:15:39.402  1596  4053 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
07-05 14:15:39.405  1737  3981 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-05 14:15:39.413  1737  3982 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:39.415  1737  3982 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-05 14:15:39.417  3868  3879 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:39.426  1737  3982 V BaseAppContext: GmsRequestQueue started.
,07-05 14:15:39.434  1737  1790 W Herrevad: Invalid mccmnc 
,07-05 14:15:39.434  1737  1790 W Herrevad: Invalid mccmnc 
,07-05 14:15:39.461  3868  3879 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:39.593  1737  1790 V NQFileLogger: [131] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:15:39.647  1737  1790 V ProcessReports: [131] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 14:15:39.656  4032  4049 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,07-05 14:15:39.656  4032  4049 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-05 14:15:39.664  1596  3707 I CheckinUtil: Classify the device as Phone.
,07-05 14:15:39.724  2277  3971 I art     : Note: end time exceeds epoch: 
,07-05 14:15:39.731  4032  4049 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-05 14:15:39.754  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:39.754  4032  4049 I ContactDirectoryManager: Discovered 0 contact directories in 279ms
,07-05 14:15:39.762  2277  4066 I Babel   : Account registration complete:1-Redacted-21
,07-05 14:15:39.786  2277  4066 I Babel   : ProcessRegisterDeviceResponse
,07-05 14:15:39.786  2277  4066 I Babel   : Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,07-05 14:15:39.793  3691  3742 I Gmail   : getStartSyncRequest: handledServerOpId: 24798, upperFetchedConvoId: 1537274259643039744, lowerFetchedConvoId: 0, ackedClientOp: 0
,07-05 14:15:39.824  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:39.826  1737  3982 W WakefulBroadcastReceiver: No active wake lock id #1
,07-05 14:15:39.855  1737  3982 W WakefulBroadcastReceiver: No active wake lock id #2
,07-05 14:15:39.862  1737  3982 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
,07-05 14:15:39.913  1596  3707 W System.err: java.lang.Exception: Error converting session
,07-05 14:15:39.930  1596  3707 W System.err: 	at slt.log(SourceFile:302)
,07-05 14:15:39.930  1596  3707 W System.err: 	at slt.toSession(SourceFile:269)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:310)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.verifyHostname(SourceFile:217)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:507)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
,07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:15:39.930  1596  3707 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-05 14:15:39.930  1596  3707 W System.err: 	at htp.a(SourceFile:386)
07-05 14:15:39.930  1596  3707 W System.err: 	at htp.a(SourceFile:249)
,07-05 14:15:39.930  1596  3707 W System.err: 	at hti.a(SourceFile:822)
07-05 14:15:39.930  1596  3707 W System.err: 	at hti.doInBackground(SourceFile:789)
07-05 14:15:39.930  1596  3707 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
07-05 14:15:39.930  1596  3707 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:15:39.930  1596  3707 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:15:39.930  1596  3707 W System.err: Caused by: java.io.IOException: Invalid session data
07-05 14:15:39.931  1596  3707 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
07-05 14:15:39.931  1596  3707 W System.err: 	at slt.toSession(SourceFile:267)
07-05 14:15:39.931  1596  3707 W System.err: 	... 25 more
,07-05 14:15:39.974  1737  4080 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,07-05 14:15:40.012  1596  4083 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-05 14:15:40.013  1596  4083 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 14:15:40.034  1596  3707 I CheckinTask: Sending checkin request (10215 bytes)
,07-05 14:15:40.087  1225  3956 I DictionaryProvider:UpdateHandler: downloadFinished() : Success = true
,07-05 14:15:40.087  1225  3956 I DictionaryProvider:UpdateHandler: downloadFinished() : Metadata Success
,07-05 14:15:40.089  1225  1225 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-05 14:15:40.116  1225  4088 I Keyboard.Facilitator.DecoderInitializer: run()
,07-05 14:15:40.122  1225  4088 I Decoder : createOrResetDecoder
,07-05 14:15:40.159  1737  3982 W WakefulBroadcastReceiver: No active wake lock id #3
,07-05 14:15:40.159   198   828 D WVCdm   : Instantiating CDM.
,07-05 14:15:40.160   198  1102 I WVCdm   : CdmEngine::OpenSession
,07-05 14:15:40.161   198  1102 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:15:40.163  1225  4088 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-05 14:15:40.164   198  1102 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-05 14:15:40.167   198  1102 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-05 14:15:40.167   198  1102 D DrmWidevineDash: Service_Initialize: starts!
,07-05 14:15:40.167   198  1102 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-05 14:15:40.167   198  1102 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:15:40.184   198  1102 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:15:40.184   198  1102 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:15:40.184   198  1102 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
,07-05 14:15:40.184   198  1102 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
,07-05 14:15:40.193   198  1102 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:15:40.193   198  1102 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:15:40.199   198  1102 D DrmWidevineDash: hlos api version =  10
07-05 14:15:40.199   198  1102 D DrmWidevineDash: tz api version =  10
07-05 14:15:40.199   198  1102 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:15:40.199   198  1102 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:15:40.203  1225  4088 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-05 14:15:40.205  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-05 14:15:40.205  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-05 14:15:40.207  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,07-05 14:15:40.207  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-05 14:15:40.208  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-05 14:15:40.208  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-05 14:15:40.208  1225  4088 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-05 14:15:40.208  1225  4088 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-05 14:15:40.208  1225  4088 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-05 14:15:40.208  1225  4088 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-05 14:15:40.208  1225  4088 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-05 14:15:40.208  1225  4088 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-05 14:15:40.209   198  1102 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:15:40.209   198  1102 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:15:40.209   198  1102 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb357f134
,07-05 14:15:40.215   198  1102 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-05 14:15:40.215   198  1102 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:15:40.215   198  1102 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb46672c8, dataLength=8
,07-05 14:15:40.222   198  1102 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:15:40.224   198  1102 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb24e6c00, wrapped_rsa_key_length=1280
,07-05 14:15:40.231   198  1102 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 14:15:40.231   198  1102 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:15:40.232   198   828 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:15:40.232   198   828 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:15:40.232   198   828 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:15:40.232   198   828 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb38ffb80, idLength=0xb36fef2c
,07-05 14:15:40.243   198   828 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:15:40.243   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:15:40.249   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:15:40.249   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:15:40.249   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:15:40.249   198   828 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:15:40.255   198   828 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-05 14:15:40.255   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:15:40.261   198   828 D DrmWidevineDash: hlos api version =  10
,07-05 14:15:40.261   198   828 D DrmWidevineDash: tz api version =  10
07-05 14:15:40.261   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:15:40.261   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:15:40.266   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-05 14:15:40.266   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:15:40.266   198   828 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:15:40.273   198   828 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-05 14:15:40.273   198   828 D WVCdm   : PrepareKeyRequest: nonce=1502821569
07-05 14:15:40.273   198   828 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb33e4700
07-05 14:15:40.273   198   828 D DrmWidevineDash: message_length=1639, signature=0xb6036840, signature_length=3010457604
,07-05 14:15:40.298  1737  1790 W Herrevad: Invalid mccmnc 
,07-05 14:15:40.299  1737  1790 W Herrevad: Invalid mccmnc 
,07-05 14:15:40.314  3691  3742 I Gmail   : StartSyncInfoProto: Personal inbox enabled: true
,07-05 14:15:40.316  3691  3742 I Gmail   : StartSyncInfoProto: Personal inbox android config: com.google.c.c.a.a@6142c1c
,07-05 14:15:40.365  4096  4096 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/cache/1459442732877.jar --oat-file=/data/user/0/com.google.android.gms/cache/1459442732877.dex
,07-05 14:15:40.386   198   828 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:15:40.387   198   198 I WVCdm   : CdmEngine::CloseSession
07-05 14:15:40.387   198   198 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:15:40.402  1596  3707 I CheckinResponseProcessor: From server: 17 gservices updates and 10 deletes
,07-05 14:15:40.404   198   198 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-05 14:15:40.404   198   198 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:15:40.406  2277  2785 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:15:40.406  2277  2785 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:15:40.420  1737  1790 V NQFileLogger: [131] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:15:40.420  1737  1790 V ProcessReports: [131] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
07-05 14:15:40.424  3868  3878 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:40.429   198   198 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:15:40.429   198   198 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:15:40.429   198   198 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:15:40.430   198   198 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:15:40.430   198   198 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:15:40.443  4096  4096 I dex2oat : dex2oat took 78.475ms (threads: 4) arena alloc=306KB java alloc=38KB native alloc=1449KB free=1366KB
,07-05 14:15:40.467  3868  3878 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:40.530  1737  3982 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_identity_app_security_threat
,07-05 14:15:40.543  1737  3982 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_google_g_icon
,07-05 14:15:40.553  3868  3878 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:15:40.632  3691  3742 I Gmail   : checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^f]), all([^b, userlabel:90242001, userlabel:93982, userlabel:2914615, userlabel:90242029, userlabel:2914456, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, ^f, userlabel:-1492383895, userlabel:94076, userlabel:823616170, userlabel:-1492276994, userlabel:-1492276990, userlabel:3026, userlabel:-1492276991, ^u, ^t, ^s, ^smartlabel_group, userlabel:-812318908, ^smartlabel_personal, ^smartlabel_social, ^p_mtunsub, userlabel:2914593, ^sq_ig_i_personal, ^g, ^punsub, ^r, userlabel:-1497452393, ^i, ^smartlabel_promo, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, userlabel:93692, userlabel:2907326, userlabel:-244132349, ^sq_ig_i_social, userlabel:3011, userlabel:90241971, userlabel:1123230114, ^p_abs])
,07-05 14:15:40.633   930   930 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,07-05 14:15:40.728   930   930 W PathParser: Points are too far apart 4.030360828967057
07-05 14:15:40.728   930   930 W PathParser: Points are too far apart 4.030360538880159
07-05 14:15:40.729   930   930 W PathParser: Points are too far apart 4.030360828967057
07-05 14:15:40.729   930   930 W PathParser: Points are too far apart 4.030360538880159
,07-05 14:15:40.795  3691  3742 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 1539016952535580673, highestHandledServerOp: 24798, normalSync: true
,07-05 14:15:40.805  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:40.815  2277  3971 I art     : Note: end time exceeds epoch: 
,07-05 14:15:41.094  1737  3982 W WakefulBroadcastReceiver: No active wake lock id #4
,07-05 14:15:41.118  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:41.124  1737  1790 W Herrevad: Invalid mccmnc 
,07-05 14:15:41.125  1737  1790 W Herrevad: Invalid mccmnc 
,07-05 14:15:41.140  1737  3982 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_identity_app_security_threat
07-05 14:15:41.140  3691  3742 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24807, normalSync: true
,07-05 14:15:41.141  3691  3742 I Gmail   : lowestBackward conversation id 0
,07-05 14:15:41.144  1737  3982 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_google_g_icon
,07-05 14:15:41.200  1737  1744 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7dfb0fd)
,07-05 14:15:41.222  1737  1790 V NQFileLogger: [131] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:15:41.223  1737  1790 V ProcessReports: [131] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 14:15:41.283  1596  4123 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:15:41.323  3691  3742 I Gmail   : notifyAccountChanged
,07-05 14:15:41.325  3691  3771 I Gmail   : getAccountsCursor
,07-05 14:15:41.329  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:41.333  3691  3742 I Gmail   : notifyAccountChanged
,07-05 14:15:41.336  3691  3742 W Gmail   : Sync complete for account: account:61035162
,07-05 14:15:41.336  3691  3772 I Gmail   : getAccountsCursor
,07-05 14:15:41.340  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:41.397  1737  3982 W WakefulBroadcastReceiver: No active wake lock id #5
,07-05 14:15:41.426  3856  3856 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-05 14:15:41.467  3856  4126 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:41.480  3856  4126 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:15:41.480  3856  4126 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
07-05 14:15:41.484  3856  4126 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:41.508  3856  4126 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:41.513  3856  4126 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,07-05 14:15:41.666  3691  3736 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:15:41.742  1225  3956 I DictionaryProvider:UpdateHandler: downloadFinished() : Success = true
,07-05 14:15:41.742  1225  3956 I DictionaryProvider:UpdateHandler: downloadFinished() : Metadata Success
,07-05 14:15:41.743  1225  1225 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-05 14:15:41.745  1225  4129 I Keyboard.Facilitator.DecoderInitializer: run()
,07-05 14:15:41.746  1225  4129 I Decoder : createOrResetDecoder
,07-05 14:15:41.774  1225  4129 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-05 14:15:41.777  3743  3765 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:15:41.781   944  4130 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/metadata.json#14675158378644.1.23103.2862625.json via provider delete
,07-05 14:15:41.785   789  4133 I CertBlacklister: Certificate blacklist changed, updating...
,07-05 14:15:41.793   789  4133 I CertBlacklister: Certificate blacklist updated
07-05 14:15:41.794  1225  4129 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-05 14:15:41.796  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,07-05 14:15:41.796  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-05 14:15:41.798  1435  1457 I GservicesProvider: main difference update completed
,07-05 14:15:41.803  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,07-05 14:15:41.803  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-05 14:15:41.804  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-05 14:15:41.804  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-05 14:15:41.805  1225  4129 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-05 14:15:41.805  1225  4129 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-05 14:15:41.805  1225  4129 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-05 14:15:41.805  1225  4129 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-05 14:15:41.805  1225  4129 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,07-05 14:15:41.805  1225  4129 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-05 14:15:41.813  2277  4135 I Babel_SMS: ApnsOta: OTA version -1
,07-05 14:15:41.818   789   805 I ActivityManager: Start proc 4136:com.google.android.partnersetup/u0a13 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,07-05 14:15:41.824  1596  3707 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:15:41.826  1596  3707 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 14:15:41.833   789   974 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:15:41.833  2277  2277 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
07-05 14:15:41.833  2277  2277 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:15:41.833  2277  2277 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:15:41.833  2277  2277 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-05 14:15:41.843  4136  4136 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-05 14:15:41.885   789   800 I ActivityManager: Start proc 4157:com.google.android.googlequicksearchbox:search/u0a22 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,07-05 14:15:41.974  1596  3707 V CheckinRequestBuilder: No Subscriptions found on the device
,07-05 14:15:42.047  1596  3707 I CheckinUtil: Classify the device as Phone.
,07-05 14:15:42.126  1596  3707 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-05 14:15:42.130  1596  3707 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:15:42.131   789  1343 I ActivityManager: Killing 2545:com.android.vending/u0a16 (adj 15): empty #17
07-05 14:15:42.133  1596  1605 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/user/0/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-05 14:15:42.137  1596  1605 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@745eaae)
,07-05 14:15:42.140  1596  1605 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@6da204f)
,07-05 14:15:42.144  1596  1605 E System  : Uncaught exception thrown by finalizer
07-05 14:15:42.144  1596  1605 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:15:42.144  1596  1605 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:15:42.144  1596  1605 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-05 14:15:42.144  1596  1605 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:15:42.144  1596  1605 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:15:42.144  1596  1605 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:15:42.322  4157  4192 I GservicesUpdateTask: Updating Gservices keys
,07-05 14:15:42.330  3298  3298 W InstanceID/Rpc: Found 10008
,07-05 14:15:42.334  1596  3707 I CheckinChimeraService: Checking schedule, now: 1467720942334 next: 1467763109126
,07-05 14:15:42.334  1596  3707 I CheckinChimeraService: active receiver: disabled
,07-05 14:15:42.340  1596  1754 I Icing   : Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,07-05 14:15:42.346   789  1343 I ActivityManager: Start proc 4194:com.google.android.configupdater/u0a36 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,07-05 14:15:42.350  1596  1596 D CheckinChimeraService: Recording last checkin time for package unspecified as 1467720942349
,07-05 14:15:42.353  1596  1596 D GoogleSignatureVerifier: Package manager can't find package com.google.android.apps.work.core, defaulting to false
,07-05 14:15:42.361  3691  3773 I Gmail   : Backfilling search sequence table
,07-05 14:15:42.374  4194  4194 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm
,07-05 14:15:42.377  4157  4192 I GStaticConfiguration: #getNewConfigurationUrl [pref=2016_04_08_14_33_37, gservice=2016_06_27_18_09_34]
,07-05 14:15:42.400  4194  4194 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,07-05 14:15:42.405  1596  1754 I Icing   : Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,07-05 14:15:42.411  4194  4194 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,07-05 14:15:42.411   789   971 I ActivityManager: Killing 3337:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,07-05 14:15:42.418   789   895 D WifiService: New client listening to asynchronous messages
,07-05 14:15:42.443  4194  4194 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,07-05 14:15:42.445  4194  4194 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,07-05 14:15:42.448  4194  4194 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,07-05 14:15:42.504  1596  4234 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:15:42.504  1596  4234 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
,07-05 14:15:42.506  1596  4234 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
,07-05 14:15:42.510  1737  4231 E CommitToConfigurationOperation: Malformed snapshot token: 
,07-05 14:15:42.511  1737  4119 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:15:42.513  1596  4234 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:15:42.532  1596  4234 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 14:15:42.572  1596  1596 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,07-05 14:15:42.666  1737  4231 E CommitToConfigurationOperation: Malformed snapshot token: 
,07-05 14:15:42.667  1737  4119 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-05 14:15:42.667  1737  4241 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:15:42.702  1737  4231 E CommitToConfigurationOperation: Malformed snapshot token: 
,07-05 14:15:42.702  1737  4119 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-05 14:15:42.702  1737  4119 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-05 14:15:42.704  1737  4119 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:42.760  3856  3904 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:15:42.770  3856  4126 I CalendarSyncAdapter: Found no pending settings
,07-05 14:15:42.799   789  1318 I ActivityManager: Killing 3272:com.android.settings/1000 (adj 15): empty #17
,07-05 14:15:42.807   789   895 D WifiService: Client connection lost with reason: 4
,07-05 14:15:43.007   789   971 I ActivityManager: Killing 3457:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,07-05 14:15:43.132  1596  4253 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:15:43.138  1596  4253 I CheckinChimeraService: Checking schedule, now: 1467720943138 next: 1467763109126
,07-05 14:15:43.138  1596  4253 I CheckinChimeraService: active receiver: disabled
,07-05 14:15:43.155  1596  1596 I DynamiteModule: Considering local module com.google.android.gms.flags:0 and remote module com.google.android.gms.flags:1
,07-05 14:15:43.155  1596  1596 I DynamiteModule: Selected remote version of com.google.android.gms.flags, version >= 1
,07-05 14:15:43.219   789   804 I ActivityManager: Start proc 4255:com.google.android.music:main/u0a60 for service com.google.android.music/.sync.SyncAdapterService
,07-05 14:15:43.235  4255  4255 W System  : ClassLoader referenced unknown path: /system/app/Music2/lib/arm
,07-05 14:15:43.241  4255  4255 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:15:43.241  4255  4255 I MultiDex: install
07-05 14:15:43.241  4255  4255 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:15:43.246   789  1343 I ActivityManager: Killing 3534:com.android.chrome/u0a34 (adj 15): empty #17
,07-05 14:15:43.267  4255  4255 I MusicStore: Database version: 121
,07-05 14:15:43.309  1737  1737 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,07-05 14:15:43.317   789   799 W ActivityManager: Unable to start service Intent { act=com.google.android.gms.measurement.REFRESH_ENABLED_STATE pkg=com.google.android.gms } U=0: not found
,07-05 14:15:43.328  4255  4255 D MusicLifecycle: com.google.android.music.MusicApplication generated event: Application created
,07-05 14:15:43.376  1737  4273 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:15:43.377  4255  4255 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:43.379  1596  1596 D OcrModelBroadcastRcvr: com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:15:43.379  1596  1596 D OcrModelBroadcastRcvr: Updating OCR activity and model state
,07-05 14:15:43.389  1596  1596 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
,07-05 14:15:43.389  1596  1596 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
,07-05 14:15:43.392  4255  4255 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,07-05 14:15:43.392  4255  4255 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:43.395  4255  4255 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:43.399  1596  1596 D CmaSystemUpdateService: onCreate
07-05 14:15:43.399  1596  1596 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
,07-05 14:15:43.402  1596  1596 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
,07-05 14:15:43.407  1596  4277 V PrereqChecker: Build version: 23
,07-05 14:15:43.407  1596  4277 V PrereqChecker: Model: Nexus 5
07-05 14:15:43.407  1596  4277 V PrereqChecker: CPU_ABI: armeabi-v7a
07-05 14:15:43.407  1596  4277 V PrereqChecker: CPU_ABI2: armeabi
,07-05 14:15:43.418  1596  4277 V PrereqChecker: Camera #0 is a rear-facing camera.
,07-05 14:15:43.419  1596  4277 D CreditCardPrerequisiteChecker: All prerequisites OK.
07-05 14:15:43.419  1596  4277 I OcrModelUpdtStIntSvc: Updating ocr activity enabled=false (gservicesFlag=false, lowRamDevice=false, prereqCheck=true)
,07-05 14:15:43.422  1596  1596 I CmaSystemUpdateService: connectivity change: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-05 14:15:43.422  4255  4255 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 14:15:43.422  4255  4255 D AndroidMusic: GMSCore installation verified
07-05 14:15:43.422  1596  1596 I CmaSystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-05 14:15:43.428  1596  4278 I SystemUpdateTask: cancelUpdate (empty URL)
07-05 14:15:43.428  1596  4278 I CmaSystemUpdateService: active receiver: disabled
,07-05 14:15:43.433  4255  4255 I ConfigStore: Config Database version: 1
,07-05 14:15:43.445  1596  1596 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
,07-05 14:15:43.451  1596  4282 I SystemUpdateTask: cancelUpdate (empty URL)
07-05 14:15:43.451  1596  4282 I CmaSystemUpdateService: active receiver: disabled
,07-05 14:15:43.478  1596  1596 D CmaSystemUpdateService: onDestroy
,07-05 14:15:43.515   789   896 D ConnectivityService: handlePromptUnvalidated 100
,07-05 14:15:43.517  4255  4255 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-05 14:15:43.544  1737  4273 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 14:15:43.545   789   804 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 23039, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,07-05 14:15:43.554  4255  4255 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 14:15:43.558  4255  4255 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:43.560  1737  4273 I GCoreUlr: Unbound from all location providers
,07-05 14:15:43.569  4255  4255 D MusicLifecycle: com.google.android.music.net.NetworkMonitor generated event: Service created
,07-05 14:15:43.572  4255  4255 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:15:43.574  1737  2668 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 14:15:43.598   789   804 I ActivityManager: Start proc 4286:com.google.android.apps.cloudprint:sync/u0a35 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,07-05 14:15:43.600  4255  4255 D MusicLifecycle: com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,07-05 14:15:43.601  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,07-05 14:15:43.605  4255  4255 D MusicLifecycle: com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,07-05 14:15:43.615  4255  4255 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7aa3bd9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-05 14:15:43.616  4255  4255 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:15:43.622  4255  4255 D MusicLifecycle: com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,07-05 14:15:43.624  4255  4255 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 14:15:43.628  4255  4255 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:43.636  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service created
,07-05 14:15:43.640  4286  4286 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-05 14:15:43.648  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,07-05 14:15:43.664  4255  4303 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,07-05 14:15:43.711   789  1318 I ActivityManager: Start proc 4304:com.google.android.apps.cloudprint/u0a35 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,07-05 14:15:43.748  4304  4304 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-05 14:15:43.753  4286  4316 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,07-05 14:15:43.764   789  2167 I ActivityManager: Killing 3800:com.google.android.play.games.ui/u0a66 (adj 15): empty #17
,07-05 14:15:43.931  1737  1737 I GCoreUlr: DispatchingService.onDestroy()
07-05 14:15:43.931  1737  1737 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-05 14:15:43.934   789  2167 I ActivityManager: Killing 3908:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,07-05 14:15:44.090  1737  1737 I GCoreUlr: Unbound from all location providers
,07-05 14:15:44.100  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:44.189   789   804 I ActivityManager: Start proc 4328:com.android.chrome/u0a34 for service com.android.chrome/org.chromium.chrome.browser.sync.ChromeBrowserSyncAdapterService
,07-05 14:15:44.229  1737  1799 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:15:44.232  1737  1799 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:15:44.239   789  1319 I ActivityManager: Killing 3926:com.google.android.deskclock/u0a38 (adj 15): empty #17
,07-05 14:15:44.244   789   804 D SyncManager: handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 789064, mTimeoutStartTime 789064, mHistoryRowId 10, syncOperation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 823771, reason: Periodic
,07-05 14:15:44.290   789   800 I ActivityManager: Killing 3550:com.google.android.youtube/u0a80 (adj 15): empty #17
,07-05 14:15:44.291  1737  2711 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 14:15:44.291  4328  4349 D DelayedSyncController: Delaying sync.
,07-05 14:15:44.361   789   975 I ActivityManager: Killing 2794:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,07-05 14:15:44.460  1596  4353 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:15:44.496  1596  4356 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:15:44.512  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:44.850  4255  4303 I MusicSyncAdapter: Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,07-05 14:15:44.850  4255  4303 I MusicSyncAdapter: Periodic update
,07-05 14:15:44.872   789   805 I ActivityManager: Start proc 4364:com.android.vending/u0a16 for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver
,07-05 14:15:44.882  4255  4310 W MusicApiClient: Activity events list is null or empty. Skip reporting.
,07-05 14:15:44.894  4255  4303 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
,07-05 14:15:44.899  4255  4255 D MusicLifecycle: com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
,07-05 14:15:44.916  4364  4364 W System  : ClassLoader referenced unknown path: /data/app/com.android.vending-2/lib/arm
,07-05 14:15:44.971  1596  4382 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=284:priority=5:group=main]
,07-05 14:15:44.999  4364  4364 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,07-05 14:15:45.088  1737  4395 I GCoreUlr: Uploading GCM registration ID for account#2#
,07-05 14:15:45.094  4364  4364 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(168): Dirty, need more hygiene.
,07-05 14:15:45.108  4364  4364 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 14:15:45.109  4364  4364 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 14:15:45.122  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:45.161  4255  4255 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@66d6b09 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:15:45.162  4364  4364 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-05 14:15:45.162  4364  4364 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
,07-05 14:15:45.163  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
,07-05 14:15:45.165  4364  4364 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,07-05 14:15:45.172  4255  4255 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:15:45.176  4364  4364 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
,07-05 14:15:45.177  4255  4255 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:15:45.178  4255  4255 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@66d6b09 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:15:45.181  4255  4255 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:15:45.187  4255  4413 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 14:15:45.187  4255  4413 I MusicLeanback: Stop autocaching.
,07-05 14:15:45.191  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:15:45.196  4255  4255 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,07-05 14:15:45.197  4255  4255 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
,07-05 14:15:45.203  4255  4255 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:15:45.205  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:15:45.224  4255  4255 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@66d6b09 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:15:45.228  4255  4255 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,07-05 14:15:45.234  4255  4255 D MusicLifecycle: com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,07-05 14:15:45.242  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:15:45.245  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@66d6b09 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:15:45.265  4255  4255 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:15:45.271  1737  1737 D WearableService: callingUid 10008, callindPid: 1737
,07-05 14:15:45.277  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:15:45.279  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:15:45.301  4255  4255 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:15:45.303  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:15:45.313  4255  4255 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:15:45.313  4255  4428 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:15:45.314  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:15:45.316   789   799 I ActivityManager: Killing 3721:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,07-05 14:15:45.429   789  2167 I ActivityManager: Killing 3743:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,07-05 14:15:45.474  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:45.510   789   804 I ActivityManager: Start proc 4434:com.google.android.apps.docs/u0a40 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,07-05 14:15:45.565  1737  4395 I GCoreUlr: GCM ID uploaded for account#2#
,07-05 14:15:45.578  1737  4395 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,07-05 14:15:45.621  1737  1783 I GCoreUlr: DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 14:15:45.629  1737  1783 I GCoreUlr: Unbound from all location providers
,07-05 14:15:45.637  1737  1737 I GCoreUlr: DispatchingService.onDestroy()
,07-05 14:15:45.637  1737  1737 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-05 14:15:45.640  1737  1737 I GCoreUlr: Unbound from all location providers
,07-05 14:15:45.690  4434  4446 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:15:45.690  4434  4446 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:15:45.690  4434  4446 I GAv4    :   adb logcat -s GAv4
,07-05 14:15:45.702   789   799 I ActivityManager: Killing 3891:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-05 14:15:45.763  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 14:15:45.763  4434  4446 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:45.768  4434  4446 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:45.774  4434  4458 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:15:45.780  1596  4454 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:15:45.785  4434  4446 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.35
,07-05 14:15:45.788  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:45.800   789   799 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@5f050bc}
,07-05 14:15:45.853  4434  4463 W Flag    : Duration spec must be at least 2 characters long
,07-05 14:15:45.879  1596  4454 I PeopleSync: Setting subscription: result=true [5005f081]
07-05 14:15:45.880  1596  4454 I PeopleSync: Starting sync, feed=null [5005f081]
,07-05 14:15:45.890  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:45.904  4434  4463 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:45.920  4434  4463 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,07-05 14:15:45.920  4434  4463 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:45.924  4434  4463 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:45.926  1596  4454 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,07-05 14:15:45.941   789  1318 I ActivityManager: Killing 2277:com.google.android.talk/u0a54 (adj 15): empty #17
,07-05 14:15:45.947  4434  4463 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:46.143  4364  4364 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,07-05 14:15:46.152  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:46.479  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:46.511  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:46.609   930   930 D PhoneStatusBar: disable: < expand icons* alerts system_info* back home recent clock search quick_settings >
,07-05 14:15:46.622  4364  4389 I Finsky  : [348] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,07-05 14:15:46.623  4364  4389 I Finsky  : [348] com.google.android.finsky.g.b.a(4353): Process stable target turned on mid-process: 12607045
,07-05 14:15:46.825  4364  4364 I Finsky  : [1] com.google.android.finsky.selfupdate.f.a(163): Skipping DFE self-update. Local Version [80671300] >= Server Version [-1]
,07-05 14:15:46.850  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:46.868   789   972 I ActivityManager: Start proc 4485:com.google.android.gms:car/u0a8 for service com.google.android.gms/.car.CarService
,07-05 14:15:46.954  4485  4485 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:15:46.954  4485  4485 I MultiDex: install
07-05 14:15:46.954  4485  4485 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 14:15:46.954  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:46.980  4485  4485 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:46.991  4485  4485 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,07-05 14:15:46.991  4485  4485 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:46.996  4485  4485 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:47.021  4485  4485 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:47.032  4485  4485 D ChimeraCfgMgr: Reading stored module config
,07-05 14:15:47.097  4485  4485 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,07-05 14:15:47.097  4485  4485 D CAR.SERVICE: onBind
07-05 14:15:47.097  4485  4485 D CAR.SERVICE: CSB onBind
,07-05 14:15:47.110  4485  4485 D CAR.TEL.Service: onBind, intent: Intent { cmp=com.google.android.gms/.car.CarCallService }
07-05 14:15:47.111  4485  4485 D CAR.TEL.Service: Creating a new CarCallService.
07-05 14:15:47.111  4485  4485 D CAR.TEL.Service: bindToInCallService
,07-05 14:15:47.112   789  2167 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,07-05 14:15:47.114  4485  4485 D CAR.SERVICE: onServiceConnected: ComponentInfo{com.google.android.gms/com.google.android.gms.car.CarCallService}, service: glo@6239c3d
,07-05 14:15:47.116  4485  4506 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
07-05 14:15:47.125  4485  4496 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,07-05 14:15:47.195  4485  4496 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
07-05 14:15:47.195  4485  4496 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:15:47.200  4485  4496 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
,07-05 14:15:47.201  4485  4496 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:15:47.202  4485  4496 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:15:47.203  4485  4496 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:15:47.257  4485  4496 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:15:47.276  4485  4496 D CAR.SERVICE: Package validated; name: com.android.vending
,07-05 14:15:47.277  4485  4496 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
,07-05 14:15:47.326  1596  2646 E Volley  : [140] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CP3Z-IrXKhIBMRj4EioECAEQAQ
07-05 14:15:47.327  1596  4454 I PeopleSync: Sync Token out of date, syncing all people/gaia-map
,07-05 14:15:47.349   789   972 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@5f050bc}
,07-05 14:15:47.513   789   894 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,07-05 14:15:47.576  1596  4454 I PeopleSync: Sync finished, successful=true, took 1617ms
,07-05 14:15:47.595  1596  4454 I PeopleContactsSync: CP2 sync start [5005f081]
,07-05 14:15:47.602  1596  4454 I PeopleContactsSync: CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-05 14:15:47.608  1596  4454 I PeopleContactsSync: Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-05 14:15:47.642  1596  4454 I PeopleContactsSync: CP2 cleanup done, kept= duration=32 ms
,07-05 14:15:47.647  1596  4454 I PeopleContactsSync: ===CP2 sync finished, success=true, time=48,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,07-05 14:15:47.668  1596  4454 I PeopleSync: ***Sync finished***, duration: 1886 [5005f081]
,07-05 14:15:47.712  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:47.733  1596  4525 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:15:47.739  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:47.804  1596  4525 I PeopleSync: Setting subscription: result=true [5005f081]
,07-05 14:15:47.865   789   804 I ActivityManager: Start proc 4527:com.google.android.apps.plus/u0a67 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,07-05 14:15:47.990  4364  4364 I Finsky  : [1] com.google.android.finsky.api.model.u.b(8653): Change auto-acquire tags for com.google.android.keep from  to d_AAAAAAADF8w=
07-05 14:15:47.990  4364  4364 I Finsky  : [1] com.google.android.finsky.api.model.u.b(8653): Change auto-acquire tags for com.google.android.apps.cloudprint from  to d_AAAAAAADF8w=
,07-05 14:15:47.991  4364  4364 I Finsky  : [1] com.google.android.finsky.api.model.u.b(8653): Change auto-acquire tags for com.google.android.tts from  to d_AAAAAAADF8w=
,07-05 14:15:47.993  4364  4364 I Finsky  : [1] com.google.android.finsky.utils.db.a(64): com.google.android.gm.exchange available because owned, overriding [restriction=7].
,07-05 14:15:47.994  4364  4364 I Finsky  : [1] com.google.android.finsky.utils.db.a(64): com.google.android.apps.gcs available because owned, overriding [restriction=10].
07-05 14:15:47.994  4364  4364 I Finsky  : [1] com.google.android.finsky.utils.db.a(64): com.google.android.GoogleCamera available because owned, overriding [restriction=7].
,07-05 14:15:48.013   789  1310 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@60c23e0}
,07-05 14:15:48.037  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.j.a(469): Request install of com.google.android.gms v=9256438 pri=2 for auto_update
,07-05 14:15:48.044  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1258): Installer kick - starting com.google.android.gms
,07-05 14:15:48.045  4434  4544 W Flag    : Duration spec must be at least 2 characters long
,07-05 14:15:48.055  4364  4393 I Finsky  : [351] com.google.android.finsky.installer.y.b(204): Created session 1276760145 for com.google.android.gms
07-05 14:15:48.055  4364  4364 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,07-05 14:15:48.056  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:48.068  4364  4364 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,07-05 14:15:48.074  4364  4364 W InstanceID/Rpc: Found 10008
,07-05 14:15:48.100  4364  4364 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(42): Verify installed apps requested
,07-05 14:15:48.107  1737  1782 D DeviceConnectionService: client connected with version: 8486000
,07-05 14:15:48.116  4364  4552 I Finsky  : [379] com.google.android.vending.verifier.ac.a(103): Verifying installed packages
,07-05 14:15:48.143  4364  4364 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 14:15:48.143  4364  4364 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
,07-05 14:15:48.147  4364  4553 I Finsky  : [380] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-05 14:15:48.148  4364  4404 I PlayCommon: [359] com.google.android.play.a.w.a(27551): Starting to flush logs
,07-05 14:15:48.159  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:15:48.182  4364  4364 I Finsky  : [1] com.google.android.vending.verifier.ac.b(136): Done verifying installed packages
,07-05 14:15:48.245   789  1333 I ActivityManager: Start proc 4556:com.android.providers.calendar/u0a2 for content provider com.android.providers.calendar/.CalendarProvider2
,07-05 14:15:48.269  4556  4556 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-05 14:15:48.278  4364  4404 I PlayCommon: [359] com.google.android.play.a.w.a(27562): Log flushed by 1 successful uploads
,07-05 14:15:48.285  4556  4556 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@a635ebe(com.android.providers.calendar.CalendarProvider2@8216b1f)
,07-05 14:15:48.290   789  3843 I ActivityManager: Killing 4136:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-05 14:15:48.445  4364  4393 I Finsky  : [351] com.google.android.finsky.installer.ah.run(127): Session for com.google.android.gms already exists, skipping creation
,07-05 14:15:48.531  4255  4255 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@66d6b09 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:15:48.534  4255  4255 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:15:48.537  4255  4255 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:15:48.537  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@66d6b09 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:15:48.540  4255  4255 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:15:48.544  4255  4575 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 14:15:48.544  4255  4575 I MusicLeanback: Stop autocaching.
,07-05 14:15:48.545  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:15:48.550  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:15:48.550  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:15:48.554  4255  4255 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:15:48.555  4255  4255 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:15:48.556  4255  4255 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:15:48.557  4255  4578 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:15:48.558  4255  4255 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:15:48.760   789  1319 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@60c23e0}
,07-05 14:15:48.767   789  1333 I ActivityManager: Killing 3298:com.google.android.apps.gcs/u0a82 (adj 15): empty #17
,07-05 14:15:48.811  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.ai.onPostExecute(5001): Downloading patch for com.google.android.gms (com.google.android.gms)
,07-05 14:15:48.815  4364  4364 I Finsky  : [1] com.google.android.finsky.download.e.a(256): Duplicate state set for 'com.google.android.gms' (0). Already in that state
,07-05 14:15:48.816  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.gms added to DownloadQueue
,07-05 14:15:48.818  4364  4364 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.gms from 0 to 1.
,07-05 14:15:48.820   199   199 I installd: free_cache(23317919) avail 12112257024
,07-05 14:15:48.823  4364  4364 I Finsky  : [1] com.google.android.finsky.download.ai.run(5554): Download com.google.android.gms starting
,07-05 14:15:48.871  4364  4394 I Finsky  : [352] com.google.android.finsky.download.ae.a(1567): Enqueued com.google.android.gms as content://downloads/my_downloads/106
,07-05 14:15:48.872  4364  4364 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.gms from 1 to 2.
,07-05 14:15:48.873  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.a(632): com.google.android.gms: onStart
,07-05 14:15:48.878  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.gms: onProgress 0/-1 Status: 190.
,07-05 14:15:48.888  3856  4555 I CalendarSyncAdapter: Found no pending settings
,07-05 14:15:48.910  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.gms: onProgress 0/-1 Status: 192.
,07-05 14:15:48.911   944  4587 D DownloadManager: [106] Starting
,07-05 14:15:48.916  3856  4589 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,07-05 14:15:48.936   789  1333 I ActivityManager: Killing 4157:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,07-05 14:15:48.949   789   895 D WifiService: Client connection lost with reason: 4
,07-05 14:15:49.369  4556  4556 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-05 14:15:49.370  4556  4556 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 14:15:49.456   789   896 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:15:49.719  3856  4593 I CalendarSyncAdapter: Found no pending settings
,07-05 14:15:50.698  1737  4285 D PlaceInferenceEngine: Stop called when not running
,07-05 14:15:50.700  1737  1799 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:15:51.974   789   819 W PackageSettings: Skipping PackageSetting{f76c3b8 com.example.hello/10278} due to missing metadata
,07-05 14:15:52.331  4485  4485 D CAR.SERVICE: onUnbind
,07-05 14:15:52.332  4485  4485 D CAR.SERVICE: CSB onUnbind
07-05 14:15:52.332  4485  4485 D CAR.SERVICE: tearDown
07-05 14:15:52.332  4485  4485 D CAR.SERVICE: tearDownCarState
07-05 14:15:52.332  4485  4485 D CAR.SERVICE: Skip, car not connected.
07-05 14:15:52.332  4485  4485 D CAR.SERVICE: tearDownClientState
,07-05 14:15:52.333  4485  4485 D CAR.SERVICE: requestStop
07-05 14:15:52.334  4485  4485 D CAR.SERVICE: onDestroy
07-05 14:15:52.334  4485  4485 D CAR.SERVICE: tearDown
07-05 14:15:52.334  4485  4485 D CAR.SERVICE: tearDownCarState
07-05 14:15:52.334  4485  4485 D CAR.SERVICE: Skip, car not connected.
07-05 14:15:52.334  4485  4485 D CAR.SERVICE: tearDownClientState
07-05 14:15:52.334  4485  4485 D CAR.SERVICE: requestStop
,07-05 14:15:52.335  4485  4485 D CAR.TEL.Service: onUnbind, intent: Intent { cmp=com.google.android.gms/.car.CarCallService }
,07-05 14:15:52.335  4485  4485 D CAR.TEL.Service: unbindFromInCallService
07-05 14:15:52.336  4485  4485 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection glq@7054994 that was originally bound here
07-05 14:15:52.336  4485  4485 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection glq@7054994 that was originally bound here
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at jvs.a(SourceFile:127)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at jvs.a(SourceFile:144)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:1447)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2904)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.ActivityThread.-wrap2(ActivityThread.java)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1432)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:15:52.336  4485  4485 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:15:52.337   789   800 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@ddee9c
,07-05 14:15:52.383   789   805 I ActivityManager: Start proc 4623:com.google.android.googlequicksearchbox:search/u0a22 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,07-05 14:15:52.391   789   885 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:15:52.465   789   896 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:15:52.589   789   975 I ActivityManager: Start proc 4653:com.google.android.partnersetup/u0a13 for content provider com.google.android.partnersetup/.RlzAppProvider
,07-05 14:15:52.600   789   972 I ActivityManager: Start proc 4665:com.google.android.talk/u0a54 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
07-05 14:15:52.601   789   972 I ActivityManager: Killing 4194:com.google.android.configupdater/u0a36 (adj 15): empty #17
,07-05 14:15:52.642   789   974 I ActivityManager: Killing 3612:com.google.android.apps.photos/u0a65 (adj 15): empty #17
,07-05 14:15:52.683  1737  1737 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 14:15:52.689  4653  4653 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-05 14:15:52.872  4665  4687 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-05 14:15:52.872  4665  4687 I Babel_SMS: MmsConfig.loadMmsSettings
,07-05 14:15:52.875  4665  4687 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
07-05 14:15:52.875  4665  4687 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 14:15:52.908  4665  4687 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-05 14:15:52.908  4665  4687 I Babel_SMS: MmsConfig.loadFromResources
,07-05 14:15:52.910  4665  4687 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-05 14:15:52.911  4665  4687 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-05 14:15:52.940  4665  4690 I Babel_SMS: ApnsOta: OTA version -1
,07-05 14:15:52.947  4665  4665 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:15:52.949  4665  4665 I Babel_Crash: startup - clean
,07-05 14:15:52.957  4665  4665 I Babel_telephony: TeleModule.launchCompleted
,07-05 14:15:52.958  4665  4691 I Babel   : deleted: false for 0
,07-05 14:15:52.961   789  1319 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:15:52.963  4665  4665 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-05 14:15:52.964  4665  4665 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:15:52.964  4665  4665 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:15:52.964  4665  4665 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-05 14:15:52.966   789  3843 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:15:52.995  4623  4695 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 14:15:53.027  4665  4665 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:15:53.039  1596  4697 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:15:53.039  1596  4697 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoring.
,07-05 14:15:53.045  1596  4697 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:15:53.064  1596  4702 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
,07-05 14:15:53.070  1596  1754 I Icing   : updateResources: need to parse pru{com.google.android.gms}
,07-05 14:15:53.088  4665  4665 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 14:15:53.098  1596  4704 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:15:53.100  4665  4665 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:15:53.102  4665  4665 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:15:53.108  4665  4665 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:15:53.120  4665  4665 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:15:53.134  4623  4695 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 139 ms] updated apps [took 139 ms] 
,07-05 14:15:53.156  4665  4665 I vclib   : onServiceConnected
,07-05 14:15:53.188  4665  4665 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:15:53.203  4665  4665 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:15:53.203  4665  4665 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:15:53.206  4665  4665 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:15:53.229  4665  4665 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:15:54.202  1596  1754 I Icing   : Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,07-05 14:15:54.224  1596  1754 I Icing   : Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,07-05 14:15:54.472   789   975 I ActivityManager: Killing 4014:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-05 14:15:54.572   944  4587 D DownloadManager: [106] Finished with status SUCCESS
,07-05 14:15:54.605  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.gms: onProgress 23317919/23317919 Status: 200.
,07-05 14:15:54.609  4364  4364 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(46): Intent received at DownloadBroadcastReceiver
,07-05 14:15:54.616  4364  4364 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.gms from 2 to 3.
,07-05 14:15:54.617  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.b(600): com.google.android.gms: onComplete
07-05 14:15:54.617  4364  4364 I Finsky  : [1] com.google.android.finsky.download.x.i(341): Download com.google.android.gms removed from DownloadQueue
07-05 14:15:54.618   199   199 I installd: free_cache(0) avail 12089597952
,07-05 14:15:54.620  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.x.c(36121): Prepare to patch com.google.android.gms (com.google.android.gms) from content://downloads/my_downloads/106 format 3
,07-05 14:15:54.638   199   199 I installd: free_cache(47193605) avail 12089597952
,07-05 14:15:54.644  1596  1596 V Herrevad: NQAS connected
,07-05 14:15:54.685  1596  1754 W Herrevad: Invalid mccmnc 
,07-05 14:15:54.686  1596  1754 W Herrevad: Invalid mccmnc 
,07-05 14:15:54.811  1596  1754 I ReportNQOperation: [102] ReportNetworkQualityChimeraOperation.a: Not enough data to save wifi report to local db: pos@4102066
,07-05 14:15:58.256   789   799 I ActivityManager: Killing 4304:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
,07-05 14:16:00.094   789  1319 I ActivityManager: Killing 4286:com.google.android.apps.cloudprint:sync/u0a35 (adj 15): empty #17
,07-05 14:16:00.561  4364  4412 I Finsky  : [365] com.google.android.finsky.receivers.ab.a(3193): Patch apply task for com.google.android.gms (com.google.android.gms) (format 3) completed in 5940 ms
,07-05 14:16:00.564  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.ab.onPostExecute(4243): Successfully applied patch to update com.google.android.gms (com.google.android.gms)
,07-05 14:16:00.568  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.x.c(42122): Begin install of com.google.android.gms
,07-05 14:16:00.570   944  3719 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/downloadfile.bin via provider delete
,07-05 14:16:01.945   789   812 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:16:01.946   789   812 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:16:01.948  1225  1225 I Keyboard.Facilitator: onFinishInput()
,07-05 14:16:01.965  3179  3179 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:16:01.965  3179  3179 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:16:02.005  3179  3179 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b99ef04 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3cc425, 16908290=android.view.AbsSavedState$1@3cc425}, android:focusedViewId=100}]}]
,07-05 14:16:02.005  3179  3179 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:16:02.005  3179  3179 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:16:02.005  3179  3179 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:16:02.109   789   798 I art     : Background partial concurrent mark sweep GC freed 116566(5MB) AllocSpace objects, 16(2MB) LOS objects, 33% free, 28MB/42MB, paused 1.070ms total 135.958ms
,07-05 14:16:02.429   789   819 I ActivityManager: Start proc 4732:com.android.defcontainer/u0a5 for service com.android.defcontainer/.DefaultContainerService
,07-05 14:16:02.454   789   812 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 14:16:02.472   789   810 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:16:02.474   191   191 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,07-05 14:16:02.474   191   191 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 14:16:02.513  4364  4364 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2102): Skipping verification because own installation
,07-05 14:16:02.750   191   191 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-05 14:16:02.757   789   910 D SurfaceControl: Excessive delay in setPowerMode(): 285ms
07-05 14:16:02.757  1962  1978 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-05 14:16:02.759   198   198 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-05 14:16:02.771   789   894 D WifiConfigStore: Retrieve network priorities after PNO.
07-05 14:16:02.777   789   894 E native  : do suspend true
,07-05 14:16:04.732   789   819 I PackageManager.DexOptimizer: Running dexopt (dex2oat) on: /data/app/vmdl1276760145.tmp/base.apk pkg=com.google.android.gms isa=arm vmSafeMode=false debuggable=false oatDir = /data/app/vmdl1276760145.tmp/oat bootComplete=true
,07-05 14:16:04.768  4751  4751 I dex2oat : Starting dex2oat.
,07-05 14:16:07.006  4364  4407 I Finsky  : [362] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-05 14:16:07.100  4364  4407 I Finsky  : [362] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-05 14:16:07.101  4364  4364 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-05 14:16:09.815  1596  4773 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:16:09.949   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=819887, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:16:12.681  4751  4751 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString()
,07-05 14:16:13.471  4751  4757 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString()
,07-05 14:16:15.438  1596  4774 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:16:15.498   789   894 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,07-05 14:16:15.582  1737  1744 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b02737b)
,07-05 14:16:15.755  4751  4756 W dex2oat : Compilation of aglb aglb.a(alew) took 1.929s
,07-05 14:16:17.064  4751  4757 W dex2oat : Compilation of agle agle.a(alew) took 3.237s
,07-05 14:16:18.094  4751  4756 I dex2oat : Method exceeds compiler instruction limit: 21296 in void ankb.<init>()
07-05 14:16:18.094  4751  4756 I dex2oat : Method exceeds compiler instruction limit: 21296 in void ankb.<init>()
,07-05 14:16:18.108  4751  4757 I dex2oat : Skipping compilation of void ankc.n(char[], int, int): it contains a non natural loop
,07-05 14:16:19.103  4751  4756 W dex2oat : No verified method for method calling String.<init>: void org.json.JSONStringer.<init>(int)
,07-05 14:16:19.849   789   804 I ActivityManager: Start proc 4775:com.google.process.gapps/u0a85 for service com.google.android.syncadapters.contacts/.ContactsSyncAdapterService
,07-05 14:16:19.861  4775  4775 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-05 14:16:19.873  4775  4775 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:16:19.914  1596  4789 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-05 14:16:19.931   789   804 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 817198, reason: UserStart, SyncResult: databaseError: true stats []
,07-05 14:16:19.931   789   804 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 892957, reason: UserStart
,07-05 14:16:19.936  4775  4790 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,07-05 14:16:19.938  4775  4790 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:16:20.131  4751  4757 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString()
,07-05 14:16:20.166  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:20.169  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 14:16:20.170  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:21.082   789   972 I ActivityManager: Killing 4328:com.android.chrome/u0a34 (adj 15): empty #17
,07-05 14:16:25.183  4751  4758 I dex2oat : Method exceeds compiler instruction limit: 20154 in void pex.<init>()
,07-05 14:16:25.183  4751  4758 I dex2oat : Method exceeds compiler instruction limit: 20154 in void pex.<init>()
,07-05 14:16:25.319   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=835257, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:16:30.592  4751  4751 I dex2oat : dex2oat took 25.823s (threads: 4) arena alloc=179MB java alloc=39MB native alloc=311MB free=123MB
,07-05 14:16:30.670   789   805 I ActivityManager: Force stopping com.google.android.gms appid=10008 user=-1: replace sys pkg
,07-05 14:16:30.670   789   805 I ActivityManager: Killing 1737:com.google.android.gms.persistent/u0a8 (adj 1): stop com.google.android.gms
,07-05 14:16:30.689   789   819 W PackageManager: Trying to update system app code path from /data/app/com.google.android.gms-2 to /data/app/com.google.android.gms-1
,07-05 14:16:30.689   789   819 W PackageManager: Package com.google.android.gms desires unavailable shared library com.google.android.ble; ignoring!
,07-05 14:16:30.694   789   895 D WifiService: Client connection lost with reason: 4
,07-05 14:16:30.694   789   789 V BackupManagerService: Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-05 14:16:30.695   789   789 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,07-05 14:16:30.695   789  1333 D GpsStatusListenerHelper: Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@602d62d
,07-05 14:16:30.701   789   819 W PackageManager: Code path for com.google.android.gms changing from /data/app/com.google.android.gms-2 to /data/app/com.google.android.gms-1
,07-05 14:16:30.701   789   819 W PackageManager: Resource path for com.google.android.gms changing from /data/app/com.google.android.gms-2 to /data/app/com.google.android.gms-1
,07-05 14:16:30.718   789   819 W PackageManager: Permission group com.google.android.gms.permission.CAR_INFORMATION from package com.google.android.gms ignored: original from com.google.android.gms
,07-05 14:16:30.718   789   819 W PackageManager: Permission com.google.android.gms.permission.ACTIVITY_RECOGNITION from package com.google.android.gms in an unknown group android.permission-group.PERSONAL_INFO
,07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 1000ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService in 11000ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.PlayLogBrokerService in 20999ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 30999ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 40999ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 50999ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 60999ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 70999ms
07-05 14:16:30.720   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 80999ms
07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 90999ms
07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 100999ms
07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService in 110999ms
,07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 120999ms
07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 130999ms
07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 140999ms
07-05 14:16:30.721   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 150999ms
,07-05 14:16:30.722   789   805 I ActivityManager: Killing 4485:com.google.android.gms:car/u0a8 (adj 13): stop com.google.android.gms
,07-05 14:16:30.760   789   805 I ActivityManager: Killing 3691:com.google.android.gm/u0a70 (adj 15): stop com.google.android.gms
,07-05 14:16:30.784   789   819 W PackageSettings: Skipping PackageSetting{f76c3b8 com.example.hello/10278} due to missing metadata
,07-05 14:16:30.799   789   805 I ActivityManager: Killing 3868:com.google.android.gms.unstable/u0a8 (adj 13): stop com.google.android.gms
,07-05 14:16:30.827   789   819 W PackageManager: Unknown permission android.permission.MANAGE_SOUND_TRIGGER in package com.google.android.gms
,07-05 14:16:30.827   789   819 W PackageManager: Not granting permission android.permission.READ_PRIVILEGED_PHONE_STATE to package com.google.android.gms (protectionLevel=18 flags=0xb8483ec5)
07-05 14:16:30.827   789   819 W PackageManager: Unknown permission android.permission.TETHER_PRIVILEGED in package com.google.android.gms
07-05 14:16:30.827   789   819 W PackageManager: Unknown permission android.permission.READ_OEM_UNLOCK_STATE in package com.google.android.gms
07-05 14:16:30.827   789   819 W PackageManager: Not granting permission android.permission.OVERRIDE_WIFI_CONFIG to package com.google.android.gms (protectionLevel=18 flags=0xb8483ec5)
07-05 14:16:30.827   789   819 W PackageManager: Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
07-05 14:16:30.828   789   819 W PackageManager: Unknown permission com.google.android.wh.supervisor.permission.ACCESS_METADATA_SERVICE in package com.google.android.gms
07-05 14:16:30.828   789   819 W PackageManager: Unknown permission android.permission.SUBSTITUTE_NOTIFICATION_APP_NAME in package com.google.android.gms
,07-05 14:16:30.828   789   819 W PackageManager: Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.google.android.gms
,07-05 14:16:30.859   789   805 I ActivityManager: Killing 4434:com.google.android.apps.docs/u0a40 (adj 9): stop com.google.android.gms
,07-05 14:16:30.882   789   819 W PackageSettings: Skipping PackageSetting{f76c3b8 com.example.hello/10278} due to missing metadata
,07-05 14:16:30.899   789   805 I ActivityManager: Killing 1596:com.google.android.gms/u0a8 (adj 9): stop com.google.android.gms
,07-05 14:16:30.924   789   895 D WifiService: Client connection lost with reason: 4
,07-05 14:16:30.924   789  1319 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@68a5721)
07-05 14:16:30.925   789   896 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:16:30.927   789   896 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:16:30.949   789   805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 160770ms
,07-05 14:16:30.950   789   805 I ActivityManager: Killing 4255:com.google.android.music:main/u0a60 (adj 13): stop com.google.android.gms
,07-05 14:16:30.980   789   805 I ActivityManager: Killing 3856:com.google.android.calendar/u0a31 (adj 13): stop com.google.android.gms
,07-05 14:16:31.010   789   805 I ActivityManager: Killing 4665:com.google.android.talk/u0a54 (adj 11): stop com.google.android.gms
,07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{7cdf6f8 u0 com.google.android.gms/.backup.BackupTransportService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{4d375db u0 com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{61d9dd3 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{38f71ec u0 com.google.android.gms/.common.stats.GmsCoreStatsService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{ff7c0d8 u0 com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{c9a442f u0 com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{caecd48 u0 com.google.android.gms/com.google.android.location.network.NetworkLocationService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{dc49477 u0 com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{b4f5bb8 u0 com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{2f78f8c u0 com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{9842bc7 u0 com.google.android.gms/com.google.android.location.fused.FusedLocationService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{2925219 u0 com.google.android.gms/com.google.android.location.fused.service.FusedProviderService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{940e4cc u0 com.google.android.gms/.gcm.GcmService}
07-05 14:16:31.040   789   805 I ActivityManager:   Force stopping service ServiceRecord{1c83f92 u0 com.google.android.gms/com.google.android.location.geocode.GeocodeService}
,07-05 14:16:31.042   789   805 I ActivityManager: Force stopping com.google.android.gms appid=10008 user=-1: replace pkg
,07-05 14:16:31.044   789  1333 W ActivityManager: Spurious death for ProcessRecord{b375f4e 0:com.google.android.gms:car/u0a8}, curProc for 4485: null
,07-05 14:16:31.044   789  1343 W ActivityManager: Spurious death for ProcessRecord{56acecb 0:com.google.android.gm/u0a70}, curProc for 3691: null
,07-05 14:16:31.044   789  1318 W ActivityManager: Spurious death for ProcessRecord{e75c9a0 0:com.google.android.gms.unstable/u0a8}, curProc for 3868: null
07-05 14:16:31.045   789   974 W ActivityManager: Spurious death for ProcessRecord{d53d845 0:com.google.android.apps.docs/u0a40}, curProc for 4434: null
07-05 14:16:31.045   789  1319 W ActivityManager: Spurious death for ProcessRecord{d8ba2b1 0:com.google.android.gms/u0a8}, curProc for 1596: null
07-05 14:16:31.045   789   975 W ActivityManager: Spurious death for ProcessRecord{343b0a 0:com.google.android.music:main/u0a60}, curProc for 4255: null
07-05 14:16:31.046   789  4806 W ActivityManager: Spurious death for ProcessRecord{76dd80c 0:com.google.android.calendar/u0a31}, curProc for 3856: null
,07-05 14:16:31.046   789  4808 W ActivityManager: Spurious death for ProcessRecord{d0994b7 0:com.google.android.talk/u0a54}, curProc for 4665: null
07-05 14:16:31.047   789   819 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
07-05 14:16:31.047   789   819 I art     : Starting a blocking GC Explicit
,07-05 14:16:31.057   789   799 W ActivityManager: Spurious death for ProcessRecord{dab835 0:com.google.android.gms.persistent/u0a8}, curProc for 1737: null
,07-05 14:16:31.081   789  4805 I ActivityManager: Start proc 4809:com.google.android.gms.persistent/u0a8 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,07-05 14:16:31.160  4809  4809 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:16:31.160  4809  4809 I MultiDex: install
07-05 14:16:31.160  4809  4809 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:31.166   789   819 I art     : Explicit concurrent mark sweep GC freed 175998(9MB) AllocSpace objects, 22(1236KB) LOS objects, 33% free, 24MB/37MB, paused 1.198ms total 118.623ms
,07-05 14:16:31.189  4809  4809 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:31.199  4809  4809 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-05 14:16:31.199  4809  4809 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:31.202  4809  4809 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:31.215   789   819 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.google.android.gms-2/base.apk, retcode=-1
,07-05 14:16:31.225  4809  4809 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:31.226   199   199 E installd: Couldn't opendir /data/app/vmdl1276760145.tmp: No such file or directory
,07-05 14:16:31.228   789   819 I ActivityManager: Force stopping com.google.android.gms appid=10008 user=0: pkg removed
,07-05 14:16:31.228   789   819 I ActivityManager: Killing 4809:com.google.android.gms.persistent/u0a8 (adj 0): stop com.google.android.gms
,07-05 14:16:31.247  4364  4364 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2142): Successful install of com.google.android.gms
,07-05 14:16:31.289   789   819 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,07-05 14:16:31.290   789   819 I ActivityManager:   Force stopping service ServiceRecord{b6c1df6 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,07-05 14:16:31.294   789  4805 W ActivityManager: Spurious death for ProcessRecord{193fecd 0:com.google.android.gms.persistent/u0a8}, curProc for 4809: null
,07-05 14:16:31.295  4364  4364 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(277): Wear auto install disabled for package com.google.android.gms
,07-05 14:16:31.299   789   789 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-05 14:16:31.301  3230  3230 D BluetoothMapAppObserver: onReceive
,07-05 14:16:31.301  3230  3230 D BluetoothMapAppObserver: The removed package is: com.google.android.gms
07-05 14:16:31.302   789   885 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:16:31.328   789  4808 I ActivityManager: Start proc 4831:com.google.android.talk/u0a54 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,07-05 14:16:31.338  3230  3230 D BluetoothMapAppObserver: onReceive
,07-05 14:16:31.338  3230  3230 D BluetoothMapAppObserver: The installed package is: com.google.android.gms
07-05 14:16:31.344   789   885 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:16:31.349   789   885 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:16:31.353  3230  3230 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-05 14:16:31.357  1289  1289 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-05 14:16:31.357  3230  3230 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-05 14:16:31.381   789   799 I ActivityManager: Start proc 4843:com.google.android.gms.persistent/u0a8 for service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService
,07-05 14:16:31.414  1289  1289 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_ADDED
07-05 14:16:31.414  1289  1289 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REPLACED
07-05 14:16:31.415  1289  1289 D CarrierServiceBindHelper: mHandler: 3
07-05 14:16:31.415  1289  1289 D CarrierServiceBindHelper: mHandler: 3
07-05 14:16:31.415  1289  1289 D CarrierServiceBindHelper: mHandler: 3
07-05 14:16:31.415  1289  1289 D CarrierConfigLoader: mHandler: 9 phoneId: 0
,07-05 14:16:31.453  4843  4843 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:16:31.453  4843  4843 I MultiDex: install
07-05 14:16:31.454  4843  4843 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:31.477  4843  4843 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:31.489  4843  4843 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:16:31.489  4843  4843 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:31.492  4843  4843 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:31.507  4831  4868 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-05 14:16:31.507  4831  4868 I Babel_SMS: MmsConfig.loadMmsSettings
,07-05 14:16:31.508  4831  4868 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
07-05 14:16:31.509  4831  4868 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 14:16:31.519  4843  4843 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:31.528  4843  4843 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:31.545  4843  4843 W ChimeraModuleLdr: Config is out of date: ContainerApk(com.google.android.gms) has incorrect timestamp/version
,07-05 14:16:31.553  4843  4843 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:31.555  4843  4843 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
,07-05 14:16:31.555  4843  4843 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:31.555  4843  4843 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:31.555  4843  4843 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:31.565  4843  4843 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 14:16:31.565  4843  4843 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
07-05 14:16:31.568  4831  4868 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-05 14:16:31.568  4831  4868 I Babel_SMS: MmsConfig.loadFromResources
07-05 14:16:31.569  4831  4868 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 14:16:31.570  4831  4868 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-05 14:16:31.571  4831  4872 I Babel_SMS: ApnsOta: OTA version -1
,07-05 14:16:31.572  4843  4843 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
07-05 14:16:31.573  4843  4843 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:16:31.574  4843  4843 D ChimeraFileApk: Classloading successful. Optimized code found.
07-05 14:16:31.577  4843  4843 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
07-05 14:16:31.585  4831  4831 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:16:31.593  4843  4869 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:31.595  4831  4831 I Babel_Crash: startup - clean
,07-05 14:16:31.600  4831  4874 I Babel   : deleted: false for 0
,07-05 14:16:31.604  4831  4831 I Babel_telephony: TeleModule.launchCompleted
,07-05 14:16:31.608   789   972 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:16:31.610  4831  4831 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
07-05 14:16:31.611  4831  4831 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:16:31.611  4831  4831 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:16:31.611  4831  4831 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-05 14:16:31.613   789  1343 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:16:31.632  4843  4843 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:16:31.639  4843  4843 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:31.640  4843  4843 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:31.641  4843  4843 D ChimeraModuleApk: Loading chimera manifest from ContainerApk(com.google.android.gms)
07-05 14:16:31.642   789   974 I ActivityManager: Start proc 4878:com.android.musicfx/u0a15 for broadcast com.android.musicfx/.Compatibility$Receiver
,07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.accountsettings,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.admob,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.ads,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.analytics,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.app,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.appinvite,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.appstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.base,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.phone,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.accountactivationstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.credentials,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.proxy,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.signin,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.authzen,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.easyunlock,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.proximity,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.654  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup_lmp,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.base,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.beacon,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.car,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.cast,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.checkinbase,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.chromesync,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.clearcut,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.common.download,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.common_account,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.config,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.contextmanager,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.drive,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.droidguard,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.family,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.feedback,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebase_auth,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.fitness,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.flags,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.freighter,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.655  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.gass,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.gcm,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.googlehelp,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.herrevad,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.icing,v12) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.location,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.location.nonwearable,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.locationsharing,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.lockbox,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.maps,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.measurement,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.nearby,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.notifications,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.ocr,v7) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.panorama,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.people,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.phenotype,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.phone,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.photos,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.places,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.plus,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.656  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.pseudonymous,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.reminders,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.security,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.smart_profile,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.smartdevice,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.statementservice,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.stats,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.subscribedfeeds,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.tapandpay,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.thunderbird,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.tron,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.trustagent,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.udc,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.usagereporting,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.vision,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.wallet,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:31.657  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.wearable,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:31.657  4843  4843 D ChimeraModuleApk: Loading chimera manifest from InstalledApk(com.google.android.play.games)
07-05 14:16:31.662  4843  4843 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v37230000) from InstalledApk(com.google.android.play.games)
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: Beginning module config resolution
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(built-in,v0) has no external dependencies, accepted
,07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.accountsettings,v1) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.admob,v4) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.ads,v4) accepted
,07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.analytics,v1) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.app,v1) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.appinvite,v2) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.appstate,v1) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.base,v3) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.phone,v3) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.accountactivationstate,v1) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.credentials,v1) accepted
07-05 14:16:31.662  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.proxy,v2) accepted
,07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.signin,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.authzen,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.easyunlock,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.auth.proximity,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.backup,v1) accepted
,07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.backup_lmp,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.base,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.beacon,v4) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.car,v4) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.cast,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.checkinbase,v3) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.chromesync,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.clearcut,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.common.download,v1) accepted
,07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.common_account,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.config,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.contextmanager,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.drive,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.droidguard,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.family,v4) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.feedback,v5) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.firebase_auth,v3) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.fitness,v2) accepted
,07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.flags,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.freighter,v1) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.games,v37230000) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.gass,v4) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.gcm,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.googlehelp,v5) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.herrevad,v4) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.icing,v12) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.kids,v3) accepted
,07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.location,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.location.nonwearable,v2) accepted
07-05 14:16:31.663  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.locationsharing,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.lockbox,v4) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.maps,v6) accepted
,07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.measurement,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.nearby,v3) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.notifications,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.ocr,v7) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.panorama,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.people,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.phenotype,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.phone,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.photos,v1) accepted
,07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.places,v5) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.plus,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.pseudonymous,v2) accepted
,07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.reminders,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.security,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.signin,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.smart_profile,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.smartdevice,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.statementservice,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.stats,v3) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.subscribedfeeds,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.tapandpay,v4) accepted
,07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.thunderbird,v2) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.tron,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.trustagent,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.udc,v5) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.usagereporting,v1) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.vision,v6) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.wallet,v3) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: module(com.google.android.gms.wearable,v4) accepted
07-05 14:16:31.664  4843  4843 D ChimeraCfgRslvr: Module config resolution complete
07-05 14:16:31.672  4843  4843 D ChimeraCfgMgr: Module config changed, forcing restart due to module com.google.android.gms.googlecertificates
07-05 14:16:31.672  4843  4843 I Process : Sending signal. PID: 4843 SIG: 9
,07-05 14:16:31.689  4878  4878 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-05 14:16:31.698  4831  4831 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:16:31.718  4831  4831 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 14:16:31.723  4831  4831 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:16:31.725  4831  4831 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 14:16:31.727  4831  4831 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:16:31.732  4831  4831 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:16:31.739   789   975 I ActivityManager: Process com.google.android.gms.persistent (pid 4843) has died
,07-05 14:16:31.739   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 1000ms
,07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 11000ms
07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 21000ms
07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 31000ms
07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 41000ms
07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 51000ms
,07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService in 61000ms
,07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 71000ms
07-05 14:16:31.740   789   975 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 80999ms
,07-05 14:16:31.747  4364  4364 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 60
,07-05 14:16:31.776  4623  4623 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 14:16:31.790   789  3843 I ActivityManager: Start proc 4894:com.google.android.apps.docs/u0a40 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,07-05 14:16:31.794  4831  4891 W Babel   : Gms package replaced. Will trigger a restart of babel
,07-05 14:16:31.804  4831  4831 I vclib   : onServiceConnected
,07-05 14:16:31.842  4831  4831 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:31.846   789   974 I ActivityManager: Start proc 4908:com.google.android.gms.persistent/u0a8 for service com.google.android.gms/.auth.GetToken
,07-05 14:16:31.858  4831  4831 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-05 14:16:31.858  4831  4831 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:31.865  4831  4831 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:31.888  4831  4831 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:31.898  4908  4908 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:16:31.898  4908  4908 I MultiDex: install
07-05 14:16:31.898  4908  4908 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:31.922  4908  4908 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:31.932  4908  4908 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:16:31.932  4908  4908 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:31.935  4908  4908 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:31.958  4908  4908 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:31.968  4908  4908 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:31.986  4908  4908 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:31.992  4908  4908 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
,07-05 14:16:31.992  4908  4908 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:31.993  4908  4908 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:31.993  4908  4908 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:32.003  4908  4919 W ChimeraModuleLdr: Config is out of date: ContainerApk(com.google.android.gms) has incorrect timestamp/version
07-05 14:16:32.003  4908  4919 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:32.006  4908  4908 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 14:16:32.007  4908  4908 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:16:32.017  4908  4908 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
,07-05 14:16:32.018  4908  4908 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:16:32.021  4908  4908 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:16:32.026  4908  4908 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:16:32.028  4908  4923 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:32.083  4908  4908 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:16:32.088  4908  4908 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:32.089  4908  4908 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:32.091  4908  4908 D ChimeraModuleApk: Loading chimera manifest from ContainerApk(com.google.android.gms)
,07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.accountsettings,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.admob,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.ads,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.analytics,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.app,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.appinvite,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.appstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.base,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.phone,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.accountactivationstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.credentials,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.proxy,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.authzen,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.easyunlock,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.proximity,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.106  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup_lmp,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.base,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.beacon,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.car,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.cast,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.checkinbase,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.chromesync,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.clearcut,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.common.download,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.common_account,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.config,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.contextmanager,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.drive,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.droidguard,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.family,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.feedback,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebase_auth,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.fitness,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.flags,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.freighter,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.gass,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.gcm,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.googlehelp,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.107  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.herrevad,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.icing,v12) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.location,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.location.nonwearable,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.locationsharing,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.lockbox,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.maps,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.measurement,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.nearby,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.notifications,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.ocr,v7) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.panorama,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.people,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.phenotype,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.phone,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.photos,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.places,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.plus,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.pseudonymous,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.reminders,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.security,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.108  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.smart_profile,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.smartdevice,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.statementservice,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.stats,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.subscribedfeeds,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.tapandpay,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.thunderbird,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.tron,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.trustagent,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.udc,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.usagereporting,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.vision,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.wallet,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.wearable,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.109  4908  4908 D ChimeraModuleApk: Loading chimera manifest from InstalledApk(com.google.android.play.games)
07-05 14:16:32.112  4908  4908 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v37230000) from InstalledApk(com.google.android.play.games)
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: Beginning module config resolution
,07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(built-in,v0) has no external dependencies, accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.accountsettings,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.admob,v4) accepted
,07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.ads,v4) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.analytics,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.app,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.appinvite,v2) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.appstate,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.base,v3) accepted
,07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.phone,v3) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.accountactivationstate,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.credentials,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.proxy,v2) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.signin,v2) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.authzen,v2) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.easyunlock,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.auth.proximity,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.backup,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.backup_lmp,v1) accepted
07-05 14:16:32.113  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.base,v2) accepted
,07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.beacon,v4) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.car,v4) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.cast,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.checkinbase,v3) accepted
,07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.chromesync,v1) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.clearcut,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.common.download,v1) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.common_account,v1) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.config,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.contextmanager,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.drive,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.droidguard,v2) accepted
,07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.family,v4) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.feedback,v5) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.firebase_auth,v3) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.fitness,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.flags,v1) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.freighter,v1) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.games,v37230000) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.gass,v4) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.gcm,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.googlehelp,v5) accepted
,07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.herrevad,v4) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.icing,v12) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.kids,v3) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.location,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.location.nonwearable,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.locationsharing,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.lockbox,v4) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.maps,v6) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.measurement,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.nearby,v3) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.notifications,v2) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.ocr,v7) accepted
07-05 14:16:32.114  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.panorama,v1) accepted
,07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.people,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.phenotype,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.phone,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.photos,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.places,v5) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.plus,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.pseudonymous,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.reminders,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.security,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.signin,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.smart_profile,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.smartdevice,v2) accepted
,07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.statementservice,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.stats,v3) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.subscribedfeeds,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.tapandpay,v4) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.thunderbird,v2) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.tron,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.trustagent,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.udc,v5) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.usagereporting,v1) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.vision,v6) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.wallet,v3) accepted
,07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: module(com.google.android.gms.wearable,v4) accepted
07-05 14:16:32.115  4908  4908 D ChimeraCfgRslvr: Module config resolution complete
07-05 14:16:32.123  4908  4908 D ChimeraCfgMgr: Module config changed, forcing restart due to module com.google.android.gms.googlecertificates
07-05 14:16:32.123  4908  4908 I Process : Sending signal. PID: 4908 SIG: 9
,07-05 14:16:32.149   789  4805 I ActivityManager: Process com.google.android.gms.persistent (pid 4908) has died
,07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 1000ms
07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 11000ms
,07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 21000ms
07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 31000ms
07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 40999ms
07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 50999ms
,07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService in 60999ms
07-05 14:16:32.150   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 70999ms
07-05 14:16:32.151   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 80999ms
07-05 14:16:32.151   789  4805 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 90999ms
07-05 14:16:32.151   789  4805 I ActivityManager: Killing 4894:com.google.android.apps.docs/u0a40 (adj 0): depends on provider com.google.android.gms/.auth.account.be.legacy.AccountContentProvider in dying proc com.google.android.gms.persistent
,07-05 14:16:32.303   789   805 I ActivityManager: Start proc 4932:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,07-05 14:16:32.367  4932  4932 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,07-05 14:16:32.372  4932  4932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-05 14:16:32.418   789   972 I ActivityManager: Start proc 4947:com.google.android.gms.persistent/u0a8 for broadcast com.google.android.gms/.chimera.GmsIntentOperationService$PersistentExternalReceiver
,07-05 14:16:32.487  4947  4947 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:16:32.487  4947  4947 I MultiDex: install
07-05 14:16:32.487  4947  4947 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:32.511  4947  4947 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:32.521  4947  4947 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:16:32.521  4947  4947 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:32.524  4947  4947 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:32.549  4947  4947 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:32.570   789  4806 I ActivityManager: Start proc 4968:com.google.android.gms/u0a8 for service com.google.android.gms/.chimera.GmsIntentOperationService
07-05 14:16:32.571  4947  4947 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:32.590  4947  4947 W ChimeraModuleLdr: Config is out of date: ContainerApk(com.google.android.gms) has incorrect timestamp/version
,07-05 14:16:32.595  4947  4947 D GmsModuleFndr: Beginning GMS chimera module scan
07-05 14:16:32.596  4947  4947 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 14:16:32.596  4947  4947 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:32.597  4947  4947 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:32.597  4947  4947 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:32.606  4947  4947 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 14:16:32.606  4947  4947 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:16:32.612  4947  4947 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
,07-05 14:16:32.613  4947  4947 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-05 14:16:32.614  4947  4947 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:16:32.617  4947  4947 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:16:32.639  4968  4968 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:16:32.639  4968  4968 I MultiDex: install
07-05 14:16:32.639  4968  4968 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:32.656  4947  4967 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:32.674  4968  4968 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:32.676  4947  4947 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:16:32.681  4947  4947 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:32.682  4947  4947 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:32.683  4947  4947 D ChimeraModuleApk: Loading chimera manifest from ContainerApk(com.google.android.gms)
,07-05 14:16:32.686  4968  4968 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:16:32.686  4968  4968 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:32.689  4968  4968 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.accountsettings,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.admob,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.ads,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.analytics,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.app,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.appinvite,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.695  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.appstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.base,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.phone,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.accountactivationstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.credentials,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.proxy,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.authzen,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.easyunlock,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.proximity,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup_lmp,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.base,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.beacon,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.car,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.cast,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.checkinbase,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.chromesync,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.clearcut,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.common.download,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.common_account,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.config,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.696  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.contextmanager,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.drive,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.droidguard,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.family,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.feedback,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebase_auth,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.fitness,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.flags,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.freighter,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.gass,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.gcm,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.googlehelp,v5) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.herrevad,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.icing,v12) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.location,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.location.nonwearable,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.locationsharing,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.lockbox,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.maps,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.measurement,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.697  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.nearby,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.notifications,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.ocr,v7) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.panorama,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.people,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.phenotype,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.phone,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.photos,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.places,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.plus,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.pseudonymous,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.reminders,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.security,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.smart_profile,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.smartdevice,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.statementservice,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.stats,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.subscribedfeeds,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.tapandpay,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.thunderbird,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.698  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.tron,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.699  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.trustagent,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.699  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.udc,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.699  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.usagereporting,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.699  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.vision,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:32.699  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.wallet,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.699  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.wearable,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.699  4947  4947 D ChimeraModuleApk: Loading chimera manifest from InstalledApk(com.google.android.play.games)
,07-05 14:16:32.703  4947  4947 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v37230000) from InstalledApk(com.google.android.play.games)
07-05 14:16:32.703  4947  4947 D ChimeraCfgRslvr: Beginning module config resolution
07-05 14:16:32.703  4947  4947 D ChimeraCfgRslvr: module(built-in,v0) has no external dependencies, accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.accountsettings,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.admob,v4) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.ads,v4) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.analytics,v1) accepted
,07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.app,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.appinvite,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.appstate,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.base,v3) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.phone,v3) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.accountactivationstate,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.credentials,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.proxy,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.signin,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.authzen,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.easyunlock,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.auth.proximity,v1) accepted
,07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.backup,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.backup_lmp,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.base,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.beacon,v4) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.car,v4) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.cast,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.checkinbase,v3) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.chromesync,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.clearcut,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.common.download,v1) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.common_account,v1) accepted
,07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.config,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.contextmanager,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.drive,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.droidguard,v2) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.family,v4) accepted
07-05 14:16:32.704  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.feedback,v5) accepted
,07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.firebase_auth,v3) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.fitness,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.flags,v1) accepted
,07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.freighter,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.games,v37230000) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.gass,v4) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.gcm,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.googlehelp,v5) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.herrevad,v4) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.icing,v12) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.kids,v3) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.location,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.location.nonwearable,v2) accepted
,07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.locationsharing,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.lockbox,v4) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.maps,v6) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.measurement,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.nearby,v3) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.notifications,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.ocr,v7) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.panorama,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.people,v2) accepted
,07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.phenotype,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.phone,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.photos,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.places,v5) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.plus,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.pseudonymous,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.reminders,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.security,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.signin,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.smart_profile,v2) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.smartdevice,v2) accepted
,07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.statementservice,v1) accepted
07-05 14:16:32.705  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.stats,v3) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.subscribedfeeds,v1) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.tapandpay,v4) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.thunderbird,v2) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.tron,v1) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.trustagent,v1) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.udc,v5) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.usagereporting,v1) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.vision,v6) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.wallet,v3) accepted
,07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: module(com.google.android.gms.wearable,v4) accepted
07-05 14:16:32.706  4947  4947 D ChimeraCfgRslvr: Module config resolution complete
,07-05 14:16:32.712  4947  4947 D ChimeraCfgMgr: Module config changed, forcing restart due to module com.google.android.gms.googlecertificates
,07-05 14:16:32.713  4947  4947 I Process : Sending signal. PID: 4947 SIG: 9
,07-05 14:16:32.718  4968  4968 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:32.729  4968  4968 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:32.769   789  1343 I ActivityManager: Process com.google.android.gms.persistent (pid 4947) has died
,07-05 14:16:32.769   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 1000ms
07-05 14:16:32.769   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 11000ms
07-05 14:16:32.769   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 21000ms
07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 31000ms
07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 41000ms
,07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 51000ms
,07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService in 61000ms
07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 71000ms
07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 81000ms
07-05 14:16:32.770   789  1343 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 91000ms
,07-05 14:16:32.773  4968  4968 W ChimeraModuleLdr: Config is out of date: ContainerApk(com.google.android.gms) has incorrect timestamp/version
,07-05 14:16:32.783   789   805 I ActivityManager: Start proc 4984:com.google.android.gms.persistent/u0a8 for broadcast com.google.android.gms/.gcm.nts.SchedulerReceiver
,07-05 14:16:32.787  4968  4968 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:32.789  4968  4968 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 14:16:32.789  4968  4968 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:32.789  4968  4968 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:32.789  4968  4968 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:32.794  4968  4983 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:32.800  4968  4968 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
07-05 14:16:32.800  4968  4968 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:16:32.806  4968  4968 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
,07-05 14:16:32.807  4968  4968 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:16:32.809  4968  4968 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:16:32.812  4968  4968 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:16:32.831  4984  4984 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:16:32.831  4984  4984 I MultiDex: install
07-05 14:16:32.831  4984  4984 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:32.854  4984  4984 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
07-05 14:16:32.865  4984  4984 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-05 14:16:32.865  4984  4984 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
07-05 14:16:32.868  4984  4984 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:32.880  4968  4968 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:16:32.887  4968  4968 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:32.887  4968  4968 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:32.889  4968  4968 D ChimeraModuleApk: Loading chimera manifest from ContainerApk(com.google.android.gms)
,07-05 14:16:32.902  4968  4968 D ChimeraCfgMgr: Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.902  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.accountsettings,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.admob,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.ads,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.analytics,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.app,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.appinvite,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.appstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.base,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.phone,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.accountactivationstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.credentials,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.proxy,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.signin,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.authzen,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.easyunlock,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.proximity,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.903  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup_lmp,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.base,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.beacon,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.car,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.cast,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.checkinbase,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.chromesync,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.clearcut,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.common.download,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.904  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.common_account,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.config,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.contextmanager,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.drive,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.droidguard,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.family,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.feedback,v5) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebase_auth,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.fitness,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.flags,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.freighter,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.gass,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.gcm,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.googlehelp,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.herrevad,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.icing,v12) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.location,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.location.nonwearable,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.locationsharing,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.905  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.lockbox,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.905  4984  4984 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.maps,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.measurement,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.nearby,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.notifications,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.ocr,v7) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.panorama,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.people,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.phenotype,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.906  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.phone,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.photos,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.places,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.plus,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.pseudonymous,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.reminders,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.security,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.smart_profile,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.smartdevice,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.statementservice,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.stats,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.subscribedfeeds,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.tapandpay,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.thunderbird,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:32.907  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.tron,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.908  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.trustagent,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:32.908  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.udc,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:32.908  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.usagereporting,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:32.908  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.vision,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:32.908  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.wallet,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:32.908  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.wearable,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:32.908  4968  4968 D ChimeraModuleApk: Loading chimera manifest from InstalledApk(com.google.android.play.games)
07-05 14:16:32.912  4968  4968 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v37230000) from InstalledApk(com.google.android.play.games)
,07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: Beginning module config resolution
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(built-in,v0) has no external dependencies, accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.accountsettings,v1) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.admob,v4) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.ads,v4) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.analytics,v1) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.app,v1) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.appinvite,v2) accepted
,07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.appstate,v1) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.base,v3) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.phone,v3) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.accountactivationstate,v1) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.credentials,v1) accepted
07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.proxy,v2) accepted
,07-05 14:16:32.912  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.signin,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.authzen,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.easyunlock,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.auth.proximity,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.backup,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.backup_lmp,v1) accepted
,07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.base,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.beacon,v4) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.car,v4) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.cast,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.checkinbase,v3) accepted
,07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.chromesync,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.clearcut,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.common.download,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.common_account,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.config,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.contextmanager,v2) accepted
,07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.drive,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.droidguard,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.family,v4) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.feedback,v5) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.firebase_auth,v3) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.fitness,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.flags,v1) accepted
,07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.freighter,v1) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.games,v37230000) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.gass,v4) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.gcm,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.googlehelp,v5) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.herrevad,v4) accepted
,07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.icing,v12) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.kids,v3) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.location,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.location.nonwearable,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.locationsharing,v2) accepted
07-05 14:16:32.913  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.lockbox,v4) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.maps,v6) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.measurement,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.nearby,v3) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.notifications,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.ocr,v7) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.panorama,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.people,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.phenotype,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.phone,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.photos,v1) accepted
,07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.places,v5) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.plus,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.pseudonymous,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.reminders,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.security,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.signin,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.smart_profile,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.smartdevice,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.statementservice,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.stats,v3) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.subscribedfeeds,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.tapandpay,v4) accepted
,07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.thunderbird,v2) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.tron,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.trustagent,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.udc,v5) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.usagereporting,v1) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.vision,v6) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.wallet,v3) accepted
07-05 14:16:32.914  4968  4968 D ChimeraCfgRslvr: module(com.google.android.gms.wearable,v4) accepted
07-05 14:16:32.915  4968  4968 D ChimeraCfgRslvr: Module config resolution complete
07-05 14:16:32.915  4984  4984 D ChimeraCfgMgr: Reading stored module config
07-05 14:16:32.931  4984  4984 W ChimeraModuleLdr: Config is out of date: ContainerApk(com.google.android.gms) has incorrect timestamp/version
07-05 14:16:32.940  4984  4984 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:32.942  4984  4984 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 14:16:32.942  4984  4984 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:32.942  4984  4984 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:32.942  4984  4984 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:32.960  4984  4984 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 14:16:32.960  4984  4984 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
07-05 14:16:32.965  4984  4984 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000000/n/armeabi
07-05 14:16:32.966  4984  4984 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-05 14:16:32.967  4984  4984 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:16:32.970  4984  4984 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:16:32.980  4984  4998 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:33.022  4968  4968 D ChimeraCfgMgr: Module config changed, forcing restart due to module com.google.android.gms.googlecertificates
,07-05 14:16:33.022  4968  4968 I Process : Sending signal. PID: 4968 SIG: 9
,07-05 14:16:33.026  4984  4984 D GoogleCertificatesImpl: Fetched 154 Google release certificates
,07-05 14:16:33.032  4984  4984 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:33.032  4984  4984 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:33.034  4984  4984 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:33.042  4984  4984 D ChimeraCfgMgr: Module config changed, forcing restart due to module com.google.android.gms.googlecertificates
07-05 14:16:33.042  4984  4984 I Process : Sending signal. PID: 4984 SIG: 9
,07-05 14:16:33.059   789  2167 I ActivityManager: Process com.google.android.gms (pid 4968) has died
,07-05 14:16:33.060   789  2167 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.chimera.GmsIntentOperationService in 1000ms
,07-05 14:16:33.121   789   800 I ActivityManager: Process com.google.android.gms.persistent (pid 4984) has died
,07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 10939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 20939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 30939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 40939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 50939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 60939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.HardwareArProviderService in 70939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 80939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 90939ms
07-05 14:16:33.121   789   800 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 100939ms
,07-05 14:16:33.133   789   805 I ActivityManager: Start proc 5006:com.google.android.gms/u0a8 for broadcast com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,07-05 14:16:33.196  5006  5006 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:16:33.196  5006  5006 I MultiDex: install
,07-05 14:16:33.196  5006  5006 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:33.230  5006  5006 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:33.239  5006  5006 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:16:33.239  5006  5006 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:33.243  5006  5006 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:33.267  5006  5006 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:33.279  5006  5006 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:33.388  5006  5020 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:33.402  5006  5028 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.gms
,07-05 14:16:33.402  5006  5028 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.gms
,07-05 14:16:33.421   789   971 I ActivityManager: Start proc 5035:com.google.android.apps.docs/u0a40 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,07-05 14:16:33.435   789  4805 I ActivityManager: Start proc 5047:com.google.android.gms.persistent/u0a8 for service com.google.android.gms/.fitness.disconnect.FitCleanupService
,07-05 14:16:33.490  4623  5033 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 14:16:33.497  5006  5059 E Drive.UninstallOperation: Package still installed com.google.android.gms
,07-05 14:16:33.499  5047  5047 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:16:33.499  5047  5047 I MultiDex: install
07-05 14:16:33.499  5047  5047 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:16:33.530  5047  5047 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:33.533  4623  5033 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
,07-05 14:16:33.540  5047  5047 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-05 14:16:33.540  5047  5047 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:33.544  5047  5047 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:33.568  5047  5047 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:33.580  5047  5047 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:33.596  5006  5028 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.gms
,07-05 14:16:33.640  5047  5077 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:33.668  5047  5047 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 14:16:33.705  5047  5047 D GeofencerStateMachine: Creating GeofencerStateMachine
,07-05 14:16:33.717   789   895 D WifiService: New client listening to asynchronous messages
,07-05 14:16:33.744  5006  5028 D gH_CompatibleDatabase: Open irg@4d81bb6, release reference: 1
,07-05 14:16:33.752  5006  5028 D gH_CompatibleDatabase: Acquire reference of irg@4d81bb6: 2
,07-05 14:16:33.753  5006  5028 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.android.gms.
,07-05 14:16:33.753  5006  5028 D gH_CompatibleDatabase: Release reference of irg@4d81bb6: 1
07-05 14:16:33.753  5006  5028 D gH_CompatibleDatabase: Open irg@d3970b7, release reference: 1
,07-05 14:16:33.766  5006  5028 D gH_CompatibleDatabase: Acquire reference of irg@d3970b7: 2
,07-05 14:16:33.768  5006  5028 D gH_CompatibleDatabase: Release reference of irg@d3970b7: 1
,07-05 14:16:33.769  5006  5028 D gH_CompatibleDatabase: Open irg@656f024, release reference: 1
,07-05 14:16:33.789  5006  5028 D gH_CompatibleDatabase: Acquire reference of irg@656f024: 2
,07-05 14:16:33.791  5006  5028 D gH_CompatibleDatabase: Release reference of irg@656f024: 1
,07-05 14:16:33.792  5006  5028 D gH_CompatibleDatabase: Close irg@4d81bb6, release reference: 0
07-05 14:16:33.793  5006  5028 D gH_CompatibleDatabase: Close irg@d3970b7, release reference: 0
,07-05 14:16:33.793  5006  5028 D gH_CompatibleDatabase: Close irg@656f024, release reference: 0
,07-05 14:16:33.798  5006  5096 I Icing   : Storage manager: low false usage 1.62MB avail 11.23GB capacity 12.55GB
,07-05 14:16:33.825  5047  5094 W GeofencerStateMachine: Received SM_HARDWARE_GEOFENCE_CHANGED_CMD in NotInitializedState
,07-05 14:16:33.846   789   789 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-05 14:16:33.849   789   789 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b124f04
,07-05 14:16:33.858  5047  5102 W DynamiteLoaderImpl: Failed to load module version: module com.google.android.gms.googlecertificates not found
,07-05 14:16:33.858  5047  5102 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:0
07-05 14:16:33.858  5047  5102 I DynamiteModule: Selected local version of com.google.android.gms.googlecertificates
07-05 14:16:33.858  5047  5102 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:16:33.891  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:33.892  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:33.901  5047  5047 V GeofencerHelper: Initializing geofence's system cache.
,07-05 14:16:33.909  5047  5102 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-05 14:16:33.910  5047  5094 D GeofenceStateCache: Recovered 0 geofences.
,07-05 14:16:33.910  5047  5057 D DeviceConnectionService: client connected with version: 8486000
,07-05 14:16:33.920  5047  5094 I GeofencerStateMachine: Network location disabled.
,07-05 14:16:33.940   789   809 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d1eca5:true
,07-05 14:16:33.947  5035  5076 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:16:33.947  5035  5076 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:16:33.947  5035  5076 I GAv4    :   adb logcat -s GAv4
,07-05 14:16:33.993  5035  5076 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:16:34.005  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:34.011  5035  5076 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:16:34.031  5035  5076 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.35
,07-05 14:16:34.036  5035  5128 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:16:34.079  5006  5034 D AuthInitIntentOperation: Enabling 5 components: com.google.android.gms.auth.uiflows.common.DmDiscoverAccountActivity; com.google.android.gms.auth.account.data.WorkAccountStoreReceiver; com.google.android.gms.auth.account.service.WorkAccountService; com.google.android.gms.auth.account.be.UpdatePostAccountSetupStatusIntentService; com.google.android.gms.auth.account.be.recovery.AccountRecoveryUpdaterService
,07-05 14:16:34.087  5006  5034 D AuthInitIntentOperation: Disabling 0 components
,07-05 14:16:34.087  5006  5034 D AuthInitIntentOperation: Initializing Auth, action is com.google.android.chimera.IntentOperation.NEW_MODULE ,InitRuntimeState=12
,07-05 14:16:34.097  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:34.102  5047  5114 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:16:34.114  5047  5114 I System.out: gmsNlpServiceThread This NLP should run continuously. intent is Intent { act=com.google.android.location.internal.GMS_NLP pkg=com.google.android.gms }
,07-05 14:16:34.116  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:34.120  5047  5136 W WakefulBroadcastReceiver: No active wake lock id #1
,07-05 14:16:34.139  5006  5034 W InstanceID/Rpc: Found 10008
,07-05 14:16:34.141  5006  5028 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:34.141  5006  5028 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
,07-05 14:16:34.142  5006  5028 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:34.142  5006  5028 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:34.144  5006  5028 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:34.146  5006  5140 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:34.153  5006  5028 W DynamiteLoaderImpl: Failed to load module version: module com.google.android.gms.googlecertificates not found
,07-05 14:16:34.153  5006  5028 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:0
07-05 14:16:34.153  5006  5028 I DynamiteModule: Selected local version of com.google.android.gms.googlecertificates
07-05 14:16:34.153  5006  5028 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:16:34.173  5006  5140 D FileApkUtils: Starting staging/optimizing
,07-05 14:16:34.191  5006  5034 D AccountStateSyncAdapterInitIntentOperation: Initializing AccountStateSyncAdapter, action is com.google.android.chimera.IntentOperation.NEW_MODULE ,InitRuntimeState=12
,07-05 14:16:34.193  5006  5034 D AuthZenInitIntentOperation: Initializing Authzen, action is com.google.android.chimera.IntentOperation.NEW_MODULE ,InitRuntimeState=12
,07-05 14:16:34.195  5006  5034 D EasyUnlockInitOp: Initializing EasyUnlock, InitRuntimeState=12
,07-05 14:16:34.202  5047  5151 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-05 14:16:34.206  4364  4364 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.google.android.gms
,07-05 14:16:34.210  4364  4364 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies.a(1161): Enforced system alert window policy
07-05 14:16:34.210   789   800 I BroadcastQueue: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-05 14:16:34.212   789  1319 I BroadcastQueue: Resuming delayed broadcast
,07-05 14:16:34.219  4364  4364 I Finsky  : [1] com.google.android.finsky.c.p.run(172): Set autoupdate of com.google.android.gms to 1 (install/update)
,07-05 14:16:34.227   789   974 I BroadcastQueue: Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,07-05 14:16:34.230  5006  5028 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-05 14:16:34.234   789   971 I BroadcastQueue: Resuming delayed broadcast
,07-05 14:16:34.241  5006  5028 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:34.242  5006  5028 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:34.244  5006  5028 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 14:16:34.271  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:34.284  5047  5125 I PhenotypeDbHelper: Adding configHash to ExperimentTokens table
,07-05 14:16:34.285  5047  5125 I PhenotypeDbHelper: Adding LastFetch table
,07-05 14:16:34.289   789   975 I ActivityManager: Start proc 5158:com.google.android.apps.cloudprint/u0a35 for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver
,07-05 14:16:34.293  5006  5034 I Fitness : Module updated. Enabling [com.google.android.gms.fitness.service.wearable.WearableSyncMessageService, com.google.android.gms.fitness.service.wearable.WearableSyncAccountService, com.google.android.gms.fitness.service.wearable.WearableSyncConnectionService, com.google.android.gms.fitness.service.wearable.WearableSyncConfigService]
,07-05 14:16:34.298  5047  5125 I PhenotypeDbHelper: Relaxing LogSources Table restrictions
,07-05 14:16:34.311  5006  5028 I PeopleDatabaseHelper: Upgrading from version 1405 to 1501
,07-05 14:16:34.362  5035  5143 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:16:34.364  5158  5158 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-05 14:16:34.374  5006  5096 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-05 14:16:34.378  5035  5143 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:16:34.379  5035  5143 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:16:34.382  5035  5143 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:16:34.409  5035  5143 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:34.425   789  1333 I ActivityManager: Start proc 5183:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver
,07-05 14:16:34.449  5047  5125 I Scheduler: Use legacy PeriodicScheduler
,07-05 14:16:34.456  5183  5183 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-05 14:16:34.463  5047  5125 W InstanceID/Rpc: Found 10008
,07-05 14:16:34.466  5006  5140 D FileApkUtils: Computing digest: DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk
,07-05 14:16:34.466  5006  5034 I DynamiteModule: Considering local module com.google.android.gms.flags:0 and remote module com.google.android.gms.flags:1
07-05 14:16:34.466  5006  5034 I DynamiteModule: Selected remote version of com.google.android.gms.flags, version >= 1
07-05 14:16:34.468  5047  5125 I Scheduler: Cleaning up unwanted schedulers, if there are any.
07-05 14:16:34.471  5006  5195 V AuthZen : Handling intent: com.google.android.chimera.IntentOperation.NEW_MODULE
,07-05 14:16:34.478  5006  5028 I PerfProfileCollectorService: Turn off PerfProfile Collection
,07-05 14:16:34.485  5006  5140 D FileApkUtils: Spent 19ms computing apk SHA-256.
,07-05 14:16:34.487  5006  5140 D FileApkUtils: Staging: DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk [7f6f060a805f21d07533a5b4157f179f737b6ac39ade2616b81fdf06f34f011a]
,07-05 14:16:34.503  5006  5195 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:16:34.508  5006  5195 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-05 14:16:34.513  5006  5195 V BaseAppContext: GmsRequestQueue started.
,07-05 14:16:34.514  5006  5028 D WearInitializer: Running WearInitializer
,07-05 14:16:34.514  5006  5028 D WearInitializer: enabled .WearableService
,07-05 14:16:34.518  5006  5195 D AuthZenEventHandler: Handling event: com.google.android.chimera.IntentOperation.NEW_MODULE
,07-05 14:16:34.526  5006  5195 I AuthZen : Fetching signing key...
,07-05 14:16:34.532  5006  5209 I CheckinService: Disabling old GoogleServicesFramework version
,07-05 14:16:34.534  5183  5183 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-05 14:16:34.534  5183  5183 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:16:34.534  5183  5183 I GAv4    :   adb logcat -s GAv4
,07-05 14:16:34.549  5006  5140 D FileApkUtils: Spent 62ms copying apk.
,07-05 14:16:34.552  5183  5183 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:16:34.553  5006  5140 D FileApkUtils: Copied dynamite bytes to /data/user/0/com.google.android.gms/app_chimera/m/s/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk
,07-05 14:16:34.574  5006  5195 I AuthZen : Signing key fetched successfully!
,07-05 14:16:34.582  5183  5183 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:16:34.584  5006  5034 D PeriodicTasksManager: Will schedule periodic tasks:com.google.android.chimera.IntentOperation.NEW_MODULE.
,07-05 14:16:34.598  5006  5140 D FileApkUtils: Spent 28ms extracting native libraries.
,07-05 14:16:34.599  5006  5140 D FileApkUtils: Computing digest: DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk
,07-05 14:16:34.601  5006  5218 D FileApkUtils: Optimizing: DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk [7f6f060a805f21d07533a5b4157f179f737b6ac39ade2616b81fdf06f34f011a]
07-05 14:16:34.601  5006  5218 D DexOptUtils: Module /data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk appears to be unoptimized.
07-05 14:16:34.601  5006  5218 D DexOptUtils: Post L_MR1 platform, using oat/<isa> directory.
07-05 14:16:34.602  5006  5212 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
07-05 14:16:34.602  5006  5218 D DexOptUtils: Creating odex directory: /data/user/0/com.google.android.gms/app_chimera/m/00000003/oat/arm
07-05 14:16:34.603  5006  5218 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
07-05 14:16:34.603  5006  5218 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
07-05 14:16:34.612  5006  5210 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:16:34.620  5183  5216 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:16:34.627  5006  5034 D PeriodicTasksManager: Scheduling periodical signal task every 86400 seconds
,07-05 14:16:34.627  5006  5140 D FileApkUtils: Spent 27ms computing apk SHA-256.
07-05 14:16:34.627  5006  5140 D FileApkUtils: Staging: DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk [fe7132835f5c81d2a6f3dc2bab32154f350928809ac8969602ed65e931dc6cc7]
07-05 14:16:34.633  5006  5195 D dur     : Opening database auth.proximity.permit_store...
,07-05 14:16:34.638  5006  5034 D PeriodicTasksManager: AdAttestation signal task scheduled
,07-05 14:16:34.647  5006  5034 D GCM     : COMPAT: Multi user ser=0 current=0
,07-05 14:16:34.670  5006  5140 D FileApkUtils: Spent 42ms copying apk.
,07-05 14:16:34.672  5006  5140 D FileApkUtils: Copied dynamite bytes to /data/user/0/com.google.android.gms/app_chimera/m/s/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk
,07-05 14:16:34.677  5219  5219 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk --oat-file=/data/user/0/com.google.android.gms/app_chimera/m/00000003/oat/arm/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.dex
,07-05 14:16:34.680  5006  5140 D FileApkUtils: Spent 2ms extracting native libraries.
,07-05 14:16:34.680  5006  5140 D FileApkUtils: Computing digest: DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk
,07-05 14:16:34.698  5006  5140 D FileApkUtils: Spent 18ms computing apk SHA-256.
,07-05 14:16:34.698  5006  5140 D FileApkUtils: Staging: DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk [0e2f02c80dd03f9c83187dd34bc9dd253af228cf4353ed24402cf024e8983ba5]
07-05 14:16:34.719  5006  5140 D FileApkUtils: Spent 20ms copying apk.
07-05 14:16:34.720  5006  5140 D FileApkUtils: Copied dynamite bytes to /data/user/0/com.google.android.gms/app_chimera/m/s/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk
,07-05 14:16:34.726  5006  5140 D FileApkUtils: Spent 2ms extracting native libraries.
07-05 14:16:34.727  5006  5140 I art     : Note: end time exceeds epoch: 
,07-05 14:16:34.771  5006  5210 I CheckinChimeraService: Checking schedule, now: 1467720994771 next: 1467763109126
,07-05 14:16:34.772  5006  5210 I CheckinChimeraService: active receiver: disabled
,07-05 14:16:34.781  5006  5034 D LocationInitializer: initializing runtime state of location
,07-05 14:16:34.809  5047  5047 W ctxmgr  : [ContextManagerInitializer]Fixing UDC Model timestamps
,07-05 14:16:34.811  5006  5235 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:16:34.824  5006  5034 I FA-SVC  : App measurement is starting up, version: 9256
,07-05 14:16:34.824  5006  5034 I FA-SVC  : To enable debug logging run: adb shell setprop log.tag.FA VERBOSE
,07-05 14:16:34.864  5006  5235 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:16:34.866  5006  5250 V FA-SVC  : Update service enabled state to: 1
07-05 14:16:34.867  5006  5034 I PhenotypeSyncScheduler: Clear all shared preferences
07-05 14:16:34.868  5006  5250 I FA-SVC  : This instance being marked as an uploader
07-05 14:16:34.869  5006  5034 I PhenotypeSyncScheduler: Cancel all previously scheduled polling
,07-05 14:16:34.879  5006  5034 I PhenotypeSyncScheduler: Scheduling Phenotype for first execution 14083 seconds from now (1467720994879)
,07-05 14:16:34.901  5047  5047 D GCM     : COMPAT: Multi user ser=0 current=0
,07-05 14:16:34.929  5183  5183 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-05 14:16:34.943  5006  5123 V PrereqChecker: Build version: 23
,07-05 14:16:34.943  5006  5123 V PrereqChecker: Model: Nexus 5
07-05 14:16:34.943  5006  5123 V PrereqChecker: CPU_ABI: armeabi-v7a
07-05 14:16:34.943  5006  5123 V PrereqChecker: CPU_ABI2: armeabi
,07-05 14:16:35.040  5006  5256 I MDM     : [488] SitrepChimeraService.onHandleIntent: sending sitrep: [6, 0, [W6LhqClKPyUiNWrEzj7vaAW4918], null]
,07-05 14:16:35.071  5006  5123 V PrereqChecker: Camera #0 is a rear-facing camera.
,07-05 14:16:35.080  5006  5123 D CreditCardPrerequisiteChecker: All prerequisites OK.
,07-05 14:16:35.088  5006  5256 V GoogleAuthProtoRequest: [488] bya.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:16:35.088  5006  5123 I OcrModelUpdtStIntSvc: Updating ocr activity enabled=false (gservicesFlag=false, lowRamDevice=false, prereqCheck=true)
,07-05 14:16:35.144  5006  5034 I PlatformStatsCollectorService: Start Procstats in 64712 seconds.
,07-05 14:16:35.158  5183  5183 I LibraryLoader: Time to load native libraries: 27 ms (timestamps 5081-5108)
07-05 14:16:35.158  5183  5183 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:16:35.160  5006  5034 I PlatformStatsCollectorService: Start Batterystats in 5605 seconds.
,07-05 14:16:35.194  5006  5034 I PlatformStatsCollectorService: Start Settingsstats in 55788 seconds.
,07-05 14:16:35.212  5183  5183 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cf46960}
,07-05 14:16:35.213  5006  5034 I PlatformStatsCollectorService: Start Notificationstats in 75264 seconds.
,07-05 14:16:35.215  5183  5183 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:16:35.216  5183  5183 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 14:16:35.227  5183  5183 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 14:16:35.229  5183  5183 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 14:16:35.260  5006  5034 I PlatformStatsCollectorService: Start Fingerprintstats in 4129 seconds.
,07-05 14:16:35.284  5006  5034 I PlatformStatsCollectorService: Start Graphicsstats in 4144 seconds.
,07-05 14:16:35.298  5183  5183 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 14:16:35.304  5183  5183 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 14:16:35.304  5006  5034 I PlatformStatsCollectorService: Start Dropbox in 49394 seconds.
07-05 14:16:35.304  5183  5183 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:16:35.304  5183  5183 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:16:35.320  5006  5034 I PlatformStatsCollectorService: Start Diskstats in 19649 seconds.
,07-05 14:16:35.327  5047  5272 D GCM     : GcmService start Intent { act=com.google.android.chimera.IntentOperation.NEW_MODULE cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.chimera.IntentOperation.NEW_MODULE
07-05 14:16:35.338  5006  5034 I PlatformStatsCollectorService: Start Netstats in 30144 seconds.
,07-05 14:16:35.357  5006  5034 D UdcSystemIntentHandlers: Received an intent for com.google.android.chimera.IntentOperation.NEW_MODULE
,07-05 14:16:35.734  5219  5248 W dex2oat : No verified method for method calling String.<init>: void org.json.JSONStringer.<init>(int)
,07-05 14:16:35.793  4831  5135 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:35.793  4831  5135 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
07-05 14:16:35.802  5047  5271 I GCM     : GCM config loaded
,07-05 14:16:35.988  5047  5047 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:36.152  5047  5047 D WearableService: callingUid 10008, callindPid: 5047
,07-05 14:16:36.155  4831  5135 I Babel   : BAM#account updated: 2
,07-05 14:16:36.160  5183  5300 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-05 14:16:36.171  4831  5135 I Babel_StickerModule: Account change update: 2
,07-05 14:16:36.171  4831  5135 W Babel_StickerModule: Null account update.
,07-05 14:16:36.182  5047  5151 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-05 14:16:36.199  4831  5297 I Babel   : BAM#account updated: 1
,07-05 14:16:36.200  5183  5183 I NSApplication: Starting up...
,07-05 14:16:36.201  5006  5257 E MDM     : [489] qqf.a: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 14:16:36.221  5006  5034 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:36.221  5006  5034 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
,07-05 14:16:36.223  5006  5034 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
,07-05 14:16:36.223  5006  5034 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:36.224  5006  5034 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
,07-05 14:16:36.225  5006  5006 D AsyncTaskServiceImpl: Submit a task: nwp
,07-05 14:16:36.229  5006  5034 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
,07-05 14:16:36.229  5006  5034 D ChimeraCfgMgr: Beginning module configuration check
07-05 14:16:36.230  5006  5123 D nwp     : Processing package: com.google.android.gms
,07-05 14:16:36.231  5006  5034 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 14:16:36.231  5006  5034 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.gms
,07-05 14:16:36.258  5006  5096 I Icing   : Internal init done: storage state 0
,07-05 14:16:36.260  4831  5297 I Babel_StickerModule: Account change update: 1
,07-05 14:16:36.261  4831  5297 I Babel_StickerModule: Sticker update initiated. last:1466059120265 empty:false
,07-05 14:16:36.277  5047  5232 W ctxmgr  : [WorkManager]Long workInfo: label=RefreshLocationConsentOperation, startTime=2016-07-05 14:16:34.760+0200, stopTime=2016-07-05 14:16:36.275+0200, duration=1515ms
07-05 14:16:36.277  5047  5098 W GCoreFlp: No location to return for getLastLocation()
,07-05 14:16:36.280  5006  5096 I Icing   : Post-init done
07-05 14:16:36.280  5047  5125 E ctxmgr  : [BatteryStatsCollectorHelper]updateStateForNewContextData: could not find contextName=10002
,07-05 14:16:36.289  5006  5096 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-05 14:16:36.291  5006  5322 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:16:36.370  4831  4891 W Babel   : Gms package replaced. Will trigger a restart of babel
,07-05 14:16:36.392  5006  5123 D nwe     : Look up (com.google.android.gms:9256438) returned no result
,07-05 14:16:36.393  5006  5123 D nwp     : Starting Hash for package com.google.android.gms:9.2.56 (438-124593566)
07-05 14:16:36.393  5219  5219 I dex2oat : dex2oat took 1.716s (threads: 4) arena alloc=4MB java alloc=2MB native alloc=11MB free=3MB
,07-05 14:16:36.404  5006  5218 D DexOptUtils: Odex created at:/data/user/0/com.google.android.gms/app_chimera/m/00000003/oat/arm/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.dex
,07-05 14:16:36.404  5006  5218 D DexOptUtils: Set odex to world readable.
07-05 14:16:36.404  5006  5218 D DexOptUtils: Renamed odex to /data/user/0/com.google.android.gms/app_chimera/m/00000003/oat/arm/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.odex
07-05 14:16:36.404  5006  5218 D FileApkUtils: Optimizing: DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk [fe7132835f5c81d2a6f3dc2bab32154f350928809ac8969602ed65e931dc6cc7]
,07-05 14:16:36.405  5006  5218 D DexOptUtils: Module /data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk appears to be unoptimized.
,07-05 14:16:36.405  5006  5218 D DexOptUtils: Post L_MR1 platform, using oat/<isa> directory.
07-05 14:16:36.405  5006  5218 D DexOptUtils: Creating odex directory: /data/user/0/com.google.android.gms/app_chimera/m/00000004/oat/arm
07-05 14:16:36.405  5006  5218 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
07-05 14:16:36.405  5006  5218 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,07-05 14:16:36.452  5324  5324 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk --oat-file=/data/user/0/com.google.android.gms/app_chimera/m/00000004/oat/arm/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.dex
,07-05 14:16:36.650  4831  5297 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:36.650  4831  5297 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:36.677   789   800 I ActivityManager: Start proc 5331:com.google.android.gms.feedback/u0a8 for service com.google.android.gms/.feedback.OfflineReportSendTaskService
,07-05 14:16:36.686  5006  5006 I ChimeraConfigService: Scheduling checkin for periodic execution 70 seconds from now (1467720996686)
,07-05 14:16:36.711  4831  5297 I Babel   : BAM#account updated: 2
,07-05 14:16:36.711  4831  5297 I Babel_StickerModule: Account change update: 2
07-05 14:16:36.711  4831  5297 W Babel_StickerModule: Null account update.
,07-05 14:16:36.740  5331  5331 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:16:36.740  5331  5331 I MultiDex: install
07-05 14:16:36.740  5331  5331 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 14:16:36.759  5047  5047 E NetworkScheduler.SR: Invalid parameter app
07-05 14:16:36.759  5047  5047 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 14:16:36.767  5331  5331 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
07-05 14:16:36.777  5331  5331 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-05 14:16:36.777  5331  5331 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
07-05 14:16:36.782  5331  5331 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-05 14:16:36.790  4831  5297 I Babel   : BAM#account updated: 1
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: Timeout on service connection
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: java.lang.Throwable
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at otq.a(:com.google.android.gms:97)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at ots.a(:com.google.android.gms:146)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:1784)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:660)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at egr.a(:com.google.android.gms:87)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at egr.a(:com.google.android.gms:135)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at dcc.a(:com.google.android.gms:24157)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at dap.a(:com.google.android.gms:397)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at dao.a(:com.google.android.gms:31369)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at dao.a(:com.google.android.gms:313)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at ece.a(:com.google.android.gms:1201)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at ecd.a(:com.google.android.gms:530)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at ecd.a(:com.google.android.gms:196)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at cxm.a(:com.google.android.gms:287)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at cxm.a(:com.google.android.gms:207)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at bcv.onTransact(:com.google.android.gms:137)
07-05 14:16:36.790  5047  5057 W GoogleHttpServiceClient: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:16:36.807  5331  5331 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:16:36.837  5331  5331 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:36.892  5047  5057 W System.err: java.lang.Exception: Error converting session
,07-05 14:16:36.892  5047  5057 W System.err: 	at rtz.log(:com.google.android.gms:302)
07-05 14:16:36.892  5047  5057 W System.err: 	at rtz.toSession(:com.google.android.gms:269)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(:com.google.android.gms:87)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(:com.google.android.gms:710)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(:com.google.android.gms:377)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(:com.google.android.gms:310)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.verifyHostname(:com.google.android.gms:217)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(:com.google.android.gms:507)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-05 14:16:36.892  5047  5057 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
,07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
07-05 14:16:36.893  5047  5057 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:660)
07-05 14:16:36.893  5047  5057 W System.err: 	at egr.a(:com.google.android.gms:87)
07-05 14:16:36.893  5047  5057 W System.err: 	at egr.a(:com.google.android.gms:135)
07-05 14:16:36.893  5047  5057 W System.err: 	at dcc.a(:com.google.android.gms:24157)
07-05 14:16:36.893  5047  5057 W System.err: 	at dap.a(:com.google.android.gms:397)
07-05 14:16:36.893  5047  5057 W System.err: 	at dao.a(:com.google.android.gms:31369)
07-05 14:16:36.893  5047  5057 W System.err: 	at dao.a(:com.google.android.gms:313)
07-05 14:16:36.893  5047  5057 W System.err: 	at ece.a(:com.google.android.gms:1201)
07-05 14:16:36.893  5047  5057 W System.err: 	at ecd.a(:com.google.android.gms:530)
,07-05 14:16:36.893  5047  5057 W System.err: 	at ecd.a(:com.google.android.gms:196)
07-05 14:16:36.893  5047  5057 W System.err: 	at cxm.a(:com.google.android.gms:287)
07-05 14:16:36.893  5047  5057 W System.err: 	at cxm.a(:com.google.android.gms:207)
07-05 14:16:36.893  5047  5057 W System.err: 	at bcv.onTransact(:com.google.android.gms:137)
07-05 14:16:36.893  5047  5057 W System.err: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:16:36.893  5047  5057 W System.err: Caused by: java.io.IOException: Invalid session data
07-05 14:16:36.893  5047  5057 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(:com.google.android.gms:88)
07-05 14:16:36.893  5047  5057 W System.err: 	at rtz.toSession(:com.google.android.gms:267)
07-05 14:16:36.893  5047  5057 W System.err: 	... 34 more
,07-05 14:16:36.913  5331  5350 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:16:36.925  5006  5006 I StatsUploadService: Turn off alarms uploading
,07-05 14:16:36.941  4831  5297 I Babel_StickerModule: Account change update: 1
,07-05 14:16:36.942  4831  5297 I Babel_StickerModule: Sticker update initiated. last:1466059120265 empty:false
,07-05 14:16:36.948  5006  5006 I StatsUploadService: Turn off networkusage uploading
,07-05 14:16:36.958  5006  5006 I StatsUploadService: Turn off wakelocks uploading
,07-05 14:16:36.958  4831  4891 W Babel   : Gms package replaced. Will trigger a restart of babel
,07-05 14:16:36.969  5006  5006 I StatsUploadService: Turn off internal_service_connections uploading
,07-05 14:16:37.050  5006  5006 I PerfProfileCollectorService: Turn off PerfProfile Collection
,07-05 14:16:37.060  5047  5047 E ChimeraSrvcProxy: Can't find Chimera service impl class com.google.android.gms.clearcut.service.VacuumChimeraService
,07-05 14:16:37.060  5047  5047 E ChimeraSrvcProxy: Proxy without impl dropping onStart()
,07-05 14:16:37.073  5047  5047 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:16:37.078  5047  5047 I PhenotypeSyncScheduler: Clear all shared preferences
,07-05 14:16:37.082  5047  5047 I PhenotypeSyncScheduler: Cancel all previously scheduled polling
,07-05 14:16:37.091  5047  5047 I PhenotypeSyncScheduler: Scheduling Phenotype for first execution 3298 seconds from now (1467720997091)
,07-05 14:16:37.099  5006  5006 I PlatformStatsCollectorService: Start Procstats in 11733 seconds.
,07-05 14:16:37.109  5006  5006 I PlatformStatsCollectorService: Start Batterystats in 392 seconds.
,07-05 14:16:37.121  5006  5006 I PlatformStatsCollectorService: Start Settingsstats in 14101 seconds.
,07-05 14:16:37.131  5006  5006 I PlatformStatsCollectorService: Start Notificationstats in 55939 seconds.
,07-05 14:16:37.140  5006  5006 I PlatformStatsCollectorService: Start Fingerprintstats in 73394 seconds.
,07-05 14:16:37.150  5047  5291 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.lockbox
,07-05 14:16:37.150  5006  5006 I PlatformStatsCollectorService: Start Graphicsstats in 336 seconds.
,07-05 14:16:37.160  5006  5006 I PlatformStatsCollectorService: Start Dropbox in 38419 seconds.
07-05 14:16:37.171  5006  5006 I PlatformStatsCollectorService: Start Diskstats in 7908 seconds.
,07-05 14:16:37.183  5047  5094 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:16:37.201  5006  5006 I PlatformStatsCollectorService: Start Netstats in 56479 seconds.
,07-05 14:16:37.482  4831  5297 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:37.482  4831  5297 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:37.613  5047  5125 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 14:16:37.633  4831  5297 I Babel   : BAM#account updated: 2
07-05 14:16:37.633  4831  5297 I Babel_StickerModule: Account change update: 2
07-05 14:16:37.634  4831  5297 W Babel_StickerModule: Null account update.
,07-05 14:16:37.759  4831  5135 I Babel   : BAM#account updated: 1
,07-05 14:16:37.923  5006  5006 D OcrModelBroadcastRcvr: com.google.android.gms.GMS_UPDATED
07-05 14:16:37.923   789   800 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.google.android.gms.GMS_UPDATED flg=0x10 pkg=com.google.android.gms } from com.android.vending (pid=4364, uid=10016) is not exported from uid 10008 due to receiver com.google.android.gms/.wallet.receiver.SystemEventBroadcastReceiver
07-05 14:16:37.925  5006  5361 D GmsModuleFndr: Beginning GMS chimera module scan
07-05 14:16:37.925  5006  5361 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 14:16:37.925  5006  5361 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:37.925  5006  5361 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:37.925  5006  5361 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
07-05 14:16:37.927  5006  5361 D FileApkUtils: Staged apk file not found: /data/app/com.google.android.gms-2/base.apk
07-05 14:16:37.927  5006  5361 D ChimeraCfgMgr: Beginning module configuration check
07-05 14:16:37.930  5006  5361 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 14:16:38.024  4831  5135 I Babel_StickerModule: Account change update: 1
07-05 14:16:38.024  4831  5135 I Babel_StickerModule: Sticker update initiated. last:1466059120265 empty:false
,07-05 14:16:38.371  5047  5125 W ctxmgr  : [WorkManager]Long workInfo: label=ListenerInvokerRunner, startTime=2016-07-05 14:16:36.288+0200, stopTime=2016-07-05 14:16:38.348+0200, duration=2060ms
,07-05 14:16:38.469  5006  5123 D nwp     : Package com.google.android.gms's hash: 65fd784bc81165c933ebc7c7ebe2458c292b557ffbd0217986424ea45394ac2d
,07-05 14:16:38.470  5006  5123 D nwe     : Look up (com.google.android.gms:9256438) returned no result
,07-05 14:16:38.621  5324  5324 I dex2oat : dex2oat took 2.170s (threads: 4) arena alloc=2MB java alloc=2035KB native alloc=11MB free=2MB
,07-05 14:16:38.636  5006  5218 D DexOptUtils: Odex created at:/data/user/0/com.google.android.gms/app_chimera/m/00000004/oat/arm/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.dex
,07-05 14:16:38.636  5006  5218 D DexOptUtils: Set odex to world readable.
07-05 14:16:38.636  5006  5218 D DexOptUtils: Renamed odex to /data/user/0/com.google.android.gms/app_chimera/m/00000004/oat/arm/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.odex
07-05 14:16:38.636  5006  5218 D FileApkUtils: Optimizing: DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk [0e2f02c80dd03f9c83187dd34bc9dd253af228cf4353ed24402cf024e8983ba5]
07-05 14:16:38.637  5006  5218 D DexOptUtils: Module /data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk appears to be unoptimized.
07-05 14:16:38.637  5006  5218 D DexOptUtils: Post L_MR1 platform, using oat/<isa> directory.
07-05 14:16:38.637  5006  5218 D DexOptUtils: Creating odex directory: /data/user/0/com.google.android.gms/app_chimera/m/00000005/oat/arm
07-05 14:16:38.638  5006  5218 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
07-05 14:16:38.638  5006  5218 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,07-05 14:16:38.691  5374  5374 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk --oat-file=/data/user/0/com.google.android.gms/app_chimera/m/00000005/oat/arm/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.dex
,07-05 14:16:38.704  5006  5123 D nwp     : Saved the app info in cache for package:com.google.android.gms.
,07-05 14:16:38.747  5047  5377 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 14:16:38.801  5006  5204 D Volley  : [462] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.googleapis.com/nova/sitrep 0x58872a44 NORMAL 1> [lifetime=3682], [size=0], [rc=200], [retryCount=0]
,07-05 14:16:38.802  5006  5256 I MDM     : [488] SitrepChimeraService.onHandleIntent: Sitrep successful
,07-05 14:16:38.802  5006  5006 D Volley  : [1] Request.a: 3714 ms: [ ] https://android.googleapis.com/nova/sitrep 0x58872a44 NORMAL 1
,07-05 14:16:38.814  4831  5371 I art     : Note: end time exceeds epoch: 
,07-05 14:16:38.830  5006  5363 W InstanceID/Rpc: Found 10008
,07-05 14:16:38.934  5006  5123 I Icing   : Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,07-05 14:16:38.940  5006  5123 I Icing   : Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,07-05 14:16:39.130  5006  5015 I art     : Background partial concurrent mark sweep GC freed 83192(9MB) AllocSpace objects, 28(700KB) LOS objects, 40% free, 20MB/34MB, paused 10.963ms total 65.450ms
,07-05 14:16:40.243  5047  5125 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:16:40.250  5047  5125 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-05 14:16:40.254  5047  5125 V BaseAppContext: GmsRequestQueue started.
,07-05 14:16:40.256  5047  5125 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-07-05 14:16:38.735+0200, stopTime=2016-07-05 14:16:40.255+0200, duration=1520ms
,07-05 14:16:40.302  5006  5123 V UdcCtxListenerSrv: handle intent
,07-05 14:16:40.310  5006  5006 I GCM     : Message from null null
,07-05 14:16:40.310  5006  5006 E GCM     : Dropping message from null
,07-05 14:16:40.471  5374  5374 I dex2oat : dex2oat took 1.780s (threads: 4) arena alloc=2MB java alloc=2MB native alloc=11MB free=2MB
,07-05 14:16:40.678  5006  5218 D DexOptUtils: Odex created at:/data/user/0/com.google.android.gms/app_chimera/m/00000005/oat/arm/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.dex
07-05 14:16:40.678  5006  5218 D DexOptUtils: Set odex to world readable.
,07-05 14:16:40.679  5006  5218 D DexOptUtils: Renamed odex to /data/user/0/com.google.android.gms/app_chimera/m/00000005/oat/arm/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.odex
,07-05 14:16:40.679  5006  5140 D FileApkUtils: Unreferenced module digest: [3443bc2d1f2e363d416681a76f25d41b2237df2454414307dd26605b77a05c98]
07-05 14:16:40.679  5006  5140 D FileApkUtils: Unreferenced module digest: [37cf97fe5a525ef4d305b0cc9070ddd3238f055bfdd2dcdde652f594f857f7e5]
07-05 14:16:40.679  5006  5140 D FileApkUtils: Unreferenced module digest: [ff56b9925340b9c80c565c5e193bbb70473225669a48932820782aa55ac2eb6c]
07-05 14:16:40.680  5006  5140 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:16:40.681  5006  5140 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 14:16:40.681  5006  5140 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:40.681  5006  5140 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 14:16:40.681  5006  5140 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
07-05 14:16:40.683  5006  5140 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:40.689  5006  5140 D ChimeraModuleApk: Loading chimera manifest from ContainerApk(com.google.android.gms)
,07-05 14:16:40.701  5047  5308 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 14:16:40.706  5006  5140 D ChimeraCfgMgr: Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.accountsettings,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.admob,v4) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.ads,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.analytics,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.app,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.appinvite,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.appstate,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.base,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.account.phone,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.accountactivationstate,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.credentials,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.proxy,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.api.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.authzen,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.easyunlock,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.auth.proximity,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.backup_lmp,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.base,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.beacon,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.car,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.cast,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.checkinbase,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.chromesync,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.707  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.clearcut,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.common.download,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.common_account,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.config,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.contextmanager,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.drive,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.droidguard,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.family,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.feedback,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebase_auth,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.fitness,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.flags,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.freighter,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.gass,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.gcm,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.googlehelp,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.herrevad,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.icing,v12) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.location,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.location.nonwearable,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.locationsharing,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.lockbox,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.maps,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:40.708  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.measurement,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.nearby,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.notifications,v2) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.ocr,v7) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.panorama,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.people,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.phenotype,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.phone,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.photos,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.places,v5) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.plus,v1) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.pseudonymous,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.reminders,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.security,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.signin,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.smart_profile,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.smartdevice,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.statementservice,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.stats,v3) from ContainerApk(com.google.android.gms)
,07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.subscribedfeeds,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.tapandpay,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.thunderbird,v2) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.tron,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.trustagent,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.udc,v5) from ContainerApk(com.google.android.gms)
07-05 14:16:40.709  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.usagereporting,v1) from ContainerApk(com.google.android.gms)
07-05 14:16:40.710  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.vision,v6) from ContainerApk(com.google.android.gms)
07-05 14:16:40.710  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.wallet,v3) from ContainerApk(com.google.android.gms)
07-05 14:16:40.710  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.wearable,v4) from ContainerApk(com.google.android.gms)
07-05 14:16:40.710  5006  5140 D ChimeraModuleApk: Loading chimera manifest from InstalledApk(com.google.android.play.games)
07-05 14:16:40.717  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.games,v37230000) from InstalledApk(com.google.android.play.games)
07-05 14:16:40.717  5006  5140 D ChimeraFileApk: Loading chimera manifest from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.718  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.ads.dynamite,v6) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.718  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.googlecertificates,v1) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.718  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.piccard.dynamite,v3) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.718  5006  5140 D ChimeraFileApk: Loading chimera manifest from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk)
,07-05 14:16:40.721  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.maps_dynamite,v6) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.721  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.signinbutton_dynamite,v1) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.721  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.vision.dynamite,v6) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.722  5006  5140 D ChimeraFileApk: Loading chimera manifest from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.728  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.cast.framework.dynamite,v2) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.728  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.crash,v3) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.728  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebase_database,v3) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.728  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.firebasestorage,v1) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.728  5006  5140 D ChimeraCfgMgr: Considering module(com.google.android.gms.tagmanager,v3) from FileApk(/data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk)
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: Beginning module config resolution
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: module(built-in,v0) has no external dependencies, accepted
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.accountsettings,v1) accepted
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.admob,v4) accepted
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.ads,v4) accepted
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.ads.dynamite,v6) accepted
07-05 14:16:40.729  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.analytics,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.app,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.appinvite,v2) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.appstate,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.base,v3) accepted
,07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.account.phone,v3) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.accountactivationstate,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.credentials,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.proxy,v2) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.api.signin,v2) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.authzen,v2) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.easyunlock,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.auth.proximity,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.backup,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.backup_lmp,v1) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.base,v2) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.beacon,v4) accepted
07-05 14:16:40.730  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.car,v4) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.cast,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.cast.framework.dynamite,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.checkinbase,v3) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.chromesync,v1) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.clearcut,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.common.download,v1) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.common_account,v1) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.config,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.contextmanager,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.crash,v3) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.drive,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.droidguard,v2) accepted
,07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.family,v4) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.feedback,v5) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.firebase_auth,v3) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.firebase_database,v3) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.firebasestorage,v1) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.fitness,v2) accepted
07-05 14:16:40.731  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.flags,v1) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.freighter,v1) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.games,v37230000) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.gass,v4) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.gcm,v2) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.googlecertificates,v1) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.googlehelp,v5) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.herrevad,v4) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.icing,v12) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.kids,v3) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.location,v2) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.location.nonwearable,v2) accepted
,07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.locationsharing,v2) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.lockbox,v4) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.maps,v6) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.maps_dynamite,v6) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.measurement,v2) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.nearby,v3) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.notifications,v2) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.ocr,v7) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.panorama,v1) accepted
07-05 14:16:40.732  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.people,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.phenotype,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.phone,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.photos,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.piccard.dynamite,v3) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.places,v5) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.plus,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.pseudonymous,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.reminders,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.security,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.signin,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.signinbutton_dynamite,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.smart_profile,v2) accepted
,07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.smartdevice,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.statementservice,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.stats,v3) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.subscribedfeeds,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.tagmanager,v3) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.tapandpay,v4) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.thunderbird,v2) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.tron,v1) accepted
07-05 14:16:40.733  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.trustagent,v1) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.udc,v5) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.usagereporting,v1) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.vision,v6) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.vision.dynamite,v6) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.wallet,v3) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: module(com.google.android.gms.wearable,v4) accepted
07-05 14:16:40.734  5006  5140 D ChimeraCfgRslvr: Module config resolution complete
,07-05 14:16:40.794  5006  5006 D ChimeraCfgMgr: Notified of config change, reloading
,07-05 14:16:40.795  5331  5331 D ChimeraCfgMgr: Notified of config change, reloading
07-05 14:16:40.795  5331  5331 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:40.816  5006  5140 D FileApkUtils: Optimizing (staging complete)
,07-05 14:16:40.816  5006  5140 D FileApkUtils: Optimizing: DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk [0e2f02c80dd03f9c83187dd34bc9dd253af228cf4353ed24402cf024e8983ba5]
07-05 14:16:40.817  5006  5140 D DexOptUtils: Module /data/user/0/com.google.android.gms/app_chimera/m/00000005/DynamiteModulesC_GmsCore_prodmnc_xxhdpi_release.apk is already optimized. Bailing.
07-05 14:16:40.817  5006  5140 D FileApkUtils: Optimizing: DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk [7f6f060a805f21d07533a5b4157f179f737b6ac39ade2616b81fdf06f34f011a]
07-05 14:16:40.818  5006  5140 D DexOptUtils: Module /data/user/0/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodmnc_xxhdpi_release.apk is already optimized. Bailing.
07-05 14:16:40.819  5006  5140 D FileApkUtils: Optimizing: DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk [fe7132835f5c81d2a6f3dc2bab32154f350928809ac8969602ed65e931dc6cc7]
07-05 14:16:40.820  5006  5140 D DexOptUtils: Module /data/user/0/com.google.android.gms/app_chimera/m/00000004/DynamiteModulesB_GmsCore_prodmnc_xxhdpi_release.apk is already optimized. Bailing.
,07-05 14:16:40.820  5006  5140 D GmsModuleFndr: Beginning GMS chimera module scan
07-05 14:16:40.821  5006  5140 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 14:16:40.821  5006  5140 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:16:40.821  5006  5140 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
,07-05 14:16:40.821  5006  5140 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
07-05 14:16:40.823  5006  5140 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:16:40.830  5006  5140 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 14:16:40.835  5047  5047 D ChimeraCfgMgr: Reading stored module config
,07-05 14:16:40.847  5047  5047 D ChimeraCfgMgr: Notified of config change, reloading
,07-05 14:16:40.914  5006  5034 D FileApkUtils: Adding module set unique id: [3]
,07-05 14:16:40.914  5006  5034 D FileApkUtils: Adding module set unique id: [5]
07-05 14:16:40.914  5006  5034 D FileApkUtils: Adding module set unique id: [5]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [5]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [5]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [3]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [4]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [3]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [4]
,07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [5]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding module set unique id: [4]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding installed module unique id: [3]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding installed module unique id: [4]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Adding installed module unique id: [5]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Referenced module unique id: [5]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Referenced module unique id: [3]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Referenced module unique id: [4]
07-05 14:16:40.915  5006  5034 D FileApkUtils: Deleting stale module: 00000000
,07-05 14:16:40.927  5006  5034 D FileApkUtils: Deleting stale module: 00000001
,07-05 14:16:40.929  5006  5034 D FileApkUtils: Deleting stale module: 00000002
,07-05 14:16:40.938  5006  5034 D FileApkUtils: Keeping up-to-date module: 00000003
,07-05 14:16:40.938  5006  5034 D FileApkUtils: Keeping up-to-date module: 00000004
07-05 14:16:40.938  5006  5034 D FileApkUtils: Keeping up-to-date module: 00000005
,07-05 14:16:41.360  4831  5344 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:41.360  4831  5344 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:41.489  4831  5371 I art     : Note: end time exceeds epoch: 
,07-05 14:16:41.609  4831  5369 I art     : Note: end time exceeds epoch: 
,07-05 14:16:42.571  5047  5125 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-05 14:16:42.624  5006  5123 V UdcCtxListenerSrv: handle intent
,07-05 14:16:42.673  4831  5359 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:42.673  4831  5359 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,07-05 14:16:43.406  4831  5371 I art     : Note: end time exceeds epoch: 
,07-05 14:16:44.166   789   885 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:16:44.249  4623  5443 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 14:16:44.288  4623  5443 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 38 ms] updated apps [took 38 ms] 
,07-05 14:16:44.292  5006  5034 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:16:44.299  5006  5034 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:16:44.317  5006  5123 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-05 14:16:44.325  5047  5047 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 14:16:44.365  5006  5468 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:16:44.395  5006  5123 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-05 14:16:44.440  5006  5123 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-05 14:16:45.494  5006  5123 I Icing   : Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,07-05 14:16:45.503  5006  5123 I Icing   : Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,07-05 14:16:49.229  4364  4407 I Finsky  : [362] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-05 14:16:49.324  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:49.325  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:49.427  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:16:50.286  4364  4364 I Finsky  : [1] com.google.android.finsky.c.c.a(311): Completed 1 account content syncs with 1 successful.
,07-05 14:16:50.286  4364  4364 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-05 14:16:54.341   789  1343 I ActivityManager: Killing 4556:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-05 14:16:54.591  5006  5209 I CheckinService: Done disabling old GoogleServicesFramework version
,07-05 14:17:01.951  1225  4129 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-05 14:17:01.951  1225  4129 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:17:02.031  5047  5511 I CheckinUtil: Classify the device as Phone.
,07-05 14:17:02.102  5047  5054 E System  : Uncaught exception thrown by finalizer
,07-05 14:17:02.102  5047  5054 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:17:02.102  5047  5054 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:17:02.102  5047  5054 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(:com.google.android.gms:485)
07-05 14:17:02.102  5047  5054 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:17:02.102  5047  5054 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:17:02.102  5047  5054 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:17:08.045   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb6c4a030
,07-05 14:17:08.045   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,07-05 14:17:08.045   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
,07-05 14:17:08.046   192   507 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228670672)
,07-05 14:17:08.172   192   507 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
,07-05 14:17:08.172   192   507 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
07-05 14:17:08.172   192   507 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228670672) wakelock released: 1, error no: 0
07-05 14:17:08.172   192   507 I rmt_storage: 
,07-05 14:17:08.175   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb6c4a030
,07-05 14:17:12.432  5047  5552 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
07-05 14:17:12.432  5047  5551 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:17:12.459  5047  5551 I GLSUser : Method not found getActionBar
,07-05 14:17:12.779   789  1343 I ActivityManager: Start proc 5565:com.google.android.youtube/u0a80 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:17:12.934  5565  5577 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:17:12.947  5565  5577 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:17:12.947  5565  5577 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
07-05 14:17:12.951  5565  5577 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:17:12.987  5565  5586 D ChimeraCfgMgr: Reading stored module config
,07-05 14:17:13.003  5565  5577 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:17:13.024  5565  5586 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000003/n/armeabi
,07-05 14:17:13.025  5565  5586 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:17:13.026  5565  5586 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:17:13.032  5565  5586 D DynamitePackage: Instantiated singleton DynamitePackage.
,07-05 14:17:13.032  5565  5586 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,07-05 14:17:13.038  5565  5565 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 14:17:13.115  5620  5620 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/1460683162801.jar --oat-file=/data/user/0/com.google.android.youtube/cache/1460683162801.dex
,07-05 14:17:13.161  5620  5620 I dex2oat : dex2oat took 46.718ms (threads: 4) arena alloc=267KB java alloc=42KB native alloc=1708KB free=1875KB
,07-05 14:17:13.190  5565  5586 D hf      : File /data/user/0/com.google.android.youtube/cache/1460683162801.dex not found. No need for deletion
,07-05 14:17:13.210  5565  5565 W InstanceID/Rpc: Found 10008
,07-05 14:17:13.327  5006  5671 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-05 14:17:13.327  5006  5671 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 14:17:13.331   789   974 I ActivityManager: Killing 4775:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-05 14:17:28.930   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=898867, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:17:34.502   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=904439, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:17:39.110  5006  5691 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:17:39.125  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:17:39.130  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:17:39.130  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:17:40.126  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:17:40.170   789   800 I ActivityManager: Start proc 5719:com.google.android.gms.unstable/u0a8 for service com.google.android.gms/.droidguard.DroidGuardService
,07-05 14:17:40.213  5719  5719 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:17:40.213  5719  5719 I MultiDex: install
07-05 14:17:40.213  5719  5719 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:17:40.230  5719  5719 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-05 14:17:40.239  5719  5719 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-05 14:17:40.239  5719  5719 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-05 14:17:40.242  5719  5719 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:17:40.271  5719  5719 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:17:40.282  5719  5719 D ChimeraCfgMgr: Reading stored module config
,07-05 14:17:40.374  5719  5734 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:17:40.377   198   828 D WVCdm   : Instantiating CDM.
,07-05 14:17:40.378   198   198 I WVCdm   : CdmEngine::OpenSession
,07-05 14:17:40.378   198   198 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:17:40.382   198   198 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:17:40.385   198   198 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-05 14:17:40.385   198   198 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:17:40.385   198   198 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:17:40.385   198   198 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:17:40.400   198   198 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:17:40.401   198   198 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:17:40.401   198   198 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
07-05 14:17:40.401   198   198 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
,07-05 14:17:40.413   198   198 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:17:40.413   198   198 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:17:40.421   198   198 D DrmWidevineDash: hlos api version =  10
,07-05 14:17:40.421   198   198 D DrmWidevineDash: tz api version =  10
07-05 14:17:40.421   198   198 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:17:40.421   198   198 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:17:40.433   198   198 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:17:40.433   198   198 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:17:40.433   198   198 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbed9a214
,07-05 14:17:40.438   198   198 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 14:17:40.438   198   198 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:17:40.439   198   198 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb46672f8, dataLength=8
,07-05 14:17:40.444   198   198 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:17:40.445   198   198 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb5fc7000, wrapped_rsa_key_length=1280
,07-05 14:17:40.452   198   198 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-05 14:17:40.452   198   198 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-05 14:17:40.453   198   828 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:17:40.453   198   828 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,07-05 14:17:40.453   198   828 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:17:40.453   198   828 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb38ffea0, idLength=0xb36fef2c
,07-05 14:17:40.465   198   828 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:17:40.465   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:17:40.470   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:17:40.470   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:17:40.470   198   828 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:17:40.470   198   828 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:17:40.475   198   828 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-05 14:17:40.475   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:17:40.481   198   828 D DrmWidevineDash: hlos api version =  10
,07-05 14:17:40.481   198   828 D DrmWidevineDash: tz api version =  10
07-05 14:17:40.481   198   828 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:17:40.481   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:17:40.486   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-05 14:17:40.486   198   828 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:17:40.486   198   828 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:17:40.491   198   828 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-05 14:17:40.491   198   828 D WVCdm   : PrepareKeyRequest: nonce=1152667182
07-05 14:17:40.491   198   828 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb33e4700
07-05 14:17:40.491   198   828 D DrmWidevineDash: message_length=1639, signature=0xb6036840, signature_length=3010457604
,07-05 14:17:40.609   198   828 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:17:40.610   198  1102 I WVCdm   : CdmEngine::CloseSession
07-05 14:17:40.610   198  1102 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:17:40.615  5006  5744 D UdcContextInitService: registered all accounts: true
,07-05 14:17:40.616   198  1102 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-05 14:17:40.616   198  1102 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:17:40.622   198  1102 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:17:40.622   198  1102 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:17:40.622   198  1102 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:17:40.622   198  1102 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:17:40.623   198  1102 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:17:40.625  5006  5744 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
,07-05 14:17:40.639  5006  5123 V UdcCtxListenerSrv: handle intent
,07-05 14:17:40.924  5753  5753 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-05 14:17:40.978  5753  5753 I dex2oat : dex2oat took 55.099ms (threads: 4) arena alloc=285KB java alloc=59KB native alloc=1669KB free=1658KB
,07-05 14:17:40.983  5719  5730 W System  : ClassLoader referenced unknown path: 
,07-05 14:17:40.988  5719  5730 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:17:41.047  5719  5730 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:17:41.108  5719  5730 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:17:41.216  5047  5715 W System.err: java.lang.Exception: Error converting session
,07-05 14:17:41.216  5047  5715 W System.err: 	at rtz.log(:com.google.android.gms:302)
07-05 14:17:41.216  5047  5715 W System.err: 	at rtz.toSession(:com.google.android.gms:269)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(:com.google.android.gms:87)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(:com.google.android.gms:710)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(:com.google.android.gms:377)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(:com.google.android.gms:310)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.verifyHostname(:com.google.android.gms:217)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(:com.google.android.gms:507)
,07-05 14:17:41.216  5047  5715 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-05 14:17:41.216  5047  5715 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
,07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
07-05 14:17:41.217  5047  5715 W System.err: 	at dal.a(:com.google.android.gms:233)
07-05 14:17:41.217  5047  5715 W System.err: 	at dpb.a(:com.google.android.gms:263)
,07-05 14:17:41.217  5047  5715 W System.err: 	at dpb.a(:com.google.android.gms:4235)
07-05 14:17:41.217  5047  5715 W System.err: 	at dpa.a(:com.google.android.gms:47)
07-05 14:17:41.217  5047  5715 W System.err: 	at dou.a(:com.google.android.gms:55)
07-05 14:17:41.217  5047  5715 W System.err: 	at dot.a(:com.google.android.gms:113)
07-05 14:17:41.217  5047  5715 W System.err: 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.a(:com.google.android.gms:3054)
07-05 14:17:41.217  5047  5715 W System.err: 	at nzi.run(:com.google.android.gms:179)
07-05 14:17:41.217  5047  5715 W System.err: Caused by: java.io.IOException: Invalid session data
07-05 14:17:41.217  5047  5715 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(:com.google.android.gms:88)
07-05 14:17:41.217  5047  5715 W System.err: 	at rtz.toSession(:com.google.android.gms:267)
07-05 14:17:41.217  5047  5715 W System.err: 	... 30 more
,07-05 14:17:46.189   789  1333 I ActivityManager: Killing 4732:com.android.defcontainer/u0a5 (adj 15): empty #17
,07-05 14:17:53.740   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=923677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:18:11.840  5006  5778 I ChimeraConfigService: Scheduling checkin every 43200 seconds, with flex of 1800 seconds
,07-05 14:18:11.873  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:18:11.874  5047  5047 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:18:11.880  5006  5766 I EventLogChimeraService: Aggregate from 1467720936787 (log), 1467719258697 (data)
,07-05 14:18:11.924  5047  5047 D WearableService: callingUid 10008, callindPid: 5047
,07-05 14:18:11.948  5047  5790 I CheckinUtil: Classify the device as Phone.
,07-05 14:18:11.994  5006  5791 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 14:18:12.202  5006  5778 D ChimeraConfigService: Fetched value, gms:chimera:dogfoods = null
,07-05 14:18:12.202  5006  5778 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
07-05 14:18:12.202  5006  5778 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,07-05 14:18:13.218  5047  5804 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 14:18:13.218  5047  5799 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:18:13.236  5047  5804 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 14:18:13.237  5047  5799 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:18:13.261  5047  5804 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-05 14:18:13.261  5047  5799 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-05 14:18:13.261  5047  5799 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-05 14:18:13.385  5047  5054 E System  : Uncaught exception thrown by finalizer
07-05 14:18:13.385  5047  5054 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:18:13.385  5047  5054 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:18:13.385  5047  5054 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(:com.google.android.gms:485)
07-05 14:18:13.385  5047  5054 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:18:13.385  5047  5054 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:18:13.385  5047  5054 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:18:13.389  5047  5054 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@6c6dbc8)
,07-05 14:18:13.392  5047  5799 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:18:16.980   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:18:27.190   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=957127, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:18:39.468  5047  5326 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:19:41.132   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1031070, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:19:53.330   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1043267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:20:12.016  5006  5139 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:20:40.671   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1090608, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:20:55.650   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1105587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:21:09.942   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1119880, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:21:22.130   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1132067, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:21:39.462   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1149398, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:21:51.650   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1161587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:22:17.490   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1187427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:22:32.660   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1202597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:22:45.692   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1215629, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:22:46.221   789   804 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:23:02.050   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1231987, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:23:17.192   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1247128, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:23:17.848  5006  5883 D Graphicsstats: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 14:23:18.001  5006  5903 D Batterystats: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 14:23:33.570   789  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1263507, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms)
```
