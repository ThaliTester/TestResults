#### Test 757892685a40176_thali03_LGE-Nexus 5 Logs


```
--------- beginning of main
07-12 17:44:48.561   790   891 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 17:44:48.968   790  2783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=142387, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
07-12 17:44:49.304  3552  3552 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 17:44:49.309  3552  3552 D AndroidRuntime: CheckJNI is OFF
07-12 17:44:49.345  3552  3552 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 17:44:49.383  3552  3552 I Radio-JNI: register_android_hardware_Radio DONE
07-12 17:44:49.403  3552  3552 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-12 17:44:49.405   790  3258 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 17:44:49.428  1377  1391 W SearchService: Abort, client detached.
07-12 17:44:49.456  3552  3552 D AndroidRuntime: Shutting down VM
07-12 17:44:49.460   790   968 I ActivityManager: Start proc 3568:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-12 17:44:49.466  1377  1377 I MicroDetector: Keeping mic open: false
07-12 17:44:49.466  1377  1572 I DeviceStateChecker: DeviceStateChecker cancelled
07-12 17:44:49.466  1377  1377 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@84b71f0
07-12 17:44:49.466  1377  1472 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-12 17:44:49.519   196  1586 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-12 17:44:49.519   196  1586 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-12 17:44:49.529  1377  1583 I MicroRecognitionRunner: Detection finished
07-12 17:44:49.531  1377  1569 I MicroRecognitionRunner: Stopping hotword detection.
07-12 17:44:49.552  3568  3568 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-12 17:44:49.583  3568  3568 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 3014-3015)
07-12 17:44:49.583  3568  3568 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-12 17:44:49.597  3568  3568 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b0839e1}
07-12 17:44:49.597  3568  3568 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-12 17:44:49.597  3568  3568 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:44:49.613   790   892 D WifiService: New client listening to asynchronous messages
07-12 17:44:49.623  3568  3568 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-12 17:44:49.633  3568  3568 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-12 17:44:49.634  3568  3568 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-12 17:44:49.646  3568  3568 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 17:44:49.707   790   815 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a4586c0:true
,07-12 17:44:49.715   790  3259 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3568 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 17:44:49.724  3568  3568 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-12 17:44:49.732  3568  3568 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:44:49.733  3568  3568 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-12 17:44:49.744  3568  3568 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-12 17:44:49.768  3568  3568 I cr_Ime  : ImeThread is not enabled.
,07-12 17:44:49.779  3568  3608 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 17:44:49.819   790  1224 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3568 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 17:44:49.844  3568  3613 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 17:44:49.876  3568  3613 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 17:44:49.911  3568  3613 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-12 17:44:49.968   189   189 D SurfaceFlinger: shader cache generated - 24 shaders in 155.055420 ms
,07-12 17:44:50.031  3568  3608 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 17:44:50.101   790   816 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +653ms
,07-12 17:44:50.180  3568  3568 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3568
,07-12 17:44:50.181  3568  3568 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
07-12 17:44:50.181  3568  3568 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,07-12 17:44:50.274   790  3258 I ActivityManager: Killing 2722:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-12 17:44:50.316  3568  3568 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 17:44:50.361   790   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 17:44:50.467  3568  3638 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1722549968
,07-12 17:44:50.471  3568  3638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:44:50.471  3568  3638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:44:50.471  3568  3638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:44:50.471  3568  3638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:44:50.471  3568  3638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 17:44:50.471  3568  3638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed51f13 added. We now have 1 listener(s)
,07-12 17:44:50.475  3568  3638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,07-12 17:44:50.478  3568  3638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-12 17:44:50.480  3568  3638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:44:50.480  3568  3638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-12 17:44:50.483  3568  3638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc144e added. We now have 1 listener(s)
07-12 17:44:50.483  3568  3638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:44:50.486  3568  3638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-12 17:44:50.488  3568  3638 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-12 17:44:50.488  3568  3638 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-12 17:44:50.490  3568  3638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:44:50.490  3568  3638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:44:50.494  3568  3638 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:44:50.494  3568  3638 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-12 17:44:50.494  3568  3638 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:44:50.495  3568  3638 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:44:50.495  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:44:50.497  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:44:50.526  3568  3568 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:44:51.197  3568  3641 W jxcore-log: Initializing JXcore engine
,07-12 17:44:51.197  3568  3641 W jxcore-log: JXcore engine is ready
,07-12 17:44:51.223  3641  3641 W Thread-305: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8576]" dev="sockfs" ino=8576 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-12 17:44:51.223  3641  3641 W Thread-305: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-12 17:44:51.223  3641  3641 W Thread-305: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21730]" dev="sockfs" ino=21730 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 17:44:51.255  3568  3641 W jxcore-log: Starting JXcore engine
,07-12 17:44:51.331  3568  3641 W jxcore-log: Platform android
07-12 17:44:51.331  3568  3641 W jxcore-log: 
,07-12 17:44:51.331  3568  3641 W jxcore-log: Process ARCH arm
07-12 17:44:51.331  3568  3641 W jxcore-log: 
,07-12 17:44:51.558  3568  3641 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:44:51.558  3568  3641 I jxcore-log: 
07-12 17:44:51.558  3568  3641 W jxcore-log: JXcore engine is started
,07-12 17:44:51.563  3568  3638 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:44:51.569  3568  3568 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:44:57.785   790   818 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 17:44:57.786   790   818 I PowerManagerService: Sleeping (uid 1000)...
,07-12 17:44:57.790   189   910 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (180 us)
,07-12 17:44:57.799   790   818 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 17:44:57.812  3568  3568 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 17:44:57.813  3568  3568 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 17:44:57.871  3568  3568 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5e023fa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5892dd4, 16908290=android.view.AbsSavedState$1@5892dd4}, android:focusedViewId=100}]}]
07-12 17:44:57.871  3568  3568 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-12 17:44:57.871  3568  3568 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-12 17:44:57.871  3568  3568 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 17:44:57.934   790   799 I art     : Background partial concurrent mark sweep GC freed 31632(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 25MB/38MB, paused 1.021ms total 130.473ms
,07-12 17:44:58.341   790   818 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 17:44:58.350   790   818 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-12 17:44:58.360   790   816 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 17:44:58.369   189   189 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,07-12 17:44:58.369   189   189 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-12 17:44:58.638   189   189 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-12 17:44:58.638   790   911 D SurfaceControl: Excessive delay in setPowerMode(): 278ms
,07-12 17:44:58.638  1798  1812 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-12 17:44:58.646   196   830 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-12 17:44:58.656   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:44:58.660   790   891 E native  : do suspend false
,07-12 17:44:58.665   790   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 17:44:58.679   196   900 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-12 17:44:58.680   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 17:44:58.682   790   891 E native  : do suspend true
,07-12 17:44:58.689  1229  1229 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-12 17:44:58.903  1556  1556 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-12 17:44:58.911  1556  1556 I BeaconBle: BLE 'JB+' software access layer enabled
,07-12 17:44:58.942  1556  3692 D BluetoothAdapter: startLeScan(): null
,07-12 17:44:58.944  1556  3692 D BluetoothAdapter: STATE_ON
,07-12 17:44:58.948  1792  2088 D BtGatt.GattService: registerClient() - UUID=9cdfc9d0-5fa2-40fd-8cbb-ab6157805307
,07-12 17:44:58.949  1792  1881 D BtGatt.GattService: onClientRegistered() - UUID=9cdfc9d0-5fa2-40fd-8cbb-ab6157805307, clientIf=5
,07-12 17:44:58.950  1556  1611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:44:58.950  1792  1803 D BtGatt.GattService: start scan with filters
,07-12 17:44:58.953  1792  1884 D BtGatt.ScanManager: handling starting scan
,07-12 17:44:58.954  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-12 17:44:58.954  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 17:44:58.955  1792  1884 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 17:44:58.955  1792  1881 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 17:44:59.157   790   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,07-12 17:44:59.481  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:44:59.545  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:44:59.652   790  3259 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1568 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 17:44:59.662  1556  3673 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:44:59.712  1568  3719 W DriveInitializer: Background init thread started
,07-12 17:44:59.856  1568  3719 W DriveInitializer: Background init thread ended
,07-12 17:44:59.935  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:00.328  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:00.459  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Sluchawki Bose len=14 dev_type=3
,07-12 17:45:00.463  1556  3692 D BluetoothAdapter: stopLeScan()
,07-12 17:45:00.463  1556  3692 D BluetoothAdapter: STATE_ON
07-12 17:45:00.468  1792  2088 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:00.469  1792  1884 D BtGatt.ScanManager: stop scan
,07-12 17:45:00.469  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 17:45:00.469  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
,07-12 17:45:00.469  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-12 17:45:00.469  1792  1807 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:00.645  1556  3692 D BluetoothAdapter: startLeScan(): null
,07-12 17:45:00.647  1556  3692 D BluetoothAdapter: STATE_ON
07-12 17:45:00.650  1792  2081 D BtGatt.GattService: registerClient() - UUID=9b4cd42a-b2f0-4257-8f25-6a05f7610144
07-12 17:45:00.650  1792  1881 D BtGatt.GattService: onClientRegistered() - UUID=9b4cd42a-b2f0-4257-8f25-6a05f7610144, clientIf=5
,07-12 17:45:00.650  1556  1628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:00.650  1792  1803 D BtGatt.GattService: start scan with filters
,07-12 17:45:00.653  1792  1884 D BtGatt.ScanManager: handling starting scan
,07-12 17:45:00.654  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-12 17:45:00.654  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 17:45:00.654  1792  1884 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 17:45:00.655  1792  1881 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 17:45:00.704  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:00.745  1556  3673 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:01.383  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:01.458  1792  1881 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:01.766  1556  3673 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:01.959  1556  3692 D BluetoothAdapter: stopLeScan()
,07-12 17:45:01.960  1556  3692 D BluetoothAdapter: STATE_ON
07-12 17:45:01.960  1792  1807 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:01.961  1792  1884 D BtGatt.ScanManager: stop scan
,07-12 17:45:01.961  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 17:45:01.961  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 17:45:01.961  1792  1884 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 17:45:01.962  1792  2081 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:01.962  1556  3692 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 17:45:02.004  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 17:45:02.004  3568  3641 I jxcore-log: 
,07-12 17:45:02.006  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 17:45:02.006  3568  3641 I jxcore-log: 
,07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:02.010  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:02.012  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:02.013  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 17:45:02.013  3568  3641 I jxcore-log: 
,07-12 17:45:02.015  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 17:45:02.015  3568  3641 I jxcore-log: 
,07-12 17:45:02.350  3568  3641 I jxcore-log: Unit Test app is loadeded
07-12 17:45:02.350  3568  3641 I jxcore-log: 
,07-12 17:45:02.356  3568  3568 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 17:45:02.357  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:02.357  3568  3641 I jxcore-log: 
,07-12 17:45:02.366  3568  3641 I jxcore-log: runUTtestsBefore
07-12 17:45:02.366  3568  3641 I jxcore-log: 
,07-12 17:45:02.366  3568  3641 D JXMOBILE: Running tests
,07-12 17:45:02.444  3568  3641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-12 17:45:02.444  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-12 17:45:02.444  3568  3641 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-12 17:45:02.444  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-12 17:45:02.444  3568  3641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-12 17:45:02.444  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-12 17:45:02.445  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-12 17:45:02.445  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-12 17:45:02.445  3568  3641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-12 17:45:02.445  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:02.445  3568  3641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-12 17:45:02.445  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:02.445  3568  3641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-12 17:45:02.445  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:02.446  3568  3641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-12 17:45:02.446  3568  3641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-12 17:45:02.446  3568  3641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-12 17:45:02.446  3568  3641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-12 17:45:02.446  3568  3641 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-12 17:45:02.446  3568  3641 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-12 17:45:02.447  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:02.447  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f35817 added. We now have 2 listener(s)
07-12 17:45:02.447  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:02.449  3568  3641 D BluetoothAdapter: enable(): BT is already enabled..!
07-12 17:45:02.449   790   800 D WifiService: setWifiEnabled: true pid=3568, uid=10026
07-12 17:45:02.449   790   800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:02.449  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:02.449  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63db404 added. We now have 3 listener(s)
07-12 17:45:02.449  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:02.452  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:02.452  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4370ded added. We now have 4 listener(s)
07-12 17:45:02.453  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:02.454  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:02.454  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fd5422 added. We now have 5 listener(s)
07-12 17:45:02.454  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:02.455   790  2092 D WifiService: setWifiEnabled: false pid=3568, uid=10026
07-12 17:45:02.455   790  2092 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:02.457   790   891 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-12 17:45:02.457   790   891 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-12 17:45:02.457   790   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-12 17:45:02.457   790   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:02.460  1792  1877 D BluetoothAdapterState: Current state: ON, message: 23
,07-12 17:45:02.460  1792  1877 D BluetoothAdapterProperties: Setting state to 13
07-12 17:45:02.461  1792  1877 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-12 17:45:02.461  1792  1877 D BluetoothAdapterProperties: onBluetoothDisable()
,07-12 17:45:02.462  1792  1877 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:02.463  1792  1881 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:02.463  1792  1877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:02.465  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:02.465  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:02.467  1792  1792 D HeadsetService: Received stop request...Stopping profile...
,07-12 17:45:02.478   790   891 E native  : do suspend true
,07-12 17:45:02.483   790   804 I ActivityManager: Start proc 3746:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-12 17:45:02.486  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:02.486   790   790 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:02.486   932   943 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:02.487  1304  1329 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:02.487   790   790 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:02.487   790   790 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:02.488  1792  1792 D BluetoothMapService: onReceive
07-12 17:45:02.488  1792  1792 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:02.488  1792  1792 D BluetoothMapService: STATE_TURNING_OFF
07-12 17:45:02.488  1792  1792 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:02.488  1792  1792 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:02.488  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.488  1792  1792 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:02.493   932   932 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:02.493  1792  1792 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:02.493  1792  2068 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:02.494   790   790 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:02.494  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:02.496  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:02.496  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:02.498   932   932 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:02.500  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:02.501  1792  1792 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:02.501  1792  1792 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:02.501  1792  1792 D BluetoothMapService: MAP Service closeService in
07-12 17:45:02.501  1792  1881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-12 17:45:02.502  1792  1996 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:02.502  1792  1996 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:02.502  1792  1881 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-12 17:45:02.502  1792  1792 D BluetoothMapMasInstance0: MAP Service shutdown
07-12 17:45:02.502  1792  1792 D ObexServerSockets0: shutdown(block = true)
07-12 17:45:02.502  1792  1792 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:02.502  1792  2094 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-12 17:45:02.503  1792  2093 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-12 17:45:02.503  1792  2050 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-12 17:45:02.503  1792  1792 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:02.504  1792  1792 I BtOppRfcommListener: stopping Accept Thread
07-12 17:45:02.504  1792  2615 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-12 17:45:02.504  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:02.505   790  2785 D DhcpClient: Clearing IP address
07-12 17:45:02.505   192   784 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:02.508  1792  2615 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:02.508   192   784 D CommandListener: Setting iface cfg
07-12 17:45:02.514   790  2798 D DhcpClient: Receive thread stopped
07-12 17:45:02.519  1792  1792 D HidService: Received stop request...Stopping profile...
07-12 17:45:02.519  1792  1792 D HidService: Stopping Bluetooth HidService
07-12 17:45:02.520   932   932 D BluetoothInputDevice: Proxy object disconnected
07-12 17:45:02.520   932   932 D HidProfile: Bluetooth service disconnected
07-12 17:45:02.520  1792  1792 D HealthService: Received stop request...Stopping profile...
07-12 17:45:02.521  1792  1792 D PanService: Received stop request...Stopping profile...
07-12 17:45:02.522   932   932 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:02.522   932   932 D PanProfile: Bluetooth service disconnected
07-12 17:45:02.522  1792  1792 D BluetoothMapService: Received stop request...Stopping profile...
07-12 17:45:02.522  1792  1792 D BluetoothMapService: stop()
07-12 17:45:02.522  1792  1792 D BluetoothMapAppObserver: deinitObservers()
07-12 17:45:02.522  1792  1792 D BluetoothMapAppObserver: removeReceiver()
07-12 17:45:02.523   932   932 D BluetoothMap: Proxy object disconnected
07-12 17:45:02.523   932   932 D MapProfile: Bluetooth service disconnected
07-12 17:45:02.524  1792  1792 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:02.524  1792  1792 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:02.524  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.524  1792  1792 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:02.524  1792  1881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-12 17:45:02.524  1792  1996 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:02.524  1792  1996 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:02.525  1792  1996 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:02.525  1792  1996 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:02.525  1792  1996 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:02.525  1792  1996 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:02.528  1792  1792 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:02.528  1792  1792 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:02.529  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.529  1792  1792 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:02.529  1792  1792 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:02.529  1792  1881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 17:45:02.529  1792  1792 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:02.529  1792  1792 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:02.529  1792  1792 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:02.529  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.529  1792  1792 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:02.529  1792  1792 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:02.529  1792  1881 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:02.530  1792  1792 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-12 17:45:02.530  1792  1792 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:02.530  1792  1792 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:02.530  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.530  1792  1792 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:02.530  1792  1792 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-12 17:45:02.530  1792  1792 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:02.531  1792  1792 D BluetoothMapService: MAP Service closeService in
07-12 17:45:02.531  1792  1792 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:02.531  1792  1792 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:02.531  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.531  1792  1792 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:02.531  1792  1877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-12 17:45:02.531  1792  1877 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:02.531  1792  1877 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:02.531   790   815 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:02.531   790   815 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:02.531   790   815 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:02.532   932   943 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:02.532  1792  1877 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:02.534  1304  1430 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:02.534   932  1395 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:02.535   932   951 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:02.535   790   815 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:02.535   932   943 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:02.536   932  1395 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:02.536   932   951 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:02.536  1792  1877 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:02.536  1792  1877 D BluetoothAdapterProperties: Setting state to 16
07-12 17:45:02.536  1792  1877 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:02.537  1792  1877 D BluetoothAdapterProperties: onBleDisable
07-12 17:45:02.540  1792  1877 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:02.540  1792  1878 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:02.540  1792  1881 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:02.541  1792  1996 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-12 17:45:02.541  1792  1996 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:02.544  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:02.545  1792  1792 D BluetoothMapService: cleanup()
07-12 17:45:02.545  1792  1792 D BluetoothMapService: MAP Service closeService in
07-12 17:45:02.546  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:02.562  3746  3746 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-12 17:45:02.567  2855  3013 V NativeCrypto: Read error: ssl=0x98b6fe00: I/O error during system call, Connection timed out
07-12 17:45:02.569   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-12 17:45:02.574   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-12 17:45:02.575   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-12 17:45:02.576   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
07-12 17:45:02.577   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
07-12 17:45:02.578   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
07-12 17:45:02.579   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-12 17:45:02.581  2855  3013 V NativeCrypto: Write error: ssl=0x98b6fe00: I/O error during system call, Broken pipe
07-12 17:45:02.581  2855  3013 V NativeCrypto: Write error: ssl=0x98b6fe00: I/O error during system call, Broken pipe
07-12 17:45:02.582  2855  3013 V NativeCrypto: SSL shutdown failed: ssl=0x98b6fe00: I/O error during system call, Broken pipe
07-12 17:45:02.584  1556  2912 V NativeCrypto: Read error: ssl=0x9a734e00: I/O error during system call, Connection timed out
07-12 17:45:02.585  1556  2912 V NativeCrypto: SSL shutdown failed: ssl=0x9a734e00: I/O error during system call, Broken pipe
07-12 17:45:02.586  1556  2912 E GCM     : Wifi connection closed with errorCode 20
07-12 17:45:02.586   790  3259 D ConnectivityService: reportNetworkConnectivity(100, false) by 10007
07-12 17:45:02.587   790  2782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10007
07-12 17:45:02.588  1556  1556 E ActivityThread: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@3a073e9 that was originally bound here
07-12 17:45:02.588  1556  1556 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@3a073e9 that was originally bound here
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at rbx.run(:com.google.android.gms:94)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:02.588  1556  1556 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:45:02.588   790  2782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-12 17:45:02.589   790   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-12 17:45:02.589   790   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 17:45:02.590   790   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-12 17:45:02.593  3746  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:02.594  2855  2986 V NativeCrypto: Read error: ssl=0x9e477c00: I/O error during system call, Connection timed out
,07-12 17:45:02.594  2855  2986 V NativeCrypto: Write error: ssl=0x9e477c00: I/O error during system call, Broken pipe
07-12 17:45:02.596   790   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-12 17:45:02.597   790   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 5
07-12 17:45:02.597   790   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:02.603   790   893 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-12 17:45:02.604  2855  2986 V NativeCrypto: Write error: ssl=0x9e477c00: I/O error during system call, Broken pipe
07-12 17:45:02.605  2855  2986 V NativeCrypto: SSL shutdown failed: ssl=0x9e477c00: I/O error during system call, Broken pipe
07-12 17:45:02.607   790   790 D RttService: SCAN_AVAILABLE : 1
07-12 17:45:02.607   790   907 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: Failed to unbind NearbyDirect
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: java.lang.IllegalArgumentException: Service not registered: rbs@3a073e9
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at rbr.c(:com.google.android.gms:181)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at rca.run(:com.google.android.gms:1023)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:02.609  1556  3673 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:45:02.610   790   891 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-12 17:45:02.612   790   815 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@61ea26b:true
07-12 17:45:02.613   790   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:02.613   790   891 E native  : do suspend true
07-12 17:45:02.621  3746  3746 D LocalBluetoothProfileManager: Adding local MAP profile
07-12 17:45:02.623  3746  3746 D BluetoothMap: Create BluetoothMap proxy object
07-12 17:45:02.627  3746  3746 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 17:45:02.631  3746  3746 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:02.636   790   892 D WifiService: New client listening to asynchronous messages
,07-12 17:45:02.637   192   784 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:02.641  1792  1881 I bt_hci  : shut_down
,07-12 17:45:02.641  1792  1886 D bt_hwcfg: hw_epilog_process
,07-12 17:45:02.645   790   800 I ActivityManager: Killing 2348:com.google.android.talk/u0a51 (adj 15): empty #17
,07-12 17:45:02.646  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:02.665   192   784 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-12 17:45:02.665   192   784 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:02.666   790   893 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-12 17:45:02.666   790   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:02.668  1792  1886 I bt_vendor: low_power_mode_cb
,07-12 17:45:02.671  1792  1886 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-12 17:45:02.671  1792  1886 I bt_vendor: epilog_cb
07-12 17:45:02.671  1792  1886 I bt_hci  : epilog_finished_callback
,07-12 17:45:02.680   790   815 D Tethering: MasterInitialState.processMessage what=3
,07-12 17:45:02.681   790   891 D DhcpClient: doQuit
07-12 17:45:02.681   790   891 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 17:45:02.682   790  2785 D DhcpClient: onQuitting
,07-12 17:45:02.683  3568  3568 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-12 17:45:02.684  1377  1377 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-12 17:45:02.687  1792  1881 I bt_hci_h4: hal_close
07-12 17:45:02.688  1792  1881 I bt_userial_vendor: device fd = 49 close
07-12 17:45:02.688  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:02.688  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:02.689  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:02.690  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:02.690  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:02.691  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:02.692  1792  1878 D bt_stack_manager: event_shut_down_stack finished.
07-12 17:45:02.692  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:02.692  1792  1877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-12 17:45:02.693  1792  1792 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:02.693  1792  1792 D BtGatt.GattService: Received stop request...Stopping profile...
,07-12 17:45:02.693  1792  1877 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-12 17:45:02.693  1792  1792 D BtGatt.GattService: stop()
07-12 17:45:02.693  1792  1792 D BtGatt.AdvertiseManager: advertise clients cleared
,07-12 17:45:02.695  1792  1792 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:02.695  1792  1792 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:02.695  1792  1792 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:02.695  1792  1792 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:02.695  3746  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:02.695  1792  1877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-12 17:45:02.695  1792  1877 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:02.695  1792  1877 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-12 17:45:02.696  1792  1877 I BluetoothAdapterState: Entering OffState
07-12 17:45:02.696   790   815 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-12 17:45:02.701  3746  3746 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:02.704  1556  1556 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 17:45:02.705  1792  1792 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-12 17:45:02.705  1792  1792 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-12 17:45:02.705  1792  1792 I BluetoothServiceJni: cleanupNative: return from cleanup
07-12 17:45:02.705  1792  1878 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-12 17:45:02.706  1792  1792 I art     : System.exit called, status: 0
07-12 17:45:02.706  1792  1792 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-12 17:45:02.728  1368  1368 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-12 17:45:02.741   790   966 I ActivityManager: Process com.android.bluetooth (pid 1792) has died
07-12 17:45:02.741  1368  1368 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-12 17:45:02.744  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:02.747  1556  3793 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 17:45:02.749  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:02.753  1368  1368 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-12 17:45:02.754   192   784 E Netd    : netlink response contains error (No such file or directory)
07-12 17:45:02.755   790   893 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-12 17:45:02.755   790   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 17:45:02.762   790   800 I ActivityManager: Start proc 3794:com.google.android.talk/u0a51 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-12 17:45:02.769  1556  3793 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-12 17:45:02.808  1368  1368 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-12 17:45:02.812  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:02.812  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:02.812  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:02.828  1368  1368 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-12 17:45:02.930   790   891 D wifi    : In wifi stop Hal
,07-12 17:45:02.930   790   891 D wifi    : halHandle = 0xa0805390, mVM = 0xb4dbc000, mCls = 0x100aee
07-12 17:45:02.930   790  1365 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-12 17:45:02.930   790  1365 D WifiHAL : Got a signal to exit!!!
07-12 17:45:02.930   790  1365 I WifiHAL : Exit wifi_event_loop
07-12 17:45:02.930   790   891 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-12 17:45:02.930   790   891 E WifiHAL : Event processing terminated
,07-12 17:45:02.930   790   891 D wifi    : In wifi cleaned up handler
07-12 17:45:02.930   790   891 I WifiHAL : Internal cleanup completed
07-12 17:45:02.931  1556  1659 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 17:45:02.932  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:02.932  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:03.041   790  1365 D wifi    : set interface wlan0 flags (DOWN)
,07-12 17:45:03.042   790   891 D WifiNative-HAL: HAL event thread stopped successfully
,07-12 17:45:03.090  3794  3794 I Babel_telephony: TeleModule.onApplicationCreate
,07-12 17:45:03.098  3794  3820 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-12 17:45:03.098  3794  3820 I Babel_SMS: MmsConfig.loadMmsSettings
,07-12 17:45:03.099  3794  3820 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-12 17:45:03.099  3794  3820 I Babel_SMS: MmsConfig.loadFromDatabase
,07-12 17:45:03.111  3794  3820 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-12 17:45:03.111  3794  3820 I Babel_SMS: MmsConfig.loadFromResources
,07-12 17:45:03.113  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:03.113  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:03.113  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:03.114  3794  3820 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-12 17:45:03.114  3794  3820 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-12 17:45:03.115  3794  3794 I Babel_Crash: Startup - clean
,07-12 17:45:03.145  3794  3823 I Babel_SMS: ApnsOta: OTA version -1
,07-12 17:45:03.166   790   801 I ActivityManager: Start proc 3826:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-12 17:45:03.187  3826  3826 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-12 17:45:03.218  1556  1701 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 17:45:03.221  3826  3826 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-12 17:45:03.225   790   968 I ActivityManager: Start proc 3841:com.google.android.apps.plus/u0a63 for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver
07-12 17:45:03.225   790   968 I ActivityManager: Killing 2334:com.google.android.keep/u0a52 (adj 15): empty #17
,07-12 17:45:03.244   790   815 D Tethering: InitialState.processMessage what=4
,07-12 17:45:03.264   790   815 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-12 17:45:03.268  3826  3838 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-12 17:45:03.414  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:03.414  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:03.414  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:03.491   790   801 I ActivityManager: Killing 3130:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-12 17:45:03.523  1568  1568 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-12 17:45:03.526  1568  2884 I iu.UploadsManager: num queued entries: 0
,07-12 17:45:03.526  1568  2884 I iu.UploadsManager: num updated entries: 0
,07-12 17:45:03.527  1568  2884 I iu.SyncManager: NEXT; no task
,07-12 17:45:03.536   790  3259 I ActivityManager: Start proc 3866:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 17:45:03.560  3866  3866 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-12 17:45:03.565  3866  3866 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 17:45:03.565  3866  3866 I MultiDex: install
07-12 17:45:03.565  3866  3866 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 17:45:03.604  3866  3866 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-12 17:45:03.604  3866  3866 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:45:03.604  3866  3866 I GAv4    :   adb logcat -s GAv4
,07-12 17:45:03.612  3866  3866 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:03.620  3866  3885 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:03.715  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:03.715  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:03.715  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:03.731  3866  3866 I NSApplication: Starting up...
,07-12 17:45:03.748   790  3259 I ActivityManager: Start proc 3906:com.google.android.apps.photos/u0a83 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 17:45:03.749   790  3259 I ActivityManager: Killing 1922:com.android.providers.calendar/u0a1 (adj 15): empty #17
,07-12 17:45:03.847  1568  1568 V Herrevad: NQAS connected
,07-12 17:45:03.873  1568  1608 W Herrevad: Invalid mccmnc 
,07-12 17:45:03.874  1568  1608 W Herrevad: Invalid mccmnc 
,07-12 17:45:03.902  3866  3866 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-12 17:45:03.997   190   190 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6d0a030
07-12 17:45:03.997   190   190 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
07-12 17:45:03.997   190   190 I rmt_storage: wakelock acquired: 1, error no: 2
07-12 17:45:03.997   190   461 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1227884240)
,07-12 17:45:04.022  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.022  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:04.022  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:04.023  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.023  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at aksp.c(:com.google.android.gms:36)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at akrf.c(:com.google.android.gms:175)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:04.023  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:04.074   190   461 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
07-12 17:45:04.074   190   461 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
07-12 17:45:04.074   190   461 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1227884240) wakelock released: 1, error no: 0
07-12 17:45:04.074   190   461 I rmt_storage: 
,07-12 17:45:04.077   190   190 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6d0a030
,07-12 17:45:04.198   790  1349 I ActivityManager: Killing 3284:com.google.android.gms.feedback/u0a7 (adj 15): empty #17
,07-12 17:45:04.224  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.224  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at aklk.a(:com.google.android.gms:129)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:04.224  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:04.225  1556  3683 W MessageQueue: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.225  1556  3683 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {ee9bf65} sending message to a Handler on a dead thread
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at aksp.d(:com.google.android.gms:44)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akrh.a(:com.google.android.gms:65)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at aklk.a(:com.google.android.gms:130)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:04.225  1556  3683 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:04.228   790   968 I ActivityManager: Start proc 3925:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,07-12 17:45:04.308  3925  3925 W InstanceID/Rpc: Found 10007
,07-12 17:45:04.334   790  3259 I ActivityManager: Killing 3233:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,07-12 17:45:07.500   790   966 D WifiService: setWifiEnabled: true pid=3568, uid=10026
,07-12 17:45:07.500   790   966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:07.511   192   784 D SoftapController: Softap fwReload - Ok
07-12 17:45:07.516   192   784 D CommandListener: Setting iface cfg
07-12 17:45:07.516   192   784 D CommandListener: Trying to bring down wlan0
07-12 17:45:07.519   192   784 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:07.524   790   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:07.774   790   966 I ActivityManager: Killing 3346:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-12 17:45:08.271   790   891 D wifi    : set interface wlan0 flags (UP)
,07-12 17:45:08.271   790   891 I WifiHAL : Initializing wifi
07-12 17:45:08.271   790   891 I WifiHAL : Creating socket
07-12 17:45:08.272   790   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-12 17:45:08.272   790   891 D wifi    : Did set static halHandle = 0xa0805390
07-12 17:45:08.272   790   891 D wifi    : halHandle = 0xa0805390, mVM = 0xb4dbc000, mCls = 0x101aba
07-12 17:45:08.272   790   891 D wifi    : array field set
07-12 17:45:08.272   790   891 I WifiNative-HAL: interface[0] = p2p0
07-12 17:45:08.272   790   891 I WifiNative-HAL: interface[1] = wlan0
,07-12 17:45:08.276  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:08.277   790   815 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-12 17:45:08.277  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:08.277   790  3955 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602202736
07-12 17:45:08.277   790  3955 D wifi    : waitForHalEvents called, vm = 0xb4dbc000, obj = 0x101aba, env = 0x931630a0
07-12 17:45:08.280   790   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 17:45:08.324  3956  3956 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 17:45:08.345  3956  3956 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:08.364  3956  3956 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:08.376  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:08.376  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:08.377  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:08.377  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:08.378   790   891 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:08.382   790   891 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:08.382   790   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-12 17:45:08.383   790   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:08.383   790   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-12 17:45:08.383   790   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 17:45:08.385   790   891 D WifiNative-HAL: Setting external_sim to 1
,07-12 17:45:08.385   790   891 D wifi    : setting dfs flag to true, 0x9cc56450
07-12 17:45:08.385   790   891 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 17:45:08.385   790   891 D wifi    : setting scan oui 0x9cc56450
,07-12 17:45:08.385   790   891 D WifiHAL : Sending mac address OUI
,07-12 17:45:08.401   790   891 E native  : do suspend true
,07-12 17:45:08.405   790   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-12 17:45:08.405   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
07-12 17:45:08.405   790   790 D RttService: SCAN_AVAILABLE : 3
07-12 17:45:08.405   790   907 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 17:45:08.406   192   784 D CommandListener: Setting iface cfg
07-12 17:45:08.406   192   784 D CommandListener: Trying to bring up p2p0
,07-12 17:45:08.406   790   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 17:45:08.411   790   890 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:08.411   790   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-12 17:45:08.561   790   891 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 9, 13 -> obsolete
,07-12 17:45:12.511   790  1226 D WifiService: setWifiEnabled: false pid=3568, uid=10026
,07-12 17:45:12.511   790  1226 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:12.525   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:12.550   790   790 D RttService: SCAN_AVAILABLE : 1
,07-12 17:45:12.550   790   907 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:12.572   790   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:12.572   192   784 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:12.577   790   891 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:12.579  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:12.579  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:12.580  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:12.580  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:12.596  3956  3956 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-12 17:45:13.598  3956  3956 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-12 17:45:13.603  3956  3956 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-12 17:45:13.613  3956  3956 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-12 17:45:13.735  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:13.738  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:13.738  1556  1659 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:13.740   790   891 D wifi    : In wifi stop Hal
07-12 17:45:13.740   790   891 D wifi    : halHandle = 0xa0805390, mVM = 0xb4dbc000, mCls = 0x101aba
07-12 17:45:13.740   790  3955 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-12 17:45:13.740   790  3955 D WifiHAL : Got a signal to exit!!!
07-12 17:45:13.741   790  3955 I WifiHAL : Exit wifi_event_loop
07-12 17:45:13.743   790   891 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-12 17:45:13.747   790   891 E WifiHAL : Event processing terminated
07-12 17:45:13.747   790   891 D wifi    : In wifi cleaned up handler
07-12 17:45:13.747   790   891 I WifiHAL : Internal cleanup completed
,07-12 17:45:13.865   790  3955 D wifi    : set interface wlan0 flags (DOWN)
07-12 17:45:13.865   790   891 D WifiNative-HAL: HAL event thread stopped successfully
,07-12 17:45:14.068   790   815 D Tethering: InitialState.processMessage what=4
,07-12 17:45:14.071   790   815 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-12 17:45:17.584   790   815 I ActivityManager: Start proc 4004:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding A2dpService
07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding HidService
07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding HealthService
07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding PanService
07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding GattService
07-12 17:45:17.627  4004  4004 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 17:45:17.637   790   815 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a96ab01:true
07-12 17:45:17.638  4004  4004 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 17:45:17.640  4004  4004 I bt_bluedroid: init
07-12 17:45:17.640  4004  4016 I BluetoothAdapterState: Entering OffState
,07-12 17:45:17.642  4004  4017 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 17:45:17.642  4004  4017 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:17.642  4004  4017 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:17.642  4004  4017 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 17:45:17.643  4004  4004 I bt_bluedroid: get_profile_interface socket
07-12 17:45:17.644  4004  4004 I bt_bluedroid: get_profile_interface sdp
07-12 17:45:17.645  4004  4014 I bt_bluedroid: config_hci_snoop_log
07-12 17:45:17.646   790   815 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-12 17:45:17.648  4004  4016 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 17:45:17.648  4004  4016 D BluetoothAdapterProperties: Setting state to 14
,07-12 17:45:17.648  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 17:45:17.649  4004  4016 D BluetoothBondStateMachine: make
,07-12 17:45:17.651  4004  4020 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-12 17:45:17.652  4004  4020 D BluetoothAdapterProperties: Name is: Nexus 5
07-12 17:45:17.655  4004  4004 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-12 17:45:17.656  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:17.656  4004  4016 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:17.657  4004  4004 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:17.657  4004  4004 D BtGatt.GattService: Received start request. Starting profile...
07-12 17:45:17.657  4004  4004 D BtGatt.GattService: start()
07-12 17:45:17.657  4004  4004 I bt_bluedroid: get_profile_interface gatt
07-12 17:45:17.658  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:17.658  4004  4004 D BtGatt.AdvertiseManager: advertise manager created
07-12 17:45:17.658  4004  4021 I BluetoothBondStateMachine: StableState(): Entering Off State
07-12 17:45:17.663  4004  4004 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:17.663  4004  4004 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.663  4004  4004 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:17.663  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.663  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:17.663  4004  4016 I bt_bluedroid: enable
07-12 17:45:17.663  4004  4017 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-12 17:45:17.663  4004  4017 I bt_hci  : start_up
07-12 17:45:17.668  4004  4017 I bt_vendor: alloc value 0xb3a76631
07-12 17:45:17.668  4004  4017 I bt_vendor: init
07-12 17:45:17.668  4004  4017 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 17:45:17.668  4004  4017 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 17:45:17.708  4004  4017 D bt_hci  : start_up starting async portion
07-12 17:45:17.709  4004  4024 I bt_hci  : event_finish_startup
07-12 17:45:17.709  4004  4024 I bt_hci_h4: hal_open
07-12 17:45:17.709  4004  4024 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-12 17:45:17.711  4004  4024 I bt_userial_vendor: device fd = 49 open
,07-12 17:45:17.796  4004  4024 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:17.823  4004  4024 D bt_hwcfg: Chipset BCM4335C0
07-12 17:45:17.823  4004  4024 D bt_hwcfg: Target name = [BCM4335C0]
07-12 17:45:17.823  4004  4024 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-12 17:45:18.120  3794  3815 W Babel   : bcq TOOK TOO LONG! (15031ms > 10000ms)
,07-12 17:45:18.126  3794  3817 W Babel   : bcq TOOK TOO LONG! (15030ms > 10000ms)
,07-12 17:45:18.183   790   804 I ActivityManager: Start proc 4026:com.google.android.talk:matchstick/u0a51 for broadcast com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,07-12 17:45:18.200  3794  3825 W Babel   : bcq TOOK TOO LONG! (15052ms > 10000ms)
,07-12 17:45:18.203   790  1224 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-12 17:45:18.211  3794  3794 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-12 17:45:18.212  3794  3794 W Babel   : BAM#gBA: invalid account id: -1
07-12 17:45:18.212  3794  3794 W Babel   : BAM#gBA: invalid account id: -1
07-12 17:45:18.212  3794  3794 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-12 17:45:18.216   790   966 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-12 17:45:18.252  4004  4024 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-12 17:45:18.253  4004  4024 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:18.253  4004  4024 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:18.368  4004  4024 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-12 17:45:18.368  4004  4024 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-12 17:45:18.399  4004  4024 I bt_hwcfg: vendor lib fwcfg completed
07-12 17:45:18.399  4004  4024 I bt_vendor: firmware callback
07-12 17:45:18.399  4004  4024 I bt_hci  : firmware_config_callback
07-12 17:45:18.401  4004  4048 I bt_btu  : btu_task pending for preload complete event
07-12 17:45:18.401  4004  4048 I bt_btu_task: Bluetooth chip preload is complete
07-12 17:45:18.401  4004  4048 I bt_btu  : btu_task received preload complete event
,07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 17:45:18.402  4004  4048 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 17:45:18.403  4004  4048 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 17:45:18.403  4004  4048 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 17:45:18.403  4004  4048 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 17:45:18.403  4004  4048 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 17:45:18.403  4004  4048 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 17:45:18.403  4004  4048 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:18.539  4026  4051 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService } isPeriodic:false
,07-12 17:45:18.579  4026  4051 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 17:45:18.599  4026  4051 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-12 17:45:18.599  4026  4051 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
07-12 17:45:18.602  4026  4051 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 17:45:18.617  4004  4048 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f49b5
,07-12 17:45:18.617  4004  4048 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f49b5 
,07-12 17:45:18.661  4026  4051 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 17:45:18.662  4026  4051 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,07-12 17:45:18.663  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:18.663  4004  4020 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-12 17:45:18.665  4004  4020 D BluetoothAdapterProperties: Name is: Nexus 5
07-12 17:45:18.668  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:18.669  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:18.669  4004  4020 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:18.669  4004  4020 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:18.670  4004  4020 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-12 17:45:18.671  4004  4020 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-12 17:45:18.671  4004  4020 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-12 17:45:18.671  4004  4020 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-12 17:45:18.671  4004  4020 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-12 17:45:18.672  4004  4020 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-12 17:45:18.672  4004  4020 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
,07-12 17:45:18.674  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-12 17:45:18.678  4004  4004 I BluetoothHidServiceJni: classInitNative: succeeds
07-12 17:45:18.678  4004  4004 D HidService: getHidService(): service is NULL
07-12 17:45:18.681   790  2092 I ActivityManager: Killing 3373:com.android.musicfx/u0a13 (adj 15): empty #17
,07-12 17:45:18.701  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,07-12 17:45:18.701  4004  4004 D HidService: getHidService(): service is NULL
,07-12 17:45:18.703  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,07-12 17:45:18.703  4004  4004 D HidService: getHidService(): service is NULL
07-12 17:45:18.705  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-12 17:45:18.706  4004  4004 D HidService: getHidService(): service is NULL
07-12 17:45:18.708  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-12 17:45:18.709  4004  4004 D HidService: getHidService(): service is NULL
,07-12 17:45:18.711  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,07-12 17:45:18.712  4004  4004 D HidService: getHidService(): service is NULL
,07-12 17:45:18.715  4004  4020 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-12 17:45:18.717  4004  4004 D HidService: getHidService(): service is NULL
,07-12 17:45:18.718  4004  4020 D bt_hci  : do_postload posting postload work item
,07-12 17:45:18.718  4004  4024 I bt_hci  : event_postload
07-12 17:45:18.718  4004  4024 I bt_vendor: sco_config_cb
07-12 17:45:18.718  4004  4024 I bt_hci  : sco_config_callback postload finished.
07-12 17:45:18.719  4004  4024 I bt_vendor: low_power_mode_cb
,07-12 17:45:18.720   932  1145 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:18.720   932  1145 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-12 17:45:18.723  4004  4020 D bt_bte_conf: Device ID record 1 : primary
,07-12 17:45:18.723  4004  4020 D bt_bte_conf:   vendorId            = 000f
07-12 17:45:18.723  4004  4020 D bt_bte_conf:   vendorIdSource      = 0001
07-12 17:45:18.723  4004  4020 D bt_bte_conf:   product             = 1200
07-12 17:45:18.723  4004  4020 D bt_bte_conf:   version             = 1436
07-12 17:45:18.723  4004  4020 D bt_bte_conf:   clientExecutableURL = 
07-12 17:45:18.723  4004  4020 D bt_bte_conf:   serviceDescription  = 
,07-12 17:45:18.723  4004  4020 D bt_bte_conf:   documentationURL    = 
07-12 17:45:18.723  4004  4020 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 17:45:18.723  4004  4017 D bt_stack_manager: event_start_up_stack finished
07-12 17:45:18.723  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 17:45:18.723  4004  4016 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:18.723  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-12 17:45:18.724  4004  4016 I BluetoothAdapterState: Entering BleOnState
,07-12 17:45:18.725  4004  4016 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 17:45:18.725  4004  4016 D BluetoothAdapterProperties: Setting state to 11
,07-12 17:45:18.725  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 17:45:18.728  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
,07-12 17:45:18.730  4004  4004 D HeadsetService: Received start request. Starting profile...
,07-12 17:45:18.731  4004  4004 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 17:45:18.731  4004  4004 D HeadsetStateMachine: make
,07-12 17:45:18.744  4004  4004 D HeadsetStateMachine: max_hf_connections = 1
,07-12 17:45:18.744  4004  4004 I bt_bluedroid: get_profile_interface handsfree
,07-12 17:45:18.744  4004  4016 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:18.745  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 17:45:18.745  4004  4020 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
,07-12 17:45:18.750  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
,07-12 17:45:18.750  4004  4004 D A2dpService: Received start request. Starting profile...
07-12 17:45:18.751  4004  4004 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:18.751  4004  4004 I bt_bluedroid: get_profile_interface avrcp
,07-12 17:45:18.761  4004  4004 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 17:45:18.761  4004  4004 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-12 17:45:18.761  4004  4004 D A2dpStateMachine: make
07-12 17:45:18.761   932  1145 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:18.762   932  1145 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:18.762  4004  4004 I bt_bluedroid: get_profile_interface a2dp
,07-12 17:45:18.763  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-12 17:45:18.765  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:18.767  4004  4074 D A2dpStateMachine: Enter Disconnected: -2
07-12 17:45:18.767  4004  4004 D HidService: Received start request. Starting profile...
07-12 17:45:18.767  4004  4004 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:18.767  4004  4020 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d6099
07-12 17:45:18.767  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 17:45:18.767  4004  4004 D HidService: setHidService(): set to: null
07-12 17:45:18.768  4004  4004 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 17:45:18.768  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:18.768  4004  4004 D HealthService: Received start request. Starting profile...
07-12 17:45:18.769  4004  4004 I bt_bluedroid: get_profile_interface health
,07-12 17:45:18.771  4004  4004 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 17:45:18.771  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:18.772  4004  4004 D PanService: Received start request. Starting profile...
07-12 17:45:18.772  4004  4004 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:18.772  4004  4004 I bt_bluedroid: get_profile_interface pan
07-12 17:45:18.773  4004  4004 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:18.773  4004  4004 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:18.773  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:18.773  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:18.773  4004  4020 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 17:45:18.775  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
,07-12 17:45:18.776  4004  4004 D BluetoothMapService: Received start request. Starting profile...
07-12 17:45:18.776  4004  4004 D BluetoothMapService: start()
07-12 17:45:18.779  4004  4004 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-12 17:45:18.779  4004  4004 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-12 17:45:18.779  4004  4004 D BluetoothMapAppObserver: createReceiver()
,07-12 17:45:18.780  4004  4004 D BluetoothMapAppObserver: initObservers()
07-12 17:45:18.780  4004  4004 D BluetoothMapAppObserver: getEnabledAccountItems()
07-12 17:45:18.784  4004  4068 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:18.786  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:18.787  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:18.788  4004  4004 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:18.788  4004  4004 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:18.788  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:18.788  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:18.788  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-12 17:45:18.788  4004  4016 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:18.788  4004  4016 D BluetoothAdapterProperties: State =  11
07-12 17:45:18.789  4004  4020 D BluetoothAdapterProperties: Scan Mode:21
07-12 17:45:18.789  4004  4020 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:18.789  4004  4016 D BluetoothAdapterProperties: Setting state to 12
07-12 17:45:18.789  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 17:45:18.789   790   815 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:18.789   790   815 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:18.789   790   815 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:18.790  4004  4016 I BluetoothAdapterState: Entering OnState
07-12 17:45:18.790  3746  3758 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:18.790  3746  3746 D BluetoothInputDevice: Proxy object connected
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:18.792  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:18.794  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:18.796  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:18.797  3746  3746 D HidProfile: Bluetooth service connected
07-12 17:45:18.798  3746  3789 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:18.801  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:18.802   932  1395 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:18.803  3746  3746 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:18.804   932   932 D BluetoothInputDevice: Proxy object connected
,07-12 17:45:18.804   932   932 D HidProfile: Bluetooth service connected
07-12 17:45:18.804  4004  4004 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 17:45:18.805  4004  4004 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 17:45:18.805  1304  1430 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:18.806  4004  4004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:18.807   932   943 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:18.808  4004  4004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:18.809  4004  4004 D ObexServerSockets: Succeed to create listening sockets 
07-12 17:45:18.809  4004  4004 D ObexServerSockets0: startAccept()
07-12 17:45:18.809  4004  4004 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:18.810   932   951 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:18.811   932   932 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:18.811   932   932 D PanProfile: Bluetooth service connected
07-12 17:45:18.811   790   815 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:18.812  3746  3789 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:18.813  4004  4004 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-12 17:45:18.813  4004  4004 D BluetoothSdpJni: SDP Create record success - handle: 0
07-12 17:45:18.813  3746  3746 D PanProfile: Bluetooth service connected
,07-12 17:45:18.813   932   943 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:18.813   790   790 D BluetoothA2dp: Proxy object connected
07-12 17:45:18.815   932   932 D BluetoothA2dp: Proxy object connected
,07-12 17:45:18.815  4004  4083 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:18.816  4004  4084 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:18.816  3746  3746 D BluetoothMap: Proxy object connected
07-12 17:45:18.816  3746  3758 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:18.816   932   951 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:18.817   932  1395 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:18.817  3746  3746 D MapProfile: Bluetooth service connected
07-12 17:45:18.817  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.818   932   932 D BluetoothMap: Proxy object connected
07-12 17:45:18.818   932   932 D MapProfile: Bluetooth service connected
07-12 17:45:18.818   932   932 D BluetoothMap: getConnectedDevices()
07-12 17:45:18.819   790   790 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 17:45:18.821  4004  4004 D BluetoothMapService: onReceive
07-12 17:45:18.821  4004  4004 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:18.821  4004  4004 D BluetoothMapService: STATE_ON
07-12 17:45:18.822  3746  3746 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 17:45:18.825  3746  3746 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 17:45:18.840  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.841  4004  4004 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 17:45:18.841  4004  4004 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:18.841  3746  3746 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
07-12 17:45:18.842  3746  3746 D MapProfile: getConnectionStatus: status is: 0
07-12 17:45:18.846  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:18.850  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:18.864  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.865  3746  3746 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-12 17:45:18.867  3746  3746 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.876  1556  1556 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-12 17:45:18.879  1556  1556 I BeaconBle: BLE 'JB+' software access layer enabled
,07-12 17:45:18.879   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.886   932  1145 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
07-12 17:45:18.887  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.889   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.893   790   790 D BluetoothHeadset: Proxy object connected
07-12 17:45:18.893  3746  3746 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-12 17:45:18.893   932  1395 D BluetoothHeadset: Proxy object connected
07-12 17:45:18.894  1304  1329 D BluetoothHeadset: Proxy object connected
07-12 17:45:18.894   790   790 D BluetoothHeadset: Proxy object connected
,07-12 17:45:18.894   790   790 D BluetoothHeadset: Proxy object connected
,07-12 17:45:18.895  3746  3746 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.896  1556  4097 D BluetoothAdapter: startLeScan(): null
,07-12 17:45:18.896   932   932 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:18.898  1556  4097 D BluetoothAdapter: STATE_ON
,07-12 17:45:18.901  4004  4099 D BtGatt.GattService: registerClient() - UUID=1db5077b-e313-4045-abc5-25f17a5b7c1e
,07-12 17:45:18.901  4004  4020 D BtGatt.GattService: onClientRegistered() - UUID=1db5077b-e313-4045-abc5-25f17a5b7c1e, clientIf=5
07-12 17:45:18.902  1556  1628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:18.902  4004  4014 D BtGatt.GattService: start scan with filters
,07-12 17:45:18.905  4004  4023 D BtGatt.ScanManager: handling starting scan
,07-12 17:45:18.906  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-12 17:45:18.906  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 17:45:18.906  1304  1316 D BluetoothHeadset: Proxy object connected
07-12 17:45:18.906  4004  4023 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 17:45:18.907  4004  4020 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 17:45:18.908  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.909  3746  3746 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
07-12 17:45:18.909  3746  3746 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.915  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.916  3746  3746 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-12 17:45:18.917  3746  3746 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.918   932   951 D BluetoothHeadset: Proxy object connected
,07-12 17:45:18.923  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.923   932  1145 D BluetoothMap: getConnectedDevices()
07-12 17:45:18.923  3746  3746 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-12 17:45:18.925  3746  3746 D MapProfile: getConnectionStatus: status is: 0
07-12 17:45:18.925   932  1145 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-12 17:45:18.927   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.928  3746  3757 D BluetoothHeadset: Proxy object connected
,07-12 17:45:18.931   932   932 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:18.932  3746  3746 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.933  3746  3746 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-12 17:45:18.934  3746  3746 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.934  3746  3746 D BluetoothA2dp: Proxy object connected
,07-12 17:45:18.937  3746  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:18.939  3746  3746 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:18.946   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.947  4004  4100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:18.948   932  1145 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-12 17:45:18.949  3746  3746 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:18.952   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.955   932   932 D BluetoothPbap: Proxy object connected
07-12 17:45:18.955   932   932 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:18.962  3746  3746 D BluetoothPbap: Proxy object connected
,07-12 17:45:18.962  3746  3746 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:18.965  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:18.968  1556  4104 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 17:45:18.978  4004  4108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:18.979  4004  4108 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:18.979   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:18.980   932  1145 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-12 17:45:18.981   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:18.985  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:18.994  1556  4104 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 17:45:19.004   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:19.004   932  1145 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-12 17:45:19.005   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:19.178  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Sluchawki Bose len=14 dev_type=3
,07-12 17:45:19.396  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:19.428  1556  4069 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:19.430  1556  4069 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: java.io.IOException: Not connected
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:19.430  1556  4069 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:19.568  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:19.665  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:19.752  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:20.324  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:20.416  1556  4097 D BluetoothAdapter: stopLeScan()
,07-12 17:45:20.420  1556  4097 D BluetoothAdapter: STATE_ON
,07-12 17:45:20.421  4004  4014 D BtGatt.GattService: stopScan() - queue size =1
,07-12 17:45:20.423  4004  4023 D BtGatt.ScanManager: stop scan
,07-12 17:45:20.423  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-12 17:45:20.423  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
,07-12 17:45:20.424  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-12 17:45:20.433  4004  4098 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:20.499  1556  4069 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:20.504  1556  4069 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: java.io.IOException: Not connected
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at reh.run(:com.google.android.gms:75)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:20.504  1556  4069 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:20.624  1556  4097 D BluetoothAdapter: startLeScan(): null
,07-12 17:45:20.629  1556  4097 D BluetoothAdapter: STATE_ON
07-12 17:45:20.640  4004  4015 D BtGatt.GattService: registerClient() - UUID=bc32e419-f7f3-4325-8a78-c3e783ca6f72
07-12 17:45:20.641  4004  4020 D BtGatt.GattService: onClientRegistered() - UUID=bc32e419-f7f3-4325-8a78-c3e783ca6f72, clientIf=5
07-12 17:45:20.642  1556  1629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:20.643  4004  4014 D BtGatt.GattService: start scan with filters
07-12 17:45:20.652  4004  4023 D BtGatt.ScanManager: handling starting scan
07-12 17:45:20.688  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-12 17:45:20.688  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
,07-12 17:45:20.728  4004  4023 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 17:45:20.728  4004  4020 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 17:45:20.830  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Sluchawki Bose len=14 dev_type=3
,07-12 17:45:20.890  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:21.303  4004  4020 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:21.931  1556  4097 D BluetoothAdapter: stopLeScan()
,07-12 17:45:21.935  1556  4097 D BluetoothAdapter: STATE_ON
07-12 17:45:21.937  4004  4096 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:21.938  4004  4023 D BtGatt.ScanManager: stop scan
07-12 17:45:21.939  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 17:45:21.939  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 17:45:21.939  4004  4023 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 17:45:21.962  4004  4099 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:21.962  1556  4097 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 17:45:22.536  4004  4016 D BluetoothAdapterState: Current state: ON, message: 23
,07-12 17:45:22.537  4004  4016 D BluetoothAdapterProperties: Setting state to 13
07-12 17:45:22.537  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-12 17:45:22.538  4004  4016 D BluetoothAdapterProperties: onBluetoothDisable()
07-12 17:45:22.561  4004  4016 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:22.576  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:22.581  4004  4020 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:22.582  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:22.583  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:22.583  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:22.584  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:22.586  4004  4004 D HeadsetService: Received stop request...Stopping profile...
07-12 17:45:22.587  4004  4004 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:22.587  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:22.587  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.587  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:22.588  4004  4004 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:22.588  4004  4004 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:22.589  4004  4048 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:22.589  4004  4048 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:22.607  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-12 17:45:22.608  4004  4020 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-12 17:45:22.608   790   790 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:22.608   932   951 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:22.608   932   932 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:22.608  3746  3757 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:22.609  1304  1430 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:22.609   790   790 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:22.609   790   790 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:22.610  4004  4004 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:22.610  4004  4074 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:22.611   932   932 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:22.611  4004  4004 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:22.612  4004  4004 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:22.612  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.612  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:22.612  4004  4048 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:22.612  4004  4048 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:22.627  4004  4048 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-12 17:45:22.627  4004  4048 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:22.628  4004  4048 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:22.628  4004  4048 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:22.628  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-12 17:45:22.668   790   790 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:22.673  4004  4004 D HidService: Received stop request...Stopping profile...
07-12 17:45:22.673  4004  4004 D HidService: Stopping Bluetooth HidService
07-12 17:45:22.674   932   932 D BluetoothInputDevice: Proxy object disconnected
,07-12 17:45:22.674   932   932 D HidProfile: Bluetooth service disconnected
07-12 17:45:22.675  4004  4004 D BluetoothMapService: onReceive
07-12 17:45:22.675  4004  4004 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:22.675  4004  4004 D BluetoothMapService: STATE_TURNING_OFF
,07-12 17:45:22.675  4004  4004 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:22.675  4004  4004 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:22.675  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.675  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:22.675  4004  4004 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-12 17:45:22.675  4004  4004 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:22.675  4004  4004 D BluetoothMapService: MAP Service closeService in
07-12 17:45:22.675  4004  4004 D BluetoothMapMasInstance0: MAP Service shutdown
,07-12 17:45:22.675  4004  4004 D ObexServerSockets0: shutdown(block = true)
,07-12 17:45:22.675  4004  4083 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-12 17:45:22.676  4004  4020 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:22.676  4004  4004 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:22.676  4004  4084 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-12 17:45:22.677  4004  4064 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-12 17:45:22.677  4004  4004 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:22.677  4004  4004 I BtOppRfcommListener: stopping Accept Thread
,07-12 17:45:22.677  4004  4108 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-12 17:45:22.677  4004  4108 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:22.687  3746  3746 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:22.691  3746  3746 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:22.693  4004  4004 D HealthService: Received stop request...Stopping profile...
07-12 17:45:22.699  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-12 17:45:22.699  4004  4004 D PanService: Received stop request...Stopping profile...
07-12 17:45:22.700   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-12 17:45:22.702  4004  4004 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:22.702  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:22.702  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.702  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:22.702  4004  4004 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:22.702  1556  1556 E ActivityThread: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@388d051 that was originally bound here
07-12 17:45:22.702  1556  1556 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@388d051 that was originally bound here
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at rbx.run(:com.google.android.gms:94)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.702  1556  1556 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:45:22.702  4004  4020 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:22.703  4004  4004 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-12 17:45:22.704  4004  4004 D BluetoothMapService: Received stop request...Stopping profile...
07-12 17:45:22.704  4004  4004 D BluetoothMapService: stop()
,07-12 17:45:22.704  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-12 17:45:22.705  4004  4004 D BluetoothMapAppObserver: deinitObservers()
07-12 17:45:22.705  4004  4004 D BluetoothMapAppObserver: removeReceiver()
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: Failed to unbind NearbyDirect
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: java.lang.IllegalArgumentException: Service not registered: rbs@388d051
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at rbr.c(:com.google.android.gms:181)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at rca.run(:com.google.android.gms:1023)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.706  1556  4069 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:22.707   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-12 17:45:22.708  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
,07-12 17:45:22.709  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-12 17:45:22.709   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
,07-12 17:45:22.710  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-12 17:45:22.711   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-12 17:45:22.711  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-12 17:45:22.713  3746  3746 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-12 17:45:22.713   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-12 17:45:22.714  3746  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:22.715   932   932 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:22.715   932   932 D PanProfile: Bluetooth service disconnected
,07-12 17:45:22.716  3746  3746 D BluetoothInputDevice: Proxy object disconnected
,07-12 17:45:22.716  3746  3746 D HidProfile: Bluetooth service disconnected
07-12 17:45:22.716  3746  3746 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:22.716  3746  3746 D PanProfile: Bluetooth service disconnected
07-12 17:45:22.716   932   932 D BluetoothMap: Proxy object disconnected
07-12 17:45:22.716   932   932 D MapProfile: Bluetooth service disconnected
07-12 17:45:22.717  4004  4004 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:22.717  4004  4004 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:22.717  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.717  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:22.717  4004  4004 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-12 17:45:22.717  4004  4004 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:22.717  4004  4004 D BluetoothMapService: MAP Service closeService in
07-12 17:45:22.718  4004  4004 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:22.718  4004  4004 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:22.718  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.718  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:22.718   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
07-12 17:45:22.718  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-12 17:45:22.718  4004  4016 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:22.718  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:22.718   790   815 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:22.718   790   815 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:22.718   790   815 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:22.719  3746  3758 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:22.719  4004  4004 D BluetoothMapService: cleanup()
07-12 17:45:22.719  4004  4004 D BluetoothMapService: MAP Service closeService in
07-12 17:45:22.719  4004  4016 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:22.720   932   932 D BluetoothPbap: Proxy object disconnected
07-12 17:45:22.720   932   932 D PbapServerProfile: Bluetooth service disconnected
07-12 17:45:22.721  3746  3789 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:22.721  3746  3746 D DockEventReceiver: finishStartingService: stopping service
07-12 17:45:22.723   932   951 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:22.723  1304  1329 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:22.723   932  1395 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:22.724   932  1145 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-12 17:45:22.724   932   943 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:22.724   790   815 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:22.724  3746  3758 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:22.724   932   951 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:22.725  3746  3757 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:22.725   932  1395 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:22.725  3746  3789 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:22.726   932   943 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:22.726  3746  3758 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:22.726  4004  4016 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:22.726  4004  4016 D BluetoothAdapterProperties: Setting state to 16
07-12 17:45:22.726  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:22.727  4004  4016 D BluetoothAdapterProperties: onBleDisable
07-12 17:45:22.727  4004  4016 I BluetoothAdapterState: Ent,ering PendingCommandState
07-12 17:45:22.727  4004  4017 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:22.728  4004  4048 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-12 17:45:22.728  4004  4048 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:22.729  4004  4020 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:22.732  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:22.733  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:22.738  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:22.828  4004  4020 I bt_hci  : shut_down
07-12 17:45:22.828  4004  4024 D bt_hwcfg: hw_epilog_process
,07-12 17:45:22.831  4004  4024 I bt_vendor: low_power_mode_cb
,07-12 17:45:22.835  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:22.838  3746  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:22.845  3746  3746 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:22.851  4004  4024 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-12 17:45:22.851  4004  4024 I bt_vendor: epilog_cb
07-12 17:45:22.851  4004  4024 I bt_hci  : epilog_finished_callback
,07-12 17:45:22.856  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:22.856  4004  4020 I bt_hci_h4: hal_close
07-12 17:45:22.856  4004  4020 I bt_userial_vendor: device fd = 49 close
,07-12 17:45:22.861  1556  4174 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-12 17:45:22.861  4004  4017 D bt_stack_manager: event_shut_down_stack finished.
,07-12 17:45:22.862  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-12 17:45:22.863  4004  4016 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-12 17:45:22.863  4004  4004 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:22.863  4004  4004 D BtGatt.GattService: Received stop request...Stopping profile...
,07-12 17:45:22.863  4004  4004 D BtGatt.GattService: stop()
07-12 17:45:22.863  4004  4004 D BtGatt.AdvertiseManager: advertise clients cleared
07-12 17:45:22.863  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-12 17:45:22.866  4004  4004 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:22.866  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:22.866  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:22.866  4004  4004 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:22.866  4004  4016 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-12 17:45:22.866  4004  4016 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:22.866  4004  4016 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-12 17:45:22.867   790   815 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-12 17:45:22.867  4004  4016 I BluetoothAdapterState: Entering OffState
,07-12 17:45:22.871  1556  4174 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-12 17:45:22.872  4004  4004 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-12 17:45:22.872  4004  4004 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-12 17:45:22.872  4004  4017 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-12 17:45:22.872  4004  4004 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-12 17:45:22.874  4004  4004 I art     : System.exit called, status: 0
,07-12 17:45:22.874  4004  4004 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-12 17:45:22.875  1556  1556 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 17:45:22.898   790  1347 I ActivityManager: Process com.android.bluetooth (pid 4004) has died
,07-12 17:45:22.989  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:22.989  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.989  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:23.293  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:23.293  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:23.293  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:23.595  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:23.595  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:23.595  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:23.897  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:23.897  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:23.897  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:24.203  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.203  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:24.203  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:24.205  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.205  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at aksp.c(:com.google.android.gms:36)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at akrf.c(:com.google.android.gms:175)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:24.205  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:24.412  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.412  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at aklk.a(:com.google.android.gms:129)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:24.412  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:24.414  1556  4093 W MessageQueue: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.414  1556  4093 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e7668ab} sending message to a Handler on a dead thread
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at aksp.d(:com.google.android.gms:44)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akrh.a(:com.google.android.gms:65)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at aklk.a(:com.google.android.gms:130)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:24.414  1556  4093 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:27.534  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:27.535  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:27.542  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:27.542  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce40c70 added. We now have 6 listener(s)
07-12 17:45:27.542  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:27.545  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:27.545  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7839be9 added. We now have 7 listener(s)
,07-12 17:45:27.545  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:27.547  3568  3641 I System.out: IsBluetoothEnabled
,07-12 17:45:27.558  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:27.597   790   815 I ActivityManager: Start proc 4187:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 17:45:27.649  4187  4187 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:27.649  4187  4187 D AdapterServiceConfig: Adding A2dpService
07-12 17:45:27.650  4187  4187 D AdapterServiceConfig: Adding HidService
07-12 17:45:27.650  4187  4187 D AdapterServiceConfig: Adding HealthService
07-12 17:45:27.650  4187  4187 D AdapterServiceConfig: Adding PanService
07-12 17:45:27.650  4187  4187 D AdapterServiceConfig: Adding GattService
07-12 17:45:27.650  4187  4187 D AdapterServiceConfig: Adding BluetoothMapService
07-12 17:45:27.658   790   815 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@173ac52:true
,07-12 17:45:27.659  4187  4187 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 17:45:27.661  4187  4187 I bt_bluedroid: init
07-12 17:45:27.661  4187  4214 I BluetoothAdapterState: Entering OffState
,07-12 17:45:27.663  4187  4215 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 17:45:27.663  4187  4215 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:27.663  4187  4215 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:27.663  4187  4215 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-12 17:45:27.664  4187  4187 I bt_bluedroid: get_profile_interface socket
,07-12 17:45:27.665  4187  4187 I bt_bluedroid: get_profile_interface sdp
,07-12 17:45:27.666  4187  4218 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-12 17:45:27.667  4187  4218 D BluetoothAdapterProperties: Name is: Nexus 5
,07-12 17:45:27.669  4187  4198 I bt_bluedroid: config_hci_snoop_log
07-12 17:45:27.670   790   815 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-12 17:45:27.673  4187  4214 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 17:45:27.673  4187  4214 D BluetoothAdapterProperties: Setting state to 14
07-12 17:45:27.673  4187  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 17:45:27.675  4187  4214 D BluetoothBondStateMachine: make
,07-12 17:45:27.677  4187  4224 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 17:45:27.679  4187  4214 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:27.680  4187  4187 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 17:45:27.683  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:27.683  4187  4187 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:27.684  4187  4187 D BtGatt.GattService: Received start request. Starting profile...
,07-12 17:45:27.684  4187  4187 D BtGatt.GattService: start()
07-12 17:45:27.684  4187  4187 I bt_bluedroid: get_profile_interface gatt
07-12 17:45:27.684  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:27.684  4187  4187 D BtGatt.AdvertiseManager: advertise manager created
,07-12 17:45:27.689  4187  4187 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:27.689  4187  4187 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:27.689  4187  4187 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:27.689  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:27.690  4187  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:27.690  4187  4214 I bt_bluedroid: enable
07-12 17:45:27.690  4187  4215 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 17:45:27.690  4187  4215 I bt_hci  : start_up
,07-12 17:45:27.695  4187  4215 I bt_vendor: alloc value 0xb3a76631
,07-12 17:45:27.695  4187  4215 I bt_vendor: init
07-12 17:45:27.695  4187  4215 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 17:45:27.695  4187  4215 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 17:45:27.728  4187  4215 D bt_hci  : start_up starting async portion
,07-12 17:45:27.729  4187  4227 I bt_hci  : event_finish_startup
07-12 17:45:27.729  4187  4227 I bt_hci_h4: hal_open
07-12 17:45:27.729  4187  4227 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-12 17:45:27.732  4187  4227 I bt_userial_vendor: device fd = 49 open
,07-12 17:45:27.816  4187  4227 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:27.843  4187  4227 D bt_hwcfg: Chipset BCM4335C0
,07-12 17:45:27.843  4187  4227 D bt_hwcfg: Target name = [BCM4335C0]
07-12 17:45:27.843  4187  4227 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-12 17:45:28.329  4187  4227 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 17:45:28.330  4187  4227 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:28.330  4187  4227 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:28.448  4187  4227 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:28.448  4187  4227 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-12 17:45:28.476  4187  4227 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:28.476  4187  4227 I bt_vendor: firmware callback
07-12 17:45:28.476  4187  4227 I bt_hci  : firmware_config_callback
,07-12 17:45:28.489  4187  4239 I bt_btu  : btu_task pending for preload complete event
,07-12 17:45:28.489  4187  4239 I bt_btu_task: Bluetooth chip preload is complete
,07-12 17:45:28.489  4187  4239 I bt_btu  : btu_task received preload complete event
,07-12 17:45:28.497  4187  4239 I         : BTE_InitTraceLevels -- TRC_HCI
07-12 17:45:28.497  4187  4239 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-12 17:45:28.497  4187  4239 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_BTM
,07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_PAN
,07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_SDP
,07-12 17:45:28.498  4187  4239 I         : BTE_InitTraceLevels -- TRC_GATT
,07-12 17:45:28.499  4187  4239 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 17:45:28.499  4187  4239 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 17:45:28.499  4187  4239 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:28.720  4187  4239 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f49b5
,07-12 17:45:28.720  4187  4239 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f49b5 
,07-12 17:45:28.859  4187  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:28.859  4187  4218 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-12 17:45:28.885  4187  4218 D BluetoothAdapterProperties: Name is: Nexus 5
07-12 17:45:28.888  4187  4218 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:28.888  4187  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:28.889  4187  4218 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
,07-12 17:45:28.889  4187  4218 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-12 17:45:28.890  4187  4218 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-12 17:45:28.890  4187  4218 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-12 17:45:28.890  4187  4218 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-12 17:45:28.890  4187  4218 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-12 17:45:28.891  4187  4218 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-12 17:45:28.891  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:28.892  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,07-12 17:45:28.894  4187  4187 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 17:45:28.895  4187  4187 D HidService: getHidService(): service is NULL
,07-12 17:45:28.897  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,07-12 17:45:28.899  4187  4187 D HidService: getHidService(): service is NULL
,07-12 17:45:28.902  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-12 17:45:28.903  4187  4187 D HidService: getHidService(): service is NULL
07-12 17:45:28.903  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-12 17:45:28.905  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,07-12 17:45:28.906  4187  4187 D HidService: getHidService(): service is NULL
07-12 17:45:28.908  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.908  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-12 17:45:28.909  4187  4187 D HidService: getHidService(): service is NULL
07-12 17:45:28.911  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-12 17:45:28.911  4187  4187 D HidService: getHidService(): service is NULL
07-12 17:45:28.912  4187  4218 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-12 17:45:28.913  4187  4187 D HidService: getHidService(): service is NULL
,07-12 17:45:28.913  4187  4218 D bt_hci  : do_postload posting postload work item
07-12 17:45:28.913  4187  4227 I bt_hci  : event_postload
07-12 17:45:28.913  4187  4227 I bt_vendor: sco_config_cb
07-12 17:45:28.913  4187  4227 I bt_hci  : sco_config_callback postload finished.
07-12 17:45:28.915  4187  4227 I bt_vendor: low_power_mode_cb
07-12 17:45:28.915  4187  4218 D bt_bte_conf: Device ID record 1 : primary
07-12 17:45:28.915  4187  4218 D bt_bte_conf:   vendorId            = 000f
07-12 17:45:28.915  4187  4218 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 17:45:28.915  4187  4218 D bt_bte_conf:   product             = 1200
07-12 17:45:28.915  4187  4218 D bt_bte_conf:   version             = 1436
07-12 17:45:28.915  4187  4218 D bt_bte_conf:   clientExecutableURL = 
07-12 17:45:28.915  4187  4218 D bt_bte_conf:   serviceDescription  = 
07-12 17:45:28.915  4187  4218 D bt_bte_conf:   documentationURL    = 
,07-12 17:45:28.915  4187  4218 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 17:45:28.915  4187  4215 D bt_stack_manager: event_start_up_stack finished
07-12 17:45:28.915  4187  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 17:45:28.915  4187  4214 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:28.915  4187  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 17:45:28.916  4187  4214 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:28.917  4187  4214 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 17:45:28.917  4187  4214 D BluetoothAdapterProperties: Setting state to 11
07-12 17:45:28.917  4187  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-12 17:45:28.918  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-12 17:45:28.919  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
,07-12 17:45:28.919  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.922  4187  4187 D HeadsetService: Received start request. Starting profile...
,07-12 17:45:28.922  4187  4187 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 17:45:28.922  4187  4187 D HeadsetStateMachine: make
07-12 17:45:28.928  4187  4214 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:28.928  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.928  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.929  4187  4187 D HeadsetStateMachine: max_hf_connections = 1
07-12 17:45:28.929  4187  4187 I bt_bluedroid: get_profile_interface handsfree
07-12 17:45:28.929  4187  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 17:45:28.929  4187  4218 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-12 17:45:28.931  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:28.932  4187  4187 D A2dpService: Received start request. Starting profile...
07-12 17:45:28.932  4187  4187 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:28.932  4187  4187 I bt_bluedroid: get_profile_interface avrcp
07-12 17:45:28.934  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.934  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-12 17:45:28.937  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.937  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.937  4187  4187 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-12 17:45:28.937  4187  4187 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 17:45:28.937  4187  4187 D A2dpStateMachine: make
07-12 17:45:28.938  4187  4187 I bt_bluedroid: get_profile_interface a2dp
07-12 17:45:28.940  4187  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-12 17:45:28.941  4187  4264 D A2dpStateMachine: Enter Disconnected: -2
07-12 17:45:28.941  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:28.942  4187  4187 D HidService: Received start request. Starting profile...
07-12 17:45:28.942  4187  4187 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:28.942  4187  4187 D HidService: setHidService(): set to: null
07-12 17:45:28.942  4187  4218 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d6099
07-12 17:45:28.942  4187  4218 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 17:45:28.943  4187  4187 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 17:45:28.944  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:28.944  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.944  4187  4187 D HealthService: Received start request. Starting profile...
07-12 17:45:28.944  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.946  4187  4187 I bt_bluedroid: get_profile_interface health
07-12 17:45:28.947  4187  4187 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 17:45:28.947  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:28.948  4187  4187 D PanService: Received start request. Starting profile...
07-12 17:45:28.948  4187  4187 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:28.948  4187  4187 I bt_bluedroid: get_profile_interface pan
07-12 17:45:28.948  4187  4218 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 17:45:28.949  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@926df63
07-12 17:45:28.950  4187  4187 D BluetoothMapService: Received start request. Starting profile...
07-12 17:45:28.950  4187  4187 D BluetoothMapService: start()
07-12 17:45:28.951  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.951  4187  4187 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-12 17:45:28.951  3746  3746 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.952  4187  4187 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-12 17:45:28.952  4187  4187 D BluetoothMapAppObserver: createReceiver()
07-12 17:45:28.953  4187  4187 D BluetoothMapAppObserver: initObservers()
07-12 17:45:28.953  4187  4187 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 17:45:28.957   932  1145 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.958  4187  4261 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 17:45:28.958  4187  4187 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:28.958  4187  4187 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:28.958  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:28.958  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:28.959  4187  4187 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:28.959  4187  4187 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:28.959   932  1145 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-12 17:45:28.959  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:28.959  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:28.959  4187  4187 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:28.959  4187  4187 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:28.960  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:28.961  4187  4187 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:28.961  4187  4187 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:28.961  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:28.961  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:28.961  4187  4214 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 17:45:28.961  4187  4214 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:28.961  4187  4214 D BluetoothAdapterProperties: State =  11
07-12 17:45:28.962  4187  4214 D BluetoothAdapterProperties: Setting state to 12
07-12 17:45:28.962  4187  4214 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 17:45:28.962  4187  4214 I BluetoothAdapterState: Entering OnState
07-12 17:45:28.962   790   815 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:28.962   790   815 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:28.962   790   815 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:28.962  3746  3789 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:28.962  4187  4218 D BluetoothAdapterProperties: Scan Mode:21
07-12 17:45:28.962  4187  4218 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:28.964  3746  3758 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:28.968   932   943 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:28.968  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:28.970   932   932 D BluetoothInputDevice: Proxy object connected
07-12 17:45:28.970   932   932 D HidProfile: Bluetooth service connected
07-12 17:45:28.973  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:28.976  1304  1430 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:28.977  4187  4187 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 17:45:28.978  4187  4187 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 17:45:28.978   932   951 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:28.978  4187  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:28.979  3746  3746 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:28.979  3746  3746 D PanProfile: Bluetooth service connected
07-12 17:45:28.979  3746  3746 D BluetoothMap: Proxy object connected
07-12 17:45:28.979  3746  3746 D MapProfile: Bluetooth service connected
07-12 17:45:28.979  3746  3746 D BluetoothMap: getConnectedDevices()
07-12 17:45:28.979  4187  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:28.980  4187  4187 D ObexServerSockets: Succeed to create listening sockets 
07-12 17:45:28.980  4187  4187 D ObexServerSockets0: startAccept()
07-12 17:45:28.980  4187  4187 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:28.982  4187  4187 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-12 17:45:28.982  4187  4187 D BluetoothSdpJni: SDP Create record success - handle: 0
07-12 17:45:28.983  4187  4269 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:28.983  4187  4270 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:28.985   932  1395 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:28.986   932   932 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:28.986   932   932 D PanProfile: Bluetooth service connected
07-12 17:45:28.986   790   815 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:28.986  3746  3757 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:28.987   790   790 D BluetoothA2dp: Proxy object connected
07-12 17:45:28.992   932   951 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:28.994   932   932 D BluetoothA2dp: Proxy object connected
07-12 17:45:28.995  3746  3758 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-12 17:45:28.996   932  1395 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:28.996  3746  3746 D BluetoothInputDevice: Proxy object connected
07-12 17:45:28.996  3746  3746 D HidProfile: Bluetooth service connected
07-12 17:45:28.997  3746  3757 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:28.998   932   943 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:29.000   932   932 D BluetoothMap: Proxy object connected
07-12 17:45:29.000   932   932 D MapProfile: Bluetooth service connected
07-12 17:45:29.000   932   932 D BluetoothMap: getConnectedDevices()
07-12 17:45:29.000  3746  3758 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:29.001   790   790 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 17:45:29.001  4187  4187 D BluetoothMapService: onReceive
07-12 17:45:29.001  4187  4187 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:29.002  4187  4187 D BluetoothMapService: STATE_ON
07-12 17:45:29.002  3746  3746 D BluetoothA2dp: Proxy object connected
07-12 17:45:29.015   932  1145 D BluetoothMap: getConnectedDevices()
07-12 17:45:29.017   932  1145 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
07-12 17:45:29.018   932  1145 D MapProfile: getConnectionStatus: status is: 0
07-12 17:45:29.023  4187  4187 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 17:45:29.023  4187  4187 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:29.029  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:29.034  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:29.037  3746  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:29.042  3746  3746 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:29.049  4187  4281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:29.050   932   932 D BluetoothPbap: Proxy object connected
07-12 17:45:29.050   932   932 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:29.054  1556  4097 D BluetoothAdapter: startLeScan(): null
,07-12 17:45:29.055  1556  4097 D BluetoothAdapter: STATE_ON
,07-12 17:45:29.058  3746  3746 D BluetoothPbap: Proxy object connected
,07-12 17:45:29.058  3746  3746 D PbapServerProfile: Bluetooth service connected
07-12 17:45:29.059  4187  4259 D BtGatt.GattService: registerClient() - UUID=4e288622-da81-40b5-a631-8756b4518bb2
,07-12 17:45:29.059  4187  4218 D BtGatt.GattService: onClientRegistered() - UUID=4e288622-da81-40b5-a631-8756b4518bb2, clientIf=5
07-12 17:45:29.059  1556  1566 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:29.060  4187  4197 D BtGatt.GattService: start scan with filters
,07-12 17:45:29.062  4187  4226 D BtGatt.ScanManager: handling starting scan
,07-12 17:45:29.065  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-12 17:45:29.066  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 17:45:29.066  4187  4226 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 17:45:29.066  4187  4218 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 17:45:29.068  1556  1556 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:29.068   932  1145 D BluetoothMap: getConnectedDevices()
07-12 17:45:29.070   932  1145 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-12 17:45:29.072   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:29.073  1556  4284 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-12 17:45:29.075  1556  1556 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:29.080   790   790 D BluetoothHeadset: Proxy object connected
,07-12 17:45:29.081   932  1395 D BluetoothHeadset: Proxy object connected
07-12 17:45:29.081   932   932 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:29.082  3746  3789 D BluetoothHeadset: Proxy object connected
07-12 17:45:29.082  3746  3746 D HeadsetProfile: Bluetooth service connected
07-12 17:45:29.082  1304  1329 D BluetoothHeadset: Proxy object connected
,07-12 17:45:29.082   790   790 D BluetoothHeadset: Proxy object connected
07-12 17:45:29.083   790   790 D BluetoothHeadset: Proxy object connected
,07-12 17:45:29.088  4187  4288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:29.089  4187  4288 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:29.090  1556  4284 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 17:45:29.096   932   951 D BluetoothHeadset: Proxy object connected
,07-12 17:45:29.100  3746  3757 D BluetoothHeadset: Proxy object connected
,07-12 17:45:29.100  3746  3746 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:29.109   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:29.110   932  1145 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-12 17:45:29.111   932  1145 D MapProfile: getConnectionStatus: status is: 0
07-12 17:45:29.111   932   932 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:29.115  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:29.130   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:29.131   932  1145 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-12 17:45:29.133   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:29.143   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:29.144   932  1145 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-12 17:45:29.145   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:29.160   932  1145 D BluetoothMap: getConnectedDevices()
,07-12 17:45:29.161   932  1145 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-12 17:45:29.163   932  1145 D MapProfile: getConnectionStatus: status is: 0
,07-12 17:45:29.298  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:29.405  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:29.606  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:29.613  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:29.614  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:29.614  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc0906e added. We now have 8 listener(s)
07-12 17:45:29.614  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:29.615   790  1349 D WifiService: setWifiEnabled: false pid=3568, uid=10026
07-12 17:45:29.615   790  1349 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:29.617  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:29.617   790  1224 D WifiService: setWifiEnabled: true pid=3568, uid=10026
07-12 17:45:29.617   790  1224 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:29.619   192   784 D SoftapController: Softap fwReload - Ok
07-12 17:45:29.620   192   784 D CommandListener: Setting iface cfg
07-12 17:45:29.620   192   784 D CommandListener: Trying to bring down wlan0
07-12 17:45:29.621   192   784 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:29.622   790   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:29.648  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:29.662  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:29.671  1556  4262 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:29.672  1556  4262 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: java.io.IOException: Not connected
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:29.672  1556  4262 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:30.383   790   891 D wifi    : set interface wlan0 flags (UP)
,07-12 17:45:30.383   790   891 I WifiHAL : Initializing wifi
07-12 17:45:30.383   790   891 I WifiHAL : Creating socket
07-12 17:45:30.384   790   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-12 17:45:30.384   790   815 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 17:45:30.385   790   891 D wifi    : Did set static halHandle = 0xa0805390
07-12 17:45:30.385   790   891 D wifi    : halHandle = 0xa0805390, mVM = 0xb4dbc000, mCls = 0x101542
,07-12 17:45:30.385   790   891 D wifi    : array field set
07-12 17:45:30.385   790   891 I WifiNative-HAL: interface[0] = p2p0
07-12 17:45:30.385   790   891 I WifiNative-HAL: interface[1] = wlan0
,07-12 17:45:30.387   790  4321 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602202736
,07-12 17:45:30.388   790  4321 D wifi    : waitForHalEvents called, vm = 0xb4dbc000, obj = 0x101542, env = 0x93162aa0
,07-12 17:45:30.420  4322  4322 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 17:45:30.443  4322  4322 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:30.447  4322  4322 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:30.486   790   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 17:45:30.491  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:30.496   790   891 D WifiConfigStore: Loading config and enabling all networks 
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:30.496  3568  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:30.498  3568  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:30.505   790   891 D WifiConfigStore: loaded 0 passpoint configs
07-12 17:45:30.506   790   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 17:45:30.507   790   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:30.507   790   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-12 17:45:30.507   790   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 17:45:30.519   790   891 D WifiNative-HAL: Setting external_sim to 1
,07-12 17:45:30.519   790   891 D wifi    : setting dfs flag to true, 0x99087960
07-12 17:45:30.519   790   891 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 17:45:30.519   790   891 D wifi    : setting scan oui 0x99087960
07-12 17:45:30.519   790   891 D WifiHAL : Sending mac address OUI
,07-12 17:45:30.550   790   891 E native  : do suspend true
,07-12 17:45:30.558   790   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-12 17:45:30.558   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
07-12 17:45:30.558   790   790 D RttService: SCAN_AVAILABLE : 3
07-12 17:45:30.558   790   907 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:30.559   192   784 D CommandListener: Setting iface cfg
,07-12 17:45:30.562   192   784 D CommandListener: Trying to bring up p2p0
07-12 17:45:30.562   790   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 17:45:30.567   790   890 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:30.567   790   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-12 17:45:30.568  1556  4097 D BluetoothAdapter: stopLeScan()
07-12 17:45:30.569  1556  4097 D BluetoothAdapter: STATE_ON
,07-12 17:45:30.569  4187  4289 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:30.570  4187  4226 D BtGatt.ScanManager: stop scan
07-12 17:45:30.570  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 17:45:30.570  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 17:45:30.570  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-12 17:45:30.578  4187  4259 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:30.717  1556  4262 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:30.718  1556  4262 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: java.io.IOException: Not connected
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at reh.run(:com.google.android.gms:75)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:30.718  1556  4262 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:30.750  1556  4097 D BluetoothAdapter: startLeScan(): null
,07-12 17:45:30.751  1556  4097 D BluetoothAdapter: STATE_ON
,07-12 17:45:30.753  4187  4259 D BtGatt.GattService: registerClient() - UUID=0c493c8b-181e-46fe-bb58-6474fd483944
07-12 17:45:30.753  4187  4218 D BtGatt.GattService: onClientRegistered() - UUID=0c493c8b-181e-46fe-bb58-6474fd483944, clientIf=5
07-12 17:45:30.753  1556  1634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:30.753  4187  4198 D BtGatt.GattService: start scan with filters
,07-12 17:45:30.755  4187  4226 D BtGatt.ScanManager: handling starting scan
,07-12 17:45:30.756  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-12 17:45:30.756  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 17:45:30.756  4187  4226 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 17:45:30.756  4187  4218 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 17:45:31.027  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:31.271  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Sluchawki Bose len=14 dev_type=3
,07-12 17:45:31.308  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:31.557  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:31.577  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.651  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:31.657  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:31.664  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-12 17:45:31.667  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-12 17:45:31.685  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5e023fa Bundle[{}]
,07-12 17:45:31.687  3568  3641 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 17:45:31.687  3568  3641 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:45:31.690  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-12 17:45:31.692  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-12 17:45:31.693  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:45:31.695  3568  3641 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 17:45:31.716  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:31.722  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:31.722  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:31.722  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-12 17:45:31.722  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-12 17:45:31.722  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.726  3568  3641 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 332)
07-12 17:45:31.726  3568  3641 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 332)
,07-12 17:45:31.726  3568  3641 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 332)
07-12 17:45:31.726  3568  3641 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 332)
07-12 17:45:31.727  3568  3641 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 338)
07-12 17:45:31.727  3568  3641 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 338)
07-12 17:45:31.728  3568  3641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 338)
07-12 17:45:31.728  3568  3641 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 339)
07-12 17:45:31.728  3568  3641 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 341)
07-12 17:45:31.729  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.729  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13330f added. We now have 2 listener(s)
07-12 17:45:31.730  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.730  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.730  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:31.731  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.731  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e557f9c added. We now have 9 listener(s)
07-12 17:45:31.731  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.732  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:31.732  3568  3641 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:31.734  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.736  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.737  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.737  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.738  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.738  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.738  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.738  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c69457a added. We now have 3 listener(s)
07-12 17:45:31.739  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.739  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:31.739  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.739  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.739  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259f12b added. We now have 10 listener(s)
07-12 17:45:31.740  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.740  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.740  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.740  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.740  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.740  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.740  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.740  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.740  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13330f removed from the list
07-12 17:45:31.741  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.741  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e557f9c removed from the list
07-12 17:45:31.741  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.741  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.741  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.741  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.741  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.741  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e557f9c not in the list
,07-12 17:45:31.741  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.741  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.741  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.741  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259f12b removed from the list
07-12 17:45:31.741  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.741  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.741  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.741  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.741  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c69457a removed from the list
,07-12 17:45:31.742  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.742  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a08f988 added. We now have 2 listener(s)
,07-12 17:45:31.743  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.743  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.743  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.743  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.743  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@909df21 added. We now have 9 listener(s)
,07-12 17:45:31.743  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.745  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:31.745  3568  3641 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:31.747  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.748  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:31.751  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.751  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:31.752  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.752  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.752  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.752  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e047507 added. We now have 3 listener(s)
,07-12 17:45:31.753  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.753  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.753  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:31.753  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.753  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df82634 added. We now have 10 listener(s)
07-12 17:45:31.753  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.753  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.754  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:31.754  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:31.754  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:31.756  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.757  3568  3641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:31.757  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.757  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.758  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.758  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.758  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:31.758  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:31.758  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.758  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:31.758  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:31.758  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a08f988 removed from the list
07-12 17:45:31.758  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.758  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@909df21 removed from the list
07-12 17:45:31.758  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:31.758  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.759  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.759  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:31.759  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.759  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:31.759  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.759  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@909df21 not in the list
07-12 17:45:31.759  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:31.759  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.759  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.759  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df82634 removed from the list
07-12 17:45:31.759  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:31.759  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.759  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.759  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.759  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e047507 removed from the list
,07-12 17:45:31.759  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.760  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8709d2 added. We now have 2 listener(s)
07-12 17:45:31.760  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.761  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.761  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.761  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:31.761  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae95aa3 added. We now have 9 listener(s)
07-12 17:45:31.761  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.762  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:31.762  3568  3641 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:31.763  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.765  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:31.766  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.766  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.767  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.769  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.775  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.778  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3e5159 added. We now have 3 listener(s)
,07-12 17:45:31.780  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.780  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.780  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.780  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.780  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e27f11e added. We now have 10 listener(s)
07-12 17:45:31.780  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:31.781  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.781  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.781  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:31.781  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.781  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:31.785  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.785  3568  3641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:31.785  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.785  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.785  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.785  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.785  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.785  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:31.785  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.785  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8709d2 removed from the list
07-12 17:45:31.785  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.786  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae95aa3 removed from the list
07-12 17:45:31.786  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.786  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.786  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.786  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:31.786  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.786  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:31.786  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.786  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae95aa3 not in the list
07-12 17:45:31.786  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:31.786  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.786  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.786  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e27f11e removed from the list
07-12 17:45:31.786  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:31.787  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.787  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.787  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.787  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3e5159 removed from the list
07-12 17:45:31.787  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.787  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4607cc added. We now have 2 listener(s)
07-12 17:45:31.789  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.789  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.789  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.789  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.789  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f9aa15 added. We now have 9 listener(s)
,07-12 17:45:31.789  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.791  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:31.791  3568  3641 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:31.793  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.796  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.798  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.798  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.798  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.798  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dd7b1b added. We now have 3 listener(s)
07-12 17:45:31.799  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.799  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.800  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-12 17:45:31.800  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.800  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.800  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.800  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b1d4b8 added. We now have 10 listener(s)
07-12 17:45:31.800  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.800  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.800  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:31.800  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.800  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:31.804  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.804  3568  3641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:31.806  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.806  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.806  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.806  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:31.806  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.806  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:31.806  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.806  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4607cc removed from the list
07-12 17:45:31.806  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.806  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f9aa15 removed from the list
07-12 17:45:31.806  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:31.806  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.807  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.807  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:31.807  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.807  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.807  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.807  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f9aa15 not in the list
,07-12 17:45:31.807  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:31.807  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.807  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.807  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b1d4b8 removed from the list
07-12 17:45:31.808  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.808  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.808  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.808  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.808  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dd7b1b removed from the list
07-12 17:45:31.808  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.808  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43305f6 added. We now have 2 listener(s)
07-12 17:45:31.809  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.809  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:31.809  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.809  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.809  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ceadf7 added. We now have 9 listener(s)
07-12 17:45:31.809  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.811  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:31.811  3568  3641 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:31.812  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.814  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.815  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.815  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.815  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.815  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9606cd added. We now have 3 listener(s)
07-12 17:45:31.816  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-12 17:45:31.816  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.816  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.816  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:31.816  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5818b82 added. We now have 10 listener(s)
07-12 17:45:31.816  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.816  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.816  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.816  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.816  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.816  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.816  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.816  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:31.816  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43305f6 removed from the list
07-12 17:45:31.816  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.816  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ceadf7 removed from the list
07-12 17:45:31.817  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.817  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.817  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.817  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.817  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.817  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.817  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ceadf7 not in the list
07-12 17:45:31.817  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.817  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.817  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.817  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5818b82 removed from the list
,07-12 17:45:31.817  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.817  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.817  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.818  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.818  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9606cd removed from the list
,07-12 17:45:31.818  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:31.818  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 added. We now have 2 listener(s)
07-12 17:45:31.819  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.819  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 17:45:31.819  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:31.819  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:31.819  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:31.819  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 added. We now have 9 listener(s)
07-12 17:45:31.819  3568  3641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:31.820  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:31.820  3568  3641 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:31.822  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.824  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.825  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.825  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.826  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:31.826  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:31.826  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-12 17:45:31.826  3568  3641 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-12 17:45:31.826  3568  3641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:31.826  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:31.826  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:31.826  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:31.826  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.826  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.826  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:31.826  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.826  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.826  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.826  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:31.826  3568  3641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 removed from the list
07-12 17:45:31.826  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.826  3568  3641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 removed from the list
,07-12 17:45:31.828  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.828  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.828  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.828  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.828  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.828  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.828  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.829  3568  3641 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-12 17:45:31.829  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.829  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.829  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.829  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.829  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.829  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.829  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.829  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.829  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.829  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:31.829  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.829  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.829  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.829  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.829  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.829  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
,07-12 17:45:31.830  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.830  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-12 17:45:31.830  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,07-12 17:45:31.830  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections,: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:31.831  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.831  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.831  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.831  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.831  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.831  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
,07-12 17:45:31.831  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.831  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.831  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.831  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.831  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.831  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.831  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.831  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.831  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.832  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.832  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.832  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.832  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.832  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.832  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.832  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.832  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.832  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.832  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.832  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.832  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.832  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.832  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.832  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.832  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.832  3568  3641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:31.834  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.836  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.837  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.837  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.837  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.837  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:31.837  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:31.837  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:31.838  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.840  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.841  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.841  3568  3641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:31.841  3568  3641 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:31.842  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.842  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.842  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.842  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.842  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.842  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:31.842  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.842  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.842  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
,07-12 17:45:31.842  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.842  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.843  3568  3641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:31.844  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.846  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.847  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:31.847  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.847  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.847  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:31.848  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.850  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.850  3568  3641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:31.850  3568  3641 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:31.850  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.851  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.851  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.851  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.851  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:31.851  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.851  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:31.851  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.851  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.851  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.851  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.851  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.852  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:31.852  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.852  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.852  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.853  3568  3641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:31.853  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.855  3568  3641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.857  3568  3641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.857  3568  3641 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:31.857  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:31.857  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:31.857  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.857  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:31.858  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.860  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.860  3568  3641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:31.860  3568  3641 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:31.860  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.860  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.860  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.860  3568  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:31.860  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.860  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.860  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:31.860  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.860  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.860  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:31.860  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.860  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.861  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.861  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.861  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.861  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:31.861  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.861  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.861  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.861  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.861  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.861  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.861  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.861  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.861  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.861  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.862  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.862  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
,07-12 17:45:31.862  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.862  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.862  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.862  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.862  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.862  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.862  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.862  3568  3641 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-12 17:45:31.862  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.862  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.862  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.862  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.862  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.862  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.863  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.863  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.863  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.863  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.863  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.863  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.863  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.863  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.863  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.863  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.863  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-12 17:45:31.863  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.863  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.863  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.863  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.863  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.863  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.863  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.863  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.863  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.863  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.863  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.863  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.863  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.863  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.863  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.863  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.864  3568  3641 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-12 17:45:31.864  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.864  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.864  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.864  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.864  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.864  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.864  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.864  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.864  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.864  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.864  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.864  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.864  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.864  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.864  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.864  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.864  3568  3641 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-12 17:45:31.864  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:31.864  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.864  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.864  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.864  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.864  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.864  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.864  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.864  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
,07-12 17:45:31.864  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.865  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.865  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.865  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.865  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.865  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
,07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:31.865  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:31.865  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:31.865  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:31.865  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.865  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.865  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.865  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.865  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.865  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.865  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.865  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.865  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.865  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.865  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.865  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.865  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.865  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.866  3568  3641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:31.866  3568  3641 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:31.866  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-12 17:45:31.867  3568  3641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:31.867  3568  3641 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-12 17:45:31.867  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:31.867  3568  3641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-12 17:45:31.868  3568  3641 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-12 17:45:31.868  3568  3641 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-12 17:45:31.868  3568  3641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:31.868  3568  3641 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-12 17:45:31.868  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.868  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.868  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.868  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.868  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.868  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.868  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.869  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.869  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.869  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.869  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.869  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.869  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.869  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.869  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.869  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.869  3568  3641 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-12 17:45:31.869  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.869  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.869  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.870  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:31.870  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.870  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.870  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.870  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.870  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.870  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.870  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.870  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.870  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.870  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.870  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.870  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.870  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.870  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.870  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.870  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.870  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.870  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.870  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.870  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.870  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.870  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.870  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.870  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.870  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.870  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.871  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.871  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.871  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.871  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.871  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.871  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.871  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.871  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.871  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.871  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.871  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
,07-12 17:45:31.871  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.871  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.871  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.871  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.871  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.871  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.871  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.872  3568  3641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-12 17:45:31.872  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.872  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.872  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.872  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.872  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.872  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.872  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.873  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.873  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.873  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.873  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.873  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.873  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.873  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.873  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-12 17:45:31.873  3568  3641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connecti,on(s) left
07-12 17:45:31.873  3568  3641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:31.873  3568  3641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:31.873  3568  3641 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:31.873  3568  3641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:31.873  3568  3641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:31.873  3568  3641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-12 17:45:31.873  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.873  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.873  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.873  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.873  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.873  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.874  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.874  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.874  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.874  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.874  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.874  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.874  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.874  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.874  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.874  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.874  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.874  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.874  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.874  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.874  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.874  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.874  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.874  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.874  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.875  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.875  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.875  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.875  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.875  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.875  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.875  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.875  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.875  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.875  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.875  3568  3641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-12 17:45:31.875  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:31.876  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-12 17:45:31.877  3568  3641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-12 17:45:31.877  3568  3641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-12 17:45:31.877  3568  3568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-12 17:45:31.877  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-12 17:45:31.877  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.877  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:31.877  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-12 17:45:31.877  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-12 17:45:31.877  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-12 17:45:31.877  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.877  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.877  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.877  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:31.877  3568  3641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:31.878  3568  4374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-12 17:45:31.878  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.879  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.879  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.879  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.879  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:31.879  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.879  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:31.881  3568  3568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.881  3568  3568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:31.883  3568  3568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:31.883  3568  3568 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:31.883  3568  3641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-12 17:45:31.883  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.884  3568  3568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.884  3568  3568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-12 17:45:31.884  3568  3568 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-12 17:45:31.884  3568  3568 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-12 17:45:31.884  3568  3568 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.884  3568  3568 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:31.884  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.884  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.884  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.884  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.884  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.884  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.884  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.884  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.884  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.884  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.884  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.884  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.884  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.885  3568  3641 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-12 17:45:31.885  3568  3641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:31.885  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:31.885  3568  3641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:31.885  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.885  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.885  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.885  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.885  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.885  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.886  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.886  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.886  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.886  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.886  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.886  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:31.886  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.886  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.886  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.886  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.888  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.888  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.888  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.888  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.888  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.888  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.888  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
,07-12 17:45:31.888  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.888  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.888  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.888  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.888  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.888  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.888  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.888  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.888  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.889  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.889  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.889  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:31.889  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.889  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.889  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.889  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.889  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.889  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.889  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.889  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.889  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.889  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.889  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.889  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.889  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.889  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.889  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.889  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.890  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.890  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.890  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.890  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.890  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.890  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.890  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:31.890  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.890  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.890  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.890  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.890  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.890  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.890  3568  3641 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:31.890  3568  3641 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-12 17:45:31.890  3568  3568 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-12 17:45:31.899  3568  3641 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-12 17:45:31.899  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.899  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:31.899  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.900  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.900  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.900  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.900  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.900  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.900  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.900  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.900  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.900  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:31.900  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.900  3568  3641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:31.900  3568  3641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:31.900  3568  3641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:31.900  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.900  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.900  3568  3641 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9363293 not in the list
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.900  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.900  3568  3641 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:31.900  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:31.900  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.900  3568  3641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:31.900  3568  3641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:31.900  3568  3641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:31.900  3568  3641 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82d0 not in the list
07-12 17:45:31.901  3568  3641 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-12 17:45:31.901  3568  3641 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-12 17:45:31.901  3568  3641 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-12 17:45:31.901  3568  3641 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-12 17:45:31.901  3568  3641 E com.test.thalitest.ThaliTestRunner: Total duration: 29461 ms
07-12 17:45:31.902  3568  3641 I jxcore-log: PromiseSuccess
07-12 17:45:31.902  3568  3641 I jxcore-log: 
07-12 17:45:31.903  3568  3641 I jxcore-log: My device name is: LGE-Nexus 5
07-12 17:45:31.903  3568  3641 I jxcore-log: 
,07-12 17:45:31.956  4187  4218 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 17:45:31.979  1556  4262 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:45:31.980  1556  4262 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: java.io.IOException: Not connected
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:31.980  1556  4262 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:32.069  1556  4097 D BluetoothAdapter: stopLeScan()
,07-12 17:45:32.070  1556  4097 D BluetoothAdapter: STATE_ON
,07-12 17:45:32.071  4187  4198 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:32.071  4187  4226 D BtGatt.ScanManager: stop scan
07-12 17:45:32.071  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 17:45:32.071  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 17:45:32.071  4187  4226 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 17:45:32.078  4187  4197 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:32.078  1556  4097 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 17:45:35.104  1556  4279 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 17:45:35.906  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 17:45:35.906  3568  3641 I jxcore-log: 
,07-12 17:45:36.299  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 17:45:36.299  3568  3641 I jxcore-log: 
,07-12 17:45:36.322  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 17:45:36.322  3568  3641 I jxcore-log: 
,07-12 17:45:36.326  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 17:45:36.326  3568  3641 I jxcore-log: 
,07-12 17:45:36.341  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 17:45:36.341  3568  3641 I jxcore-log: 
,07-12 17:45:36.345  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 17:45:36.345  3568  3641 I jxcore-log: 
,07-12 17:45:38.289  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 17:45:38.289  3568  3641 I jxcore-log: 
,07-12 17:45:38.300  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 17:45:38.300  3568  3641 I jxcore-log: 
,07-12 17:45:38.307  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 17:45:38.307  3568  3641 I jxcore-log: 
,07-12 17:45:38.461  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 17:45:38.461  3568  3641 I jxcore-log: 
,07-12 17:45:39.176  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 17:45:39.176  3568  3641 I jxcore-log: 
,07-12 17:45:39.232  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 17:45:39.232  3568  3641 I jxcore-log: 
,07-12 17:45:39.237  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 17:45:39.237  3568  3641 I jxcore-log: 
,07-12 17:45:39.434  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 17:45:39.434  3568  3641 I jxcore-log: 
,07-12 17:45:39.454  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 17:45:39.454  3568  3641 I jxcore-log: 
,07-12 17:45:39.458  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 17:45:39.458  3568  3641 I jxcore-log: 
,07-12 17:45:39.463  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 17:45:39.463  3568  3641 I jxcore-log: 
,07-12 17:45:39.479  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 17:45:39.479  3568  3641 I jxcore-log: 
,07-12 17:45:39.498  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 17:45:39.498  3568  3641 I jxcore-log: 
,07-12 17:45:39.583  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 17:45:39.583  3568  3641 I jxcore-log: 
,07-12 17:45:39.588  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 17:45:39.588  3568  3641 I jxcore-log: 
,07-12 17:45:39.612  3568  3641 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 17:45:39.612  3568  3641 I jxcore-log: 
,07-12 17:45:39.621  3568  3641 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-12 17:45:39.623  3568  3641 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 17:45:39.623  3568  3641 I jxcore-log: 
,07-12 17:45:39.667  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:39.667  3568  3641 I jxcore-log: 
,07-12 17:45:39.667  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:39.667  3568  3641 I jxcore-log: 
,07-12 17:45:39.668  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.668  3568  3641 I jxcore-log: 
07-12 17:45:39.669  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.669  3568  3641 I jxcore-log: 
,07-12 17:45:39.670  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.670  3568  3641 I jxcore-log: 
,07-12 17:45:39.671  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.671  3568  3641 I jxcore-log: 
,07-12 17:45:39.672  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.672  3568  3641 I jxcore-log: 
,07-12 17:45:39.672  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.672  3568  3641 I jxcore-log: 
07-12 17:45:39.673  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.673  3568  3641 I jxcore-log: 
07-12 17:45:39.673  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.673  3568  3641 I jxcore-log: 
07-12 17:45:39.674  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.674  3568  3641 I jxcore-log: 
07-12 17:45:39.674  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.674  3568  3641 I jxcore-log: 
07-12 17:45:39.675  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.675  3568  3641 I jxcore-log: 
07-12 17:45:39.675  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:39.675  3568  3641 I jxcore-log: 
07-12 17:45:39.676  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.676  3568  3641 I jxcore-log: 
,07-12 17:45:39.676  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.676  3568  3641 I jxcore-log: 
07-12 17:45:39.676  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.676  3568  3641 I jxcore-log: 
07-12 17:45:39.677  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.677  3568  3641 I jxcore-log: 
07-12 17:45:39.677  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.677  3568  3641 I jxcore-log: 
07-12 17:45:39.678  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.678  3568  3641 I jxcore-log: 
,07-12 17:45:39.678  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.678  3568  3641 I jxcore-log: 
,07-12 17:45:39.679  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.679  3568  3641 I jxcore-log: 
07-12 17:45:39.679  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.679  3568  3641 I jxcore-log: 
07-12 17:45:39.679  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.679  3568  3641 I jxcore-log: 
07-12 17:45:39.680  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:39.680  3568  3641 I jxcore-log: 
07-12 17:45:39.680  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-12 17:45:39.680  3568  3641 I jxcore-log: 
07-12 17:45:39.681  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:39.681  3568  3641 I jxcore-log: 
07-12 17:45:39.681  3568  3641 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-12 17:45:39.681  3568  3641 I jxcore-log: 
,07-12 17:46:02.479   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:46:02.503   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-12 17:46:02.666   790   893 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-12 17:47:04.169   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:47:04.195   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-12 17:47:51.835  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:47:51.863  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 17:47:51.864  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:48:05.844   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:48:05.870   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-12 17:48:11.134  1556  3011 V NativeCrypto: SSL shutdown failed: ssl=0x9a845200: I/O error during system call, Connection timed out
,07-12 17:48:14.027  1568  3050 V NativeCrypto: SSL shutdown failed: ssl=0x9b4a0400: I/O error during system call, Connection timed out
,07-12 17:48:33.001  1556  3011 V NativeCrypto: SSL shutdown failed: ssl=0x98e33e00: I/O error during system call, Connection timed out
,07-12 17:49:04.229  1556  3011 V NativeCrypto: SSL shutdown failed: ssl=0x9a8bf200: I/O error during system call, Connection timed out
,07-12 17:54:07.570   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:54:07.595   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-12 17:58:30.527  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:58:30.558  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:58:30.563  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:00:09.308   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 18:00:09.331   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-12 18:02:47.484   790   803 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 18:03:30.718  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:03:30.751  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:03:30.754  1556  1556 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:06:11.055   790   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 18:06:11.094   790   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-12 18:06:11.200  1568  4477 I EventLogChimeraService: Aggregate from 1468337571130 (log), 1468337571130 (data)
,07-12 18:06:11.224  1377  4476 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-12 18:06:11.255  1377  4476 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,07-12 18:06:11.255  1377  4476 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-12 18:06:11.263  1377  4476 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,07-12 18:06:11.263  1377  4476 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-12 18:06:11.285  1377  4476 I ContextCompilationHandl: Recognition context unchanged for CONTACT_NAMES en-US
,07-12 18:06:11.285  1377  4476 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-12 18:06:11.342  1568  4487 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-12 18:06:11.361  1568  1643 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.gms start 0 num 1000
,07-12 18:06:11.372  1568  4486 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 18:06:11.396  1568  4486 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 18:06:11.436  1377  4476 I ContextCompilationHandl: Recognition context unchanged for APP_NAMES en-US
07-12 18:06:11.436  1377  4476 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-12 18:06:11.458  1568  1643 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-12 18:06:11.471  1568  1643 E Icing   : No scoring data for corpus [21]
,07-12 18:06:11.474  1568  1643 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 18:06:11.484  1568  1643 E Icing   : No scoring data for corpus [15]
,07-12 18:06:11.500  1568  1699 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 18:06:11.535  1568  1643 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 18:06:11.549  1568  1643 E Icing   : No scoring data for corpus [22]
,07-12 18:06:11.551  1377  4476 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,TIME-OUT KILL (timeout was 1400000ms),07-12 18:08:20.430  4513  4513 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 18:08:20.437  4513  4513 D AndroidRuntime: CheckJNI is OFF
07-12 18:08:20.491  4513  4513 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 18:08:20.543  4513  4513 I Radio-JNI: register_android_hardware_Radio DONE
07-12 18:08:20.564  4513  4513 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 18:08:20.570   790   804 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
07-12 18:08:20.570   790   804 I ActivityManager: Killing 3568:com.test.thalitest/u0a26 (adj 0): stop com.test.thalitest
07-12 18:08:20.606   790   800 D GraphicsStats: Buffer count: 2
07-12 18:08:20.607   790   966 I WindowState: WIN DEATH: Window{c40bcfa u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 18:08:20.607   790   800 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@dd17f19)
07-12 18:08:20.608   790   892 D WifiService: Client connection lost with reason: 4
07-12 18:08:20.608   790   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 18:08:20.608   790   893 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 18:08:20.662   790   831 W PackageSettings: Skipping PackageSetting{7672435 com.example.hello/10116} due to missing metadata
07-12 18:08:20.691   790   804 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-12 18:08:20.691   790   804 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-12 18:08:20.694   790   831 I art     : Starting a blocking GC Explicit
07-12 18:08:20.696   790   804 E ActivityManager: Failure starting process com.test.thalitest
07-12 18:08:20.696   790   804 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-12 18:08:20.696   790   804 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:20.696   790   804 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:20.696   790   804 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:20.696   790   804 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 18:08:20.697   790   804 I ActivityManager:   Force finishing activity ActivityRecord{da89a8c u0 com.test.thalitest/.MainActivity t46}
07-12 18:08:20.703   790   800 W ActivityManager: Spurious death for ProcessRecord{d42ebde 0:com.test.thalitest/u0a26}, curProc for 3568: null
07-12 18:08:20.738   790   831 I art     : Explicit concurrent mark sweep GC freed 18205(1258KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 25MB/38MB, paused 784us total 42.028ms
07-12 18:08:20.766   790   831 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-12 18:08:20.769  4513  4513 I art     : System.exit called, status: 0
07-12 18:08:20.769  4513  4513 I AndroidRuntime: VM exiting with result code 0.
07-12 18:08:20.773   790   831 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
07-12 18:08:20.806   790   804 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-12 18:08:20.809  4187  4187 D BluetoothMapAppObserver: onReceive
07-12 18:08:20.809  4187  4187 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-12 18:08:20.811   790   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 18:08:20.838  1556  1639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 18:08:20.860  1304  1304 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-12 18:08:20.866   790  2092 I ActivityManager: Start proc 4546:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
07-12 18:08:20.867  2056  4551 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-12 18:08:20.914  4546  4546 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-12 18:08:20.924   790   790 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 18:08:20.929  2056  4551 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
07-12 18:08:20.934   790  3258 I ActivityManager: Start proc 4567:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
--------- beginning of crash
07-12 18:08:20.942  2056  4551 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-12 18:08:20.942  2056  4551 E AndroidRuntime: Process: android.process.acore, PID: 2056
07-12 18:08:20.942  2056  4551 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:20.942  2056  4551 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:20.947  2056  4551 I Process : Sending signal. PID: 2056 SIG: 9
07-12 18:08:20.967   790  4580 E DropBoxManagerService: Can't write: system_app_crash
07-12 18:08:20.967   790  4580 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 18:08:20.967   790  4580 E DropBoxManagerService: 	... 5 more
07-12 18:08:20.967  4567  4567 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
07-12 18:08:20.970  4567  4567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
07-12 18:08:20.973   790  1226 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3568 uid 10026
07-12 18:08:20.988   790  1349 I ActivityManager: Process android.process.acore (pid 2056) has died
07-12 18:08:20.988   790  1349 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms

```
