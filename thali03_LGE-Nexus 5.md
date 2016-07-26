#### Test 757892686f45c73_thali03_LGE-Nexus 5 Logs


```
--------- beginning of main
07-26 15:20:22.221   786   892 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-26 15:20:22.942  3597  3597 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-26 15:20:22.946  3597  3597 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:22.979  3597  3597 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 15:20:23.013  3597  3597 I Radio-JNI: register_android_hardware_Radio DONE
07-26 15:20:23.032  3597  3597 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-26 15:20:23.034   786   948 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:20:23.050  1437  1617 W SearchService: Abort, client detached.
07-26 15:20:23.067  3597  3597 D AndroidRuntime: Shutting down VM
07-26 15:20:23.077   786  1321 I ActivityManager: Start proc 3614:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-26 15:20:23.081  1437  1437 I MicroDetector: Keeping mic open: false
07-26 15:20:23.082  1437  1437 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ai@9df44bd
07-26 15:20:23.082  1437  1520 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-26 15:20:23.082  1437  1568 I DeviceStateChecker: DeviceStateChecker cancelled
07-26 15:20:23.139   202  1587 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-26 15:20:23.139   202  1587 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-26 15:20:23.149  1437  1581 I MicroRecognitionRunner: Detection finished
07-26 15:20:23.149  1437  1567 I MicroRecognitionRunner: Stopping hotword detection.
07-26 15:20:23.186  3614  3614 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-26 15:20:23.213  3614  3614 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 1577-1579)
07-26 15:20:23.213  3614  3614 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-26 15:20:23.226  3614  3614 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a1de466}
07-26 15:20:23.226  3614  3614 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-26 15:20:23.227  3614  3614 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:20:23.241   786   893 D WifiService: New client listening to asynchronous messages
07-26 15:20:23.250  3614  3614 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-26 15:20:23.260  3614  3614 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-26 15:20:23.260  3614  3614 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-26 15:20:23.272  3614  3614 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:20:23.321   786   804 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c8bbdc:true
,07-26 15:20:23.340   786  1344 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3614 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:20:23.349  3614  3614 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-26 15:20:23.355  3614  3614 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:20:23.356  3614  3614 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-26 15:20:23.367  3614  3614 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-26 15:20:23.385  3614  3614 I cr_Ime  : ImeThread is not enabled.
,07-26 15:20:23.398  3614  3663 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-26 15:20:23.450   786   948 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3614 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:20:23.456  3614  3667 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-26 15:20:23.482  3614  3663 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:20:23.498  3614  3667 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:20:23.536  3614  3667 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-26 15:20:23.548   786   805 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +482ms
,07-26 15:20:23.579  3614  3614 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3614
,07-26 15:20:23.580  3614  3614 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
07-26 15:20:23.580  3614  3614 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,07-26 15:20:23.810  3614  3614 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:20:23.812   786   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:20:23.878   786   948 I ActivityManager: Killing 2829:com.google.android.apps.plus/u0a63 (adj 15): empty #17
,07-26 15:20:23.902   786  1320 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ], android.os.BinderProxy@596500e)
,07-26 15:20:23.902   786   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 15:20:23.903   786   894 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 15:20:24.017  3614  3686 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1756169936
,07-26 15:20:24.023  3614  3686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:24.023  3614  3686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:24.023  3614  3686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:24.023  3614  3686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:24.023  3614  3686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-26 15:20:24.023  3614  3686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d163b0 added. We now have 1 listener(s)
,07-26 15:20:24.026  3614  3686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,07-26 15:20:24.027  3614  3686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-26 15:20:24.028  3614  3686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:20:24.028  3614  3686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-26 15:20:24.030  3614  3686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c34e34f added. We now have 1 listener(s)
,07-26 15:20:24.031  3614  3686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:24.032  3614  3686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:24.032  3614  3686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:24.032  3614  3686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:24.032  3614  3686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:20:24.034  3614  3686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:24.036  3614  3686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,07-26 15:20:24.040  3614  3686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:24.040  3614  3686 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:24.040  3614  3686 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-26 15:20:24.041  3614  3686 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:24.041  3614  3686 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:20:24.042  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:24.043  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:24.062  3614  3614 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:20:24.655  3614  3688 W jxcore-log: Initializing JXcore engine
,07-26 15:20:24.655  3614  3688 W jxcore-log: JXcore engine is ready
,07-26 15:20:24.682  3688  3688 W Thread-314: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[9490]" dev="sockfs" ino=9490 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-26 15:20:24.682  3688  3688 W Thread-314: type=1400 audit(0.0:9): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-26 15:20:24.692  3688  3688 W Thread-314: type=1400 audit(0.0:10): avc: denied { ioctl } for path="socket:[21964]" dev="sockfs" ino=21964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-26 15:20:24.703  3614  3688 W jxcore-log: Starting JXcore engine
,07-26 15:20:24.776  3614  3688 W jxcore-log: Platform android
07-26 15:20:24.776  3614  3688 W jxcore-log: 
,07-26 15:20:24.776  3614  3688 W jxcore-log: Process ARCH arm
07-26 15:20:24.776  3614  3688 W jxcore-log: 
,07-26 15:20:24.933  3614  3688 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:24.933  3614  3688 I jxcore-log: 
,07-26 15:20:24.933  3614  3688 W jxcore-log: JXcore engine is started
,07-26 15:20:24.938  3614  3686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:24.939  3614  3614 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:20:28.904   786  2785 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127257, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-26 15:20:33.232   196   196 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6cca030
,07-26 15:20:33.232   196   196 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
07-26 15:20:33.232   196   196 I rmt_storage: wakelock acquired: 1, error no: 2
07-26 15:20:33.232   196   506 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228146384)
,07-26 15:20:33.308   196   506 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,07-26 15:20:33.308   196   506 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,07-26 15:20:33.308   196   506 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228146384) wakelock released: 1, error no: 0
07-26 15:20:33.308   196   506 I rmt_storage: 
07-26 15:20:33.309   196   196 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6cca030
,07-26 15:20:34.916  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-26 15:20:34.916  3614  3688 I jxcore-log: 
07-26 15:20:34.918  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-26 15:20:34.918  3614  3688 I jxcore-log: 
,07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:34.922  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:34.923  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:20:34.925  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-26 15:20:34.925  3614  3688 I jxcore-log: 
,07-26 15:20:34.927  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-26 15:20:34.927  3614  3688 I jxcore-log: 
,07-26 15:20:35.262  3614  3688 D ExecuteNativeTests: Running unit tests
,07-26 15:20:35.319  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:35.319  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f added. We now have 2 listener(s)
07-26 15:20:35.320  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:35.320  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:35.320  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:35.320  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:35.320  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c added. We now have 2 listener(s)
07-26 15:20:35.320  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:35.320  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:20:35.323  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.326  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:35.327  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:20:35.327  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:35.329  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.330  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:20:35.330  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-26 15:20:35.331  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-26 15:20:35.331  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.332  3614  3688 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-26 15:20:35.332  3614  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-26 15:20:35.332  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:20:35.332  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:20:35.332  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-26 15:20:35.332  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:20:35.333  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:20:35.333  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:20:35.333  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:20:35.333  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:35.333  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:35.333  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:35.333  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f removed from the list
,07-26 15:20:35.333  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.333  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c removed from the list
07-26 15:20:35.333  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.333  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.333  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:35.333  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:35.335  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.335  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.335  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:20:35.335  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
,07-26 15:20:35.336  3614  3688 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-26 15:20:35.336  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.336  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.336  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.336  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:20:35.336  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.336  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.336  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.336  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:20:35.336  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.336  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.336  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.336  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.336  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:35.336  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.337  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:20:35.337  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:20:35.337  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.337  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-26 15:20:35.341  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:20:35.341  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.341  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.341  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.341  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.341  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.341  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:35.342  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
,07-26 15:20:35.342  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.342  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.342  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:20:35.342  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.342  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.342  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:35.342  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.342  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:20:35.342  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:20:35.342  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.342  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.343  3614  3688 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-26 15:20:35.344  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.347  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:35.349  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:20:35.349  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:35.349  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:35.350  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:35.350  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.350  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:20:35.353  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.354  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-26 15:20:35.354  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:20:35.354  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.358  3614  3688 E BluetoothAdapter: Bluetooth LE advertising not supported
,07-26 15:20:35.358  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:20:35.359  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-26 15:20:35.359  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:20:35.361  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:35.361  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:35.362  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:20:35.363  3614  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:35.364  3614  3688 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:20:35.366  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.366  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.366  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.366  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.366  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.366  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:35.366  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.366  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.366  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.366  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.366  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.366  3614  3688 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:20:35.367  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.371  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:35.372  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.372  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:35.372  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:35.372  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:35.372  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.372  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:35.375  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.376  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:35.378  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:35.378  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.378  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:35.379  3614  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:35.379  3614  3688 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:20:35.380  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.380  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.380  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.380  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.380  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.380  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:35.380  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.380  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.380  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.380  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.380  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.380  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.380  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.381  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.381  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.382  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.382  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.382  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.382  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.382  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.382  3614  3688 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:20:35.384  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.387  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:35.388  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.388  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:35.388  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:35.388  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:35.388  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.388  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:35.390  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.391  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:35.392  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.393  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:35.393  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:35.394  3614  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:35.394  3614  3688 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:20:35.394  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.394  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.394  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.394  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.394  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.394  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.394  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.394  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.394  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:35.394  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.394  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.394  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.395  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.395  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.395  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.395  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.395  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.395  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.396  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.396  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.396  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.396  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.396  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.396  3614  3688 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-26 15:20:35.396  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.396  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.396  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.397  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.397  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.397  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.397  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.397  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.397  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.397  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.397  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.397  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.397  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.397  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.397  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.397  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.398  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.398  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.398  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.398  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.398  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.398  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:20:35.398  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.398  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.398  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.398  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.398  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.398  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.398  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.398  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.398  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.399  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.399  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.399  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.399  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.399  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.399  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.399  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.400  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.400  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.400  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.400  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.400  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.400  3614  3688 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-26 15:20:35.400  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.400  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.400  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:20:35.400  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.400  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.400  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.400  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.400  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.400  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.400  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.400  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.400  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.400  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.400  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.401  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.401  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.401  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.401  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.401  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.401  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.401  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.402  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-26 15:20:35.402  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.402  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.402  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.402  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.402  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.402  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.402  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.402  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.402  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.402  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.402  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.402  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.402  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.402  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.402  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.402  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.403  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.403  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.403  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.403  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.403  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.403  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:20:35.403  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:20:35.403  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:20:35.403  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:20:35.403  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:20:35.403  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:20:35.403  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.403  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.403  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.403  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.404  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.404  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.404  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.404  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.404  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.404  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.404  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.404  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.404  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.404  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.405  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.405  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.405  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.405  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.405  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.405  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.405  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.405  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:35.405  3614  3688 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:20:35.405  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:20:35.407  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:35.407  3614  3688 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:20:35.408  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:20:35.408  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-26 15:20:35.408  3614  3688 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:20:35.408  3614  3688 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-26 15:20:35.408  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:35.409  3614  3688 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:20:35.409  3614  3688 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-26 15:20:35.409  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:35.409  3614  3688 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:20:35.409  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-26 15:20:35.411  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-26 15:20:35.412  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-26 15:20:35.412  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-26 15:20:35.412  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-26 15:20:35.412  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-26 15:20:35.412  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-26 15:20:35.412  3614  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:35.413  3614  3688 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-26 15:20:35.413  3614  3730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 378)
07-26 15:20:35.413  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.413  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.413  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.413  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.413  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.413  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.413  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-26 15:20:35.413  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.414  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.414  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.414  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.414  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.414  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.414  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.414  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.415  3614  3730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:20:35.415  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.415  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.416  3614  3731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 378
07-26 15:20:35.416  3614  3731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 378)
07-26 15:20:35.416  3614  3731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 378)
07-26 15:20:35.417  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.417  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.417  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.417  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.417  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.418  3614  3730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 378)
07-26 15:20:35.419  3614  3688 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-26 15:20:35.421  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.421  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.421  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.421  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.421  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.421  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.422  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.422  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.422  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.422  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.422  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.422  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.422  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.422  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.424  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.424  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.425  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.425  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.425  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.425  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.425  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.425  3614  3688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-26 15:20:35.434  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.434  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.434  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.434  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.434  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.434  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.434  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.434  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.434  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.434  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.434  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.434  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.434  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.434  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.435  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.435  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.435  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.435  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.435  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.435  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.435  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.436  3614  3688 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-26 15:20:35.436  3614  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-26 15:20:35.436  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:20:35.436  3614  3688 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-26 15:20:35.436  3614  3688 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:20:35.437  3614  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-26 15:20:35.437  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:20:35.437  3614  3688 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-26 15:20:35.437  3614  3688 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:20:35.437  3614  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:20:35.437  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:20:35.437  3614  3688 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-26 15:20:35.437  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.437  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.437  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.437  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.437  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.437  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.437  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.437  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.437  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.437  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.437  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.437  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.437  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.437  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.438  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.438  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.438  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.438  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.438  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 15:20:35.438  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.438  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.439  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.439  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.439  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.439  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.439  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.439  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.439  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.439  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.439  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.439  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.439  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.439  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.439  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.439  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.439  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.439  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.439  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.439  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.439  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.439  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.439  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.439  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.440  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.441  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.441  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.441  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.441  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.441  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.441  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.441  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.441  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.442  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.442  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.442  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.442  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.442  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.446  3614  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 15:20:35.446  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.447  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-26 15:20:35.447  3614  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 15:20:35.448  3614  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 15:20:35.448  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 15:20:35.448  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.448  3614  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 15:20:35.448  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:20:35.448  3614  3688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:20:35.448  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:20:35.448  3614  3614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 15:20:35.448  3614  3614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 15:20:35.448  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:20:35.448  3614  3741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:20:35.449  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:35.449  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:35.449  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:35.449  3614  3688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:20:35.449  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.449  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.450  3614  3688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:20:35.450  3614  3614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:20:35.450  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.450  3614  3614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:20:35.450  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.450  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.450  3614  3614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:20:35.450  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.450  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.450  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.450  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.450  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.450  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.450  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.450  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.450  3614  3741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 15:20:35.450  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.450  3614  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 15:20:35.450  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.450  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.450  3614  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 15:20:35.450  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.451  3614  3614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 15:20:35.451  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.451  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.451  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.451  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.452  3614  3688 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-26 15:20:35.452  3614  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:20:35.452  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:20:35.452  3614  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:20:35.452  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.452  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.452  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.452  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.452  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.452  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.452  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.452  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.452  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.453  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.453  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.453  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.453  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.453  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.454  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.454  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.454  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.454  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.456  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.457  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.457  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.457  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.457  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.457  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.457  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.457  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.457  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.457  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.457  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.457  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.457  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.457  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.457  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.457  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.457  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.457  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.458  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:35.458  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:35.458  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:35.458  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:35.458  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.458  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.458  3614  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ad9d2f not in the list
07-26 15:20:35.458  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.458  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.458  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:35.458  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.458  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.458  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:35.458  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:35.459  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:35.459  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:35.459  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:35.459  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52a6f3c not in the list
07-26 15:20:35.459  3614  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-26 15:20:35.460  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:20:35.460  3614  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-26 15:20:35.460  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:20:35.460  3614  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-26 15:20:35.460  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:20:35.461  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:20:35.461  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-26 15:20:35.461  3614  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-26 15:20:35.461  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:20:35.461  3614  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-26 15:20:35.461  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:20:35.461  3614  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-26 15:20:35.461  3614  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-26 15:20:35.462  3614  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-26 15:20:35.462  3614  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-26 15:20:35.462  3614  3688 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-26 15:20:35.462  3614  3688 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-26 15:20:35.462  3614  3688 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-26 15:20:35.462  3614  3688 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-26 15:20:35.463  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:35.463  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39ed77d added. We now have 2 listener(s)
07-26 15:20:35.463  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:35.464  3614  3688 D BluetoothAdapter: enable(): BT is already enabled..!
07-26 15:20:35.464   786  1320 D WifiService: setWifiEnabled: true pid=3614, uid=10026
07-26 15:20:35.464   786  1320 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:20:35.464  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:35.465  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f80672 added. We now have 3 listener(s)
07-26 15:20:35.465  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:35.468  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:35.468  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4bdaac3 added. We now have 4 listener(s)
07-26 15:20:35.468  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:35.469  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:35.469  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@49b4f40 added. We now have 5 listener(s)
07-26 15:20:35.469  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:35.470   786  2228 D WifiService: setWifiEnabled: false pid=3614, uid=10026
07-26 15:20:35.470   786  2228 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:20:35.472   786   892 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 15:20:35.472   786   892 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-26 15:20:35.473   786   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:20:35.473   786   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:20:35.474  1800  1882 D BluetoothAdapterState: Current state: ON, message: 23
07-26 15:20:35.474  1800  1882 D BluetoothAdapterProperties: Setting state to 13
07-26 15:20:35.474  1800  1882 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:20:35.475  1800  1882 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:20:35.475  1800  1882 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:20:35.475  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:35.476  1800  1886 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:35.476  1800  1882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-26 15:20:35.479  1800  1800 D HeadsetService: Received stop request...Stopping profile...
07-26 15:20:35.483   786  2786 D DhcpClient: Clearing IP address
07-26 15:20:35.483   198   635 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:20:35.484  1800  2037 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
07-26 15:20:35.484  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluet,oothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.484  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:35.486  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.486  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.486  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:35.488  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.489   786   800 I ActivityManager: Start proc 3748:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-26 15:20:35.493   198   635 D CommandListener: Setting iface cfg
,07-26 15:20:35.498   786  2787 D DhcpClient: Receive thread stopped
,07-26 15:20:35.507  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.512   786   786 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:35.512  1800  1800 D BluetoothMapService: onReceive
07-26 15:20:35.512  1800  1800 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:20:35.512  1800  1800 D BluetoothMapService: STATE_TURNING_OFF
07-26 15:20:35.512  1800  1800 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:35.512  1800  1800 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:35.512  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:35.512  1800  1800 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:35.513   927   941 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:35.513   786   786 D BluetoothHeadset: Proxy object disconnected
,07-26 15:20:35.513  1306  1459 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:35.513   786   786 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:35.513   927   927 D HeadsetProfile: Bluetooth service disconnected
07-26 15:20:35.514  1800  1800 D A2dpService: Received stop request...Stopping profile...
07-26 15:20:35.514  1800  2041 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:20:35.519  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.519   927   927 D BluetoothA2dp: Proxy object disconnected
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.519  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:35.521   786   786 D BluetoothA2dp: Proxy object disconnected
,07-26 15:20:35.522  1800  1800 D HidService: Received stop request...Stopping profile...
07-26 15:20:35.522  1800  1800 D HidService: Stopping Bluetooth HidService
,07-26 15:20:35.523  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:35.523  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:35.523   927   927 D BluetoothInputDevice: Proxy object disconnected
07-26 15:20:35.523   927   927 D HidProfile: Bluetooth service disconnected
,07-26 15:20:35.527  1261  2943 V NativeCrypto: Read error: ssl=0x99ed8600: I/O error during system call, Connection timed out
,07-26 15:20:35.533   786   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-26 15:20:35.533   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
,07-26 15:20:35.533   786   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 5
07-26 15:20:35.533  1261  2943 V NativeCrypto: SSL shutdown failed: ssl=0x99ed8600: I/O error during system call, Broken pipe
07-26 15:20:35.533   786   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:20:35.534  1261  2943 E GCM     : Wifi connection closed with errorCode 20
,07-26 15:20:35.538  1800  1800 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:20:35.539  1800  1800 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:20:35.539  1800  1886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-26 15:20:35.539  1800  1992 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:35.539  1800  1992 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:35.539  1800  1886 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-26 15:20:35.539  1800  1800 D HealthService: Received stop request...Stopping profile...
,07-26 15:20:35.542  1800  1800 D BluetoothMapService: MAP Service closeService in
,07-26 15:20:35.542  1800  1800 D BluetoothMapMasInstance0: MAP Service shutdown
07-26 15:20:35.542  1800  1800 D ObexServerSockets0: shutdown(block = true)
07-26 15:20:35.542  1800  1800 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:20:35.542  1800  1800 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:20:35.542  1800  2037 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 15:20:35.543  1800  2069 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-26 15:20:35.543  1800  2070 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,07-26 15:20:35.543  1800  1800 I BtOppRfcommListener: stopping Accept Thread
07-26 15:20:35.543  1800  2663 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:20:35.543   786   894 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-26 15:20:35.543  1800  2663 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:20:35.544   786   786 D RttService: SCAN_AVAILABLE : 1
07-26 15:20:35.544   786   906 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:20:35.546   786   892 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-26 15:20:35.548   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-26 15:20:35.549   786   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:20:35.550  1800  1800 D PanService: Received stop request...Stopping profile...
,07-26 15:20:35.553  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:35.553  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:35.564   927   927 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-26 15:20:35.564   927   927 D PanProfile: Bluetooth service disconnected
07-26 15:20:35.564  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:35.564  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:20:35.564  1800  1800 V BluetoothAdapterState: isTurningOff()=true
,07-26 15:20:35.564  1800  1800 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:20:35.564  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:35.564  1800  1800 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:20:35.565  1800  1886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-26 15:20:35.565  1800  1992 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:35.566  1800  1992 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:35.566  1800  1992 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:20:35.566  1800  1992 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:20:35.566  1800  1992 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:20:35.566  1800  1992 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:20:35.574  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:35.574  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:35.575  1800  1800 D BluetoothMapService: Received stop request...Stopping profile...
,07-26 15:20:35.575  1800  1800 D BluetoothMapService: stop()
07-26 15:20:35.575  1800  1800 D BluetoothMapAppObserver: deinitObservers()
07-26 15:20:35.575  1800  1800 D BluetoothMapAppObserver: removeReceiver()
07-26 15:20:35.575  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.575  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:35.576   927   927 D BluetoothMap: Proxy object disconnected
07-26 15:20:35.576   927   927 D MapProfile: Bluetooth service disconnected
,07-26 15:20:35.576  1800  1800 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:35.576  1800  1800 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:35.576  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:35.576  1800  1800 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:35.577   198   635 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 15:20:35.578  1800  1800 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:20:35.578  1800  1886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:20:35.578  1800  1800 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-26 15:20:35.578  1800  1800 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:35.578  1800  1800 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:35.578  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:35.578  1800  1800 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:35.578  1800  1800 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:20:35.578  1800  1886 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-26 15:20:35.578   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-26 15:20:35.578  1800  1800 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:20:35.579  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:35.579  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:35.580  1800  1800 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:35.580  1800  1800 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:35.580  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:35.580  1800  1800 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:35.580  1800  1800 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 15:20:35.580  1800  1800 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:20:35.581  1800  1800 D BluetoothMapService: MAP Service closeService in
07-26 15:20:35.581  1800  1800 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:35.581  1800  1800 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:35.581  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:20:35.581  1800  1800 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:35.581  1800  1800 D BluetoothMapService: cleanup()
07-26 15:20:35.581  1800  1800 D BluetoothMapService: MAP Service closeService in
07-26 15:20:35.582  1800  1882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-26 15:20:35.582  1800  1882 D BluetoothAdapterProperties: Setting state to 15
07-26 15:20:35.582  1800  1882 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-26 15:20:35.582  1800  1882 I BluetoothAdapterState: Entering BleOnState
07-26 15:20:35.582  1306  1318 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:20:35.582   786   804 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:35.582   927   941 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:20:35.583   927  1452 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:20:35.583   786   804 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:20:35.583   786   804 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:35.583   786   804 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:35.584   927   942 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:20:35.585  3748  3748 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-26 15:20:35.587   927   941 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:35.587   927  1452 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:20:35.588   927   942 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:35.589  1800  1882 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-26 15:20:35.589  1800  1882 D BluetoothAdapterProperties: Setting state to 16
07-26 15:20:35.589  1800  1882 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-26 15:20:35.590  1800  1882 D BluetoothAdapterProperties: onBleDisable
07-26 15:20:35.591  1800  1882 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:20:35.591  1800  1883 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,07-26 15:20:35.592  1800  1886 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:35.592  1800  1992 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-26 15:20:35.592  1800  1992 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:35.592  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:35.594  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.595  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.596   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
07-26 15:20:35.596  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:35.600   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-26 15:20:35.602   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-26 15:20:35.608   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-26 15:20:35.611  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:20:35.612   198   635 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:20:35.613   786   894 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-26 15:20:35.613   786   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:20:35.615   786   804 D Tethering: MasterInitialState.processMessage what=3
07-26 15:20:35.615   198   635 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:20:35.617  3614  3614 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-26 15:20:35.620  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:35.621  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.626   786   804 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a922e07:true
,07-26 15:20:35.630  1437  1437 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-26 15:20:35.635  3748  3748 D LocalBluetoothProfileManager: Adding local MAP profile
,07-26 15:20:35.637  3748  3748 D BluetoothMap: Create BluetoothMap proxy object
,07-26 15:20:35.643  1602  1650 D MdnsClient: Multicast lock held. Releasing
,07-26 15:20:35.647  3748  3748 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-26 15:20:35.655  3748  3748 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:35.664   786   893 D WifiService: New client listening to asynchronous messages
,07-26 15:20:35.680   198   635 E Netd    : netlink response contains error (No such file or directory)
,07-26 15:20:35.681   786   894 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-26 15:20:35.683   786   892 D DhcpClient: doQuit
,07-26 15:20:35.684   786   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-26 15:20:35.684   786  2786 D DhcpClient: onQuitting
,07-26 15:20:35.687  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:35.687  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:35.687  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.687  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:35.688  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:35.688  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:35.689  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:35.689  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:20:35.694  1800  1886 I bt_hci  : shut_down
,07-26 15:20:35.694  1800  1891 D bt_hwcfg: hw_epilog_process
,07-26 15:20:35.697  1800  1891 I bt_vendor: low_power_mode_cb
,07-26 15:20:35.704  1422  1422 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-26 15:20:35.715  1422  1422 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-26 15:20:35.717  1800  1891 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-26 15:20:35.717  1800  1891 I bt_vendor: epilog_cb
07-26 15:20:35.717  1800  1891 I bt_hci  : epilog_finished_callback
,07-26 15:20:35.718  1800  1886 I bt_hci_h4: hal_close
,07-26 15:20:35.719  1800  1886 I bt_userial_vendor: device fd = 49 close
,07-26 15:20:35.728  1422  1422 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-26 15:20:35.731  1800  1883 D bt_stack_manager: event_shut_down_stack finished.
07-26 15:20:35.731  1800  1882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-26 15:20:35.732  1800  1882 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-26 15:20:35.732  1800  1800 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:20:35.732  1800  1800 D BtGatt.GattService: Received stop request...Stopping profile...
,07-26 15:20:35.732  1800  1800 D BtGatt.GattService: stop()
07-26 15:20:35.733  1800  1800 D BtGatt.AdvertiseManager: advertise clients cleared
,07-26 15:20:35.733  1800  1800 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:35.733  1800  1800 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:20:35.733  1800  1800 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:35.733  1800  1800 V BluetoothAdapterState: isBleTurningOff()=true
07-26 15:20:35.733  1800  1882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-26 15:20:35.734  1800  1882 D BluetoothAdapterProperties: Setting state to 10
07-26 15:20:35.734  1800  1882 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 15:20:35.734  1800  1882 I BluetoothAdapterState: Entering OffState
07-26 15:20:35.734   786   804 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-26 15:20:35.740  1800  1800 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-26 15:20:35.740  1800  1800 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-26 15:20:35.740  1800  1800 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-26 15:20:35.741  1800  1883 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-26 15:20:35.746  1800  1883 D bt_stack_manager: event_clean_up_stack finished.
07-26 15:20:35.751  1800  1800 I art     : System.exit called, status: 0
,07-26 15:20:35.751  1800  1800 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 15:20:35.759  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:35.765  1422  1422 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-26 15:20:35.784  1422  1422 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-26 15:20:35.786   786  1344 I ActivityManager: Process com.android.bluetooth (pid 1800) has died
,07-26 15:20:35.805   786  1320 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1602 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:20:35.861  1602  3780 W DriveInitializer: Background init thread started
,07-26 15:20:35.886  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:35.890   786   892 D wifi    : In wifi stop Hal
,07-26 15:20:35.890   786   892 D wifi    : halHandle = 0xa076db20, mVM = 0xb4d3c000, mCls = 0x100bda
07-26 15:20:35.890   786  1411 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-26 15:20:35.890   786  1411 D WifiHAL : Got a signal to exit!!!
,07-26 15:20:35.890   786  1411 I WifiHAL : Exit wifi_event_loop
,07-26 15:20:35.891   786   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,07-26 15:20:35.891   786   892 E WifiHAL : Event processing terminated
,07-26 15:20:35.891   786   892 D wifi    : In wifi cleaned up handler
,07-26 15:20:35.891   786   892 I WifiHAL : Internal cleanup completed
07-26 15:20:35.891  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:35.892  1261  1589 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:20:35.892  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:35.899  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:20:35.912   786   971 I ActivityManager: Start proc 3785:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-26 15:20:35.913  3748  3748 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:35.957  1602  3780 W DriveInitializer: Background init thread ended
,07-26 15:20:35.965  3785  3785 D AdapterServiceConfig: Adding HeadsetService
,07-26 15:20:35.965  3785  3785 D AdapterServiceConfig: Adding A2dpService
07-26 15:20:35.965  3785  3785 D AdapterServiceConfig: Adding HidService
07-26 15:20:35.965  3785  3785 D AdapterServiceConfig: Adding HealthService
07-26 15:20:35.965  3785  3785 D AdapterServiceConfig: Adding PanService
07-26 15:20:35.965  3785  3785 D AdapterServiceConfig: Adding GattService
07-26 15:20:35.966  3785  3785 D AdapterServiceConfig: Adding BluetoothMapService
,07-26 15:20:35.978   786   971 I ActivityManager: Killing 2722:com.google.android.gms.feedback/u0a7 (adj 15): empty #17
,07-26 15:20:36.000   786  1411 D wifi    : set interface wlan0 flags (DOWN)
07-26 15:20:36.000   786   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-26 15:20:36.016  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:36.021  1261  3802 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:20:36.023  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:36.041   786   797 I ActivityManager: Start proc 3804:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-26 15:20:36.052  1261  3802 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-26 15:20:36.085  3804  3804 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-26 15:20:36.122   786   797 I ActivityManager: Killing 3044:com.google.android.youtube/u0a71 (adj 15): empty #17
,07-26 15:20:36.126  3804  3804 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-26 15:20:36.150   786  1344 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ], android.os.BinderProxy@c46b82e)
,07-26 15:20:36.150   786   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-26 15:20:36.151   786   894 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-26 15:20:36.201   786   892 E WifiStateMachine: Error! unhandled message{ when=-2m14s567ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:20:36.203   786   804 D Tethering: InitialState.processMessage what=4
,07-26 15:20:36.210   786   804 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-26 15:20:36.228  3804  3816 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-26 15:20:36.239   786   971 I ActivityManager: Start proc 3819:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-26 15:20:36.293  3819  3819 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-26 15:20:36.297  1261  1261 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=276c1050-fdf5-456d-a3f6-589bbe116979
,07-26 15:20:36.301  3819  3819 I MultiDex: VM with version 2.1.0 has multidex support
07-26 15:20:36.301  3819  3819 I MultiDex: install
07-26 15:20:36.301  3819  3819 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-26 15:20:36.303  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:20:36.303  1261  1261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:20:36.370  3819  3819 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-26 15:20:36.370  3819  3819 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-26 15:20:36.370  3819  3819 I GAv4    :   adb logcat -s GAv4
,07-26 15:20:36.381  3819  3819 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:20:36.391  3819  3840 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:20:36.466  1261  1514 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:36.509  1602  3783 D UdcContextInitService: registered all accounts: true
,07-26 15:20:36.509  1261  1563 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:36.517  1261  1552 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-26 15:20:36.585  3819  3819 I NSApplication: Starting up...
07-26 15:20:36.585  1261  1552 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-26 15:20:36.601   786  1321 I ActivityManager: Start proc 3867:com.google.android.apps.photos/u0a83 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-26 15:20:36.603   786  1321 I ActivityManager: Killing 2283:com.google.android.keep/u0a52 (adj 15): empty #17
,07-26 15:20:36.677  1602  1602 V Herrevad: NQAS connected
,07-26 15:20:36.709  1261  1552 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-26 15:20:36.712  1602  1650 W Herrevad: Invalid mccmnc 
,07-26 15:20:36.715  1602  1650 W Herrevad: Invalid mccmnc 
,07-26 15:20:36.717  1602  1630 V UdcCtxListenerSrv: handle intent
,07-26 15:20:36.735  3819  3819 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-26 15:20:36.999   786   948 I ActivityManager: Start proc 3888:com.google.android.apps.plus/u0a63 for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver
07-26 15:20:36.999   786   948 I ActivityManager: Killing 3183:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,07-26 15:20:37.250   786  1320 I ActivityManager: Killing 2770:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-26 15:20:37.349   786  1320 I ActivityManager: Start proc 3921:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,07-26 15:20:37.458  3921  3921 W InstanceID/Rpc: Found 10007
,07-26 15:20:37.476   786   797 I ActivityManager: Killing 3309:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-26 15:20:38.487   786  2228 D WifiService: setWifiEnabled: true pid=3614, uid=10026
,07-26 15:20:38.487   786  2228 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:20:38.489   198   635 D SoftapController: Softap fwReload - Ok
,07-26 15:20:38.491   198   635 D CommandListener: Setting iface cfg
,07-26 15:20:38.491   198   635 D CommandListener: Trying to bring down wlan0
07-26 15:20:38.492   198   635 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:20:38.494   786   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-26 15:20:38.744  1261  1552 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-26 15:20:38.745  1261  1552 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-26 15:20:39.255   786   892 D wifi    : set interface wlan0 flags (UP)
07-26 15:20:39.255   786   892 I WifiHAL : Initializing wifi
07-26 15:20:39.255   786   892 I WifiHAL : Creating socket
,07-26 15:20:39.256   786   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-26 15:20:39.256   786   892 D wifi    : Did set static halHandle = 0xa076db20
07-26 15:20:39.256   786   892 D wifi    : halHandle = 0xa076db20, mVM = 0xb4d3c000, mCls = 0x201aa6
07-26 15:20:39.256   786   892 D wifi    : array field set
07-26 15:20:39.256   786   892 I WifiNative-HAL: interface[0] = p2p0
07-26 15:20:39.256   786   892 I WifiNative-HAL: interface[1] = wlan0
,07-26 15:20:39.257   786   804 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-26 15:20:39.259   786   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-26 15:20:39.261  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:39.261  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:39.262   786   892 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-26 15:20:39.263   786  3941 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602823392
07-26 15:20:39.263   786  3941 D wifi    : waitForHalEvents called, vm = 0xb4d3c000, obj = 0x201aa6, env = 0xa07e7a80
,07-26 15:20:39.304  3942  3942 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:20:39.327  3942  3942 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:20:39.336  3942  3942 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:20:40.303  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:40.303  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:40.304  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:40.304  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:40.307  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:40.307  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:40.307  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:40.307  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:20:40.317   786   892 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:20:40.350   786   892 D WifiConfigStore: loaded 0 passpoint configs
07-26 15:20:40.354   786   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-26 15:20:40.354   786   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:20:40.354   786   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,07-26 15:20:40.354   786   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-26 15:20:40.356   786   892 D WifiNative-HAL: Setting external_sim to 1
,07-26 15:20:40.356   786   892 D wifi    : setting dfs flag to true, 0x9b3fd418
07-26 15:20:40.357   786   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:20:40.357   786   892 D wifi    : setting scan oui 0x9b3fd418
07-26 15:20:40.357   786   892 D WifiHAL : Sending mac address OUI
,07-26 15:20:40.371   786   892 E native  : do suspend false
07-26 15:20:40.376   786   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-26 15:20:40.378   786   786 D RttService: SCAN_AVAILABLE : 3
07-26 15:20:40.378   786   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:20:40.380   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-26 15:20:40.382   198   635 D CommandListener: Setting iface cfg
,07-26 15:20:40.382   198   635 D CommandListener: Trying to bring up p2p0
07-26 15:20:40.382   786   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 15:20:40.387   786   891 D WifiNative-HAL: p2pGetDeviceAddress
07-26 15:20:40.387   786   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-26 15:20:41.065   786  1321 I ActivityManager: Killing 2479:com.android.providers.calendar/u0a1 (adj 15): empty #17
,07-26 15:20:41.489   786   798 D WifiService: setWifiEnabled: false pid=3614, uid=10026
,07-26 15:20:41.489   786   798 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:20:41.490   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-26 15:20:41.492   786   786 D RttService: SCAN_AVAILABLE : 1
,07-26 15:20:41.492   786   906 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:20:41.502   786   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-26 15:20:41.502   198   635 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:20:41.513   786   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-26 15:20:41.515  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:41.515  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:41.515  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:41.515  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:41.516  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:41.516  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:41.516  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:41.516  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:20:41.532  3942  3942 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-26 15:20:42.534  3942  3942 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-26 15:20:42.537  3942  3942 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-26 15:20:42.544  3942  3942 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-26 15:20:42.548   786   892 D wifi    : In wifi stop Hal
07-26 15:20:42.548   786   892 D wifi    : halHandle = 0xa076db20, mVM = 0xb4d3c000, mCls = 0x201aa6
,07-26 15:20:42.549   786  3941 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-26 15:20:42.549   786  3941 D WifiHAL : Got a signal to exit!!!
07-26 15:20:42.549   786  3941 I WifiHAL : Exit wifi_event_loop
,07-26 15:20:42.551  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:42.552  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:42.552  1261  1589 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:20:42.553   786   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-26 15:20:42.553   786   892 E WifiHAL : Event processing terminated
07-26 15:20:42.553   786   892 D wifi    : In wifi cleaned up handler
,07-26 15:20:42.553   786   892 I WifiHAL : Internal cleanup completed
,07-26 15:20:42.671   786  3941 D wifi    : set interface wlan0 flags (DOWN)
,07-26 15:20:42.671   786   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-26 15:20:42.882   786   804 D Tethering: InitialState.processMessage what=4
,07-26 15:20:42.909   786   804 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-26 15:20:44.551   786   804 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@510ef11:true
,07-26 15:20:44.551  3785  3785 D BluetoothAdapterState: make() - Creating AdapterState
07-26 15:20:44.553  3785  3785 I bt_bluedroid: init
07-26 15:20:44.553  3785  3978 I BluetoothAdapterState: Entering OffState
07-26 15:20:44.554  3785  3979 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-26 15:20:44.554  3785  3979 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:20:44.554  3785  3979 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:20:44.554  3785  3979 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-26 15:20:44.555  3785  3785 I bt_bluedroid: get_profile_interface socket
,07-26 15:20:44.555  3785  3785 I bt_bluedroid: get_profile_interface sdp
07-26 15:20:44.557  3785  3796 I bt_bluedroid: config_hci_snoop_log
07-26 15:20:44.557   786   804 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-26 15:20:44.559  3785  3978 D BluetoothAdapterState: Current state: OFF, message: 0
07-26 15:20:44.559  3785  3978 D BluetoothAdapterProperties: Setting state to 14
07-26 15:20:44.559  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-26 15:20:44.560  3785  3978 D BluetoothBondStateMachine: make
07-26 15:20:44.562  3785  3982 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-26 15:20:44.562  3785  3982 D BluetoothAdapterProperties: Name is: Nexus 5
07-26 15:20:44.565  3785  3785 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-26 15:20:44.567  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:44.567  3785  3978 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:20:44.568  3785  3785 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:20:44.568  3785  3785 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:20:44.568  3785  3785 D BtGatt.GattService: start()
07-26 15:20:44.568  3785  3785 I bt_bluedroid: get_profile_interface gatt
,07-26 15:20:44.568  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:44.568  3785  3785 D BtGatt.AdvertiseManager: advertise manager created
07-26 15:20:44.569  3785  3983 I BluetoothBondStateMachine: StableState(): Entering Off State
07-26 15:20:44.571  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:44.572  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:44.572  3785  3785 V BluetoothAdapterState: isBleTurningOn()=true
07-26 15:20:44.572  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:44.572  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-26 15:20:44.572  3785  3978 I bt_bluedroid: enable
07-26 15:20:44.572  3785  3979 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-26 15:20:44.572  3785  3979 I bt_hci  : start_up
07-26 15:20:44.576  3785  3979 I bt_vendor: alloc value 0xb3979631
07-26 15:20:44.576  3785  3979 I bt_vendor: init
07-26 15:20:44.576  3785  3979 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-26 15:20:44.576  3785  3979 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-26 15:20:44.614  3785  3979 D bt_hci  : start_up starting async portion
,07-26 15:20:44.615  3785  3986 I bt_hci  : event_finish_startup
07-26 15:20:44.615  3785  3986 I bt_hci_h4: hal_open
07-26 15:20:44.615  3785  3986 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-26 15:20:44.617  3785  3986 I bt_userial_vendor: device fd = 49 open
,07-26 15:20:44.702  3785  3986 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:20:44.729  3785  3986 D bt_hwcfg: Chipset BCM4335C0
,07-26 15:20:44.729  3785  3986 D bt_hwcfg: Target name = [BCM4335C0]
07-26 15:20:44.730  3785  3986 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-26 15:20:45.207  3785  3986 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-26 15:20:45.208  3785  3986 D bt_hwcfg: Settlement delay -- 100 ms
,07-26 15:20:45.208  3785  3986 I bt_hwcfg: Setting fw settlement delay to 100 
,07-26 15:20:45.325  3785  3986 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:20:45.326  3785  3986 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-26 15:20:45.354  3785  3986 I bt_hwcfg: vendor lib fwcfg completed
,07-26 15:20:45.354  3785  3986 I bt_vendor: firmware callback
,07-26 15:20:45.354  3785  3986 I bt_hci  : firmware_config_callback
,07-26 15:20:45.366  3785  3988 I bt_btu  : btu_task pending for preload complete event
,07-26 15:20:45.366  3785  3988 I bt_btu_task: Bluetooth chip preload is complete
,07-26 15:20:45.366  3785  3988 I bt_btu  : btu_task received preload complete event
,07-26 15:20:45.377  3785  3988 I         : BTE_InitTraceLevels -- TRC_HCI
,07-26 15:20:45.377  3785  3988 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_AVDT
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_AVRC
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_A2D
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_BNEP
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_BTM
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_GAP
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_PAN
,07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_GATT
07-26 15:20:45.378  3785  3988 I         : BTE_InitTraceLevels -- TRC_SMP
07-26 15:20:45.379  3785  3988 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:20:45.379  3785  3988 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-26 15:20:45.607  3785  3988 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f79b5
,07-26 15:20:45.607  3785  3988 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f79b5 
,07-26 15:20:45.696  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:20:45.696  3785  3982 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-26 15:20:45.734  3785  3982 D BluetoothAdapterProperties: Name is: Nexus 5
07-26 15:20:45.736  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:45.736  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:45.736  3785  3982 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:45.736  3785  3982 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-26 15:20:45.737  3785  3982 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-26 15:20:45.737  3785  3982 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-26 15:20:45.738  3785  3982 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-26 15:20:45.738  3785  3982 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-26 15:20:45.738  3785  3982 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
,07-26 15:20:45.738  3785  3982 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-26 15:20:45.738  3785  3982 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-26 15:20:45.740  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-26 15:20:45.741  3785  3785 I BluetoothHidServiceJni: classInitNative: succeeds
07-26 15:20:45.741  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.745  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-26 15:20:45.746  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.747  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-26 15:20:45.748  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.750  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-26 15:20:45.753  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.757  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-26 15:20:45.758  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.759  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,07-26 15:20:45.760  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.764  3785  3982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-26 15:20:45.765  3785  3785 D HidService: getHidService(): service is NULL
07-26 15:20:45.766  3785  3982 D bt_hci  : do_postload posting postload work item
07-26 15:20:45.766  3785  3986 I bt_hci  : event_postload
07-26 15:20:45.766  3785  3986 I bt_vendor: sco_config_cb
07-26 15:20:45.766  3785  3986 I bt_hci  : sco_config_callback postload finished.
07-26 15:20:45.767  3785  3982 D bt_bte_conf: Device ID record 1 : primary
07-26 15:20:45.767  3785  3982 D bt_bte_conf:   vendorId            = 000f
07-26 15:20:45.767  3785  3982 D bt_bte_conf:   vendorIdSource      = 0001
07-26 15:20:45.767  3785  3982 D bt_bte_conf:   product             = 1200
,07-26 15:20:45.767  3785  3982 D bt_bte_conf:   version             = 1436
07-26 15:20:45.767  3785  3982 D bt_bte_conf:   clientExecutableURL = 
07-26 15:20:45.767  3785  3982 D bt_bte_conf:   serviceDescription  = 
07-26 15:20:45.767  3785  3982 D bt_bte_conf:   documentationURL    = 
07-26 15:20:45.767  3785  3986 I bt_vendor: low_power_mode_cb
07-26 15:20:45.767  3785  3982 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-26 15:20:45.767  3785  3979 D bt_stack_manager: event_start_up_stack finished
07-26 15:20:45.767  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-26 15:20:45.767  3785  3978 D BluetoothAdapterProperties: Setting state to 15
07-26 15:20:45.767  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-26 15:20:45.768  3785  3978 I BluetoothAdapterState: Entering BleOnState
,07-26 15:20:45.769  3785  3978 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-26 15:20:45.770  3785  3978 D BluetoothAdapterProperties: Setting state to 11
07-26 15:20:45.770  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-26 15:20:45.772  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
,07-26 15:20:45.775  3785  3785 D HeadsetService: Received start request. Starting profile...
,07-26 15:20:45.776  3785  3785 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-26 15:20:45.776  3785  3785 D HeadsetStateMachine: make
,07-26 15:20:45.781  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:45.783  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:45.786  3785  3978 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:20:45.786   927  1110 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:45.787   927  1110 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:45.788  3785  3785 D HeadsetStateMachine: max_hf_connections = 1
07-26 15:20:45.788  3785  3785 I bt_bluedroid: get_profile_interface handsfree
07-26 15:20:45.788  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-26 15:20:45.788  3785  3982 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-26 15:20:45.791  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:45.791  3785  3785 D A2dpService: Received start request. Starting profile...
07-26 15:20:45.791  3785  3785 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-26 15:20:45.792  3785  3785 I bt_bluedroid: get_profile_interface avrcp
,07-26 15:20:45.801  3785  3785 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-26 15:20:45.801  3785  3785 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:20:45.801  3785  3785 D A2dpStateMachine: make
07-26 15:20:45.802  3785  3785 I bt_bluedroid: get_profile_interface a2dp
,07-26 15:20:45.803  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-26 15:20:45.804  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
,07-26 15:20:45.805  3785  4018 D A2dpStateMachine: Enter Disconnected: -2
,07-26 15:20:45.810  3785  3785 D HidService: Received start request. Starting profile...
,07-26 15:20:45.811  3785  3785 I bt_bluedroid: get_profile_interface hidhost
07-26 15:20:45.811  3785  3785 D HidService: setHidService(): set to: null
07-26 15:20:45.811  3785  3785 I BluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:20:45.812  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:45.812  3785  3982 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d9099
07-26 15:20:45.812  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-26 15:20:45.812  3785  3785 D HealthService: Received start request. Starting profile...
07-26 15:20:45.814  3785  3785 I bt_bluedroid: get_profile_interface health
07-26 15:20:45.814  3785  3785 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-26 15:20:45.815  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
,07-26 15:20:45.816  3785  3785 D PanService: Received start request. Starting profile...
07-26 15:20:45.816  3785  3785 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:20:45.816  3785  3785 I bt_bluedroid: get_profile_interface pan
07-26 15:20:45.816  3785  3982 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-26 15:20:45.817  3785  3785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:45.818  3785  3785 D BluetoothMapService: Received start request. Starting profile...
07-26 15:20:45.818  3785  3785 D BluetoothMapService: start()
,07-26 15:20:45.819  3748  3748 D BluetoothInputDevice: Proxy object connected
,07-26 15:20:45.819  3748  3748 D HidProfile: Bluetooth service connected
07-26 15:20:45.820  3748  3748 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:20:45.820  3748  3748 D PanProfile: Bluetooth service connected
07-26 15:20:45.821  3748  3748 D BluetoothMap: Proxy object connected
07-26 15:20:45.821  3748  3748 D MapProfile: Bluetooth service connected
07-26 15:20:45.821  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.823  3748  3748 D BluetoothMap: Bluetooth is Not enabled
,07-26 15:20:45.824  3785  3785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-26 15:20:45.824  3785  3785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-26 15:20:45.824  3785  3785 D BluetoothMapAppObserver: createReceiver()
07-26 15:20:45.825  3785  3785 D BluetoothMapAppObserver: initObservers()
,07-26 15:20:45.825  3785  3785 D BluetoothMapAppObserver: getEnabledAccountItems()
07-26 15:20:45.832  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:45.833  3785  3785 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:45.833  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:45.833  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:45.834  3785  4014 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:45.834  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:45.835  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:45.835  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-26 15:20:45.835  3785  3978 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:20:45.835  3785  3978 D BluetoothAdapterProperties: State =  11
07-26 15:20:45.835  3785  3978 D BluetoothAdapterProperties: Setting state to 12
07-26 15:20:45.835  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 15:20:45.836  1306  1319 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:45.836   786   804 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:45.836  3748  3758 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:20:45.837  3785  3978 I BluetoothAdapterState: Entering OnState
,07-26 15:20:45.837  3785  3982 D BluetoothAdapterProperties: Scan Mode:21
,07-26 15:20:45.838  3785  3982 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:20:45.838  3748  3760 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:20:45.838   927  1452 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:20:45.840  3614  3614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:45.841   927   941 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:20:45.843   786   804 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:45.843   786   804 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:45.843   786   804 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:45.844  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:45.845  3748  3758 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:20:45.845   927   927 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:20:45.845   927   927 D PanProfile: Bluetooth service connected
07-26 15:20:45.845   927   927 D BluetoothInputDevice: Proxy object connected
07-26 15:20:45.845   927   927 D HidProfile: Bluetooth service connected
07-26 15:20:45.846   786   786 D BluetoothA2dp: Proxy object connected
,07-26 15:20:45.849  3748  3760 D BluetoothMap: onBluetoothStateChange: up=true
,07-26 15:20:45.849   927   941 D BluetoothPbap: onBluetoothStateChange: up=true
,07-26 15:20:45.850  3785  3785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:20:45.850  3785  3785 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-26 15:20:45.851   927   942 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:45.851   927  1452 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:20:45.852  3785  3785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:20:45.853   927   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:20:45.854  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:20:45.856  3785  3785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:45.857   786   786 I Telecom : BluetoothPhoneService: queryPhoneState
07-26 15:20:45.857  3785  3785 D ObexServerSockets: Succeed to create listening sockets 
07-26 15:20:45.857  3785  3785 D ObexServerSockets0: startAccept()
07-26 15:20:45.857  3785  3785 D ObexServerSockets0: prepareForNewConnect()
07-26 15:20:45.860  3785  3785 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-26 15:20:45.860  3785  3785 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-26 15:20:45.860   927   927 D BluetoothMap: Proxy object connected
,07-26 15:20:45.860   927   927 D MapProfile: Bluetooth service connected
,07-26 15:20:45.860   927   927 D BluetoothMap: getConnectedDevices()
07-26 15:20:45.860  3785  3785 D BluetoothMapService: onReceive
07-26 15:20:45.860  3785  3785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:20:45.860  3785  3785 D BluetoothMapService: STATE_ON
07-26 15:20:45.861  3785  4024 D ObexServerSockets0: Accepting socket connection...
07-26 15:20:45.863  3785  4025 D ObexServerSockets0: Accepting socket connection...
,07-26 15:20:45.864   927   927 D BluetoothA2dp: Proxy object connected
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:45.864  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:45.865  3748  3748 D LocalBluetoothProfileManager: Adding local A2DP profile
07-26 15:20:45.866  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:45.867  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:45.869  3748  3748 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-26 15:20:45.869  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:45.871  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:45.875  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:45.881  3785  3785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-26 15:20:45.881  3785  3785 D ObexServerSockets0: prepareForNewConnect()
,07-26 15:20:45.885  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.886   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.888  3748  3748 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-26 15:20:45.889  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.889   927  1110 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-26 15:20:45.893   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.905  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.906  3748  3748 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-26 15:20:45.907  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.918  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.919  3748  3748 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-26 15:20:45.920  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.924   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.927   927  1110 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-26 15:20:45.929  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.932  3748  3748 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-26 15:20:45.933   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.934  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.937   786   786 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.937   927  1452 D BluetoothHeadset: Proxy object connected
07-26 15:20:45.937   927   927 D HeadsetProfile: Bluetooth service connected
,07-26 15:20:45.937   786   786 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.937  1261  1261 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-26 15:20:45.937  1306  1720 D BluetoothHeadset: Proxy object connected
07-26 15:20:45.938   786   786 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.942   786   804 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.942   786   804 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.946  1261  1261 I BeaconBle: BLE 'JB+' software access layer enabled
,07-26 15:20:45.947  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.948  3748  3748 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-26 15:20:45.950  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.952   927   942 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.959  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.959  3748  3748 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-26 15:20:45.960  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.963   927   927 D HeadsetProfile: Bluetooth service connected
,07-26 15:20:45.972  3748  3748 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.972  3748  3758 D BluetoothHeadset: Proxy object connected
,07-26 15:20:45.974  3748  3748 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-26 15:20:45.978  3748  3748 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:45.978  3748  3748 D BluetoothA2dp: Proxy object connected
,07-26 15:20:45.983  1261  4041 D BluetoothAdapter: startLeScan(): null
,07-26 15:20:45.983  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:20:45.984   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:45.985  3748  3748 D HeadsetProfile: Bluetooth service connected
,07-26 15:20:45.986  1261  4041 D BluetoothAdapter: STATE_ON
,07-26 15:20:45.989   927  1110 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-26 15:20:45.990  3785  3796 D BtGatt.GattService: registerClient() - UUID=ce68115c-0d4f-4516-8e1f-382c9f6d1fa3
07-26 15:20:45.991   927  1110 D MapProfile: getConnectionStatus: status is: 0
07-26 15:20:45.991  3785  3982 D BtGatt.GattService: onClientRegistered() - UUID=ce68115c-0d4f-4516-8e1f-382c9f6d1fa3, clientIf=5
,07-26 15:20:45.991  1261  1275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-26 15:20:45.992  3785  4009 D BtGatt.GattService: start scan with filters
07-26 15:20:45.993  3748  3748 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:45.996   927   927 D BluetoothPbap: Proxy object connected
07-26 15:20:45.996   927   927 D PbapServerProfile: Bluetooth service connected
,07-26 15:20:45.999  3785  3985 D BtGatt.ScanManager: handling starting scan
,07-26 15:20:45.999  3785  4043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:46.001  3785  3985 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-26 15:20:46.001  3785  3985 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-26 15:20:46.001  3785  3985 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
,07-26 15:20:46.002  3785  3982 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-26 15:20:46.006  3748  3748 D BluetoothPbap: Proxy object connected
07-26 15:20:46.006  3748  3748 D PbapServerProfile: Bluetooth service connected
,07-26 15:20:46.012  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:46.018  1261  4046 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:20:46.020  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:46.028  3785  4050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:46.034  3785  4050 I BtOppRfcommListener: Accept thread started.
,07-26 15:20:46.039   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:46.042   927  1110 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-26 15:20:46.042  1261  4046 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-26 15:20:46.044   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:46.060   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:46.061   927  1110 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-26 15:20:46.064   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:46.080   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:46.081   927  1110 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-26 15:20:46.083   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:46.503  3785  3982 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:46.618  1261  4015 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:20:46.619  1261  4015 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: java.io.IOException: Not connected
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:46.619  1261  4015 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:46.742  3785  3982 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:46.775  3785  3982 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:47.326  3785  3982 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:47.422  3785  3982 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:47.510  3785  3978 D BluetoothAdapterState: Current state: ON, message: 23
07-26 15:20:47.510  3785  3978 D BluetoothAdapterProperties: Setting state to 13
07-26 15:20:47.510  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-26 15:20:47.511  3785  3978 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:20:47.535  1261  4041 D BluetoothAdapter: stopLeScan()
,07-26 15:20:47.541  3785  3978 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:20:47.546  3785  3785 D BluetoothMapService: onReceive
07-26 15:20:47.546  3785  3785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:20:47.546  3785  3785 D BluetoothMapService: STATE_TURNING_OFF
,07-26 15:20:47.546  3785  3785 D BluetoothMapService: MAP Service closeService in
,07-26 15:20:47.546  3785  3785 D BluetoothMapMasInstance0: MAP Service shutdown
,07-26 15:20:47.546  3785  3785 D ObexServerSockets0: shutdown(block = true)
07-26 15:20:47.547  3785  3785 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:20:47.547  3785  3785 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:20:47.547  3785  4024 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-26 15:20:47.547  3785  4005 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 15:20:47.548  3785  4025 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,07-26 15:20:47.549  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:47.549  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:47.549  3785  3785 I BtOppRfcommListener: stopping Accept Thread
07-26 15:20:47.549  3785  4050 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:20:47.549  3785  4050 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:20:47.549  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:20:47.550  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:47.551  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:47.551  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:47.551  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:47.551  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:47.552  3785  3982 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:20:47.557  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.557  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.558  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-26 15:20:47.558  3785  3785 D HeadsetService: Received stop request...Stopping profile...
07-26 15:20:47.560  3785  3785 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:47.560  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.560  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:47.560  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:47.560   786   786 D BluetoothHeadset: Proxy object disconnected
,07-26 15:20:47.560  3748  3760 D BluetoothHeadset: Proxy object disconnected
,07-26 15:20:47.561   927  1452 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:47.561   786   786 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:47.561  1306  1459 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:47.561   786   786 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:47.561  3785  3785 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:20:47.562  3785  3785 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:20:47.562  3785  3988 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:47.562  3785  3988 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-26 15:20:47.562  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-26 15:20:47.562  3785  3982 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
07-26 15:20:47.586  3785  3785 D A2dpService: Received stop request...Stopping profile...
07-26 15:20:47.586  3785  4018 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:20:47.588   786   786 D BluetoothA2dp: Proxy object disconnected
07-26 15:20:47.588  3785  3785 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:47.588  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.589  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:20:47.589  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:47.589  3785  3988 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:47.589  3785  3988 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:47.589  3785  3988 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:20:47.589  3785  3988 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:20:47.589  3785  3988 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:20:47.589  3785  3988 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-26 15:20:47.589  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-26 15:20:47.648  3785  3785 D HidService: Received stop request...Stopping profile...
07-26 15:20:47.648  3785  3785 D HidService: Stopping Bluetooth HidService
07-26 15:20:47.651  3785  3785 D HealthService: Received stop request...Stopping profile...
07-26 15:20:47.652  3785  3785 D PanService: Received stop request...Stopping profile...
07-26 15:20:47.653  3785  3785 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:47.653  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.653  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:47.653  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:47.653  3785  3785 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:20:47.654  3785  3982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:20:47.654  3785  3785 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:20:47.654  3785  3785 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:20:47.654  3785  3785 D BluetoothMapService: stop()
,07-26 15:20:47.655  3785  3785 D BluetoothMapAppObserver: deinitObservers()
,07-26 15:20:47.655  3785  3785 D BluetoothMapAppObserver: removeReceiver()
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:47.656  3785  3785 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:20:47.656  3785  3982 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-26 15:20:47.656  3785  3785 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:47.656  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:20:47.657  3785  3785 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-26 15:20:47.699  3785  3785 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:20:47.699  3785  3785 D BluetoothMapService: MAP Service closeService in
07-26 15:20:47.699  3785  3785 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:47.699  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.699  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:47.699  3785  3785 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:47.700  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-26 15:20:47.700  3785  3978 D BluetoothAdapterProperties: Setting state to 15
07-26 15:20:47.700  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-26 15:20:47.701  3748  3758 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:47.701  1306  1318 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:47.701  3748  3760 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:47.701   786   804 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:47.701  3748  3758 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:20:47.702  3748  3760 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:20:47.702   927   941 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:20:47.702   927  1452 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:20:47.703   786   804 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:47.703   786   804 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:47.703   786   804 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:47.703  3748  3758 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:20:47.703  3748  3760 D BluetoothMap: onBluetoothStateChange: up=false
,07-26 15:20:47.703  3785  3978 I BluetoothAdapterState: Entering BleOnState
07-26 15:20:47.703   927   942 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:20:47.704   927   941 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:47.704   927  1452 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:20:47.705   927   942 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:47.705  3785  3978 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-26 15:20:47.705  3785  3978 D BluetoothAdapterProperties: Setting state to 16
07-26 15:20:47.705  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-26 15:20:47.706  3785  3978 D BluetoothAdapterProperties: onBleDisable
07-26 15:20:47.706  3785  3982 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:47.707   927   927 D HeadsetProfile: Bluetooth service disconnected
07-26 15:20:47.708  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.709  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.709  3785  3979 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-26 15:20:47.710  3785  3988 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-26 15:20:47.710  3785  3988 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:47.711  3785  3978 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:20:47.713  3785  3785 D BluetoothMapService: cleanup()
,07-26 15:20:47.713  3785  3785 D BluetoothMapService: MAP Service closeService in
07-26 15:20:47.715  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.716  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.720  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-26 15:20:47.721  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-26 15:20:47.726  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-26 15:20:47.727  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-26 15:20:47.728  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
07-26 15:20:47.729  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
07-26 15:20:47.730  3748  3748 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-26 15:20:47.731  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:20:47.738  3748  3748 D HeadsetProfile: Bluetooth service disconnected
07-26 15:20:47.741   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
,07-26 15:20:47.742   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-26 15:20:47.744  3748  3748 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:47.748   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
,07-26 15:20:47.749   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-26 15:20:47.751   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-26 15:20:47.753   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-26 15:20:47.758  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:47.760  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:47.762  1261  4041 D BluetoothAdapter: startLeScan(): null
,07-26 15:20:47.762  1261  4015 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-26 15:20:47.762  1261  4041 E BluetoothAdapter: startLeScan: cannot get BluetoothLeScanner
07-26 15:20:47.763   927  1110 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-26 15:20:47.765  1261  4015 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: java.io.IOException: Not connected
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:47.765  1261  4015 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:47.765  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:20:47.770  3748  3748 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:47.778  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:47.783  1261  4083 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:20:47.784  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:47.786  1261  1261 E ActivityThread: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@a621f9a that was originally bound here
07-26 15:20:47.786  1261  1261 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@a621f9a that was originally bound here
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at rbx.run(:com.google.android.gms:94)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:47.786  1261  1261 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:47.794  1261  4083 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-26 15:20:47.796  1261  4015 E NearbyDiscovery: Failed to unbind NearbyDirect
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: java.lang.IllegalArgumentException: Service not registered: rbs@a621f9a
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at rbr.c(:com.google.android.gms:181)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at rca.run(:com.google.android.gms:1023)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:47.796  1261  4015 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:47.810  3785  3982 I bt_hci  : shut_down
,07-26 15:20:47.810  3785  3986 D bt_hwcfg: hw_epilog_process
,07-26 15:20:47.813  3785  3986 I bt_vendor: low_power_mode_cb
,07-26 15:20:47.842  3785  3986 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-26 15:20:47.842  3785  3986 I bt_vendor: epilog_cb
07-26 15:20:47.842  3785  3986 I bt_hci  : epilog_finished_callback
,07-26 15:20:47.843  3785  3982 I bt_hci_h4: hal_close
07-26 15:20:47.843  3785  3982 I bt_userial_vendor: device fd = 49 close
,07-26 15:20:47.848  3785  3979 D bt_stack_manager: event_shut_down_stack finished.
,07-26 15:20:47.848  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-26 15:20:47.849  3785  3785 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-26 15:20:47.849  3785  3978 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-26 15:20:47.849  3785  3785 D BtGatt.GattService: Received stop request...Stopping profile...
07-26 15:20:47.849  3785  3785 D BtGatt.GattService: stop()
07-26 15:20:47.849  3785  3785 D BtGatt.AdvertiseManager: advertise clients cleared
07-26 15:20:47.850  3785  3785 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:20:47.850  3785  3785 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:47.850  3785  3785 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:47.850  3785  3785 V BluetoothAdapterState: isBleTurningOff()=true
07-26 15:20:47.850  3785  3978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-26 15:20:47.850  3785  3978 D BluetoothAdapterProperties: Setting state to 10
07-26 15:20:47.850  3785  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 15:20:47.850  3785  3978 I BluetoothAdapterState: Entering OffState
,07-26 15:20:47.851   786   804 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-26 15:20:47.855  3785  3785 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-26 15:20:47.856  3785  3785 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-26 15:20:47.856  3785  3785 I BluetoothServiceJni: cleanupNative: return from cleanup
07-26 15:20:47.856  3785  3979 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-26 15:20:47.857  1261  1261 I BeaconBle: Scan : No clients left, canceling alarm.
07-26 15:20:47.858  3785  3979 D bt_stack_manager: event_clean_up_stack finished.
,07-26 15:20:47.859  3785  3785 I art     : System.exit called, status: 0
,07-26 15:20:47.859  3785  3785 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 15:20:47.863  1261  4041 D BluetoothAdapter: stopLeScan()
,07-26 15:20:47.863  1261  4041 I BeaconBle: Scan : No clients left, canceling alarm.
,07-26 15:20:47.908   786   797 I ActivityManager: Process com.android.bluetooth (pid 3785) has died
,07-26 15:20:47.950  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:47.950  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:47.950  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:48.251  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:48.251  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:48.251  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:48.556  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:48.556  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:48.556  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:48.861  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:48.861  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:48.861  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.167  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.167  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.167  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.472  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.472  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.472  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.778  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.778  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at akmx.run(:com.google.android.gms:2049)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.778  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.780  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.780  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at aksp.c(:com.google.android.gms:36)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at akrf.c(:com.google.android.gms:175)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.780  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.987  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.987  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at aklk.a(:com.google.android.gms:129)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.987  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.989  1261  4032 W MessageQueue: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.989  1261  4032 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {b39a5e4} sending message to a Handler on a dead thread
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at aksp.d(:com.google.android.gms:44)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akrh.a(:com.google.android.gms:65)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at aklk.a(:com.google.android.gms:130)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.989  1261  4032 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:50.507  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:20:50.508  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:53.202  1437  1509 W GmsLocationProvider: Error removing location updates: 16
,07-26 15:20:53.249   786   807 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-26 15:20:53.252   786   807 I PowerManagerService: Sleeping (uid 1000)...
07-26 15:20:53.278   195   832 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (741 us)
07-26 15:20:53.281   786   807 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-26 15:20:53.329  3614  3614 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-26 15:20:53.329  3614  3614 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-26 15:20:53.374  3614  3614 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34f458b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bbc17be, 16908290=android.view.AbsSavedState$1@bbc17be}, android:focusedViewId=100}]}]
,07-26 15:20:53.374  3614  3614 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-26 15:20:53.375  3614  3614 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-26 15:20:53.375  3614  3614 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-26 15:20:53.510  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:53.510  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@946301f added. We now have 6 listener(s)
,07-26 15:20:53.510  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:53.511  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:53.511  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c861f6c added. We now have 7 listener(s)
07-26 15:20:53.511  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:53.511  3614  3688 I System.out: IsBluetoothEnabled
,07-26 15:20:53.514  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:53.527   786   804 I ActivityManager: Start proc 4134:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding HeadsetService
,07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding A2dpService
07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding HidService
07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding HealthService
07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding PanService
07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding GattService
07-26 15:20:53.583  4134  4134 D AdapterServiceConfig: Adding BluetoothMapService
,07-26 15:20:53.591   786   804 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a7ab3b:true
,07-26 15:20:53.592  4134  4134 D BluetoothAdapterState: make() - Creating AdapterState
,07-26 15:20:53.594  4134  4134 I bt_bluedroid: init
,07-26 15:20:53.594  4134  4147 I BluetoothAdapterState: Entering OffState
,07-26 15:20:53.596  4134  4148 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-26 15:20:53.596  4134  4148 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:20:53.596  4134  4148 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:20:53.596  4134  4148 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-26 15:20:53.597  4134  4134 I bt_bluedroid: get_profile_interface socket
,07-26 15:20:53.598  4134  4134 I bt_bluedroid: get_profile_interface sdp
,07-26 15:20:53.599  4134  4151 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-26 15:20:53.600  4134  4151 D BluetoothAdapterProperties: Name is: Nexus 5
,07-26 15:20:53.600  4134  4145 I bt_bluedroid: config_hci_snoop_log
,07-26 15:20:53.601   786   804 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-26 15:20:53.603  4134  4147 D BluetoothAdapterState: Current state: OFF, message: 0
07-26 15:20:53.603  4134  4147 D BluetoothAdapterProperties: Setting state to 14
07-26 15:20:53.603  4134  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-26 15:20:53.604  4134  4147 D BluetoothBondStateMachine: make
,07-26 15:20:53.607  4134  4152 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-26 15:20:53.610  4134  4134 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-26 15:20:53.610  4134  4147 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:20:53.611  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
,07-26 15:20:53.612  4134  4134 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:20:53.612  4134  4134 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:20:53.612  4134  4134 D BtGatt.GattService: start()
07-26 15:20:53.612  4134  4134 I bt_bluedroid: get_profile_interface gatt
07-26 15:20:53.613  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:53.613  4134  4134 D BtGatt.AdvertiseManager: advertise manager created
,07-26 15:20:53.617  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:20:53.617  4134  4134 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:53.617  4134  4134 V BluetoothAdapterState: isBleTurningOn()=true
07-26 15:20:53.617  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:53.617  4134  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-26 15:20:53.617  4134  4147 I bt_bluedroid: enable
,07-26 15:20:53.618  4134  4148 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-26 15:20:53.618  4134  4148 I bt_hci  : start_up
,07-26 15:20:53.625  4134  4148 I bt_vendor: alloc value 0xb39f6631
,07-26 15:20:53.625  4134  4148 I bt_vendor: init
07-26 15:20:53.625  4134  4148 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-26 15:20:53.625  4134  4148 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-26 15:20:53.665  4134  4148 D bt_hci  : start_up starting async portion
,07-26 15:20:53.665  4134  4158 I bt_hci  : event_finish_startup
07-26 15:20:53.665  4134  4158 I bt_hci_h4: hal_open
,07-26 15:20:53.666  4134  4158 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-26 15:20:53.669  4134  4158 I bt_userial_vendor: device fd = 49 open
,07-26 15:20:53.754  4134  4158 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:20:53.780  4134  4158 D bt_hwcfg: Chipset BCM4335C0
,07-26 15:20:53.780  4134  4158 D bt_hwcfg: Target name = [BCM4335C0]
07-26 15:20:53.781  4134  4158 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-26 15:20:53.877   786   807 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-26 15:20:53.896   786   807 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-26 15:20:53.899   786   805 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-26 15:20:53.899   195   195 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,07-26 15:20:53.899   195   195 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-26 15:20:54.164  4134  4158 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-26 15:20:54.164  4134  4158 D bt_hwcfg: Settlement delay -- 100 ms
07-26 15:20:54.164  4134  4158 I bt_hwcfg: Setting fw settlement delay to 100 
07-26 15:20:54.165   195   195 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-26 15:20:54.165   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 266ms
07-26 15:20:54.166  1807  1829 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-26 15:20:54.172   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:20:54.172   786   892 E WifiNative-wlan0: Update priority failed for :0
07-26 15:20:54.173   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
07-26 15:20:54.173   202   202 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-26 15:20:54.234   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:20:54.234   786   892 E WifiNative-wlan0: Update priority failed for :0
07-26 15:20:54.234   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
,07-26 15:20:54.250   202   831 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-26 15:20:54.256  1238  1238 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-26 15:20:54.280  4134  4158 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:20:54.280  4134  4158 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-26 15:20:54.311  4134  4158 I bt_hwcfg: vendor lib fwcfg completed
,07-26 15:20:54.311  4134  4158 I bt_vendor: firmware callback
07-26 15:20:54.311  4134  4158 I bt_hci  : firmware_config_callback
,07-26 15:20:54.314  4134  4166 I bt_btu  : btu_task pending for preload complete event
,07-26 15:20:54.314  4134  4166 I bt_btu_task: Bluetooth chip preload is complete
07-26 15:20:54.314  4134  4166 I bt_btu  : btu_task received preload complete event
,07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_HCI
,07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_AVDT
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_A2D
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_BNEP
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_BTM
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_GAP
,07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_PAN
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_GATT
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_SMP
,07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:20:54.318  4134  4166 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-26 15:20:54.714  4134  4166 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39749b5
,07-26 15:20:54.714  4134  4166 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39749b5 
,07-26 15:20:54.733  4134  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-26 15:20:54.733  4134  4151 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-26 15:20:54.734  4134  4151 D BluetoothAdapterProperties: Name is: Nexus 5
,07-26 15:20:54.735  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:54.736  4134  4151 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:54.736  4134  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:20:54.736  4134  4151 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-26 15:20:54.737  4134  4151 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-26 15:20:54.737  4134  4151 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-26 15:20:54.737  4134  4151 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-26 15:20:54.737  4134  4151 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-26 15:20:54.737  4134  4151 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
,07-26 15:20:54.737  4134  4151 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
,07-26 15:20:54.739  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-26 15:20:54.741  4134  4134 I BluetoothHidServiceJni: classInitNative: succeeds
,07-26 15:20:54.741  4134  4134 D HidService: getHidService(): service is NULL
,07-26 15:20:54.744  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,07-26 15:20:54.745  4134  4134 D HidService: getHidService(): service is NULL
07-26 15:20:54.747  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-26 15:20:54.748  4134  4134 D HidService: getHidService(): service is NULL
,07-26 15:20:54.750  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-26 15:20:54.752  4134  4134 D HidService: getHidService(): service is NULL
07-26 15:20:54.754  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.754  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.756  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,07-26 15:20:54.757  4134  4134 D HidService: getHidService(): service is NULL
07-26 15:20:54.758  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,07-26 15:20:54.760  4134  4134 D HidService: getHidService(): service is NULL
07-26 15:20:54.763  4134  4151 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-26 15:20:54.765  4134  4134 D HidService: getHidService(): service is NULL
,07-26 15:20:54.766  4134  4151 D bt_hci  : do_postload posting postload work item
,07-26 15:20:54.766  4134  4158 I bt_hci  : event_postload
07-26 15:20:54.766  4134  4158 I bt_vendor: sco_config_cb
07-26 15:20:54.766  4134  4158 I bt_hci  : sco_config_callback postload finished.
,07-26 15:20:54.767  4134  4151 D bt_bte_conf: Device ID record 1 : primary
07-26 15:20:54.767  4134  4151 D bt_bte_conf:   vendorId            = 000f
07-26 15:20:54.767  4134  4151 D bt_bte_conf:   vendorIdSource      = 0001
,07-26 15:20:54.767  4134  4151 D bt_bte_conf:   product             = 1200
,07-26 15:20:54.767  4134  4151 D bt_bte_conf:   version             = 1436
07-26 15:20:54.767  4134  4151 D bt_bte_conf:   clientExecutableURL = 
,07-26 15:20:54.767  4134  4151 D bt_bte_conf:   serviceDescription  = 
,07-26 15:20:54.767  4134  4151 D bt_bte_conf:   documentationURL    = 
,07-26 15:20:54.767  4134  4151 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-26 15:20:54.767  4134  4148 D bt_stack_manager: event_start_up_stack finished
,07-26 15:20:54.768  4134  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-26 15:20:54.768  4134  4147 D BluetoothAdapterProperties: Setting state to 15
07-26 15:20:54.768  4134  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-26 15:20:54.768  4134  4147 I BluetoothAdapterState: Entering BleOnState
07-26 15:20:54.768  4134  4158 I bt_vendor: low_power_mode_cb
,07-26 15:20:54.772  4134  4147 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-26 15:20:54.772  4134  4147 D BluetoothAdapterProperties: Setting state to 11
07-26 15:20:54.772  4134  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-26 15:20:54.777  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:54.778  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.779  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
,07-26 15:20:54.781  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.783  4134  4134 D HeadsetService: Received start request. Starting profile...
,07-26 15:20:54.783  4134  4134 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:20:54.783  4134  4134 D HeadsetStateMachine: make
,07-26 15:20:54.787  4134  4147 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:20:54.789  4134  4134 D HeadsetStateMachine: max_hf_connections = 1
,07-26 15:20:54.790  4134  4134 I bt_bluedroid: get_profile_interface handsfree
07-26 15:20:54.790  4134  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-26 15:20:54.790  4134  4151 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-26 15:20:54.790  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.790  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.793  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.793  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.796  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:54.796  4134  4134 D A2dpService: Received start request. Starting profile...
,07-26 15:20:54.797  4134  4134 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-26 15:20:54.797  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.797  4134  4134 I bt_bluedroid: get_profile_interface avrcp
,07-26 15:20:54.797  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.800  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.801  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.804  4134  4134 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-26 15:20:54.804  4134  4134 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:20:54.804  4134  4134 D A2dpStateMachine: make
07-26 15:20:54.805  4134  4134 I bt_bluedroid: get_profile_interface a2dp
07-26 15:20:54.806  4134  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-26 15:20:54.807  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.807  3748  3748 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-26 15:20:54.811  4134  4187 D A2dpStateMachine: Enter Disconnected: -2
07-26 15:20:54.811  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:54.811  4134  4134 D HidService: Received start request. Starting profile...
07-26 15:20:54.811  4134  4134 I bt_bluedroid: get_profile_interface hidhost
07-26 15:20:54.812  4134  4134 D HidService: setHidService(): set to: null
07-26 15:20:54.812  4134  4134 I BluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:20:54.813  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:54.813  4134  4151 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3956099
,07-26 15:20:54.813  4134  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-26 15:20:54.813  4134  4134 D HealthService: Received start request. Starting profile...
07-26 15:20:54.814  4134  4134 I bt_bluedroid: get_profile_interface health
07-26 15:20:54.815  4134  4134 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-26 15:20:54.815  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
07-26 15:20:54.815  4134  4134 D PanService: Received start request. Starting profile...
,07-26 15:20:54.815  4134  4134 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:20:54.815  4134  4134 I bt_bluedroid: get_profile_interface pan
07-26 15:20:54.816  4134  4151 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-26 15:20:54.819   927  1110 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.819   927  1110 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.834  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b78edc0
,07-26 15:20:54.836  4134  4134 D BluetoothMapService: Received start request. Starting profile...
,07-26 15:20:54.837  4134  4134 D BluetoothMapService: start()
,07-26 15:20:54.839  4134  4134 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-26 15:20:54.840  4134  4134 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-26 15:20:54.840  4134  4134 D BluetoothMapAppObserver: createReceiver()
,07-26 15:20:54.841  4134  4134 D BluetoothMapAppObserver: initObservers()
07-26 15:20:54.841  4134  4134 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-26 15:20:54.847  4134  4134 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:54.847  4134  4134 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:54.847  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:20:54.847  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:54.847  4134  4184 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-26 15:20:54.847   927  1110 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.849   927  1110 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isTurningOn()=true
,07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:54.849  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isTurningOn()=true
,07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isTurningOff()=false
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isTurningOn()=true
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:54.850  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:54.850  4134  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-26 15:20:54.850  4134  4147 D BluetoothAdapterProperties: ScanMode =  20
,07-26 15:20:54.850  4134  4147 D BluetoothAdapterProperties: State =  11
07-26 15:20:54.851  4134  4147 D BluetoothAdapterProperties: Setting state to 12
07-26 15:20:54.851  4134  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 15:20:54.851  3748  3758 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:54.851  4134  4147 I BluetoothAdapterState: Entering OnState
07-26 15:20:54.851  1306  1459 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:54.852  4134  4151 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:20:54.852  3748  3760 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:20:54.852  4134  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:20:54.855   786   804 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:54.855  3748  3758 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:20:54.857  3748  3760 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:20:54.858   927   942 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:54.858  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:54.860   927   927 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:20:54.860   927   927 D PanProfile: Bluetooth service connected
07-26 15:20:54.860  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:54.861   927   941 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:20:54.862   786   804 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:20:54.862   786   804 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:54.863   786   804 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:20:54.863  3748  3758 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:20:54.864   786   786 D BluetoothA2dp: Proxy object connected
07-26 15:20:54.865   927   927 D BluetoothInputDevice: Proxy object connected
07-26 15:20:54.865   927   927 D HidProfile: Bluetooth service connected
07-26 15:20:54.866  4134  4134 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-26 15:20:54.866  4134  4134 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-26 15:20:54.867  4134  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:20:54.867  3748  3760 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:20:54.871  3748  3748 D BluetoothA2dp: Proxy object connected
07-26 15:20:54.872   927   941 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:20:54.872  4134  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:54.874  4134  4134 D ObexServerSockets: Succeed to create listening sockets 
,07-26 15:20:54.874  4134  4134 D ObexServerSockets0: startAccept()
,07-26 15:20:54.874  4134  4134 D ObexServerSockets0: prepareForNewConnect()
07-26 15:20:54.875  4134  4134 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-26 15:20:54.875  4134  4134 D BluetoothSdpJni: SDP Create record success - handle: 0
07-26 15:20:54.875   927   942 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:20:54.876  4134  4207 D ObexServerSockets0: Accepting socket connection...
07-26 15:20:54.876  4134  4208 D ObexServerSockets0: Accepting socket connection...
07-26 15:20:54.876   927  1452 D BluetoothMap: onBluetoothStateChange: up=true
,07-26 15:20:54.878   927   927 D BluetoothMap: Proxy object connected
,07-26 15:20:54.878   927   927 D MapProfile: Bluetooth service connected
07-26 15:20:54.878   927   927 D BluetoothMap: getConnectedDevices()
,07-26 15:20:54.879   927   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:20:54.879  3748  3748 D BluetoothPan: BluetoothPAN Proxy object connected
,07-26 15:20:54.879  3748  3748 D PanProfile: Bluetooth service connected
07-26 15:20:54.879  3748  3748 D BluetoothInputDevice: Proxy object connected
07-26 15:20:54.879  3748  3748 D HidProfile: Bluetooth service connected
07-26 15:20:54.880   927   927 D BluetoothA2dp: Proxy object connected
07-26 15:20:54.881  3748  3748 D BluetoothMap: Proxy object connected
,07-26 15:20:54.881  3748  3748 D MapProfile: Bluetooth service connected
,07-26 15:20:54.881  3748  3748 D BluetoothMap: getConnectedDevices()
07-26 15:20:54.881   786   786 I Telecom : BluetoothPhoneService: queryPhoneState
07-26 15:20:54.882  4134  4134 D BluetoothMapService: onReceive
07-26 15:20:54.882  4134  4134 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:20:54.882  4134  4134 D BluetoothMapService: STATE_ON
07-26 15:20:54.883  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:54.896  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:54.899  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:54.900   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:54.902  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:20:54.904  4134  4134 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:20:54.904  4134  4134 D ObexServerSockets0: prepareForNewConnect()
,07-26 15:20:54.904   927  1110 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-26 15:20:54.916   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:54.918  4134  4213 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:54.919  3748  3748 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:54.924   927   927 D BluetoothPbap: Proxy object connected
,07-26 15:20:54.924   927   927 D PbapServerProfile: Bluetooth service connected
,07-26 15:20:54.928  3748  3748 D BluetoothPbap: Proxy object connected
,07-26 15:20:54.928  3748  3748 D PbapServerProfile: Bluetooth service connected
,07-26 15:20:54.939  1261  4041 D BluetoothAdapter: startLeScan(): null
,07-26 15:20:54.940  1261  4041 D BluetoothAdapter: STATE_ON
,07-26 15:20:54.942  4134  4176 D BtGatt.GattService: registerClient() - UUID=8df1f5ee-bb8a-4f02-bb1d-8e598aaa50fe
07-26 15:20:54.942  4134  4151 D BtGatt.GattService: onClientRegistered() - UUID=8df1f5ee-bb8a-4f02-bb1d-8e598aaa50fe, clientIf=5
07-26 15:20:54.942  1261  1275 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-26 15:20:54.944  4134  4145 D BtGatt.GattService: start scan with filters
,07-26 15:20:54.944  1261  1261 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:54.947  4134  4157 D BtGatt.ScanManager: handling starting scan
,07-26 15:20:54.948  1261  4219 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:20:54.949  1261  1261 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:54.951  4134  4221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:54.952  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-26 15:20:54.952  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-26 15:20:54.952  4134  4157 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
,07-26 15:20:54.952   786   786 D BluetoothHeadset: Proxy object connected
07-26 15:20:54.953  3748  3758 D BluetoothHeadset: Proxy object connected
07-26 15:20:54.953  4134  4151 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-26 15:20:54.953  4134  4221 I BtOppRfcommListener: Accept thread started.
,07-26 15:20:54.953   927   941 D BluetoothHeadset: Proxy object connected
07-26 15:20:54.953   786   786 D BluetoothHeadset: Proxy object connected
07-26 15:20:54.953  3748  3748 D HeadsetProfile: Bluetooth service connected
07-26 15:20:54.953   927   927 D HeadsetProfile: Bluetooth service connected
07-26 15:20:54.953  1306  1318 D BluetoothHeadset: Proxy object connected
07-26 15:20:54.954   786   786 D BluetoothHeadset: Proxy object connected
,07-26 15:20:54.958   786   804 D BluetoothHeadset: Proxy object connected
,07-26 15:20:54.963   786   804 D BluetoothHeadset: Proxy object connected
,07-26 15:20:54.963   786   804 D BluetoothHeadset: Proxy object connected
,07-26 15:20:54.968  1261  4219 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-26 15:20:54.974   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:54.975   927  1110 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-26 15:20:54.975   927  1452 D BluetoothHeadset: Proxy object connected
,07-26 15:20:54.977   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:54.986   927   927 D HeadsetProfile: Bluetooth service connected
,07-26 15:20:54.987   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:54.989   927  1110 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-26 15:20:54.990   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:55.000   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:55.001   927  1110 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-26 15:20:55.002   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:55.016   927  1110 D BluetoothMap: getConnectedDevices()
,07-26 15:20:55.017   927  1110 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-26 15:20:55.018   927  1110 D MapProfile: getConnectionStatus: status is: 0
,07-26 15:20:55.339  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:55.425  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:55.462  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:55.466  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:55.508  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:55.525  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:55.528  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:55.530  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:55.530  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c367935 added. We now have 8 listener(s)
07-26 15:20:55.530  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:55.533   786  1321 D WifiService: setWifiEnabled: false pid=3614, uid=10026
07-26 15:20:55.533   786  1321 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:20:55.541  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:55.541   786   948 D WifiService: setWifiEnabled: true pid=3614, uid=10026
07-26 15:20:55.541   786   948 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:20:55.549   198   635 D SoftapController: Softap fwReload - Ok
07-26 15:20:55.555   198   635 D CommandListener: Setting iface cfg
07-26 15:20:55.555   198   635 D CommandListener: Trying to bring down wlan0
07-26 15:20:55.557   198   635 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:20:55.558   786   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-26 15:20:56.022  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-26 15:20:56.097  1261  4185 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:20:56.099  1261  4185 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: java.io.IOException: Not connected
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:56.099  1261  4185 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:56.360   786   892 D wifi    : set interface wlan0 flags (UP)
,07-26 15:20:56.360   786   892 I WifiHAL : Initializing wifi
,07-26 15:20:56.360   786   892 I WifiHAL : Creating socket
,07-26 15:20:56.361   786   804 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-26 15:20:56.361   786   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-26 15:20:56.361   786   892 D wifi    : Did set static halHandle = 0xa076db20
,07-26 15:20:56.361   786   892 D wifi    : halHandle = 0xa076db20, mVM = 0xb4d3c000, mCls = 0x16d2
,07-26 15:20:56.361   786   892 D wifi    : array field set
07-26 15:20:56.362   786   892 I WifiNative-HAL: interface[0] = p2p0
07-26 15:20:56.362   786   892 I WifiNative-HAL: interface[1] = wlan0
07-26 15:20:56.366  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:56.367   786   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-26 15:20:56.367   786   892 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-26 15:20:56.374   786  4275 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602823392
,07-26 15:20:56.375   786  4275 D wifi    : waitForHalEvents called, vm = 0xb4d3c000, obj = 0x16d2, env = 0x98aaf060
,07-26 15:20:56.398  4276  4276 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:20:56.418  4276  4276 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:20:56.453  1261  4041 D BluetoothAdapter: stopLeScan()
,07-26 15:20:56.454  1261  4041 D BluetoothAdapter: STATE_ON
,07-26 15:20:56.458  4134  4222 D BtGatt.GattService: stopScan() - queue size =1
,07-26 15:20:56.458  4134  4157 D BtGatt.ScanManager: stop scan
07-26 15:20:56.458  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-26 15:20:56.458  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-26 15:20:56.458  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-26 15:20:56.459  4134  4144 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 15:20:56.465  4276  4276 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:20:56.630  1261  4041 D BluetoothAdapter: startLeScan(): null
,07-26 15:20:56.631  1261  4041 D BluetoothAdapter: STATE_ON
,07-26 15:20:56.632  4134  4144 D BtGatt.GattService: registerClient() - UUID=4c5ef8d4-43e3-4cd5-bd78-104749687788
,07-26 15:20:56.633  4134  4151 D BtGatt.GattService: onClientRegistered() - UUID=4c5ef8d4-43e3-4cd5-bd78-104749687788, clientIf=5
,07-26 15:20:56.633  1261  1545 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-26 15:20:56.633  4134  4180 D BtGatt.GattService: start scan with filters
,07-26 15:20:56.635  4134  4157 D BtGatt.ScanManager: handling starting scan
07-26 15:20:56.638  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-26 15:20:56.638  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
,07-26 15:20:56.638  4134  4157 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-26 15:20:56.638  4134  4151 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-26 15:20:57.178  1261  4185 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:20:57.179  1261  4185 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: java.io.IOException: Not connected
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at reh.run(:com.google.android.gms:75)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.179  1261  4185 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:57.373  3614  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:20:57.382  3614  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:57.392   786   892 D WifiConfigStore: Loading config and enabling all networks 
07-26 15:20:57.424   786   892 D WifiConfigStore: loaded 0 passpoint configs
07-26 15:20:57.429   786   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-26 15:20:57.429  4134  4151 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
07-26 15:20:57.432   786   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:20:57.432   786   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,07-26 15:20:57.432   786   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-26 15:20:57.434   786   892 D WifiNative-HAL: Setting external_sim to 1
07-26 15:20:57.435   786   892 D wifi    : setting dfs flag to true, 0x9b3f9800
07-26 15:20:57.435   786   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:20:57.435   786   892 D wifi    : setting scan oui 0x9b3f9800
07-26 15:20:57.435   786   892 D WifiHAL : Sending mac address OUI
07-26 15:20:57.446   786   892 E native  : do suspend true
07-26 15:20:57.450   786   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-26 15:20:57.451   786   786 D RttService: SCAN_AVAILABLE : 3
,07-26 15:20:57.452   786   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:20:57.456   198   635 D CommandListener: Setting iface cfg
07-26 15:20:57.456   198   635 D CommandListener: Trying to bring up p2p0
07-26 15:20:57.456   786   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 15:20:57.466   786   891 D WifiNative-HAL: p2pGetDeviceAddress
07-26 15:20:57.466   786   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:57.568  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:57.569  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:20:57.570  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-26 15:20:57.571  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-26 15:20:57.572  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34f458b Bundle[{}]
07-26 15:20:57.572  3614  3688 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:20:57.572  3614  3688 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:20:57.572  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-26 15:20:57.573  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-26 15:20:57.573  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-26 15:20:57.573  3614  3688 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-26 15:20:57.577  3614  3688 I System.out: Running OutgoingSocketThread
,07-26 15:20:57.577  3614  4303 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 408)
,07-26 15:20:57.578  3614  4303 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58960
07-26 15:20:57.578  3614  4303 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-26 15:20:57.941  1261  4041 D BluetoothAdapter: stopLeScan()
,07-26 15:20:57.942  1261  4041 D BluetoothAdapter: STATE_ON
07-26 15:20:57.943  4134  4145 D BtGatt.GattService: stopScan() - queue size =1
07-26 15:20:57.943  4134  4157 D BtGatt.ScanManager: stop scan
07-26 15:20:57.943  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-26 15:20:57.943  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-26 15:20:57.943  4134  4157 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-26 15:20:57.944  4134  4222 D BtGatt.GattService: unregisterClient() - clientIf=5
07-26 15:20:57.944  1261  4041 I BeaconBle: Scan : No clients left, canceling alarm.
,07-26 15:20:58.270  1261  4185 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:20:58.270  1261  4185 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: java.io.IOException: Not connected
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at reh.run(:com.google.android.gms:75)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:58.270  1261  4185 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:58.577  3614  3688 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 409)
,07-26 15:20:58.577  3614  3688 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 409)
07-26 15:20:58.577  3614  3688 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 409)
07-26 15:20:58.578  3614  3688 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 409)
07-26 15:20:58.579  3614  3688 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 414)
07-26 15:20:58.579  3614  3688 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 414)
07-26 15:20:58.579  3614  3688 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 414)
07-26 15:20:58.579  3614  3688 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 415)
07-26 15:20:58.580  3614  3688 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 417)
07-26 15:20:58.581  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.581  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df1ca added. We now have 2 listener(s)
07-26 15:20:58.582  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.582  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.582  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.582  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.582  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a7af3b added. We now have 9 listener(s)
07-26 15:20:58.582  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.582  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:58.588  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:58.598  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:58.605  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:58.605  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:58.609  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.613  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.613  3614  3688 V or,g.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.614  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96273b1 added. We now have 3 listener(s)
07-26 15:20:58.620  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.620  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.620  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.621  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.621  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a116096 added. We now have 10 listener(s)
07-26 15:20:58.621  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.621  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:58.622  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:58.622  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:58.624  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.625  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.625  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.625  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.625  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df1ca removed from the list
07-26 15:20:58.625  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.625  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a7af3b removed from the list
07-26 15:20:58.625  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:58.625  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.627  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.627  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.630  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.630  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.630  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.630  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a7af3b not in the list
,07-26 15:20:58.630  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.630  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.633  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.633  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.633  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.633  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a116096 removed from the list
07-26 15:20:58.633  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.633  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.633  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.634  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.634  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96273b1 removed from the list
07-26 15:20:58.639  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.639  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed80417 added. We now have 2 listener(s)
07-26 15:20:58.640  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.640  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.640  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.640  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.640  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@402f004 added. We now have 9 listener(s)
,07-26 15:20:58.640  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.640  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:20:58.642  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:58.643  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:58.644  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:58.645  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:58.645  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.646  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.646  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.646  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7faf022 added. We now have 3 listener(s)
07-26 15:20:58.647  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.647  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.647  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.647  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:20:58.647  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74ecab3 added. We now have 10 listener(s)
07-26 15:20:58.647  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.647  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:58.647  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:58.647  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.647  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:58.649  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:58.649  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:20:58.651  3614  3688 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:20:58.651  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:20:58.652  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:20:58.652  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:20:58.652  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:58.653  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:20:58.653  3614  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:58.654  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:58.654  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:58.655  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:58.655  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:58.655  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:58.655  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.655  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.655  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.655  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.655  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed80417 removed from the list
07-26 15:20:58.655  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.655  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@402f004 removed from the list
,07-26 15:20:58.655  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:58.655  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.655  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.655  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.656  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.656  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.656  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.656  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@402f004 not in the list
07-26 15:20:58.656  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.656  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.656  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.657  3614  3688 D BluetoothAdapter: STATE_ON
,07-26 15:20:58.657  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:58.657  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:58.657  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.657  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.657  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74ecab3 removed from the list
07-26 15:20:58.657  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.657  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.657  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:58.657  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.657  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7faf022 removed from the list
07-26 15:20:58.657  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.657  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fbec6e added. We now have 2 listener(s)
07-26 15:20:58.658  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.658  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.658  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:20:58.658  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:20:58.658  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3615f0f added. We now have 9 listener(s)
07-26 15:20:58.658  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.658  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:58.660  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:58.662  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:58.663  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:58.663  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:58.663  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.664  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.664  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.664  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7919a5 added. We now have 3 listener(s)
07-26 15:20:58.665  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-26 15:20:58.665  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.665  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.665  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.665  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe617a added. We now have 10 listener(s)
07-26 15:20:58.665  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.665  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:58.666  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:20:58.666  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:58.666  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.666  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:58.668  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:58.668  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:20:58.670  3614  3688 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:20:58.670  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:20:58.670  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:20:58.670  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:20:58.671  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:58.671  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.672  3614  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:58.672  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:58.672  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:20:58.672  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:58.672  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.673  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.673  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.673  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.673  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fbec6e removed from the list
,07-26 15:20:58.673  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.673  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3615f0f removed from the list
07-26 15:20:58.673  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:58.673  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.673  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.673  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.673  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.673  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:20:58.673  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:20:58.673  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3615f0f not in the list
,07-26 15:20:58.673  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.673  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.674  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.674  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:58.674  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:58.674  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:58.674  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.674  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.674  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe617a removed from the list
07-26 15:20:58.674  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.674  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.674  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.674  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.674  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7919a5 removed from the list
07-26 15:20:58.675  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:20:58.675  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106ab21 added. We now have 2 listener(s)
07-26 15:20:58.676  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.676  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.676  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.676  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.676  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4811b46 added. We now have 9 listener(s)
07-26 15:20:58.676  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.676  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:58.678  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:58.679  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:58.680  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:58.680  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:58.681  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:58.682  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.682  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.682  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5846234 added. We now have 3 listener(s)
07-26 15:20:58.683  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.683  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.683  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.683  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.683  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@781d85d added. We now have 10 listener(s)
07-26 15:20:58.683  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.683  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:20:58.683  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:58.683  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.683  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:58.695  3614  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:58.695  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:20:58.698  3614  3688 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:20:58.698  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:20:58.698  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:20:58.698  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:20:58.699  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:58.699  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.701  3614  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-26 15:20:58.702  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:58.702  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:58.702  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:58.702  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.702  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.702  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.702  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.702  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106ab21 removed from the list
07-26 15:20:58.702  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.702  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4811b46 removed from the list
,07-26 15:20:58.702  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:58.702  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.702  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.702  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.703  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.703  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.703  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.703  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4811b46 not in the list
07-26 15:20:58.703  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:58.703  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.703  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.704  3614  3688 D BluetoothAdapter: STATE_ON
07-26 15:20:58.704  3614  3688 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:58.704  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:58.704  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.704  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.704  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@781d85d removed from the list
07-26 15:20:58.704  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.704  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:58.704  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.704  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.704  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5846234 removed from the list
07-26 15:20:58.704  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:20:58.704  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61f6da0 added. We now have 2 listener(s)
07-26 15:20:58.705  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.705  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.705  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.705  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:20:58.705  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8889d59 added. We now have 9 listener(s)
07-26 15:20:58.705  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.706  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:58.707  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:58.709  3614  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:58.711  3614  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:58.711  3614  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:58.711  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:20:58.711  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de29ff added. We now have 3 listener(s)
07-26 15:20:58.711  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.712  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-26 15:20:58.712  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:58.712  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:58.712  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:58.712  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79dc3cc added. We now have 10 listener(s)
07-26 15:20:58.712  3614  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:58.712  3614  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:58.712  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:58.712  3614  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:20:58.712  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.712  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.712  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:58.712  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.712  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61f6da0 removed from the list
07-26 15:20:58.712  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.712  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8889d59 removed from the list
07-26 15:20:58.712  3614  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.712  3614  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:58.712  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:58.713  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.713  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.713  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.713  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.713  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.713  3614  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8889d59 not in the list
07-26 15:20:58.713  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.713  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:58.714  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:58.714  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:58.714  3614  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.714  3614  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79dc3cc removed from the list
07-26 15:20:58.714  3614  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.714  3614  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.714  3614  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.714  3614  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-26 15:20:58.714  3614  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de29ff removed from the list
07-26 15:20:58.714  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:20:58.714  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-26 15:20:58.715  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:20:58.715  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 15:20:58.715  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-26 15:20:58.715  3614  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:20:58.718  3614  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: My test thread name)
07-26 15:20:58.719  3614  4328 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 423, thread name: My test thread name)
07-26 15:20:58.719  3614  4328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: My test thread name)
07-26 15:20:58.720  3614  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: My test thread name)
07-26 15:20:58.720  3614  4329 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 425, thread name: My test thread name)
07-26 15:20:58.720  3614  4329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: My test thread name)
07-26 15:20:58.721  3614  3688 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-26 15:20:58.721  3614  3688 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
,07-26 15:20:58.721  3614  3688 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-26 15:20:58.721  3614  3688 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-26 15:20:58.721  3614  3688 D com.test.thalitest.ThaliTestRunner: Total duration: 23404 ms
07-26 15:20:58.722  3614  3688 I jxcore-log: Total number of executed tests:  84
07-26 15:20:58.722  3614  3688 I jxcore-log: 
07-26 15:20:58.722  3614  3688 I jxcore-log: Number of passed tests:  84
07-26 15:20:58.722  3614  3688 I jxcore-log: 
07-26 15:20:58.722  3614  3688 I jxcore-log: Number of failed tests:  0
07-26 15:20:58.722  3614  3688 I jxcore-log: 
07-26 15:20:58.723  3614  3688 I jxcore-log: Number of ignored tests:  0
07-26 15:20:58.723  3614  3688 I jxcore-log: 
,07-26 15:20:58.723  3614  3688 I jxcore-log: Total duration:  23404
07-26 15:20:58.723  3614  3688 I jxcore-log: 
,07-26 15:20:58.725  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.725  3614  3688 I jxcore-log: 
,07-26 15:20:58.725  3614  3614 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Unsupported return type."", source: file:///android_asset/www/js/thali_main.js (57)
07-26 15:20:58.726  3614  3614 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-26 15:20:58.726  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.726  3614  3688 I jxcore-log: 
07-26 15:20:58.727  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.727  3614  3688 I jxcore-log: 
07-26 15:20:58.728  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.728  3614  3688 I jxcore-log: 
07-26 15:20:58.728  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.728  3614  3688 I jxcore-log: 
07-26 15:20:58.729  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-26 15:20:58.729  3614  3688 I jxcore-log: 
07-26 15:20:58.731  3614  3614 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-26 15:20:58.731  3614  3614 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:20:58.731  3614  3614 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:58.731  3614  3614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:58.731  3614  3614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:58.731  3614  3614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:58.731  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:20:58.731  3614  3688 I jxcore-log: 
07-26 15:20:58.731  3614  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d163b0 removed from the list
07-26 15:20:58.731  3614  3614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:58.731  3614  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c34e34f removed from the list
07-26 15:20:58.731  3614  3614 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:58.731  3614  3614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-26 15:20:58.732  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.732  3614  3688 I jxcore-log: 
07-26 15:20:58.732  3614  3614 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:20:58.732  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.732  3614  3688 I jxcore-log: 
07-26 15:20:58.733  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.733  3614  3688 I jxcore-log: 
07-26 15:20:58.734,  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:20:58.734  3614  3688 I jxcore-log: 
07-26 15:20:58.734  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.734  3614  3688 I jxcore-log: 
07-26 15:20:58.735  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.735  3614  3688 I jxcore-log: 
07-26 15:20:58.736  3614  3614 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
07-26 15:20:58.736  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.736  3614  3688 I jxcore-log: 
07-26 15:20:58.737  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.737  3614  3688 I jxcore-log: 
07-26 15:20:58.737  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.737  3614  3688 I jxcore-log: 
07-26 15:20:58.738  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.738  3614  3688 I jxcore-log: 
07-26 15:20:58.738  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.738  3614  3688 I jxcore-log: 
07-26 15:20:58.739  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.739  3614  3688 I jxcore-log: 
07-26 15:20:58.739  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.739  3614  3688 I jxcore-log: 
07-26 15:20:58.740  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.740  3614  3688 I jxcore-log: 
07-26 15:20:58.740  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.740  3614  3688 I jxcore-log: 
07-26 15:20:58.741  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:20:58.741  3614  3688 I jxcore-log: 
07-26 15:20:58.741  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.741  3614  3688 I jxcore-log: 
07-26 15:20:58.742  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.742  3614  3688 I jxcore-log: 
07-26 15:20:58.743  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.743  3614  3688 I jxcore-log: 
07-26 15:20:58.744  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.744  3614  3688 I jxcore-log: 
07-26 15:20:58.744  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.744  3614  3688 I jxcore-log: 
07-26 15:20:58.745  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.745  3614  3688 I jxcore-log: 
07-26 15:20:58.745  3614  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:20:58.745  3614  3688 I jxcore-log: 
07-26 15:20:58.758  3614  3614 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-26 15:20:59.369  4334  4334 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-26 15:20:59.373  4334  4334 D AndroidRuntime: CheckJNI is OFF
,07-26 15:20:59.408  4334  4334 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-26 15:20:59.443  4334  4334 I Radio-JNI: register_android_hardware_Radio DONE
,07-26 15:20:59.462  4334  4334 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-26 15:20:59.468   786   800 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
,07-26 15:20:59.468   786   800 I ActivityManager: Killing 3614:com.test.thalitest/u0a26 (adj 9): stop com.test.thalitest
,07-26 15:20:59.537   786  2228 D GraphicsStats: Buffer count: 2
07-26 15:20:59.537   786  2228 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@30d7754)
07-26 15:20:59.538   786   893 D WifiService: Client connection lost with reason: 4
07-26 15:20:59.538   786   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:20:59.538   786   894 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:20:59.551   786   812 W PackageSettings: Skipping PackageSetting{8597fb8 com.example.hello/10116} due to missing metadata
,07-26 15:20:59.593   786   812 I art     : Starting a blocking GC Explicit
,07-26 15:20:59.596   786   971 W ActivityManager: Spurious death for ProcessRecord{60f96fd 0:com.test.thalitest/u0a26}, curProc for 3614: null
,07-26 15:20:59.644   786   812 I art     : Explicit concurrent mark sweep GC freed 36036(2MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 25MB/38MB, paused 688us total 44.881ms
,07-26 15:20:59.668   786   812 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-26 15:20:59.670  4334  4334 I art     : System.exit called, status: 0
07-26 15:20:59.670  4334  4334 I AndroidRuntime: VM exiting with result code 0.
07-26 15:20:59.674   786   812 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
,07-26 15:20:59.706  4134  4134 D BluetoothMapAppObserver: onReceive
,07-26 15:20:59.706  4134  4134 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-26 15:20:59.709  1261  1563 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:59.730   786   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-26 15:20:59.766  1306  1306 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-26 15:20:59.768   786  1327 I ActivityManager: Start proc 4364:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,07-26 15:20:59.769  2194  4362 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-26 15:20:59.800  4364  4364 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,07-26 15:20:59.802  4364  4364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-26 15:20:59.818  1602  4383 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:20:59.819  1602  4383 D AccountUtils: Clearing selected account for com.test.thalitest
,07-26 15:20:59.824  1261  1261 E NetworkScheduler.SR: Invalid parameter app
07-26 15:20:59.824  1261  1261 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-26 15:20:59.827   786   786 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:20:59.829  1602  4383 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-26 15:20:59.835  2194  4362 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,07-26 15:20:59.836  1602  4383 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:20:59.850   786   798 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3614 uid 10026
,07-26 15:20:59.850  1602  4387 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-26 15:20:59.852  1602  4383 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:20:59.853  4364  4381 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:59.853  4364  4381 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
07-26 15:20:59.854  2194  4362 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-26 15:20:59.854  2194  4362 E AndroidRuntime: Process: android.process.acore, PID: 2194
07-26 15:20:59.854  2194  4362 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:59.854  2194  4362 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:59.854  4364  4381 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
07-26 15:20:59.854  4364  4381 E AndroidRuntime: Process: com.android.keychain, PID: 4364
07-26 15:20:59.854  4364  4381 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:59.854  4364  4381 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:59.860  1570  1570 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(302): Wear auto uninstall disabled for package com.test.thalitest
,07-26 15:20:59.863  1602  4383 D gH_CompatibleDatabase: Open irg@1df4e69, release reference: 1
,07-26 15:20:59.864  4364  4381 I Process : Sending signal. PID: 4364 SIG: 9
,07-26 15:20:59.865  1602  4389 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qrp.getWritableDatabase(:com.google.android.gms:2343)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qrm.e(:com.google.android.gms:428)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qrm.b(:com.google.android.gms:764)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qtc.a(:com.google.android.gms:901)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qtc.a(:com.google.android.gms:20622)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qte.run(:com.google.android.gms:1053)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 15:20:59.865  1602  4389 E SQLiteDatabase: 	at qtb.run(:com.google.android.gms:335)
07-26 15:20:59.865  1602  4389 E FA-SVC  : Opening the database failed, dropping and recreating it
07-26 15:20:59.866  2194  4362 I Process : Sending signal. PID: 2194 SIG: 9
,07-26 15:20:59.877  1602  1654 I Icing   : doRemovePackageData com.test.thalitest
,07-26 15:20:59.878  1602  1701 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
07-26 15:20:59.878  1602  1701 E IcingInternalCorpora: Failed to open Apps corpus file.
,07-26 15:20:59.881  1602  1701 E IcingInternalCorpora: Failed to open Apps corpus file.
,07-26 15:20:59.886  1602  1701 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,07-26 15:20:59.896   786   971 I ActivityManager: Process com.android.keychain (pid 4364) has died
,07-26 15:20:59.897   786   971 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,07-26 15:20:59.900  1602  1630 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-26 15:20:59.901  1602  4389 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qrp.getWritableDatabase(:com.google.android.gms:2355)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qrm.e(:com.google.android.gms:428)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qrm.b(:com.google.android.gms:764)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qtc.a(:com.google.android.gms:901)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qtc.a(:com.google.android.gms:20622)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qte.run(:com.google.android.gms:1053)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 15:20:59.901  1602  4389 E SQLiteDatabase: 	at qtb.run(:com.google.android.gms:335)
,07-26 15:20:59.901  1602  4389 E FA-SVC  : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: qtc.a(:com.google.android.gms:901)
07-26 15:20:59.901  1602  4389 W FA-SVC  : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: qtc.a(:com.google.android.gms:901)
07-26 15:20:59.902  1602  4389 E FA-SVC  : Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: qtc.a(:com.google.android.gms:901)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:20:59.902   786  4390 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:20:59.902   786  4390 E DropBoxManagerService: 	... 5 more
07-26 15:20:59.902   786  4391 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:20:59.902   786  4391 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:20:59.902   786  4391 E DropBoxManagerService: 	... 5 more
,07-26 15:20:59.905  1602  4383 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:560)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at irl.c(:com.google.android.gms:216)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at irl.d(:com.google.android.gms:187)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at irg.m(:com.google.android.gms:35519)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at ogk.b(:com.google.android.gms:64)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at okk.c(:com.google.android.gms:278)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentOperation.onHandleIntent(:com.google.android.gms:36)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:82)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at bev.run(:com.google.android.gms:1846)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-26 15:20:59.905  1602  4383 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-26 15:20:59.907  1602  1630 E DriveAsyncService: disk I/O error (code 3850)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at irg.a(:com.google.android.gms:47)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at jzk.l(:com.google.android.gms:487)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at jzk.b(:com.google.android.gms:462)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at jzf.i(:com.google.android.gms:1512)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at jvt.a(:com.google.android.gms:1033)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at gpq.run(:com.google.android.gms:188)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at itt.run(:com.google.android.gms:453)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at iyg.run(:com.google.android.gms:17)
07-26 15:20:59.907  1602  1630 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)

```
