#### Test 7578926821ef376_thali03_LGE-Nexus 5 Logs


```
--------- beginning of system
,07-07 20:26:43.565   792   974 I ActivityManager: Killing 2753:com.google.android.music:main/u0a58 (adj 15): empty #17
--------- beginning of main
07-07 20:26:44.182  3753  3753 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-07 20:26:44.186  3753  3753 D AndroidRuntime: CheckJNI is OFF
07-07 20:26:44.223  3753  3753 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-07 20:26:44.273  3753  3753 I Radio-JNI: register_android_hardware_Radio DONE
07-07 20:26:44.291  3753  3753 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-07 20:26:44.293   792  2031 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-07 20:26:44.305  1381  1399 W SearchService: Abort, client detached.
07-07 20:26:44.311  3753  3753 D AndroidRuntime: Shutting down VM
07-07 20:26:44.325   792  2032 I ActivityManager: Start proc 3769:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-07 20:26:44.340  1381  1381 I MicroDetector: Keeping mic open: false
07-07 20:26:44.340  1381  1381 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@bbd02f6
07-07 20:26:44.340  1381  1576 I DeviceStateChecker: DeviceStateChecker cancelled
07-07 20:26:44.341  1381  1475 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-07 20:26:44.378  1381  1690 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
07-07 20:26:44.397   198  1582 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-07 20:26:44.399   198  1582 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-07 20:26:44.404  1381  1579 I MicroRecognitionRunner: Detection finished
07-07 20:26:44.404  1381  1575 I MicroRecognitionRunner: Stopping hotword detection.
07-07 20:26:44.421  3769  3769 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-07 20:26:44.452  3769  3769 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 8425-8426)
07-07 20:26:44.452  3769  3769 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-07 20:26:44.467  3769  3769 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {278bc01}
07-07 20:26:44.467  3769  3769 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-07 20:26:44.467  3769  3769 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 20:26:44.487   792   896 D WifiService: New client listening to asynchronous messages
07-07 20:26:44.499  3769  3769 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-07 20:26:44.513  3769  3769 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-07 20:26:44.513  3769  3769 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-07 20:26:44.528  3769  3769 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-07 20:26:44.574   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6df0e4a:true
,07-07 20:26:44.604   792  1214 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3769 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-07 20:26:44.617  3769  3769 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-07 20:26:44.627  3769  3769 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:26:44.628  3769  3769 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-07 20:26:44.644  3769  3769 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-07 20:26:44.686  3769  3769 I cr_Ime  : ImeThread is not enabled.
,07-07 20:26:44.702  3769  3821 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-07 20:26:44.764   792  1214 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3769 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-07 20:26:44.783  3769  3825 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:26:44.811  3769  3821 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 20:26:44.828  3769  3825 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-07 20:26:44.883  3769  3825 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-07 20:26:44.910   792   813 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +603ms
,07-07 20:26:44.939  3769  3769 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3769
,07-07 20:26:44.939  3769  3769 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
07-07 20:26:44.940  3769  3769 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,07-07 20:26:45.138   792   964 I ActivityManager: Killing 2220:com.google.android.calendar/u0a28 (adj 15): empty #17
,07-07 20:26:45.215  3769  3769 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:26:45.216   792   897 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-07 20:26:45.329  3769  3841 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1760855760
,07-07 20:26:45.332  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:26:45.332  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:26:45.332  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:26:45.332  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:26:45.332  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-07 20:26:45.332  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f93833 added. We now have 1 listener(s)
,07-07 20:26:45.335  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,07-07 20:26:45.337  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:26:45.338  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:26:45.338  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 20:26:45.340  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26557ee added. We now have 1 listener(s)
07-07 20:26:45.341  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:26:45.342  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-07 20:26:45.343  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:26:45.343  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:26:45.345  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:26:45.345  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:26:45.350  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:26:45.350  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 20:26:45.350  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:26:45.351  3769  3841 I io.jxcore.node.LifeCycleMonitor: start: OK
07-07 20:26:45.352  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:26:45.355  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:26:45.377  3769  3769 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:26:46.113  3769  3843 W jxcore-log: Initializing JXcore engine
07-07 20:26:46.113  3769  3843 W jxcore-log: JXcore engine is ready
,07-07 20:26:46.148  3843  3843 W Thread-318: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[8145]" dev="sockfs" ino=8145 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-07 20:26:46.148  3843  3843 W Thread-318: type=1400 audit(0.0:9): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 20:26:46.148  3843  3843 W Thread-318: type=1400 audit(0.0:10): avc: denied { ioctl } for path="socket:[22212]" dev="sockfs" ino=22212 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-07 20:26:46.170  3769  3843 W jxcore-log: Starting JXcore engine
,07-07 20:26:46.247  3769  3843 W jxcore-log: Platform android
07-07 20:26:46.247  3769  3843 W jxcore-log: 
,07-07 20:26:46.247  3769  3843 W jxcore-log: Process ARCH arm
07-07 20:26:46.247  3769  3843 W jxcore-log: 
,07-07 20:26:46.436  3769  3843 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:26:46.436  3769  3843 I jxcore-log: 
,07-07 20:26:46.436  3769  3843 W jxcore-log: JXcore engine is started
,07-07 20:26:46.439  3769  3841 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 20:26:46.440  3769  3769 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 20:26:54.431  1513  1600 I Finsky  : [110] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-07 20:26:54.569  1513  1600 I Finsky  : [110] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-07 20:26:54.575  1513  1513 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-07 20:26:56.332  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-07 20:26:56.332  3769  3843 I jxcore-log: 
,07-07 20:26:56.334  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-07 20:26:56.334  3769  3843 I jxcore-log: 
,07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:26:56.338  3769  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:26:56.340  3769  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:26:56.341  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-07 20:26:56.341  3769  3843 I jxcore-log: 
07-07 20:26:56.343  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-07 20:26:56.343  3769  3843 I jxcore-log: 
,07-07 20:26:56.715  3769  3843 I jxcore-log: Unit Test app is loaded
07-07 20:26:56.715  3769  3843 I jxcore-log: 
,07-07 20:26:56.719  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:26:56.719  3769  3843 I jxcore-log: 
,07-07 20:26:56.723  3769  3843 I jxcore-log: My device name is: LGE-Nexus 5
07-07 20:26:56.723  3769  3843 I jxcore-log: 
,07-07 20:26:56.724  3769  3769 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-07 20:26:56.725  3769  3841 D JX-Cordova: Running tests
07-07 20:26:56.725  3769  3843 I jxcore-log: WARN testUtils: myNameCallback not set!
07-07 20:26:56.725  3769  3843 I jxcore-log: 
,07-07 20:26:56.803  3769  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-07 20:26:56.803  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-07 20:26:56.803  3769  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-07 20:26:56.803  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-07 20:26:56.803  3769  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-07 20:26:56.803  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-07 20:26:56.804  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:26:56.804  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-07 20:26:56.805  3769  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-07 20:26:56.805  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:26:56.805  3769  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,07-07 20:26:56.805  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-07 20:26:56.805  3769  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-07 20:26:56.805  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-07 20:26:56.807  3769  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-07 20:26:56.807  3769  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-07 20:26:56.807  3769  3841 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-07 20:26:56.807  3769  3841 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,07-07 20:26:56.807  3769  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-07 20:26:56.807  3769  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-07 20:26:56.809  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:26:56.809  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bc75e added. We now have 2 listener(s)
07-07 20:26:56.809  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:26:56.810  3769  3841 D BluetoothAdapter: enable(): BT is already enabled..!
,07-07 20:26:56.810   792  1292 D WifiService: setWifiEnabled: true pid=3769, uid=10026
,07-07 20:26:56.810   792  1292 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:26:56.811  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:26:56.811  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e6b73f added. We now have 3 listener(s)
07-07 20:26:56.811  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:26:56.814  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:26:56.814  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7cb680c added. We now have 4 listener(s)
07-07 20:26:56.814  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:26:56.815  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:26:56.815  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@972555 added. We now have 5 listener(s)
07-07 20:26:56.815  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:26:56.816   792  1312 D WifiService: setWifiEnabled: false pid=3769, uid=10026
07-07 20:26:56.816   792  1312 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:26:56.819   792   895 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-07 20:26:56.819   792   895 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-07 20:26:56.819   792   895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:26:56.819   792   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:26:56.822  1795  1838 D BluetoothAdapterState: Current state: ON, message: 23
07-07 20:26:56.822  1795  1838 D BluetoothAdapterProperties: Setting state to 13
07-07 20:26:56.822  1795  1838 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:26:56.823  1795  1838 D BluetoothAdapterProperties: onBluetoothDisable()
07-07 20:26:56.825  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:26:56.827  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:26:56.827  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:56.827  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:26:56.829  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:26:56.829  1795  1838 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:26:56.830  1795  1795 D BluetoothMapService: onReceive
07-07 20:26:56.830  1795  1795 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:26:56.830  1795  179,5 D BluetoothMapService: STATE_TURNING_OFF
,07-07 20:26:56.830  1795  1795 D BluetoothMapService: MAP Service closeService in
,07-07 20:26:56.830  1795  1795 D BluetoothMapMasInstance0: MAP Service shutdown
,07-07 20:26:56.830  1795  1795 D ObexServerSockets0: shutdown(block = true)
07-07 20:26:56.831  1795  1795 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-07 20:26:56.831  1795  2020 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-07 20:26:56.831  1795  1795 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:26:56.831  1795  2021 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-07 20:26:56.831  1795  2000 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-07 20:26:56.836  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:26:56.837  1795  1795 I BtOppRfcommListener: stopping Accept Thread
,07-07 20:26:56.841   792  2308 D DhcpClient: Clearing IP address
07-07 20:26:56.845   194   667 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:26:56.846  1795  2843 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:26:56.846  1795  2843 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:26:56.849   792   808 I ActivityManager: Start proc 3887:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-07 20:26:56.857   194   667 D CommandListener: Setting iface cfg
07-07 20:26:56.866   792  2309 D DhcpClient: Receive thread stopped
,07-07 20:26:56.865  1795  1842 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:26:56.868  1795  1838 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:26:56.898  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:26:56.898  1795  1795 D HeadsetService: Received stop request...Stopping profile...
07-07 20:26:56.906  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:56.909  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:26:56.912   932   950 D BluetoothHeadset: Proxy object disconnected
07-07 20:26:56.912   932   932 D HeadsetProfile: Bluetooth service disconnected
07-07 20:26:56.912  1313  1441 D BluetoothHeadset: Proxy object disconnected
,07-07 20:26:56.914   792   792 D BluetoothHeadset: Proxy object disconnected
07-07 20:26:56.914   792   792 D BluetoothHeadset: Proxy object disconnected
07-07 20:26:56.914   792   792 D BluetoothHeadset: Proxy object disconnected
07-07 20:26:56.916  1795  1795 D A2dpService: Received stop request...Stopping profile...
07-07 20:26:56.916  1795  2009 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:26:56.917   792   792 D BluetoothA2dp: Proxy object disconnected
07-07 20:26:56.917   932   932 D BluetoothA2dp: Proxy object disconnected
,07-07 20:26:56.918  1795  1795 V BluetoothAdapterState: isTurningOff()=true
,07-07 20:26:56.918  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:56.918  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:26:56.918  1795  1795 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:26:56.918  1795  1795 D HidService: Received stop request...Stopping profile...
,07-07 20:26:56.918  1795  1795 D HidService: Stopping Bluetooth HidService
,07-07 20:26:56.919   932   932 D BluetoothInputDevice: Proxy object disconnected
,07-07 20:26:56.919   932   932 D HidProfile: Bluetooth service disconnected
,07-07 20:26:56.921  1795  1795 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-07 20:26:56.922  1795  1795 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-07 20:26:56.922  1795  1842 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-07 20:26:56.922  1795  1956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:26:56.922  1795  1956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:26:56.922  1795  1842 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-07 20:26:56.922  1795  1795 D HealthService: Received stop request...Stopping profile...
07-07 20:26:56.924  1617  3014 V NativeCrypto: Read error: ssl=0x9a8bdc00: I/O error during system call, Connection timed out
07-07 20:26:56.924  1795  1795 D PanService: Received stop request...Stopping profile...
07-07 20:26:56.925   932   932 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-07 20:26:56.925   932   932 D PanProfile: Bluetooth service disconnected
07-07 20:26:56.926  1617  3014 V NativeCrypto: SSL shutdown failed: ssl=0x9a8bdc00: I/O error during system call, Broken pipe
07-07 20:26:56.928  1617  3014 E GCM     : Wifi connection closed with errorCode 20
07-07 20:26:56.928   792   802 D ConnectivityService: reportNetworkConnectivity(100, false) by 10007
07-07 20:26:56.928   792  2306 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10007
07-07 20:26:56.929  1795  1795 V BluetoothAdapterState: isTurningOff()=true
07-07 20:26:56.929  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:56.929  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:26:56.929  1795  1795 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:26:56.929   792   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:26:56.929   792   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-07 20:26:56.929   792   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 4
07-07 20:26:56.934  1795  1842 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-07 20:26:56.934  1795  1956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:26:56.934  1795  1956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:26:56.934  1795  1956 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:26:56.934  1795  1956 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:26:56.934  1795  1956 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-07 20:26:56.934  1795  1956 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:26:56.935  1795  1795 D BluetoothMapService: Received stop request...Stopping profile...
07-07 20:26:56.935  1795  1795 D BluetoothMapService: stop()
07-07 20:26:56.935  1795  1795 D BluetoothMapAppObserver: deinitObservers()
07-07 20:26:56.935  1795  1795 D BluetoothMapAppObserver: removeReceiver()
07-07 20:26:56.935   792   897 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-07 20:26:56.936   932   932 D BluetoothMap: Proxy object disconnected
,07-07 20:26:56.936   932   932 D MapProfile: Bluetooth service disconnected
,07-07 20:26:56.936  1795  1795 V BluetoothAdapterState: isTurningOff()=true
07-07 20:26:56.936  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:56.936  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:26:56.936  1795  1795 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:26:56.937  1795  1795 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:26:56.937  1795  1795 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:26:56.937  1795  1795 V BluetoothAdapterState: isTurningOff()=true
07-07 20:26:56.937  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:56.937  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:26:56.937  1795  1795 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:26:56.937  1795  1795 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:26:56.937  1795  1842 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-07 20:26:56.937  1795  1842 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-07 20:26:56.937  1795  1795 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:26:56.938  1795  1795 V BluetoothAdapterState: isTurningOff()=true
07-07 20:26:56.938  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:56.938  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:26:56.938   792  2306 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-07 20:26:56.939  1795  1795 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:26:56.939  1795  1795 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-07 20:26:56.939  1795  1795 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:26:56.940  1795  1795 D BluetoothMapService: MAP Service closeService in
07-07 20:26:56.940  1795  1795 V BluetoothAdapterState: isTurningOff()=true
07-07 20:26:56.940  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:56.940  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:26:56.940  1795  1795 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:26:56.940  1795  1838 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:26:56.940  1795  1838 D BluetoothAdapterProperties: Setting state to 15
07-07 20:26:56.940  1795  1838 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:26:56.940  1795  1795 D BluetoothMapService: cleanup()
,07-07 20:26:56.940  1795  1795 D BluetoothMapService: MAP Service closeService in
07-07 20:26:56.941   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:26:56.941   792   812 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:26:56.941   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:26:56.941  1795  1838 I BluetoothAdapterState: Entering BleOnState
07-07 20:26:56.941   932  1401 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:26:56.943   792   792 D RttService: SCAN_AVAILABLE : 1
07-07 20:26:56.944   792   908 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-07 20:26:56.944  1313  1326 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:26:56.944   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:26:56.944   932   950 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:26:56.945   932  1400 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:26:56.945   932   944 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:26:56.946   932  1401 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:26:56.946   932   950 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:26:56.947  1795  1838 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-07 20:26:56.947  1795  1838 D BluetoothAdapterProperties: Setting state to 16
07-07 20:26:56.947  1795  1838 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-07 20:26:56.948   792   895 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-07 20:26:56.949  1795  1838 D BluetoothAdapterProperties: onBleDisable
07-07 20:26:56.949  1795  1838 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:26:56.950  1795  1839 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:26:56.950  1795  1842 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:26:56.952  1795  1956 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-07 20:26:56.952  1795  1956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:26:56.953  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:26:56.954  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:26:56.955   792   895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:26:56.956  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:26:56.956  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:26:56.963   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-07 20:26:56.966   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-07 20:26:56.969  3887  3887 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-07 20:26:56.972   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-07 20:26:56.973   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
07-07 20:26:56.975   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
07-07 20:26:56.992   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-07 20:26:57.003   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-07 20:26:57.006   194   667 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:26:57.018  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:26:57.032   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e834f8b:true
07-07 20:26:57.038   194   667 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:26:57.039   194   667 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:26:57.039   792   897 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-07 20:26:57.039   792   897 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-07 20:26:57.040   792   812 D Tethering: MasterInitialState.processMessage what=3
07-07 20:26:57.043   792   895 D DhcpClient: doQuit
07-07 20:26:57.043   792   895 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:26:57.050   792  2308 D DhcpClient: onQuitting
,07-07 20:26:57.053  3769  3769 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-07 20:26:57.060  1381  1381 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:26:57.064  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:26:57.065  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:26:57.069  1795  1842 I bt_hci  : shut_down
,07-07 20:26:57.069  1795  1857 D bt_hwcfg: hw_epilog_process
,07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:26:57.072  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:26:57.072  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:26:57.073  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:26:57.074  1795  1857 I bt_vendor: low_power_mode_cb
07-07 20:26:57.075  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:26:57.082  3887  3887 D LocalBluetoothProfileManager: Adding local MAP profile
,07-07 20:26:57.094  1795  1857 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-07 20:26:57.094  1795  1857 I bt_vendor: epilog_cb
07-07 20:26:57.094  1795  1857 I bt_hci  : epilog_finished_callback
07-07 20:26:57.095  1795  1842 I bt_hci_h4: hal_close
,07-07 20:26:57.095  1795  1842 I bt_userial_vendor: device fd = 49 close
,07-07 20:26:57.102  3887  3887 D BluetoothMap: Create BluetoothMap proxy object
,07-07 20:26:57.103   792   802 I ActivityManager: Killing 3087:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-07 20:26:57.105  1795  1839 D bt_stack_manager: event_shut_down_stack finished.
,07-07 20:26:57.106  1795  1838 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-07 20:26:57.116  1257  1257 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-07 20:26:57.118  1257  1257 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-07 20:26:57.128   194   667 E Netd    : netlink response contains error (No such file or directory)
07-07 20:26:57.128  1257  1257 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-07 20:26:57.129   792   897 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-07 20:26:57.216  1257  1257 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-07 20:26:57.266  1795  1795 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:26:57.266  1795  1838 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-07 20:26:57.267  1795  1795 D BtGatt.GattService: Received stop request...Stopping profile...
07-07 20:26:57.268  1795  1795 D BtGatt.GattService: stop()
,07-07 20:26:57.268  1795  1795 D BtGatt.AdvertiseManager: advertise clients cleared
07-07 20:26:57.269  1795  1795 V BluetoothAdapterState: isTurningOff()=false
07-07 20:26:57.269  1795  1795 V BluetoothAdapterState: isTurningOn()=false
07-07 20:26:57.269  1795  1795 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:26:57.269  1795  1795 V BluetoothAdapterState: isBleTurningOff()=true
,07-07 20:26:57.269  1795  1838 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-07 20:26:57.269  1795  1838 D BluetoothAdapterProperties: Setting state to 10
07-07 20:26:57.269  1795  1838 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:26:57.269  3887  3887 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-07 20:26:57.270  1795  1838 I BluetoothAdapterState: Entering OffState
07-07 20:26:57.270   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-07 20:26:57.274  1795  1795 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-07 20:26:57.274  1795  1795 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:26:57.274  1795  1795 I BluetoothServiceJni: cleanupNative: return from cleanup
07-07 20:26:57.274  1795  1839 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-07 20:26:57.279  3887  3887 D DockEventReceiver: finishStartingService: stopping service
07-07 20:26:57.279  1795  1795 I art     : System.exit called, status: 0
,07-07 20:26:57.279  1795  1795 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:26:57.286  1257  1257 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-07 20:26:57.294   792   896 D WifiService: New client listening to asynchronous messages
,07-07 20:26:57.476   792  1214 I ActivityManager: Process com.android.bluetooth (pid 1795) has died
,07-07 20:26:57.480   792   895 D wifi    : In wifi stop Hal
07-07 20:26:57.480   792   895 D wifi    : halHandle = 0x93165f60, mVM = 0xb4d7c000, mCls = 0x100a2a
07-07 20:26:57.480   792  1256 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-07 20:26:57.480   792  1256 D WifiHAL : Got a signal to exit!!!
07-07 20:26:57.480   792  1256 I WifiHAL : Exit wifi_event_loop
,07-07 20:26:57.481   792   895 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-07 20:26:57.481   792   895 E WifiHAL : Event processing terminated
,07-07 20:26:57.481   792   895 D wifi    : In wifi cleaned up handler
07-07 20:26:57.481   792   895 I WifiHAL : Internal cleanup completed
,07-07 20:26:57.484  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:26:57.484  1617  1694 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:26:57.484  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:26:57.500   792   803 I ActivityManager: Start proc 3934:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,07-07 20:26:57.506   792  2769 I ActivityManager: Killing 3108:com.android.providers.calendar/u0a1 (adj 15): empty #17
,07-07 20:26:57.598   792  1256 D wifi    : set interface wlan0 flags (DOWN)
,07-07 20:26:57.598   792   895 D WifiNative-HAL: HAL event thread stopped successfully
,07-07 20:26:57.803   792   812 D Tethering: InitialState.processMessage what=4
07-07 20:26:57.805   792   812 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-07 20:26:57.810  3934  3934 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:26:57.811  3934  3934 D AdapterServiceConfig: Adding A2dpService
07-07 20:26:57.811  3934  3934 D AdapterServiceConfig: Adding HidService
07-07 20:26:57.811  3934  3934 D AdapterServiceConfig: Adding HealthService
,07-07 20:26:57.811  3934  3934 D AdapterServiceConfig: Adding PanService
07-07 20:26:57.813  3934  3934 D AdapterServiceConfig: Adding GattService
,07-07 20:26:57.813  3934  3934 D AdapterServiceConfig: Adding BluetoothMapService
07-07 20:26:57.816   792  1292 I ActivityManager: Killing 3201:com.google.android.talk/u0a51 (adj 15): empty #17
,07-07 20:26:57.929  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-07 20:26:57.932  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:26:57.956   792   964 I ActivityManager: Start proc 3949:com.google.android.talk/u0a51 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-07 20:26:58.310  3949  3949 I Babel_telephony: TeleModule.onApplicationCreate
,07-07 20:26:58.338  3949  3949 I Babel_Crash: Startup - clean
,07-07 20:26:58.340  3949  3972 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-07 20:26:58.340  3949  3972 I Babel_SMS: MmsConfig.loadMmsSettings
07-07 20:26:58.341  3949  3972 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
07-07 20:26:58.341  3949  3972 I Babel_SMS: MmsConfig.loadFromDatabase
,07-07 20:26:58.348  3949  3975 I Babel_SMS: ApnsOta: OTA version -1
,07-07 20:26:58.366  3949  3972 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-07 20:26:58.366  3949  3972 I Babel_SMS: MmsConfig.loadFromResources
07-07 20:26:58.367  3949  3972 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-07 20:26:58.367  3949  3972 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-07 20:26:58.390  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:26:58.397  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:26:58.405  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:26:58.410   792  1312 I ActivityManager: Killing 2279:com.google.android.keep/u0a52 (adj 15): empty #17
,07-07 20:26:58.411  1617  3987 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:26:58.412  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:26:58.699   792  1312 I ActivityManager: Start proc 4000:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-07 20:26:58.731  1617  3987 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-07 20:26:58.754  4000  4000 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-07 20:26:58.795  4000  4000 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-07 20:26:58.801   792  1308 I ActivityManager: Start proc 4027:com.google.android.apps.plus/u0a63 for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver
,07-07 20:26:58.810  4000  4023 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-07 20:26:59.042   792   964 I ActivityManager: Killing 3016:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,07-07 20:26:59.124  1603  1603 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-07 20:26:59.128  1603  3000 I iu.UploadsManager: num queued entries: 0
,07-07 20:26:59.128  1603  3000 I iu.UploadsManager: num updated entries: 0
07-07 20:26:59.129  1603  3000 I iu.SyncManager: NEXT; no task
,07-07 20:26:59.139   792  2769 I ActivityManager: Start proc 4057:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-07 20:26:59.174  4057  4057 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-07 20:26:59.179  4057  4057 I MultiDex: VM with version 2.1.0 has multidex support
,07-07 20:26:59.179  4057  4057 I MultiDex: install
07-07 20:26:59.179  4057  4057 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-07 20:26:59.219  4057  4057 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-07 20:26:59.219  4057  4057 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-07 20:26:59.219  4057  4057 I GAv4    :   adb logcat -s GAv4
,07-07 20:26:59.229  4057  4057 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:26:59.236  4057  4075 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:26:59.347  4057  4057 I NSApplication: Starting up...
,07-07 20:26:59.365   792  1214 I ActivityManager: Killing 3500:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-07 20:26:59.492  1603  1603 V Herrevad: NQAS connected
,07-07 20:26:59.507   792   964 I ActivityManager: Start proc 4100:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,07-07 20:26:59.558  1603  1647 W Herrevad: Invalid mccmnc 
,07-07 20:26:59.566  1603  1647 W Herrevad: Invalid mccmnc 
,07-07 20:26:59.592  4057  4057 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-07 20:26:59.601  4100  4100 W InstanceID/Rpc: Found 10007
,07-07 20:26:59.619   792   964 I ActivityManager: Killing 3641:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-07 20:26:59.828   792   802 D WifiService: setWifiEnabled: true pid=3769, uid=10026
07-07 20:26:59.828   792   802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:26:59.831   194   667 D SoftapController: Softap fwReload - Ok
,07-07 20:26:59.833   194   667 D CommandListener: Setting iface cfg
07-07 20:26:59.833   194   667 D CommandListener: Trying to bring down wlan0
,07-07 20:26:59.834   194   667 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:26:59.836   792   895 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:27:00.583   792   895 D wifi    : set interface wlan0 flags (UP)
,07-07 20:27:00.584   792   895 I WifiHAL : Initializing wifi
,07-07 20:27:00.584   792   895 I WifiHAL : Creating socket
,07-07 20:27:00.584   792   812 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-07 20:27:00.586   792   895 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-07 20:27:00.586   792   895 D wifi    : Did set static halHandle = 0x93165f60
07-07 20:27:00.586   792   895 D wifi    : halHandle = 0x93165f60, mVM = 0xb4d7c000, mCls = 0x1622
07-07 20:27:00.586   792   895 D wifi    : array field set
07-07 20:27:00.586   792   895 I WifiNative-HAL: interface[0] = p2p0
07-07 20:27:00.586   792   895 I WifiNative-HAL: interface[1] = wlan0
07-07 20:27:00.588   792   895 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-07 20:27:00.589  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:00.590  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:00.590   792   895 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-07 20:27:00.591   792  4129 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1827250336
07-07 20:27:00.592   792  4129 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x1622, env = 0xacb8c0c0
,07-07 20:27:00.646  4130  4130 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-07 20:27:00.673  4130  4130 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:27:00.840  4130  4130 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:27:00.930  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-07 20:27:00.930  3769  3843 I jxcore-log: 
,07-07 20:27:01.331  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-07 20:27:01.331  3769  3843 I jxcore-log: 
,07-07 20:27:01.355  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-07 20:27:01.355  3769  3843 I jxcore-log: 
,07-07 20:27:01.359  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-07 20:27:01.359  3769  3843 I jxcore-log: 
,07-07 20:27:01.374  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-07 20:27:01.374  3769  3843 I jxcore-log: 
,07-07 20:27:01.378  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-07 20:27:01.378  3769  3843 I jxcore-log: 
,07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:01.598  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:01.598  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:01.599  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:01.599  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:01.600   792   895 D WifiConfigStore: Loading config and enabling all networks 
07-07 20:27:01.609   792   895 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:27:01.610   792   895 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-07 20:27:01.610   792   895 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:27:01.611   792   895 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-07 20:27:01.611   792   895 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-07 20:27:01.614   792   895 D WifiNative-HAL: Setting external_sim to 1
07-07 20:27:01.615   792   895 D wifi    : setting dfs flag to true, 0x9d47dc90
07-07 20:27:01.615   792   895 D WifiStateMachine: Setting OUI to DA-A1-19
07-07 20:27:01.615   792   895 D wifi    : setting scan oui 0x9d47dc90
07-07 20:27:01.615   792   895 D WifiHAL : Sending mac address OUI
,07-07 20:27:01.626   792   895 E native  : do suspend false
,07-07 20:27:01.632   792   895 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-07 20:27:01.634   792   792 D RttService: SCAN_AVAILABLE : 3
07-07 20:27:01.634   792   908 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler },
07-07 20:27:01.640   792   895 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:27:01.641   194   667 D CommandListener: Setting iface cfg
07-07 20:27:01.641   194   667 D CommandListener: Trying to bring up p2p0
07-07 20:27:01.641   792   894 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-07 20:27:01.644   792   894 D WifiNative-HAL: p2pGetDeviceAddress,
07-07 20:27:01.645   792   894 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-07 20:27:02.831   792   803 D WifiService: setWifiEnabled: false pid=3769, uid=10026
,07-07 20:27:02.831   792   803 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:27:02.834   792   895 D WifiConfigStore: Retrieve network priorities after PNO.
07-07 20:27:02.836   792   792 D RttService: SCAN_AVAILABLE : 1
07-07 20:27:02.836   792   908 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-07 20:27:02.851   792   895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:27:02.851   194   667 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:27:02.867   792   895 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:02.871  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:02.871  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:02.872  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:02.872  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:02.956  4130  4130 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-07 20:27:02.987  4130  4130 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-07 20:27:03.185  4130  4130 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-07 20:27:03.217  4130  4130 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-07 20:27:03.319   792   895 D wifi    : In wifi stop Hal
,07-07 20:27:03.319   792   895 D wifi    : halHandle = 0x93165f60, mVM = 0xb4d7c000, mCls = 0x1622
,07-07 20:27:03.320   792  4129 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-07 20:27:03.320   792  4129 D WifiHAL : Got a signal to exit!!!
07-07 20:27:03.321   792  4129 I WifiHAL : Exit wifi_event_loop
07-07 20:27:03.322  1617  1694 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:27:03.322  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:03.322   792   895 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,07-07 20:27:03.322   792   895 E WifiHAL : Event processing terminated
,07-07 20:27:03.322   792   895 D wifi    : In wifi cleaned up handler
,07-07 20:27:03.322   792   895 I WifiHAL : Internal cleanup completed
07-07 20:27:03.322  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:03.428  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-07 20:27:03.428  3769  3843 I jxcore-log: 
,07-07 20:27:03.439  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-07 20:27:03.439  3769  3843 I jxcore-log: 
,07-07 20:27:03.443   792  4129 D wifi    : set interface wlan0 flags (DOWN)
,07-07 20:27:03.443   792   895 D WifiNative-HAL: HAL event thread stopped successfully
,07-07 20:27:03.447  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-07 20:27:03.447  3769  3843 I jxcore-log: 
,07-07 20:27:03.599  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-07 20:27:03.599  3769  3843 I jxcore-log: 
,07-07 20:27:03.645   792   812 D Tethering: InitialState.processMessage what=4
,07-07 20:27:03.646   792   812 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-07 20:27:03.682  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-07 20:27:03.682  3769  3843 I jxcore-log: 
,07-07 20:27:03.750   792  2769 I ActivityManager: Killing 3663:com.android.musicfx/u0a13 (adj 15): empty #17
,07-07 20:27:03.807  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-07 20:27:03.807  3769  3843 I jxcore-log: 
,07-07 20:27:03.817  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-07 20:27:03.817  3769  3843 I jxcore-log: 
,07-07 20:27:04.014  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-07 20:27:04.014  3769  3843 I jxcore-log: 
,07-07 20:27:04.034  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-07 20:27:04.034  3769  3843 I jxcore-log: 
,07-07 20:27:04.039  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-07 20:27:04.039  3769  3843 I jxcore-log: 
,07-07 20:27:04.044  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-07 20:27:04.044  3769  3843 I jxcore-log: 
,07-07 20:27:04.059  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-07 20:27:04.059  3769  3843 I jxcore-log: 
,07-07 20:27:04.078  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-07 20:27:04.078  3769  3843 I jxcore-log: 
,07-07 20:27:04.163  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-07 20:27:04.163  3769  3843 I jxcore-log: 
,07-07 20:27:04.168  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-07 20:27:04.168  3769  3843 I jxcore-log: 
,07-07 20:27:04.193  3769  3843 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-07 20:27:04.193  3769  3843 I jxcore-log: 
,07-07 20:27:04.202  3769  3843 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-07 20:27:04.202  3769  3843 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-07 20:27:04.202  3769  3843 I jxcore-log: 
,07-07 20:27:04.250  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:27:04.250  3769  3843 I jxcore-log: 
,07-07 20:27:04.250  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:27:04.250  3769  3843 I jxcore-log: 
07-07 20:27:04.251  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:04.251  3769  3843 I jxcore-log: 
07-07 20:27:04.253  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:04.253  3769  3843 I jxcore-log: 
07-07 20:27:04.253  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:04.253  3769  3843 I jxcore-log: 
07-07 20:27:04.254  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:04.254  3769  3843 I jxcore-log: 
07-07 20:27:04.255  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:04.255  3769  3843 I jxcore-log: 
07-07 20:27:04.255  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:04.255  3769  3843 I jxcore-log: 
,07-07 20:27:04.256  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:04.256  3769  3843 I jxcore-log: 
,07-07 20:27:04.256  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:04.256  3769  3843 I jxcore-log: 
,07-07 20:27:05.894   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@46d6307:true
,07-07 20:27:05.894  3934  3934 D BluetoothAdapterState: make() - Creating AdapterState
,07-07 20:27:05.896  3934  3934 I bt_bluedroid: init
07-07 20:27:05.897  3934  4193 I BluetoothAdapterState: Entering OffState
,07-07 20:27:05.899  3934  4194 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-07 20:27:05.899  3934  4194 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-07 20:27:05.899  3934  4194 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:27:05.899  3934  4194 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-07 20:27:05.900  3934  3934 I bt_bluedroid: get_profile_interface socket
,07-07 20:27:05.901  3934  3934 I bt_bluedroid: get_profile_interface sdp
,07-07 20:27:05.902  3934  3945 I bt_bluedroid: config_hci_snoop_log
07-07 20:27:05.903   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-07 20:27:05.905  3934  4193 D BluetoothAdapterState: Current state: OFF, message: 0
07-07 20:27:05.905  3934  4193 D BluetoothAdapterProperties: Setting state to 14
07-07 20:27:05.905  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-07 20:27:05.906  3934  4193 D BluetoothBondStateMachine: make
,07-07 20:27:05.908  3934  4197 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-07 20:27:05.909  3934  4197 D BluetoothAdapterProperties: Name is: Nexus 5
,07-07 20:27:05.912  3934  3934 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-07 20:27:05.913  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:05.914  3934  4193 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:05.914  3934  3934 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:27:05.914  3934  3934 D BtGatt.GattService: Received start request. Starting profile...
07-07 20:27:05.914  3934  3934 D BtGatt.GattService: start()
07-07 20:27:05.914  3934  3934 I bt_bluedroid: get_profile_interface gatt
,07-07 20:27:05.915  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:05.915  3934  3934 D BtGatt.AdvertiseManager: advertise manager created
07-07 20:27:05.915  3934  4198 I BluetoothBondStateMachine: StableState(): Entering Off State
07-07 20:27:05.920  3934  3934 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:05.920  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:05.920  3934  3934 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:27:05.920  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:05.921  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:27:05.921  3934  4193 I bt_bluedroid: enable
07-07 20:27:05.921  3934  4194 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-07 20:27:05.921  3934  4194 I bt_hci  : start_up
07-07 20:27:05.926  3934  4194 I bt_vendor: alloc value 0xb39f9631
07-07 20:27:05.926  3934  4194 I bt_vendor: init
07-07 20:27:05.926  3934  4194 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-07 20:27:05.926  3934  4194 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-07 20:27:05.965  3934  4194 D bt_hci  : start_up starting async portion
,07-07 20:27:05.966  3934  4201 I bt_hci  : event_finish_startup
07-07 20:27:05.966  3934  4201 I bt_hci_h4: hal_open
07-07 20:27:05.966  3934  4201 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-07 20:27:05.969  3934  4201 I bt_userial_vendor: device fd = 49 open
,07-07 20:27:06.054  3934  4201 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:27:06.081  3934  4201 D bt_hwcfg: Chipset BCM4335C0
,07-07 20:27:06.081  3934  4201 D bt_hwcfg: Target name = [BCM4335C0]
07-07 20:27:06.081  3934  4201 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-07 20:27:06.595  3934  4201 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:27:06.596  3934  4201 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:27:06.596  3934  4201 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:27:06.711  3934  4201 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-07 20:27:06.711  3934  4201 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-07 20:27:06.742  3934  4201 I bt_hwcfg: vendor lib fwcfg completed
07-07 20:27:06.742  3934  4201 I bt_vendor: firmware callback
07-07 20:27:06.742  3934  4201 I bt_hci  : firmware_config_callback
,07-07 20:27:06.744  3934  4205 I bt_btu  : btu_task pending for preload complete event
,07-07 20:27:06.744  3934  4205 I bt_btu_task: Bluetooth chip preload is complete
07-07 20:27:06.744  3934  4205 I bt_btu  : btu_task received preload complete event
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_HCI
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_AVDT
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_AVRC
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_A2D
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_BNEP
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_BTM
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_PAN
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_SDP
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_GATT
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_SMP
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-07 20:27:06.746  3934  4205 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:27:06.971  3934  4205 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39779b5
,07-07 20:27:06.971  3934  4205 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39779b5 
,07-07 20:27:07.087  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:27:07.087  3934  4197 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-07 20:27:07.088  3934  4197 D BluetoothAdapterProperties: Name is: Nexus 5
07-07 20:27:07.090  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:07.090  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:07.090  3934  4197 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:07.090  3934  4197 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:27:07.091  3934  4197 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-07 20:27:07.091  3934  4197 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-07 20:27:07.091  3934  4197 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-07 20:27:07.092  3934  4197 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
,07-07 20:27:07.092  3934  4197 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-07 20:27:07.092  3934  4197 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-07 20:27:07.092  3934  4197 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-07 20:27:07.130  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-07 20:27:07.134  3934  3934 I BluetoothHidServiceJni: classInitNative: succeeds
07-07 20:27:07.134  3934  3934 D HidService: getHidService(): service is NULL
,07-07 20:27:07.138  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,07-07 20:27:07.139  3934  3934 D HidService: getHidService(): service is NULL
,07-07 20:27:07.140  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-07 20:27:07.141  3934  3934 D HidService: getHidService(): service is NULL
07-07 20:27:07.142  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-07 20:27:07.143  3934  3934 D HidService: getHidService(): service is NULL
07-07 20:27:07.144  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-07 20:27:07.144  3934  3934 D HidService: getHidService(): service is NULL
,07-07 20:27:07.147  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,07-07 20:27:07.148  3934  3934 D HidService: getHidService(): service is NULL
,07-07 20:27:07.150  3934  4197 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,07-07 20:27:07.150  3934  3934 D HidService: getHidService(): service is NULL
07-07 20:27:07.151  3934  4197 D bt_hci  : do_postload posting postload work item
07-07 20:27:07.151  3934  4201 I bt_hci  : event_postload
07-07 20:27:07.151  3934  4201 I bt_vendor: sco_config_cb
07-07 20:27:07.151  3934  4201 I bt_hci  : sco_config_callback postload finished.
,07-07 20:27:07.152  3934  4197 D bt_bte_conf: Device ID record 1 : primary
,07-07 20:27:07.152  3934  4197 D bt_bte_conf:   vendorId            = 000f
07-07 20:27:07.152  3934  4197 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:27:07.152  3934  4197 D bt_bte_conf:   product             = 1200
07-07 20:27:07.152  3934  4197 D bt_bte_conf:   version             = 1436
07-07 20:27:07.152  3934  4197 D bt_bte_conf:   clientExecutableURL = 
07-07 20:27:07.152  3934  4197 D bt_bte_conf:   serviceDescription  = 
07-07 20:27:07.152  3934  4197 D bt_bte_conf:   documentationURL    = 
07-07 20:27:07.156  3934  4197 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-07 20:27:07.156  3934  4194 D bt_stack_manager: event_start_up_stack finished
07-07 20:27:07.156  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-07 20:27:07.156  3934  4193 D BluetoothAdapterProperties: Setting state to 15
07-07 20:27:07.156  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-07 20:27:07.158  3934  4193 I BluetoothAdapterState: Entering BleOnState
07-07 20:27:07.159  3934  4193 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-07 20:27:07.159  3934  4193 D BluetoothAdapterProperties: Setting state to 11
07-07 20:27:07.159  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-07 20:27:07.163  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:07.166  3934  4201 I bt_vendor: low_power_mode_cb
07-07 20:27:07.168  3934  3934 D HeadsetService: Received start request. Starting profile...
07-07 20:27:07.168  3934  3934 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:27:07.169  3934  3934 D HeadsetStateMachine: make
,07-07 20:27:07.186  3934  3934 D HeadsetStateMachine: max_hf_connections = 1
,07-07 20:27:07.186  3934  3934 I bt_bluedroid: get_profile_interface handsfree
07-07 20:27:07.189  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:07.189  3934  3934 D A2dpService: Received start request. Starting profile...
07-07 20:27:07.189  3934  3934 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-07 20:27:07.189  3934  3934 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:27:07.198  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-07 20:27:07.198  3934  4197 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-07 20:27:07.201  3934  4193 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:07.206  3934  3934 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:27:07.206  3934  3934 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-07 20:27:07.206  3934  3934 D A2dpStateMachine: make
07-07 20:27:07.206   932  1144 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:07.207  3934  3934 I bt_bluedroid: get_profile_interface a2dp
07-07 20:27:07.208  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-07 20:27:07.209  3934  4224 D A2dpStateMachine: Enter Disconnected: -2
07-07 20:27:07.211  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:07.216  3934  3934 D HidService: Received start request. Starting profile...
07-07 20:27:07.216  3934  3934 I bt_bluedroid: get_profile_interface hidhost
07-07 20:27:07.216  3934  3934 D HidService: setHidService(): set to: null
,07-07 20:27:07.216  3934  4197 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3959099
,07-07 20:27:07.216  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-07 20:27:07.217  3934  3934 I BluetoothHealthServiceJni: classInitNative: succeeds
07-07 20:27:07.218  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:07.219  3934  3934 D HealthService: Received start request. Starting profile...
07-07 20:27:07.220  3934  3934 I bt_bluedroid: get_profile_interface health
07-07 20:27:07.220  3934  3934 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-07 20:27:07.220  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:07.220  3887  3887 D BluetoothInputDevice: Proxy object connected
07-07 20:27:07.221  3934  3934 D PanService: Received start request. Starting profile...
,07-07 20:27:07.221  3934  3934 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:27:07.221  3934  3934 I bt_bluedroid: get_profile_interface pan
07-07 20:27:07.222  3934  4197 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:27:07.224  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:07.228  3934  3934 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:07.228  3934  3934 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:07.228  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:27:07.228  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:07.232  3934  3934 D BluetoothMapService: Received start request. Starting profile...
07-07 20:27:07.232  3934  3934 D BluetoothMapService: start()
07-07 20:27:07.236  3934  3934 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-07 20:27:07.236  3934  3934 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-07 20:27:07.236  3934  3934 D BluetoothMapAppObserver: createReceiver()
,07-07 20:27:07.237  3934  3934 D BluetoothMapAppObserver: initObservers()
07-07 20:27:07.237  3934  3934 D BluetoothMapAppObserver: getEnabledAccountItems()
07-07 20:27:07.238  3887  3887 D HidProfile: Bluetooth service connected
07-07 20:27:07.243  3934  4219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:27:07.244  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:07.245  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:07.245  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:27:07.245  3934  4193 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:27:07.245  3934  4193 D BluetoothAdapterProperties: State =  11
07-07 20:27:07.245  3934  4193 D BluetoothAdapterProperties: Setting state to 12
,07-07 20:27:07.245  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:27:07.246  3887  3898 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:27:07.248  3934  4197 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:27:07.248  3934  4197 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:07.249  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:07.251  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:07.252  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:27:07.252  3769  3843 I jxcore-log: 
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:07.254  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:07.255  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:07.256  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:27:07.256  3769  3843 I jxcore-log: 
07-07 20:27:07.257  3934  4193 I BluetoothAdapterState: Entering OnState
07-07 20:27:07.257   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:07.258  3887  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:27:07.258  3887  3907 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:27:07.259  3887  3898 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:27:07.261   792   812 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:27:07.262   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:07.262   932  1400 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:27:07.265  1313  1442 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:07.266   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:07.266   932  1401 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:07.267   932   950 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-07 20:27:07.270   932   944 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:27:07.272   932   932 D BluetoothInputDevice: Proxy object connected
07-07 20:27:07.272   932   932 D HidProfile: Bluetooth service connected
07-07 20:27:07.273   932  1401 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:27:07.275   932  1400 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:27:07.279   792   792 I Telecom : BluetoothPhoneService: queryPhoneState
07-07 20:27:07.281  3934  3934 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:27:07.281  3934  3934 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-07 20:27:07.282  3887  3887 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:27:07.282  3887  3887 D PanProfile: Bluetooth service connected
07-07 20:27:07.283  3934  3934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:27:07.285  3934  3934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:27:07.285  3934  3934 D ObexServerSockets: Succeed to create listening sockets 
,07-07 20:27:07.285  3934  3934 D ObexServerSockets0: startAccept()
07-07 20:27:07.285  3934  3934 D ObexServerSockets0: prepareForNewConnect()
07-07 20:27:07.292  3887  3887 D BluetoothMap: Proxy object connected
07-07 20:27:07.293  3887  3887 D MapProfile: Bluetooth service connected
07-07 20:27:07.293  3887  3887 D BluetoothMap: getConnectedDevices()
07-07 20:27:07.293  3934  3934 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-07 20:27:07.293  3934  3934 D BluetoothSdpJni: SDP Create record success - handle: 0
07-07 20:27:07.294   792   792 D BluetoothA2dp: Proxy object connected
07-07 20:27:07.294  3934  4237 D ObexServerSockets0: Accepting socket connection...
07-07 20:27:07.295  3934  4238 D ObexServerSockets0: Accepting socket connection...
07-07 20:27:07.296  3934  3934 D BluetoothMapService: onReceive
07-07 20:27:07.296  3934  3934 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:27:07.296  3934  3934 D BluetoothMapService: STATE_ON
,07-07 20:27:07.298  3887  3887 D LocalBluetoothProfileManager: Adding local A2DP profile
07-07 20:27:07.305   932   932 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:27:07.305   932   932 D PanProfile: Bluetooth service connected
07-07 20:27:07.305   932   932 D BluetoothMap: Proxy object connected
07-07 20:27:07.305   932   932 D MapProfile: Bluetooth service connected
,07-07 20:27:07.305   932   932 D BluetoothMap: getConnectedDevices()
07-07 20:27:07.308  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-07 20:27:07.310   932   932 D BluetoothA2dp: Proxy object connected
07-07 20:27:07.313  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-07 20:27:07.314  3887  3887 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-07 20:27:07.321  3934  3934 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:27:07.321  3934  3934 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:27:07.352  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.354  3887  3887 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-07 20:27:07.357  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.360   932  1401 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.360  1313  1326 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.362   792   792 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.362   792   792 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.362   792   792 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.362   792   812 D BluetoothHeadset: Proxy object connected
07-07 20:27:07.362   932   932 D HeadsetProfile: Bluetooth service connected
,07-07 20:27:07.366  1313  1327 D BluetoothHeadset: Proxy object connected
07-07 20:27:07.366   792   812 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.368   932   944 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.380   932   932 D HeadsetProfile: Bluetooth service connected
,07-07 20:27:07.396   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.397  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.398  3887  3887 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-07 20:27:07.399  1617  1617 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-07 20:27:07.402  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.402   932  1144 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-07 20:27:07.408   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.410  1617  1617 I BeaconBle: BLE 'JB+' software access layer enabled
,07-07 20:27:07.412  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.413  3887  3887 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-07 20:27:07.414  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.422  3887  3898 D BluetoothHeadset: Proxy object connected
,07-07 20:27:07.424  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.426  3887  3887 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-07 20:27:07.428  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.430  1617  4260 D BluetoothAdapter: startLeScan(): null
,07-07 20:27:07.433  1617  4260 D BluetoothAdapter: STATE_ON
,07-07 20:27:07.436  3934  3944 D BtGatt.GattService: registerClient() - UUID=8e8a1136-a95d-42a2-9f52-2d1c202f217f
,07-07 20:27:07.437  3934  4197 D BtGatt.GattService: onClientRegistered() - UUID=8e8a1136-a95d-42a2-9f52-2d1c202f217f, clientIf=5
,07-07 20:27:07.437  1617  1627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:27:07.438  3934  4246 D BtGatt.GattService: start scan with filters
,07-07 20:27:07.440  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.440  3934  4200 D BtGatt.ScanManager: handling starting scan
,07-07 20:27:07.442  3887  3887 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-07 20:27:07.442  3934  4200 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-07 20:27:07.442  3934  4200 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-07 20:27:07.442  3934  4200 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-07 20:27:07.443  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.444  3934  4197 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-07 20:27:07.454   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.454  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.456  3887  3887 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
07-07 20:27:07.456  3887  3887 D MapProfile: getConnectionStatus: status is: 0
07-07 20:27:07.458   932  1144 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-07 20:27:07.460   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.467  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.468  3887  3887 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-07 20:27:07.470  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.470  3887  3887 D BluetoothA2dp: Proxy object connected
,07-07 20:27:07.472  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:27:07.474  3887  3887 D HeadsetProfile: Bluetooth service connected
,07-07 20:27:07.481  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:07.485  3934  4262 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:07.488  3887  3887 D BluetoothPbap: Proxy object connected
,07-07 20:27:07.489  3887  3887 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:07.497   932   932 D BluetoothPbap: Proxy object connected
,07-07 20:27:07.497   932   932 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:07.500  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:07.503   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.504  1617  4265 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:27:07.507  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:27:07.513  3934  4269 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:07.513   932  1144 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-07 20:27:07.514  3934  4269 I BtOppRfcommListener: Accept thread started.
,07-07 20:27:07.517   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.522  1617  4265 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-07 20:27:07.538   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.539   932  1144 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-07 20:27:07.540   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.553   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.554   932  1144 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-07 20:27:07.555   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:07.570   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:07.571   932  1144 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-07 20:27:07.572   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:08.854  3934  4193 D BluetoothAdapterState: Current state: ON, message: 23
,07-07 20:27:08.855  3934  4193 D BluetoothAdapterProperties: Setting state to 13
07-07 20:27:08.855  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:27:08.856  3934  4193 D BluetoothAdapterProperties: onBluetoothDisable()
,07-07 20:27:08.892  3934  4193 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:08.893  3934  4197 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:08.893  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:08.894  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:08.895  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:08.895  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:08.899  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:27:08.902  3934  3934 D BluetoothMapService: onReceive
,07-07 20:27:08.902  3934  3934 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-07 20:27:08.902  3934  3934 D BluetoothMapService: STATE_TURNING_OFF
07-07 20:27:08.902  3934  3934 D BluetoothMapService: MAP Service closeService in
07-07 20:27:08.902  3934  3934 D BluetoothMapMasInstance0: MAP Service shutdown
07-07 20:27:08.902  3934  3934 D ObexServerSockets0: shutdown(block = true)
07-07 20:27:08.903  3934  3934 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:27:08.903  3934  3934 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:27:08.903  3934  4237 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-07 20:27:08.903  3934  4214 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-07 20:27:08.903  3934  4238 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-07 20:27:08.904  3934  3934 I BtOppRfcommListener: stopping Accept Thread
,07-07 20:27:08.904  3934  4269 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:27:08.904  3934  4269 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:27:08.907  3934  3934 D HeadsetService: Received stop request...Stopping profile...
07-07 20:27:08.909  3934  3934 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:08.909  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:08.909  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:08.909  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:08.910  3934  3934 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-07 20:27:08.910  3934  3934 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-07 20:27:08.910  3934  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:08.910  3934  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:08.911  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-07 20:27:08.911  3934  4197 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
07-07 20:27:08.912  3934  3934 D A2dpService: Received stop request...Stopping profile...
07-07 20:27:08.912  3934  4224 D A2dpStateMachine: Exit Disconnected: -1
,07-07 20:27:08.917  3934  3934 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:08.917  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:08.917  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:08.917  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:08.918  3934  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:27:08.918  3934  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:27:08.918  3934  4205 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:27:08.918  3934  4205 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-07 20:27:08.918  3934  4205 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-07 20:27:08.918  3934  4205 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-07 20:27:08.918  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-07 20:27:08.919  3887  3908 D BluetoothHeadset: Proxy object disconnected
,07-07 20:27:08.976  1617  4260 D BluetoothAdapter: stopLeScan(),
07-07 20:27:09.047   932   932 D BluetoothA2dp: Proxy object disconnected
,07-07 20:27:09.056   932  1401 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:09.056   932   932 D HeadsetProfile: Bluetooth service disconnected
07-07 20:27:09.057  1313  1442 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:09.057   792   792 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:09.058   792   792 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:09.058   792   792 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:09.058   792   792 D BluetoothA2dp: Proxy object disconnected
07-07 20:27:09.067  3934  3934 D HidService: Received stop request...Stopping profile...
07-07 20:27:09.067  3934  3934 D HidService: Stopping Bluetooth HidService
07-07 20:27:09.068  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:09.068  3769  3843 I jxcore-log: 
,07-07 20:27:09.068  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:09.068  3769  3843 I jxcore-log: 
07-07 20:27:09.075  3934  3934 D HealthService: Received stop request...Stopping profile...
07-07 20:27:09.077   932   932 D BluetoothInputDevice: Proxy object disconnected
07-07 20:27:09.077   932   932 D HidProfile: Bluetooth service disconnected
07-07 20:27:09.078  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-07 20:27:09.082  3934  3934 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:09.082  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:09.082  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:09.082  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:27:09.085  3934  3934 D PanService: Received stop request...Stopping profile...
07-07 20:27:09.086   932   932 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:27:09.086   932   932 D PanProfile: Bluetooth service disconnected
07-07 20:27:09.086  3934  3934 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:09.086  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:09.086  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:09.086  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:27:09.086  3934  3934 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-07 20:27:09.086  3934  3934 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:27:09.087  3934  3934 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:27:09.088  3934  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-07 20:27:09.088  3934  4197 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-07 20:27:09.088  3934  3934 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:27:09.089  3934  3934 D BluetoothMapService: Received stop request...Stopping profile...
07-07 20:27:09.089  3934  3934 D BluetoothMapService: stop()
07-07 20:27:09.089  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-07 20:27:09.089  3934  3934 D BluetoothMapAppObserver: deinitObservers()
07-07 20:27:09.089  3934  3934 D BluetoothMapAppObserver: removeReceiver()
07-07 20:27:09.090   932   932 D BluetoothMap: Proxy object disconnected
07-07 20:27:09.090   932   932 D MapProfile: Bluetooth service disconnected
07-07 20:27:09.090  3934  3934 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:09.090  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:09.090  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:09.090  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:09.091  3934  3934 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-07 20:27:09.091  3934  3934 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:27:09.091  3934  3934 D BluetoothMapService: MAP Service closeService in
07-07 20:27:09.091  3934  3934 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:09.091  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:09.091  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:09.091  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:09.091  3934  3934 D BluetoothMapService: cleanup()
07-07 20:27:09.091  3934  3934 D BluetoothMapService: MAP Service closeService in
07-07 20:27:09.092  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:27:09.092  3934  4193 D BluetoothAdapterProperties: Setting state to 15
07-07 20:27:09.092  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:27:09.093  3934  4193 I BluetoothAdapterState: Entering BleOnState
07-07 20:27:09.094  3887  3908 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:27:09.096   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:09.096  3887  3898 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:27:09.101   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-07 20:27:09.101  3887  3907 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:27:09.103  3887  3908 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:27:09.106   792   812 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:09.106   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:09.106   932  1401 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:27:09.107  1313  1326 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:09.107   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:09.107   932   944 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:09.107  3887  3898 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:09.108   932   950 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:09.108   932  1400 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:27:09.108  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-07 20:27:09.109   932  1401 D BluetoothPan: onBluetoothStateChange on: false
,07-07 20:27:09.110   932   944 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:27:09.110  3887  3907 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:09.111  3934  4193 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-07 20:27:09.111  3934  4193 D BluetoothAdapterProperties: Setting state to 16
07-07 20:27:09.111  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-07 20:27:09.112  3934  4193 D BluetoothAdapterProperties: onBleDisable
07-07 20:27:09.112  3934  4193 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:09.113  3934  4194 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:27:09.114  3934  4205 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-07 20:27:09.114  3934  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:09.114  3934  4197 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:27:09.121  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:09.122  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:09.123  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-07 20:27:09.127  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-07 20:27:09.127   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-07 20:27:09.128  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
07-07 20:27:09.129  3887  3887 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-07 20:27:09.130  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:27:09.131  3887  3887 D HeadsetProfile: Bluetooth service disconnected
07-07 20:27:09.132   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
,07-07 20:27:09.140   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-07 20:27:09.142  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:09.143   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-07 20:27:09.146   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-07 20:27:09.150   932  1144 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-07 20:27:09.152  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:09.156  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:27:09.158  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:27:09.158  1617  1617 E ActivityThread: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@17b6d70 that was originally bound here
07-07 20:27:09.158  1617  1617 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@17b6d70 that was originally bound here
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at rbx.run(:com.google.android.gms:94)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:09.158  1617  1617 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:09.163  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:09.164  1617  4220 E NearbyDiscovery: Failed to unbind NearbyDirect
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: java.lang.IllegalArgumentException: Service not registered: rbs@17b6d70
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at rbr.c(:com.google.android.gms:181)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at rca.run(:com.google.android.gms:1023)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:09.164  1617  4220 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:09.173  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:09.178  1617  4311 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:27:09.179  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:27:09.185  1617  4311 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-07 20:27:09.186  1617  4260 D BluetoothAdapter: startLeScan(): null
,07-07 20:27:09.187  1617  4260 E BluetoothAdapter: startLeScan: cannot get BluetoothLeScanner
,07-07 20:27:09.217  3934  4197 I bt_hci  : shut_down
,07-07 20:27:09.217  3934  4201 D bt_hwcfg: hw_epilog_process
,07-07 20:27:09.220  3934  4201 I bt_vendor: low_power_mode_cb
,07-07 20:27:09.249  3934  4201 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-07 20:27:09.249  3934  4201 I bt_vendor: epilog_cb
07-07 20:27:09.249  3934  4201 I bt_hci  : epilog_finished_callback
,07-07 20:27:09.251  3934  4197 I bt_hci_h4: hal_close
,07-07 20:27:09.251  3934  4197 I bt_userial_vendor: device fd = 49 close
,07-07 20:27:09.256  3934  4194 D bt_stack_manager: event_shut_down_stack finished.
,07-07 20:27:09.256  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-07 20:27:09.257  3934  4193 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-07 20:27:09.258  3934  3934 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:27:09.258  3934  3934 D BtGatt.GattService: Received stop request...Stopping profile...
,07-07 20:27:09.258  3934  3934 D BtGatt.GattService: stop()
07-07 20:27:09.258  3934  3934 D BtGatt.AdvertiseManager: advertise clients cleared
,07-07 20:27:09.259  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:09.259  3934  3934 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:09.259  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:09.259  3934  3934 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:27:09.259  3934  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-07 20:27:09.259  3934  4193 D BluetoothAdapterProperties: Setting state to 10
07-07 20:27:09.259  3934  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:27:09.260  3934  4193 I BluetoothAdapterState: Entering OffState
07-07 20:27:09.260   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-07 20:27:09.266  3934  3934 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-07 20:27:09.266  3934  3934 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:27:09.266  3934  3934 I BluetoothServiceJni: cleanupNative: return from cleanup
07-07 20:27:09.266  3934  4194 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-07 20:27:09.268  1617  1617 I BeaconBle: Scan : No clients left, canceling alarm.
07-07 20:27:09.269  3934  3934 I art     : System.exit called, status: 0
07-07 20:27:09.269  3934  3934 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:27:09.288  1617  4260 D BluetoothAdapter: stopLeScan()
,07-07 20:27:09.288  1617  4260 I BeaconBle: Scan : No clients left, canceling alarm.
,07-07 20:27:09.295   792   964 I ActivityManager: Process com.android.bluetooth (pid 3934) has died
,07-07 20:27:09.367  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:09.367  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:09.367  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:09.670  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:09.670  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:09.670  1617  4248 W MessageQueue: ,	at akll.a(:com.google.android.gms:93)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:09.670  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:09.975  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:09.975  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:09.975  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:10.280  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.280  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:10.280  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:10.586  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.586  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:10.586  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:10.588  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.588  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at akrj.run(:com.google.android.gms:98),
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at aksp.c(:com.google.android.gms:36)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at akrf.c(:com.google.android.gms:175)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:10.588  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:10.794  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.794  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at aklk.a(:com.google.android.gms:129)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:10.794  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:10.800  1617  4248 W MessageQueue: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.800  1617  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {4ea758a} sending message to a Handler on a dead thread
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
,07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at aksp.d(:com.google.android.gms:44)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akrh.a(:com.google.android.gms:65)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at aklk.a(:com.google.android.gms:130)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:10.800  1617  4248 W MessageQueue: ,	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:10.800  1617  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:27:11.853  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:27:11.853  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:27:11.861  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:27:11.861  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@819885b added. We now have 6 listener(s)
,07-07 20:27:11.861  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:11.864  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:11.864  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bccf8f8 added. We now have 7 listener(s)
07-07 20:27:11.865  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:11.868  3769  3841 I System.out: IsBluetoothEnabled
,07-07 20:27:11.884  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:11.916   792   812 I ActivityManager: Start proc 4325:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-07 20:27:11.979  4325  4325 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:27:11.980  4325  4325 D AdapterServiceConfig: Adding A2dpService
07-07 20:27:11.980  4325  4325 D AdapterServiceConfig: Adding HidService
07-07 20:27:11.980  4325  4325 D AdapterServiceConfig: Adding HealthService
07-07 20:27:11.980  4325  4325 D AdapterServiceConfig: Adding PanService
07-07 20:27:11.980  4325  4325 D AdapterServiceConfig: Adding GattService
,07-07 20:27:11.981  4325  4325 D AdapterServiceConfig: Adding BluetoothMapService
,07-07 20:27:11.995   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ac8a6a8:true
,07-07 20:27:11.996  4325  4325 D BluetoothAdapterState: make() - Creating AdapterState
,07-07 20:27:11.999  4325  4325 I bt_bluedroid: init
,07-07 20:27:11.999  4325  4353 I BluetoothAdapterState: Entering OffState
,07-07 20:27:12.002  4325  4354 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-07 20:27:12.002  4325  4354 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-07 20:27:12.002  4325  4354 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:27:12.002  4325  4354 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-07 20:27:12.003  4325  4325 I bt_bluedroid: get_profile_interface socket
,07-07 20:27:12.004  4325  4357 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-07 20:27:12.004  4325  4325 I bt_bluedroid: get_profile_interface sdp
,07-07 20:27:12.005  4325  4357 D BluetoothAdapterProperties: Name is: Nexus 5
,07-07 20:27:12.007  4325  4335 I bt_bluedroid: config_hci_snoop_log
,07-07 20:27:12.008   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-07 20:27:12.010  4325  4353 D BluetoothAdapterState: Current state: OFF, message: 0
07-07 20:27:12.010  4325  4353 D BluetoothAdapterProperties: Setting state to 14
07-07 20:27:12.011  4325  4353 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-07 20:27:12.012  4325  4353 D BluetoothBondStateMachine: make
,07-07 20:27:12.016  4325  4359 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-07 20:27:12.017  4325  4353 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:27:12.018  4325  4325 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-07 20:27:12.020  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:12.021  4325  4325 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:27:12.021  4325  4325 D BtGatt.GattService: Received start request. Starting profile...
07-07 20:27:12.021  4325  4325 D BtGatt.GattService: start()
,07-07 20:27:12.021  4325  4325 I bt_bluedroid: get_profile_interface gatt
07-07 20:27:12.022  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:12.022  4325  4325 D BtGatt.AdvertiseManager: advertise manager created
,07-07 20:27:12.027  4325  4325 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:12.027  4325  4325 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:12.027  4325  4325 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:27:12.027  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:12.027  4325  4353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:27:12.027  4325  4353 I bt_bluedroid: enable
07-07 20:27:12.027  4325  4354 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-07 20:27:12.028  4325  4354 I bt_hci  : start_up
,07-07 20:27:12.034  4325  4354 I bt_vendor: alloc value 0xb3a69631
,07-07 20:27:12.034  4325  4354 I bt_vendor: init
07-07 20:27:12.034  4325  4354 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-07 20:27:12.034  4325  4354 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-07 20:27:12.077  4325  4354 D bt_hci  : start_up starting async portion
,07-07 20:27:12.077  4325  4364 I bt_hci  : event_finish_startup
07-07 20:27:12.077  4325  4364 I bt_hci_h4: hal_open
07-07 20:27:12.077  4325  4364 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-07 20:27:12.080  4325  4364 I bt_userial_vendor: device fd = 49 open
,07-07 20:27:12.164  4325  4364 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:27:12.191  4325  4364 D bt_hwcfg: Chipset BCM4335C0
07-07 20:27:12.191  4325  4364 D bt_hwcfg: Target name = [BCM4335C0]
07-07 20:27:12.191  4325  4364 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-07 20:27:12.577  4325  4364 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:27:12.577  4325  4364 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:27:12.577  4325  4364 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:27:12.693  4325  4364 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:27:12.693  4325  4364 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-07 20:27:12.723  4325  4364 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:27:12.723  4325  4364 I bt_vendor: firmware callback
,07-07 20:27:12.723  4325  4364 I bt_hci  : firmware_config_callback
,07-07 20:27:12.729  4325  4375 I bt_btu  : btu_task pending for preload complete event
,07-07 20:27:12.729  4325  4375 I bt_btu_task: Bluetooth chip preload is complete
07-07 20:27:12.729  4325  4375 I bt_btu  : btu_task received preload complete event
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_HCI
07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_AVDT
07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_A2D
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_BNEP
07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_BTM
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_PAN
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_SDP
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_GATT
07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_SMP
07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-07 20:27:12.736  4325  4375 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:27:12.964  4325  4375 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e79b5
,07-07 20:27:12.964  4325  4375 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e79b5 
,07-07 20:27:13.097  4325  4357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:27:13.097  4325  4357 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-07 20:27:13.098  4325  4357 D BluetoothAdapterProperties: Name is: Nexus 5
07-07 20:27:13.099  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:13.099  4325  4357 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:13.100  4325  4357 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:27:13.100  4325  4357 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-07 20:27:13.101  4325  4357 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-07 20:27:13.101  4325  4357 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-07 20:27:13.101  4325  4357 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-07 20:27:13.101  4325  4357 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
,07-07 20:27:13.101  4325  4357 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-07 20:27:13.101  4325  4357 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-07 20:27:13.136  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-07 20:27:13.138  4325  4325 I BluetoothHidServiceJni: classInitNative: succeeds
07-07 20:27:13.138  4325  4325 D HidService: getHidService(): service is NULL
07-07 20:27:13.142  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-07 20:27:13.143  4325  4325 D HidService: getHidService(): service is NULL
07-07 20:27:13.145  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,07-07 20:27:13.147  4325  4325 D HidService: getHidService(): service is NULL
07-07 20:27:13.148  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-07 20:27:13.149  4325  4325 D HidService: getHidService(): service is NULL
07-07 20:27:13.151  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-07 20:27:13.152  4325  4325 D HidService: getHidService(): service is NULL
07-07 20:27:13.154  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-07 20:27:13.155  4325  4325 D HidService: getHidService(): service is NULL
07-07 20:27:13.157  4325  4357 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-07 20:27:13.158  4325  4325 D HidService: getHidService(): service is NULL
,07-07 20:27:13.158  4325  4357 D bt_hci  : do_postload posting postload work item
07-07 20:27:13.158  4325  4364 I bt_hci  : event_postload
,07-07 20:27:13.158  4325  4364 I bt_vendor: sco_config_cb
07-07 20:27:13.158  4325  4364 I bt_hci  : sco_config_callback postload finished.
07-07 20:27:13.159  4325  4364 I bt_vendor: low_power_mode_cb
07-07 20:27:13.160  4325  4357 D bt_bte_conf: Device ID record 1 : primary
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   vendorId            = 000f
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   product             = 1200
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   version             = 1436
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   clientExecutableURL = 
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   serviceDescription  = 
07-07 20:27:13.160  4325  4357 D bt_bte_conf:   documentationURL    = 
07-07 20:27:13.160  4325  4357 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-07 20:27:13.160  4325  4354 D bt_stack_manager: event_start_up_stack finished
07-07 20:27:13.160  4325  4353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-07 20:27:13.160  4325  4353 D BluetoothAdapterProperties: Setting state to 15
07-07 20:27:13.160  4325  4353 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-07 20:27:13.161  4325  4353 I BluetoothAdapterState: Entering BleOnState
07-07 20:27:13.163  4325  4353 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-07 20:27:13.163  4325  4353 D BluetoothAdapterProperties: Setting state to 11
07-07 20:27:13.163  4325  4353 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-07 20:27:13.171  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:13.178  4325  4325 D HeadsetService: Received start request. Starting profile...
07-07 20:27:13.179  4325  4325 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:27:13.179  4325  4325 D HeadsetStateMachine: make
07-07 20:27:13.182  4325  4353 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:13.186  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:13.187  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:13.194  4325  4325 D HeadsetStateMachine: max_hf_connections = 1
07-07 20:27:13.194  4325  4325 I bt_bluedroid: get_profile_interface handsfree
07-07 20:27:13.195  4325  4357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-07 20:27:13.195  4325  4357 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-07 20:27:13.209  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:13.213  4325  4325 D A2dpService: Received start request. Starting profile...
,07-07 20:27:13.213  4325  4325 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-07 20:27:13.214  4325  4325 I bt_bluedroid: get_profile_interface avrcp
07-07 20:27:13.217  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:13.217  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-07 20:27:13.224  4325  4325 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:27:13.224  4325  4325 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:27:13.224  4325  4325 D A2dpStateMachine: make
07-07 20:27:13.225  4325  4325 I bt_bluedroid: get_profile_interface a2dp
,07-07 20:27:13.226  4325  4357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-07 20:27:13.227  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:13.228  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-07 20:27:13.238  4325  4401 D A2dpStateMachine: Enter Disconnected: -2
07-07 20:27:13.239  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:13.239  4325  4325 D HidService: Received start request. Starting profile...
07-07 20:27:13.240  4325  4325 I bt_bluedroid: get_profile_interface hidhost
07-07 20:27:13.240  4325  4357 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c9099
07-07 20:27:13.240  4325  4325 D HidService: setHidService(): set to: null
07-07 20:27:13.240  4325  4357 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-07 20:27:13.240  4325  4325 I BluetoothHealthServiceJni: classInitNative: succeeds
07-07 20:27:13.241  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:13.242  4325  4325 D HealthService: Received start request. Starting profile...
,07-07 20:27:13.244  4325  4325 I bt_bluedroid: get_profile_interface health
,07-07 20:27:13.244  4325  4325 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-07 20:27:13.245  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
07-07 20:27:13.246  4325  4325 D PanService: Received start request. Starting profile...
07-07 20:27:13.246  4325  4325 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-07 20:27:13.246  4325  4325 I bt_bluedroid: get_profile_interface pan
07-07 20:27:13.247  4325  4357 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:27:13.249  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e5083
,07-07 20:27:13.249  4325  4325 D BluetoothMapService: Received start request. Starting profile...
07-07 20:27:13.249  4325  4325 D BluetoothMapService: start()
07-07 20:27:13.251  4325  4325 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-07 20:27:13.251  4325  4325 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-07 20:27:13.251  4325  4325 D BluetoothMapAppObserver: createReceiver()
07-07 20:27:13.252  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-07 20:27:13.252  4325  4325 D BluetoothMapAppObserver: initObservers()
07-07 20:27:13.252  4325  4325 D BluetoothMapAppObserver: getEnabledAccountItems()
07-07 20:27:13.252  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:13.266  4325  4325 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:13.266  4325  4325 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:13.266  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:13.266  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:13.266  4325  4386 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:13.267  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:13.268  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:13.268  4325  4353 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:27:13.268  4325  4353 D BluetoothAdapterProperties: ScanMode =  20
,07-07 20:27:13.268  4325  4353 D BluetoothAdapterProperties: State =  11
07-07 20:27:13.269  4325  4357 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:27:13.269  4325  4353 D BluetoothAdapterProperties: Setting state to 12
07-07 20:27:13.269  4325  4353 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:27:13.269  4325  4357 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-07 20:27:13.270  3887  3887 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-07 20:27:13.270  4325  4353 I BluetoothAdapterState: Entering OnState
07-07 20:27:13.270  3887  3898 D BluetoothPan: onBluetoothStateChange on: true
,07-07 20:27:13.273   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:13.274  3887  3908 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:13.275  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:13.278  3887  3907 D BluetoothPbap: onBluetoothStateChange: up=true
,07-07 20:27:13.278  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:13.280  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:27:13.280  3769  3843 I jxcore-log: 
07-07 20:27:13.284  4325  4325 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:27:13.284  4325  4325 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-07 20:27:13.289  4325  4325 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:13.290  3887  3908 D BluetoothMap: onBluetoothStateChange: up=true
,07-07 20:27:13.292  4325  4325 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:13.292   792   812 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-07 20:27:13.293   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:27:13.293  4325  4325 D ObexServerSockets: Succeed to create listening sockets 
,07-07 20:27:13.293  4325  4325 D ObexServerSockets0: startAccept()
,07-07 20:27:13.293  4325  4325 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:27:13.293   932  1401 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:27:13.294  4325  4325 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-07 20:27:13.295  4325  4325 D BluetoothSdpJni: SDP Create record success - handle: 0
07-07 20:27:13.295  1313  1326 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:13.296   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:13.296   932   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:27:13.297   792   792 D BluetoothA2dp: Proxy object connected
07-07 20:27:13.298  3887  3907 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:27:13.298  4325  4413 D ObexServerSockets0: Accepting socket connection...
07-07 20:27:13.300   932  1400 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:27:13.300  4325  4412 D ObexServerSockets0: Accepting socket connection...
,07-07 20:27:13.301   932  1401 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-07 20:27:13.303   932   932 D BluetoothA2dp: Proxy object connected
,07-07 20:27:13.307   932  1400 D BluetoothPan: onBluetoothStateChange on: true
,07-07 20:27:13.307   932   932 D BluetoothInputDevice: Proxy object connected
07-07 20:27:13.307   932   932 D HidProfile: Bluetooth service connected
07-07 20:27:13.309   932   950 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:27:13.311  3887  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:27:13.313   792   792 I Telecom : BluetoothPhoneService: queryPhoneState
,07-07 20:27:13.314  4325  4325 D BluetoothMapService: onReceive
,07-07 20:27:13.314  4325  4325 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-07 20:27:13.314  4325  4325 D BluetoothMapService: STATE_ON
07-07 20:27:13.317   932   932 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:27:13.317   932   932 D PanProfile: Bluetooth service connected
,07-07 20:27:13.318   932   932 D BluetoothMap: Proxy object connected
,07-07 20:27:13.318   932   932 D MapProfile: Bluetooth service connected
07-07 20:27:13.318   932   932 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.327  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.327  3887  3887 W BluetoothMap: Proxy not attached to service
07-07 20:27:13.327  3887  3887 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
07-07 20:27:13.327  3887  3887 W BluetoothMap: Proxy not attached to service
07-07 20:27:13.327  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.335  4325  4325 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-07 20:27:13.335  4325  4325 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:27:13.337   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.340   932  1144 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-07 20:27:13.342  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.342  3887  3887 W BluetoothMap: Proxy not attached to service
07-07 20:27:13.342  3887  3887 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
07-07 20:27:13.342  3887  3887 W BluetoothMap: Proxy not attached to service
07-07 20:27:13.342  3887  3887 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.344  1617  4260 D BluetoothAdapter: startLeScan(): null
,07-07 20:27:13.345  3887  3887 D BluetoothPan: BluetoothPAN Proxy object connected
,07-07 20:27:13.345  1617  4260 D BluetoothAdapter: STATE_ON
07-07 20:27:13.345   932  1144 D MapProfile: getConnectionStatus: status is: 0
07-07 20:27:13.346  3887  3887 D PanProfile: Bluetooth service connected
,07-07 20:27:13.346  3887  3887 D BluetoothInputDevice: Proxy object connected
07-07 20:27:13.346  3887  3887 D HidProfile: Bluetooth service connected
07-07 20:27:13.347  3949  3969 W Babel   : bcq TOOK TOO LONG! (15032ms > 10000ms)
07-07 20:27:13.348  4325  4377 D BtGatt.GattService: registerClient() - UUID=c2a26421-f2cc-4dcd-8245-43c2495c5fe5
,07-07 20:27:13.348  3949  3967 W Babel   : bcq TOOK TOO LONG! (15037ms > 10000ms)
07-07 20:27:13.349  4325  4357 D BtGatt.GattService: onClientRegistered() - UUID=c2a26421-f2cc-4dcd-8245-43c2495c5fe5, clientIf=5
07-07 20:27:13.349  3887  3887 D BluetoothMap: Proxy object connected
07-07 20:27:13.349  3887  3887 D MapProfile: Bluetooth service connected
07-07 20:27:13.349  3887  3887 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.349  1617  1662 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:27:13.350  4325  4377 D BtGatt.GattService: start scan with filters
07-07 20:27:13.350  3887  3887 D BluetoothA2dp: Proxy object connected
,07-07 20:27:13.352  4325  4363 D BtGatt.ScanManager: handling starting scan
,07-07 20:27:13.355  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-07 20:27:13.355  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-07 20:27:13.355  4325  4363 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-07 20:27:13.355  4325  4357 D BtGatt.GattService: onScanParamSetupCompleted : 0
07-07 20:27:13.359   792   803 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-07 20:27:13.363  3949  3949 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-07 20:27:13.363  3949  3949 W Babel   : BAM#gBA: invalid account id: -1
07-07 20:27:13.363  3949  3949 W Babel   : BAM#gBA: invalid account id: -1
07-07 20:27:13.363  3949  3949 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
07-07 20:27:13.364  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:13.366  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:27:13.369   792   803 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-07 20:27:13.370  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:27:13.377  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:13.381  3887  3898 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.382   932  1400 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.382  1313  1327 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.383   792   792 D BluetoothHeadset: Proxy object connected
07-07 20:27:13.383   792   792 D BluetoothHeadset: Proxy object connected
07-07 20:27:13.383   792   792 D BluetoothHeadset: Proxy object connected
07-07 20:27:13.385   932   932 D BluetoothPbap: Proxy object connected
,07-07 20:27:13.385   932   932 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:13.385   932   932 D HeadsetProfile: Bluetooth service connected
07-07 20:27:13.385  4325  4419 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:13.391  3887  3887 D BluetoothPbap: Proxy object connected
,07-07 20:27:13.391  3887  3887 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:13.391  3887  3887 D HeadsetProfile: Bluetooth service connected
07-07 20:27:13.393   792   812 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.396  1313  1441 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.396   792   812 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.397   932  1400 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.402   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.403   932  1144 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-07 20:27:13.404   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.406   932   932 D HeadsetProfile: Bluetooth service connected
,07-07 20:27:13.407  1617  1617 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:13.412  1617  4423 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:27:13.412  3887  3907 D BluetoothHeadset: Proxy object connected
,07-07 20:27:13.412  3887  3887 D HeadsetProfile: Bluetooth service connected
07-07 20:27:13.413  1617  1617 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:27:13.425   792   802 I ActivityManager: Start proc 4427:com.google.android.talk:matchstick/u0a51 for broadcast com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,07-07 20:27:13.428  4325  4426 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:13.432  4325  4426 I BtOppRfcommListener: Accept thread started.
,07-07 20:27:13.435  1617  4423 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-07 20:27:13.449  3949  3977 W Babel   : bcq TOOK TOO LONG! (15039ms > 10000ms)
,07-07 20:27:13.475   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.477   932  1144 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-07 20:27:13.478   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.500   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.504   932  1144 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-07 20:27:13.508   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.527   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.529   932  1144 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-07 20:27:13.530   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.546   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.547   932  1144 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-07 20:27:13.549   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.566   932  1144 D BluetoothMap: getConnectedDevices()
,07-07 20:27:13.568   932  1144 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-07 20:27:13.570   932  1144 D MapProfile: getConnectionStatus: status is: 0
,07-07 20:27:13.824  4427  4445 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService } isPeriodic:false
,07-07 20:27:13.854  4427  4445 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-07 20:27:13.867  4427  4445 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-07 20:27:13.867  4427  4445 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-07 20:27:13.870  4427  4445 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-07 20:27:13.893  4427  4445 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-07 20:27:13.894  4427  4445 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:13.919  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:13.920  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:13.921  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:13.921  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f1c1d1 added. We now have 8 listener(s)
07-07 20:27:13.921  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:13.922  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:27:13.922  3769  3843 I jxcore-log: 
07-07 20:27:13.923   792   964 D WifiService: setWifiEnabled: false pid=3769, uid=10026
07-07 20:27:13.923   792   964 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:27:13.925  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:13.925   792  1214 D WifiService: setWifiEnabled: true pid=3769, uid=10026
07-07 20:27:13.925   792  1214 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:27:13.926   194   667 D SoftapController: Softap fwReload - Ok
07-07 20:27:13.928   194   667 D CommandListener: Setting iface cfg
07-07 20:27:13.928   194   667 D CommandListener: Trying to bring down wlan0
,07-07 20:27:13.928   194   667 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:27:13.929   792   895 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:27:14.754   792   895 D wifi    : set interface wlan0 flags (UP)
,07-07 20:27:14.754   792   895 I WifiHAL : Initializing wifi
,07-07 20:27:14.754   792   895 I WifiHAL : Creating socket
,07-07 20:27:14.755   792   895 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-07 20:27:14.756   792   895 D wifi    : Did set static halHandle = 0x93165f60
07-07 20:27:14.756   792   895 D wifi    : halHandle = 0x93165f60, mVM = 0xb4d7c000, mCls = 0x201b32
,07-07 20:27:14.756   792   895 D wifi    : array field set
,07-07 20:27:14.756   792   895 I WifiNative-HAL: interface[0] = p2p0
,07-07 20:27:14.756   792   895 I WifiNative-HAL: interface[1] = wlan0
,07-07 20:27:14.756   792   812 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-07 20:27:14.758   792   895 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-07 20:27:14.758   792   895 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-07 20:27:14.762  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:14.764   792  4460 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1827250336
07-07 20:27:14.764   792  4460 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x201b32, env = 0x96f45240
,07-07 20:27:14.795  4461  4461 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-07 20:27:14.815  4461  4461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:27:14.826  4461  4461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:27:14.861  1617  4260 D BluetoothAdapter: stopLeScan()
,07-07 20:27:14.861  1617  4260 D BluetoothAdapter: STATE_ON
,07-07 20:27:14.866  4325  4335 D BtGatt.GattService: stopScan() - queue size =1
,07-07 20:27:14.867  4325  4363 D BtGatt.ScanManager: stop scan
,07-07 20:27:14.867  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-07 20:27:14.867  4325  4400 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:27:14.867  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-07 20:27:14.868  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-07 20:27:15.044  1617  4260 D BluetoothAdapter: startLeScan(): null
,07-07 20:27:15.048  1617  4260 D BluetoothAdapter: STATE_ON
,07-07 20:27:15.051  4325  4400 D BtGatt.GattService: registerClient() - UUID=d53be390-e46b-4291-b342-df7178ab75e5
,07-07 20:27:15.052  4325  4357 D BtGatt.GattService: onClientRegistered() - UUID=d53be390-e46b-4291-b342-df7178ab75e5, clientIf=5
07-07 20:27:15.053  1617  1662 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:27:15.053  4325  4411 D BtGatt.GattService: start scan with filters
,07-07 20:27:15.058  4325  4363 D BtGatt.ScanManager: handling starting scan
,07-07 20:27:15.061  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-07 20:27:15.061  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-07 20:27:15.061  4325  4363 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-07 20:27:15.062  4325  4357 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:15.808  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:15.819  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:15.820  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:15.820  3769  3843 I jxcore-log: 
07-07 20:27:15.822   792   895 D WifiConfigStore: Loading config and enabling all networks 
07-07 20:27:15.826   792   895 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:27:15.826   792   895 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-07 20:27:15.827   792   895 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:27:15.827   792   895 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-07 20:27:15.827   792   895 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-07 20:27:15.830   792   895 D WifiNative-HAL: Setting external_sim to 1
07-07 20:27:15.830   792   895 D wifi    : setting dfs flag to true, 0x989706e8
,07-07 20:27:15.830   792   895 D WifiStateMachine: Setting OUI to DA-A1-19
07-07 20:27:15.830   792   895 D wifi    : setting scan oui 0x989706e8
,07-07 20:27:15.830   792   895 D WifiHAL : Sending mac address OUI
,07-07 20:27:15.839   792   895 E native  : do suspend false
07-07 20:27:15.846   792   895 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-07 20:27:15.848   792   792 D RttService: SCAN_AVAILABLE : 3
07-07 20:27:15.848   792   908 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-07 20:27:15.852   792   895 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:27:15.853   194   667 D CommandListener: Setting iface cfg
07-07 20:27:15.853   194   667 D CommandListener: Trying to bring up p2p0
,07-07 20:27:15.853   792   894 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-07 20:27:15.877   792   894 D WifiNative-HAL: p2pGetDeviceAddress
07-07 20:27:15.877   792   894 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:15.932  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:15.933  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:15.934  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-07 20:27:15.935  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-07 20:27:15.936  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:15.936  3769  3843 I jxcore-log: 
,07-07 20:27:15.937  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@642b19a Bundle[{}]
,07-07 20:27:15.937  3769  3841 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:27:15.937  3769  3841 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-07 20:27:15.938  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-07 20:27:15.938  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-07 20:27:15.938  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-07 20:27:15.939  3769  3841 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-07 20:27:15.942  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-07 20:27:15.942  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-07 20:27:15.942  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-07 20:27:15.942  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-07 20:27:15.942  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-07 20:27:15.942  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:15.946  3769  3841 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 345)
07-07 20:27:15.946  3769  3841 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 345)
07-07 20:27:15.946  3769  3841 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 345)
07-07 20:27:15.946  3769  3841 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 345)
,07-07 20:27:15.948  3769  3841 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 351)
,07-07 20:27:15.948  3769  3841 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 351)
07-07 20:27:15.948  3769  3841 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 351)
07-07 20:27:15.948  3769  3841 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 352)
,07-07 20:27:15.949  3769  3841 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 354)
,07-07 20:27:15.950  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.950  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a36436 added. We now have 2 listener(s)
07-07 20:27:15.951  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:15.951  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:15.951  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:15.951  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.951  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6de4f37 added. We now have 9 listener(s)
07-07 20:27:15.951  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:15.953  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-07 20:27:15.953  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-07 20:27:15.954  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:15.956  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:15.957  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:15.957  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:15.957  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.958  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7faa0d added. We now have 3 listener(s)
,07-07 20:27:15.958  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:15.959  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-07 20:27:15.959  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:15.959  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:15.959  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.959  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2398dc2 added. We now have 10 listener(s)
,07-07 20:27:15.959  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:15.959  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:15.959  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:15.959  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:15.959  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:15.959  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:27:15.959  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.959  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:15.959  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:15.959  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a36436 removed from the list
07-07 20:27:15.959  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:15.960  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6de4f37 removed from the list
,07-07 20:27:15.960  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:15.960  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.960  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:15.960  3769  3843 I jxcore-log: 
,07-07 20:27:15.960  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.960  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.960  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:15.960  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6de4f37 not in the list
07-07 20:27:15.960  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.960  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.960  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:15.960  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2398dc2 removed from the list
,07-07 20:27:15.960  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:15.960  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.960  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.960  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-07 20:27:15.960  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7faa0d removed from the list
07-07 20:27:15.960  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.961  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bea7d3 added. We now have 2 listener(s)
07-07 20:27:15.962  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:15.962  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:27:15.962  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:15.962  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.962  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@581ef10 added. We now have 9 listener(s)
07-07 20:27:15.962  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:15.963  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-07 20:27:15.963  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:27:15.964  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:15.966  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:15.967  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:15.967  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:15.967  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.967  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@816c40e added. We now have 3 listener(s)
,07-07 20:27:15.968  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:15.969  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:15.969  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:15.969  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:27:15.969  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:15.969  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.969  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@241ee2f added. We now have 10 listener(s)
07-07 20:27:15.969  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:15.969  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:15.969  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:27:15.969  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:15.969  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:15.970  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:15.970  3769  3843 I jxcore-log: 
07-07 20:27:15.972  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-07 20:27:15.972  3769  3841 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:27:15.972  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:15.972  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:27:15.973  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:27:15.973  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:27:15.973  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:15.973  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:15.973  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.973  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:27:15.973  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:15.973  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bea7d3 removed from the list
07-07 20:27:15.974  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:15.974  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@581ef10 removed from the list
07-07 20:27:15.974  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:27:15.974  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:15.974  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.974  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:27:15.974  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.974  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:15.974  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:15.974  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@581ef10 not in the list
07-07 20:27:15.974  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:27:15.974  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.974  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:15.974  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@241ee2f removed from the list
07-07 20:27:15.974  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:15.974  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.974  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.974  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-07 20:27:15.974  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@816c40e removed from the list
07-07 20:27:15.975  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.975  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed0dc5 added. We now have 2 listener(s)
07-07 20:27:15.976  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-07 20:27:15.976  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:15.976  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:15.976  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.976  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77f131a added. We now have 9 listener(s)
07-07 20:27:15.976  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:15.977  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:27:15.977  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:27:15.979  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:15.981  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:15.982  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:15.982  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:15.982  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.982  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec9028 added. We now have 3 listener(s)
07-07 20:27:15.983  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:15.983  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:27:15.983  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:15.983  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:27:15.983  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@995c141 added. We now have 10 listener(s)
,07-07 20:27:15.983  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:15.983  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:15.984  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:15.984  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-07 20:27:15.984  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:15.984  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:15.984  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:15.985  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:15.986  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:15.986  3769  3843 I jxcore-log: 
,07-07 20:27:15.987  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-07 20:27:15.987  3769  3841 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:27:15.987  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:15.987  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:15.987  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:27:15.987  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:15.987  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.987  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:27:15.987  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:15.987  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed0dc5 removed from the list
,07-07 20:27:15.987  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:15.987  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77f131a removed from the list
07-07 20:27:15.987  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:15.987  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:15.988  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:27:15.988  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:27:15.988  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.988  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:15.988  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:15.988  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77f131a not in the list
,07-07 20:27:15.988  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:27:15.988  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.988  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:15.988  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@995c141 removed from the list
07-07 20:27:15.988  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:27:15.988  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:15.988  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:15.988  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:15.988  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec9028 removed from the list
07-07 20:27:15.989  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.989  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ab7427 added. We now have 2 listener(s)
,07-07 20:27:15.990  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:15.990  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:15.990  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:27:15.990  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.990  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48e86d4 added. We now have 9 listener(s)
07-07 20:27:15.990  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:15.991  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:27:15.991  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-07 20:27:15.992  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:15.994  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:15.995  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:15.995  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:15.995  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:15.995  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@994eb72 added. We now have 3 listener(s)
07-07 20:27:15.997  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:15.997  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:27:15.997  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:15.997  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:15.997  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@512bc3 added. We now have 10 listener(s)
07-07 20:27:15.997  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:15.997  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:15.997  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:15.997  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:27:15.997  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:15.997  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:15.998  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:15.999  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:15.999  3769  3843 I jxcore-log: 
,07-07 20:27:16.001  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-07 20:27:16.001  3769  3841 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-07 20:27:16.002  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:27:16.002  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.002  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.002  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.002  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.002  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:27:16.002  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:16.002  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ab7427 removed from the list
,07-07 20:27:16.002  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:16.002  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48e86d4 removed from the list
,07-07 20:27:16.002  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.002  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.002  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.002  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-07 20:27:16.003  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.003  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.003  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.003  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48e86d4 not in the list
07-07 20:27:16.003  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-07 20:27:16.003  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.003  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.003  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@512bc3 removed from the list
07-07 20:27:16.003  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.003  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:27:16.003  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.003  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:16.003  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@994eb72 removed from the list
07-07 20:27:16.003  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:16.003  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e05779 added. We now have 2 listener(s)
,07-07 20:27:16.004  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:16.004  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:16.005  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:16.005  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:16.005  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac24cbe added. We now have 9 listener(s)
07-07 20:27:16.005  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:16.006  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:27:16.006  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:27:16.007  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:16.009  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:16.010  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:16.010  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:16.010  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:16.010  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf3dc6c added. We now have 3 listener(s)
07-07 20:27:16.011  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-07 20:27:16.012  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:16.012  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:16.012  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:16.012  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b85f235 added. We now have 10 listener(s)
07-07 20:27:16.012  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:16.012  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:16.012  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:27:16.012  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.012  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.012  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.012  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:27:16.012  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.012  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:16.012  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e05779 removed from the list
07-07 20:27:16.012  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:16.012  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac24cbe removed from the list
07-07 20:27:16.012  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.012  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.013  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:16.013  3769  3843 I jxcore-log: 
07-07 20:27:16.012  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:27:16.013  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.013  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.013  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.014  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac24cbe not in the list
,07-07 20:27:16.014  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.014  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.014  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.014  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b85f235 removed from the list
07-07 20:27:16.014  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.014  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.014  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.014  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:16.014  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf3dc6c removed from the list
,07-07 20:27:16.014  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:27:16.014  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca added. We now have 2 listener(s)
07-07 20:27:16.015  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-07 20:27:16.015  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:16.015  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:27:16.015  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:16.015  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b added. We now have 9 listener(s)
07-07 20:27:16.015  3769  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:16.017  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:27:16.017  3769  3841 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-07 20:27:16.018  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:16.020  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:16.021  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:16.021  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:16.021  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:27:16.021  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:27:16.021  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:27:16.021  3769  3841 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-07 20:27:16.022  3769  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:27:16.022  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:27:16.022  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:27:16.022  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-07 20:27:16.022  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.022  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.022  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.022  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.022  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:27:16.022  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.022  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:16.022  3769  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca removed from the list
07-07 20:27:16.022  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:16.022  3769  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b removed from the list
07-07 20:27:16.023  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.023  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:27:16.023  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:27:16.023  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.023  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.023  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.023  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
,07-07 20:27:16.024  3769  3841 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-07 20:27:16.024  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.024  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.024  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:27:16.024  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.024  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.024  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.024  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.024  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.024  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.025  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.025  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.025  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.025  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.025  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.025  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.025  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.025  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.026  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:16.026  3769  3843 I jxcore-log: 
07-07 20:27:16.026  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.,ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:27:16.026  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:27:16.027  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.027  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.027  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.027  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.027  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.027  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.027  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.027  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.027  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.027  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.027  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.027  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.027  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.027  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.027  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.027  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.027  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.027  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.027  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.027  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.028  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.028  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.028  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.028  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.028  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.028  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.028  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.028  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.028  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.028  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.028  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.028  3769  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:27:16.029  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:16.031  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:16.032  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:16.032  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:16.032  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:16.032  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:27:16.032  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.032  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:16.033  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.034  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.035  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:27:16.036  3769  3841 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:27:16.036  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:16.036  3769  3843 I jxcore-log: 
07-07 20:27:16.036  3769  3841 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:27:16.037  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.037  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.037  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.037  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.037  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.037  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:27:16.037  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.037  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.037  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.037  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.037  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.037  3769  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:27:16.039  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:16.041  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:16.042  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:16.042  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:16.042  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:16.042  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:27:16.044  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.044  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:27:16.044  3769  3841 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:27:16.044  3769  3841 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:27:16.046  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.046  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.046  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.046  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.046  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.046  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.046  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:27:16.046  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.046  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.046  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.046  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.046  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.047  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:27:16.047  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:16.047  3769  3843 I jxcore-log: 
07-07 20:27:16.047  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.047  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.047  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.048  3769  3841 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:27:16.049  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:16.051  3769  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:16.052  3769  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:16.053  3769  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:16.053  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:27:16.053  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:27:16.053  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.053  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:16.054  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.055  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:16.056  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:27:16.056  3769  3843 I jxcore-log: 
07-07 20:27:16.056  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-07 20:27:16.056  3769  3841 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:27:16.056  3769  3841 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:27:16.056  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.056  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.056  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.057  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.057  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.057  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.057  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.057  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.057  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:27:16.057  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.057  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.057  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.057  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.057  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.057  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:27:16.058  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.058  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.058  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.058  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.058  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.058  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.058  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.059  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.059  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.059  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.059  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.059  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.059  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.059  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.059  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.059  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.059  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.059  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.059  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.059  3769  3841 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-07 20:27:16.060  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.060  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.060  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.060  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.060  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.060  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.060  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.060  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.060  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.060  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.060  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.060  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.060  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.060  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.060  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.060  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.061  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:27:16.061  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.061  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.061  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.061  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.061  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.061  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.061  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.061  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.061  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.061  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.061  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.061  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.061  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.062  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.062  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.062  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.062  3769  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-07 20:27:16.062  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.062  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.062  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.062  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.062  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.062  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.062  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.062  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.062  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.062  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.062  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.063  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.063  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.063  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.063  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.063  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.063  3769  3841 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-07 20:27:16.063  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.063  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.063  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.063  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.063  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.063  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.063  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.063  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.063  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.064  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.064  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.064  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.064  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.064  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.064  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.064  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.064  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:27:16.064  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:27:16.064  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:27:16.064  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:27:16.065  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:27:16.065  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:27:16.065  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.065  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.065  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.065  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.065  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.065  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.065  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.065  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.065  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.065  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.065  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.065  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.065  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.065  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.065  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.066  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.066  3769  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:27:16.067  3769  3841 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:27:16.067  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:27:16.068  3769  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:27:16.068  3769  3841 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:27:16.068  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:27:16.069  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:27:16.069  3769  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-07 20:27:16.069  3769  3841 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-07 20:27:16.070  3769  3841 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-07 20:27:16.070  3769  3841 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:27:16.070  3769  3841 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-07 20:27:16.070  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.070  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.070  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.071  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.071  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.071  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.071  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.071  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.071  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.071  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.071  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.071  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.071  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.071  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.071  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.071  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.073  3769  3841 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-07 20:27:16.074  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.074  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.074  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.074  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.074  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.074  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.074  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.074  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.074  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.074  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.074  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.074  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.074  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.074  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.074  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.074  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.075  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.075  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.075  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.075  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.075  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.075  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.075  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.075  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.075  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.075  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.075  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.075  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.075  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.075  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.076  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.076  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.076  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.076  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.076  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.076  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.076  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.076  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.076  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.076  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.076  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.076  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.076  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.076  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.076  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.076  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.076  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.077  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.077  3769  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-07 20:27:16.078  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.078  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.078  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.078  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.078  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.078  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:27:16.078  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.078  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.078  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.078  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.078  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.078  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.078  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.078  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.078  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.078  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.078  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-07 20:27:16.078  3769  3843 I jxcore-log: 
07-07 20:27:16.079  3769  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-07 20:27:16.079  3769  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-07 20:27:16.079  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:27:16.079  3769  3841 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-07 20:27:16.079  3769  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:27:16.079  3769  3841 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-07 20:27:16.079  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:27:16.079  3769  3841 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-07 20:27:16.079  3769  3841 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:27:16.079  3769  3841 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:27:16.079  3769  3841 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:27:16.079  3769  3841 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-07 20:27:16.080  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.080  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.080  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.080  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.080  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.080  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.080  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.080  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.080  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.080  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.080  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.080  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.080  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.080  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.080  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.081  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.081  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.081  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.081  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.081  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.081  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.081  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.081  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.081  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.081  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.081  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.081  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.081  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.081  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.081  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.082  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.082  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.082  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.082  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.082  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.082  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.082  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.082  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.082  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.082  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.082  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.082  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.082  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.082  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.082  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.082  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.082  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.083  3769  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-07 20:27:16.083  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.084  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-07 20:27:16.085  3769  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-07 20:27:16.085  3769  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-07 20:27:16.085  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-07 20:27:16.085  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-07 20:27:16.086  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.086  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:27:16.086  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-07 20:27:16.086  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-07 20:27:16.086  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-07 20:27:16.086  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.086  3769  4489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-07 20:27:16.086  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.086  3769  4489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-07 20:27:16.086  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.086  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:27:16.086  3769  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:27:16.086  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:27:16.086  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-07 20:27:16.086  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-07 20:27:16.086  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.086  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.086  3769  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:27:16.087  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:27:16.087  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.087  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:16.088  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.088  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.088  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.088  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.088  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.088  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.088  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.088  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.088  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.088  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.088  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.088  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.088  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.090  3769  3769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:27:16.090  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-07 20:27:16.090  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:27:16.090  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.090  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:27:16.090  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:16.090  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:27:16.093  3769  3769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:27:16.093  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.093  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:27:16.094  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.094  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:27:16.094  3769  3843 I jxcore-log: 
07-07 20:27:16.094  3769  3841 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-07 20:27:16.095  3769  3841 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:27:16.095  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:27:16.095  3769  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:27:16.095  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.095  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.095  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.095  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.095  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.095  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.095  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.095  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.095  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.095  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.095  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.095  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:27:16.095  3769  3841 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:27:16.096  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.096  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.096  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.098  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.098  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.098  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.099  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.099  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.099  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.099  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.099  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.099  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.099  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.099  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.099  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.099  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.099  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.099  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.099  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.099  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.099  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.100  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.100  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.100  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.100  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.100  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.100  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.100  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.100  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.100  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.100  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.100  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.100  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.100  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.100  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.101  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.101  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.101  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.101  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.101  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.101  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.101  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.101  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.101  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.101  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.101  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.101  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.101  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.101  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.101  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.101  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.102  3769  3841 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-07 20:27:16.102  3769  3841 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-07 20:27:16.102  3769  3769 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-07 20:27:16.102  3769  3841 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-07 20:27:16.103  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.103  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.103  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.103  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.103  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.103  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.103  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.103  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.103  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-07 20:27:16.103  3769  3843 I jxcore-log: 
07-07 20:27:16.103  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.103  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.103  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.103  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.103  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.103  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.104  3769  3841 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-07 20:27:16.104  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.104  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.104  3769  3841 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:27:16.104  3769  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_ST,ARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:27:16.104  3769  3841 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:27:16.104  3769  3841 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:16.104  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.104  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.104  3769  3841 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d276ca not in the list
07-07 20:27:16.104  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:27:16.104  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.104  3769  3841 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:16.104  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.104  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:16.104  3769  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:16.104  3769  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:27:16.104  3769  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:16.104  3769  3841 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a503b not in the list
07-07 20:27:16.105  3769  3841 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-07 20:27:16.105  3769  3841 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
,07-07 20:27:16.105  3769  3841 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-07 20:27:16.105  3769  3841 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-07 20:27:16.105  3769  3841 E com.test.thalitest.ThaliTestRunner: Total duration: 19306 ms
07-07 20:27:16.105  3769  3841 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 19381ms. Plugin should use CordovaInterface.getThreadPool().
,07-07 20:27:16.366  1617  4260 D BluetoothAdapter: stopLeScan()
,07-07 20:27:16.368  1617  4260 D BluetoothAdapter: STATE_ON
,07-07 20:27:16.370  4325  4400 D BtGatt.GattService: stopScan() - queue size =1
,07-07 20:27:16.371  4325  4363 D BtGatt.ScanManager: stop scan
,07-07 20:27:16.371  4325  4377 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-07 20:27:16.371  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-07 20:27:16.371  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-07 20:27:16.371  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-07 20:27:16.372  1617  4260 I BeaconBle: Scan : No clients left, canceling alarm.
,07-07 20:27:16.671   792   895 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,07-07 20:27:17.513   792   895 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-07 20:27:17.516   792   895 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-07 20:27:17.516   792   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:27:17.525   792   895 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-07 20:27:17.556   792   895 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-07 20:27:17.557  4461  4461 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-07 20:27:17.638  4461  4461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-07 20:27:17.669  4461  4461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-07 20:27:17.669  4461  4461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-07 20:27:17.670   792   895 D WifiConfigStore: Retrieve network priorities after PNO.
07-07 20:27:17.679   792   895 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-07 20:27:17.679   792   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:27:17.680   792   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-07 20:27:17.690   792   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:27:17.697   194   667 D CommandListener: Setting iface cfg
,07-07 20:27:17.701   792   895 D WifiStateMachine: Start Dhcp Watchdog 2
,07-07 20:27:17.709   792   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:27:17.709   792   897 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,07-07 20:27:17.711   792   895 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-07 20:27:17.719   792  4503 D DhcpClient: Receive thread started
,07-07 20:27:17.788   792   895 E native  : do suspend false
,07-07 20:27:17.798   792  4502 D DhcpClient: Broadcasting DHCPDISCOVER
,07-07 20:27:17.814   792  4503 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172710, domain null
,07-07 20:27:17.815   792  4502 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172710 seconds
,07-07 20:27:17.817   792  4502 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-07 20:27:17.826   792  4503 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-07 20:27:17.826   792  4502 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-07 20:27:17.829   194   667 D CommandListener: Setting iface cfg
07-07 20:27:17.846   792   895 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
07-07 20:27:17.854   792  4502 D DhcpClient: Scheduling renewal in 86399s
,07-07 20:27:17.865   792   895 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-07 20:27:17.867   792   895 D WifiConfigStore: No blacklist allowed without epno enabled
,07-07 20:27:17.869   792   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-07 20:27:17.872   792   897 D ConnectivityService: Adding iface wlan0 to network 101
,07-07 20:27:17.919   792   895 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-07 20:27:17.960   792   897 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-07 20:27:17.960   792   897 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-07 20:27:17.963   792   897 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-07 20:27:17.972   792   897 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-07 20:27:17.974   792   897 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-07 20:27:17.992   792   897 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:27:18.006   792   897 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-07 20:27:18.006   792   897 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-07 20:27:18.006   792   897 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-07 20:27:18.006   792   895 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-07 20:27:18.006   792   897 D ConnectivityService:    accepting network in place of null
,07-07 20:27:18.007   792   895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:27:18.010   792   897 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -65]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-07 20:27:18.020   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131982, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:27:18.045   194   667 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:27:18.070   194   667 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:27:18.072   792   897 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-07 20:27:18.072   792   897 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:27:18.072   792   897 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-07 20:27:18.073   792   812 D Tethering: MasterInitialState.processMessage what=3
,07-07 20:27:18.082  3769  3769 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-07 20:27:18.084  1381  1381 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-07 20:27:18.088  4000  4000 E SetupWizard: tickleCheckinService called after completing user setup
,07-07 20:27:18.088  2763  2763 W ChromiumNet: type=1400 audit(0.0:11): avc: denied { ioctl } for path="socket:[17344]" dev="sockfs" ino=17344 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:18.100  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:18.105  1603  1603 V Herrevad: NQAS connected
,07-07 20:27:18.109  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:27:18.111  3769  3843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:27:18.111  3769  3843 I jxcore-log: 
,07-07 20:27:18.125   792  4500 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.201.238,2a00:1450:4001:815::200e
,07-07 20:27:18.163  1603  1647 W Herrevad: Invalid mccmnc 
,07-07 20:27:18.164  1603  1647 W Herrevad: Invalid mccmnc 
,07-07 20:27:18.174  1603  1603 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-07 20:27:18.179  1603  3000 I iu.UploadsManager: num queued entries: 0
,07-07 20:27:18.179  1603  3000 I iu.UploadsManager: num updated entries: 0
,07-07 20:27:18.180  1603  3000 I iu.SyncManager: NEXT; no task
,07-07 20:27:18.207   792  4500 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jul 2016 18:27:18 GMT], X-Android-Received-Millis=[1467916038207], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467916038164]}
,07-07 20:27:18.207   792   897 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-07 20:27:18.208   792   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,07-07 20:27:18.208   792   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-07 20:27:18.209   792   897 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-07 20:27:18.344  1617  4549 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-07 20:27:18.344  1617  4547 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-07 20:27:18.358  1617  4549 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-07 20:27:18.359  1617  4547 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-07 20:27:18.374  1617  4549 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-07 20:27:18.375  1617  4547 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-07 20:27:18.375  1617  4547 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-07 20:27:18.397  1617  4547 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-07 20:27:18.890  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:27:18.891  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:27:19.072   792   897 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-07 20:27:19.348  1617  4416 I BeaconBle: Scan : No clients left, canceling alarm.
,07-07 20:27:20.722   792   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:27:26.007   792   897 D ConnectivityService: handlePromptUnvalidated 101
,07-07 20:27:27.207   792  1312 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1603 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-07 20:27:27.253  1603  4597 W DriveInitializer: Background init thread started
,07-07 20:27:27.336  1603  4597 W DriveInitializer: Background init thread ended
,07-07 20:27:30.903   792   895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,07-07 20:27:44.764   792   815 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-07 20:27:44.769   792   815 I PowerManagerService: Sleeping (uid 1000)...
07-07 20:27:44.809   191  1010 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1542 us)
07-07 20:27:44.812   792   815 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-07 20:27:44.842  3769  3769 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-07 20:27:44.842  3769  3769 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-07 20:27:44.898  3769  3769 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@642b19a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@44910e9, 16908290=android.view.AbsSavedState$1@44910e9}, android:focusedViewId=100}]}]
,07-07 20:27:44.899  3769  3769 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-07 20:27:44.899  3769  3769 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-07 20:27:44.899  3769  3769 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-07 20:27:45.401   792   815 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-07 20:27:45.434   792   815 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-07 20:27:45.437   792   813 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-07 20:27:45.441   191   191 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,07-07 20:27:45.441   191   191 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-07 20:27:45.707   191   191 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-07 20:27:45.708   792   911 D SurfaceControl: Excessive delay in setPowerMode(): 271ms
,07-07 20:27:45.709  1801  1810 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-07 20:27:45.726   198  1375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-07 20:27:45.741   792   895 D WifiConfigStore: Retrieve network priorities after PNO.
07-07 20:27:45.751   792   895 E native  : do suspend false
,07-07 20:27:45.761   792   895 D WifiConfigStore: No blacklist allowed without epno enabled
,07-07 20:27:45.779   198   835 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-07 20:27:45.784   792   895 D WifiConfigStore: Retrieve network priorities after PNO.
07-07 20:27:45.786   792   895 E native  : do suspend true
,07-07 20:27:45.793  1238  1238 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-07 20:27:45.823  1617  1617 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-07 20:27:45.825  1617  1617 I BeaconBle: BLE 'JB+' software access layer enabled
,07-07 20:27:45.837  1617  4664 D BluetoothAdapter: startLeScan(): null
,07-07 20:27:45.838  1617  4664 D BluetoothAdapter: STATE_ON
,07-07 20:27:45.839  4325  4335 D BtGatt.GattService: registerClient() - UUID=e5b8ea6d-1770-42e6-a4b8-f70ae1e9e0ea
,07-07 20:27:45.840  4325  4357 D BtGatt.GattService: onClientRegistered() - UUID=e5b8ea6d-1770-42e6-a4b8-f70ae1e9e0ea, clientIf=5
07-07 20:27:45.840  1617  1662 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:27:45.840  4325  4400 D BtGatt.GattService: start scan with filters
,07-07 20:27:45.841  4325  4363 D BtGatt.ScanManager: handling starting scan
,07-07 20:27:45.843  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-07 20:27:45.843  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-07 20:27:45.843  4325  4363 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-07 20:27:45.843  4325  4357 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-07 20:27:46.244   792   895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,07-07 20:27:47.353  1617  4664 D BluetoothAdapter: stopLeScan()
,07-07 20:27:47.359  1617  4664 D BluetoothAdapter: STATE_ON
07-07 20:27:47.361  4325  4336 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:27:47.362  4325  4363 D BtGatt.ScanManager: stop scan
07-07 20:27:47.362  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-07 20:27:47.363  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-07 20:27:47.363  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-07 20:27:47.403  4325  4335 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-07 20:27:47.579  1617  4664 D BluetoothAdapter: startLeScan(): null
,07-07 20:27:47.580  1617  4664 D BluetoothAdapter: STATE_ON
07-07 20:27:47.581  4325  4335 D BtGatt.GattService: registerClient() - UUID=28a0fd71-f2d9-4ff5-ba4d-4b662bdc1bdf
07-07 20:27:47.581  4325  4357 D BtGatt.GattService: onClientRegistered() - UUID=28a0fd71-f2d9-4ff5-ba4d-4b662bdc1bdf, clientIf=5
07-07 20:27:47.582  1617  1627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:27:47.582  4325  4400 D BtGatt.GattService: start scan with filters
07-07 20:27:47.583  4325  4363 D BtGatt.ScanManager: handling starting scan
07-07 20:27:47.584  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-07 20:27:47.584  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-07 20:27:47.584  4325  4363 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-07 20:27:47.587  4325  4357 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-07 20:27:48.226   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=162187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:27:48.845  1617  4664 D BluetoothAdapter: stopLeScan()
,07-07 20:27:48.849  1617  4664 D BluetoothAdapter: STATE_ON
07-07 20:27:48.850  4325  4411 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:27:48.852  4325  4363 D BtGatt.ScanManager: stop scan
07-07 20:27:48.852  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-07 20:27:48.852  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-07 20:27:48.852  4325  4363 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-07 20:27:48.890  4325  4377 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:27:48.890  1617  4664 I BeaconBle: Scan : No clients left, canceling alarm.
,07-07 20:27:51.847  1617  4656 I BeaconBle: Scan : No clients left, canceling alarm.
,07-07 20:27:51.905  1617  1724 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:27:54.830  1603  2985 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:27:57.965   792   895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,07-07 20:28:20.816   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=194777, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:28:43.386   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:29:53.777   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287738, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:30:21.226   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=315187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:30:35.867   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329828, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:30:37.893  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:30:37.921  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:30:37.922  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:30:52.107  1617  2630 V NativeCrypto: SSL shutdown failed: ssl=0x9a8aa800: I/O error during system call, Connection timed out
,07-07 20:30:55.109  1617  2630 V NativeCrypto: SSL shutdown failed: ssl=0x99598c00: I/O error during system call, Connection timed out
,07-07 20:30:57.060  1603  2859 V NativeCrypto: SSL shutdown failed: ssl=0x9327f600: I/O error during system call, Connection timed out
,07-07 20:31:05.976   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=359937, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:31:23.497   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377458, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:31:30.725  1513  1513 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.onStartJob(142): JobScheduler invoked, loading libraries.
,07-07 20:31:30.827  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.j.a(469): Request install of com.google.android.apps.photos v=316191 pri=3 for auto_update
,07-07 20:31:30.836  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1258): Installer kick - starting com.google.android.apps.photos
,07-07 20:31:30.854  1513  1513 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.a(186): auto-updates finished successfully.
,07-07 20:31:30.855  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:31:30.859  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:31:30.859  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:31:30.861  1513  1588 I Finsky  : [99] com.google.android.finsky.installer.y.b(204): Created session 296411114 for com.google.android.apps.photos
,07-07 20:31:31.277  1513  1588 I Finsky  : [99] com.google.android.finsky.installer.ah.run(127): Session for com.google.android.apps.photos already exists, skipping creation
,07-07 20:31:31.580  3563  3595 V NativeCrypto: SSL shutdown failed: ssl=0xaf0a2800: I/O error during system call, Connection timed out
,07-07 20:31:31.613  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.ai.onPostExecute(5001): Downloading patch for com.google.android.apps.photos (com.google.android.apps.photos)
,07-07 20:31:31.617  1513  1513 I Finsky  : [1] com.google.android.finsky.download.e.a(256): Duplicate state set for 'com.google.android.apps.photos' (0). Already in that state
,07-07 20:31:31.618  1513  1513 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.apps.photos added to DownloadQueue
,07-07 20:31:31.620  1513  1513 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.apps.photos from 0 to 1.
,07-07 20:31:31.628   199   199 I installd: free_cache(3951553) avail 10750291968
,07-07 20:31:31.632  1513  1513 I Finsky  : [1] com.google.android.finsky.download.ai.run(5554): Download com.google.android.apps.photos starting
,07-07 20:31:31.663  1513  1589 I Finsky  : [100] com.google.android.finsky.download.ae.a(1567): Enqueued com.google.android.apps.photos as content://downloads/my_downloads/976
,07-07 20:31:31.665  1513  1513 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.apps.photos from 1 to 2.
,07-07 20:31:31.669  1513  1513 I Finsky  : [1] com.google.android.finsky.download.x.a(632): com.google.android.apps.photos: onStart
,07-07 20:31:31.691  1513  1513 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.apps.photos: onProgress 0/-1 Status: 192.
,07-07 20:31:31.704   945  4687 D DownloadManager: [976] Starting
,07-07 20:31:31.716   945  4687 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-07 20:31:31.807  1617  2630 V NativeCrypto: SSL shutdown failed: ssl=0x99624c00: I/O error during system call, Connection timed out
,07-07 20:31:32.535  1617  2630 V NativeCrypto: SSL shutdown failed: ssl=0x99597c00: I/O error during system call, Connection timed out
,07-07 20:31:32.971   945  4687 D DownloadManager: [976] Finished with status SUCCESS
,07-07 20:31:32.999  1513  1513 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(46): Intent received at DownloadBroadcastReceiver
,07-07 20:31:33.003  1513  1513 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.apps.photos: onProgress 3951553/3951553 Status: 200.
,07-07 20:31:33.009  1513  1513 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.apps.photos from 2 to 3.
,07-07 20:31:33.009  1513  1513 I Finsky  : [1] com.google.android.finsky.download.x.b(600): com.google.android.apps.photos: onComplete
07-07 20:31:33.009  1513  1513 I Finsky  : [1] com.google.android.finsky.download.x.i(341): Download com.google.android.apps.photos removed from DownloadQueue
07-07 20:31:33.010   199   199 I installd: free_cache(0) avail 10746339328
,07-07 20:31:33.011  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.x.c(36121): Prepare to patch com.google.android.apps.photos (com.google.android.apps.photos) from content://downloads/my_downloads/976 format 2
,07-07 20:31:33.023   199   199 I installd: free_cache(23232230) avail 10746339328
,07-07 20:31:33.884  1513  1616 I Finsky  : [113] com.google.android.finsky.receivers.ab.a(3193): Patch apply task for com.google.android.apps.photos (com.google.android.apps.photos) (format 2) completed in 873 ms
,07-07 20:31:33.888  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.ab.onPostExecute(4243): Successfully applied patch to update com.google.android.apps.photos (com.google.android.apps.photos)
,07-07 20:31:33.891  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.x.c(42122): Begin install of com.google.android.apps.photos
,07-07 20:31:33.894   945   958 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/downloadfile.bin via provider delete
,07-07 20:31:35.020  1513  1513 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2102): Skipping verification because own installation
,07-07 20:31:35.033   792   819 W PackageParser: Problem in package /data/app/vmdl296411114.tmp/base.apk:
,07-07 20:31:35.033   792   819 W PackageParser: Unknown element under <activity>: category at /data/app/vmdl296411114.tmp/base.apk Binary XML file line #1212
,07-07 20:31:36.194   792   819 I PackageManager.DexOptimizer: Running dexopt (dex2oat) on: /data/app/vmdl296411114.tmp/base.apk pkg=com.google.android.apps.photos isa=arm vmSafeMode=false debuggable=false oatDir = /data/app/vmdl296411114.tmp/oat bootComplete=true
,07-07 20:31:36.239  4693  4693 I dex2oat : Starting dex2oat.
,07-07 20:31:41.926  4693  4696 W dex2oat : Compilation of void gen_binder.root.RootModule$Generated.a(android.content.Context, java.lang.Class, tyf) took 126.115ms
,07-07 20:31:43.241  4693  4696 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
,07-07 20:31:45.722  4693  4697 W dex2oat : Compilation of void wer.a(wnl) took 110.570ms
,07-07 20:31:45.728  4693  4696 W dex2oat : Compilation of wnu wov.a(wnk) took 143.938ms
,07-07 20:31:45.918  4693  4695 W dex2oat : Compilation of wsd wsd.b(wnk) took 211.279ms
,07-07 20:31:47.350  4693  4693 I dex2oat : dex2oat took 11.110s (threads: 4) arena alloc=18MB java alloc=18MB native alloc=74MB free=11MB
,07-07 20:31:47.380   792   808 I ActivityManager: Force stopping com.google.android.apps.photos appid=10083 user=-1: replace sys pkg
07-07 20:31:47.380   792   808 I ActivityManager: Killing 2131:com.google.android.apps.photos/u0a83 (adj 1): stop com.google.android.apps.photos
,07-07 20:31:47.392   792   819 W PackageManager: Trying to update system app code path from /data/app/com.google.android.apps.photos-2 to /data/app/com.google.android.apps.photos-1
,07-07 20:31:47.393   792   819 W PackageManager: Code path for com.google.android.apps.photos changing from /data/app/com.google.android.apps.photos-2 to /data/app/com.google.android.apps.photos-1
,07-07 20:31:47.393   792   819 W PackageManager: Resource path for com.google.android.apps.photos changing from /data/app/com.google.android.apps.photos-2 to /data/app/com.google.android.apps.photos-1
,07-07 20:31:47.455   792   808 W ActivityManager: Scheduling restart of crashed service com.google.android.apps.photos/.onboarding.autosignin.AutoSignInAndSyncJobService in 1000ms
,07-07 20:31:47.456   792   808 I ActivityManager:   Force stopping service ServiceRecord{7b42c65 u0 com.google.android.apps.photos/.onboarding.autosignin.AutoSignInAndSyncJobService}
,07-07 20:31:47.458   792   808 I ActivityManager: Force stopping com.google.android.apps.photos appid=10083 user=-1: replace pkg
,07-07 20:31:47.459   792  2032 W ActivityManager: Spurious death for ProcessRecord{a29d8d1 0:com.google.android.apps.photos/u0a83}, curProc for 2131: null
,07-07 20:31:47.501   792   819 W PackageSettings: Skipping PackageSetting{b815c55 com.example.hello/10116} due to missing metadata
,07-07 20:31:47.536   792   819 W PackageManager: Not granting permission android.permission.WRITE_MEDIA_STORAGE to package com.google.android.apps.photos (protectionLevel=18 flags=0x3858bec5)
,07-07 20:31:47.602   792   819 W PackageSettings: Skipping PackageSetting{b815c55 com.example.hello/10116} due to missing metadata
,07-07 20:31:47.630   792   819 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,07-07 20:31:47.630   792   819 I art     : Starting a blocking GC Explicit
,07-07 20:31:47.678   792   819 I art     : Explicit concurrent mark sweep GC freed 87109(4MB) AllocSpace objects, 6(472KB) LOS objects, 33% free, 25MB/38MB, paused 848us total 48.205ms
,07-07 20:31:47.719   792   819 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.google.android.apps.photos-2/base.apk, retcode=-1
,07-07 20:31:47.719   199   199 E installd: Couldn't opendir /data/app/vmdl296411114.tmp: No such file or directory
,07-07 20:31:47.722   792   819 I ActivityManager: Force stopping com.google.android.apps.photos appid=10083 user=0: pkg removed
,07-07 20:31:47.728   792   792 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-07 20:31:47.731  4325  4325 D BluetoothMapAppObserver: onReceive
07-07 20:31:47.731  4325  4325 D BluetoothMapAppObserver: The removed package is: com.google.android.apps.photos
07-07 20:31:47.738   792   887 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 20:31:47.745  1513  1513 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2142): Successful install of com.google.android.apps.photos
,07-07 20:31:47.758   792   803 I ActivityManager: Start proc 4727:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
07-07 20:31:47.781   792   887 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-07 20:31:47.782  4325  4325 D BluetoothMapAppObserver: onReceive
07-07 20:31:47.782  4325  4325 D BluetoothMapAppObserver: The installed package is: com.google.android.apps.photos
07-07 20:31:47.785  4325  4325 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-07 20:31:47.785  4325  4325 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-07 20:31:47.816  1313  1313 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-07 20:31:47.828   792   887 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 20:31:47.851  1313  1313 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_ADDED
,07-07 20:31:47.851  1313  1313 D CarrierServiceBindHelper: mHandler: 3
07-07 20:31:47.851  1313  1313 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REPLACED
07-07 20:31:47.851  1313  1313 D CarrierServiceBindHelper: mHandler: 3
07-07 20:31:47.851  1313  1313 D CarrierServiceBindHelper: mHandler: 3
07-07 20:31:47.851  1313  1313 D CarrierConfigLoader: mHandler: 9 phoneId: 0
,07-07 20:31:47.889  4727  4727 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-07 20:31:47.904  1513  1513 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(277): Wear auto install disabled for package com.google.android.apps.photos
,07-07 20:31:47.918   792  1214 I ActivityManager: Start proc 4753:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,07-07 20:31:47.943  4753  4753 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,07-07 20:31:47.947  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-07 20:31:47.964  1603  4767 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.photos
,07-07 20:31:47.971  1603  4767 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.photos
,07-07 20:31:47.972  1617  1617 E NetworkScheduler.SR: Invalid parameter app
,07-07 20:31:47.972  1617  1617 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-07 20:31:48.009  1603  4767 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.photos
,07-07 20:31:48.011  1603  1647 E Drive.UninstallOperation: Package still installed com.google.android.apps.photos
,07-07 20:31:48.021   792  1214 I ActivityManager: Start proc 4770:com.google.android.partnersetup/u0a11 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver,
,07-07 20:31:48.041  1603  4767 D gH_CompatibleDatabase: Open irg@80b3bf2, release reference: 1
,07-07 20:31:48.045  4770  4770 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-07 20:31:48.050  1603  4767 D gH_CompatibleDatabase: Acquire reference of irg@80b3bf2: 2
,07-07 20:31:48.050  1603  4767 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.android.apps.photos.
07-07 20:31:48.050  1603  4767 D gH_CompatibleDatabase: Release reference of irg@80b3bf2: 1
07-07 20:31:48.050  1603  4767 D gH_CompatibleDatabase: Open irg@5ab40c0, release reference: 1
,07-07 20:31:48.057  1603  4767 D gH_CompatibleDatabase: Acquire reference of irg@5ab40c0: 2
,07-07 20:31:48.057  1603  4767 D gH_CompatibleDatabase: Release reference of irg@5ab40c0: 1
07-07 20:31:48.057  1603  4767 D gH_CompatibleDatabase: Open irg@58d253e, release reference: 1
,07-07 20:31:48.064  1513  1513 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.google.android.apps.photos
,07-07 20:31:48.067  1603  4767 D gH_CompatibleDatabase: Acquire reference of irg@58d253e: 2
,07-07 20:31:48.068  1603  4767 D gH_CompatibleDatabase: Release reference of irg@58d253e: 1
07-07 20:31:48.068  1603  4767 D gH_CompatibleDatabase: Close irg@80b3bf2, release reference: 0
07-07 20:31:48.068  1603  4767 D gH_CompatibleDatabase: Close irg@5ab40c0, release reference: 0
07-07 20:31:48.069  1603  4767 D gH_CompatibleDatabase: Close irg@58d253e, release reference: 0
,07-07 20:31:48.070   792   974 I ActivityManager: Killing 3563:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,07-07 20:31:48.089  1603  4767 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.photos
,07-07 20:31:48.090  1603  4766 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-07 20:31:48.093  1603  4767 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.photos
,07-07 20:31:48.096  1603  1603 D AsyncTaskServiceImpl: Submit a task: nwp
,07-07 20:31:48.098  1603  4767 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.photos
,07-07 20:31:48.107  1617  2170 D GCM     : GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,07-07 20:31:48.108  1603  1671 D nwp     : Processing package: com.google.android.apps.photos
,07-07 20:31:48.113  1603  1671 D nwe     : Look up (com.google.android.apps.photos:316191) returned no result
,07-07 20:31:48.114  1603  1671 D nwp     : Starting Hash for package com.google.android.apps.photos:1.23.1.126715090
,07-07 20:31:48.125  1381  4792 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.apps.photos, CONTACTS=MAYBE
,07-07 20:31:48.150  1603  4767 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.apps.photos
,07-07 20:31:48.152  1603  1603 D AsyncTaskServiceImpl: Submit a task: nwp
,07-07 20:31:48.184   792  1308 I ActivityManager: Start proc 4797:com.google.android.apps.photos/u0a83 for service com.google.android.apps.photos/.backup.core.PhotosBackupGcoreGcmTaskService
,07-07 20:31:48.185  1617  1617 E NetworkScheduler.SR: Invalid parameter app
07-07 20:31:48.185  1617  1617 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-07 20:31:48.201   792  2031 I ActivityManager: Start proc 4809:com.google.android.apps.cloudprint/u0a32 for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver
,07-07 20:31:48.204  1603  4795 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-07 20:31:48.352  1603  1671 D nwp     : Package com.google.android.apps.photos's hash: c865063445a85868d5be8d4aa4a06d03d2b400e5833a271c1e98ffa17061f7a3
,07-07 20:31:48.353  1603  1671 D nwe     : Look up (com.google.android.apps.photos:316191) returned no result
,07-07 20:31:48.358  1617  1617 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-07 20:31:48.372  1381  4792 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 246 ms] updated apps [took 246 ms] 
,07-07 20:31:48.375   792   802 I ActivityManager: Killing 4427:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-07 20:31:48.385  1603  1671 D nwp     : Saved the app info in cache for package:com.google.android.apps.photos.
07-07 20:31:48.385  1603  1671 D nwp     : Processing package: com.google.android.apps.photos
,07-07 20:31:48.392  1603  1671 D GassUtils: Found app info for package com.google.android.apps.photos:316191. Hash: c865063445a85868d5be8d4aa4a06d03d2b400e5833a271c1e98ffa17061f7a3
07-07 20:31:48.392  1603  1671 D nwp     : Found info for package com.google.android.apps.photos in db.
,07-07 20:31:50.127  1603  1641 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-07 20:31:50.140  4797  4797 W InstanceID/Rpc: Found 10007
,07-07 20:31:50.207  4797  4797 W TrustedPartners: no provider found for com.motorola.camera.provider.bestshotprovider.BestShotProvider; do not trust
,07-07 20:31:50.208  4797  4797 W TrustedPartners: no provider found for com.google.android.apps.photos.api.SpecialTypesProvider; do not trust
,07-07 20:31:50.208  4797  4797 W TrustedPartners: no provider found for com.lge.photos.specialtypeprovider; do not trust
,07-07 20:31:50.236  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:31:50.238  1603  1641 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
,07-07 20:31:50.239  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:31:50.278  1603  1641 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-07 20:31:50.295  1603  1641 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,07-07 20:31:50.324  1617  2575 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-07 20:31:50.714  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.718   792  1292 D ConnectivityService: listenForNetwork for Listen from uid/pid:10083/4797 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-07 20:31:50.821  1617  4825 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-07 20:31:50.838  1617  4825 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-07 20:31:50.857  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.917  4797  4854 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.918  4797  4854 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.936  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.938  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.967  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:50.968  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:51.127  1603  1641 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-07 20:31:51.128  1603  1641 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-07 20:31:51.159  4797  4854 I art     : Note: end time exceeds epoch: 
,07-07 20:31:51.160  4797  4854 I art     : Note: end time exceeds epoch: 
,07-07 20:31:51.200  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:51.201  4797  4861 I art     : Note: end time exceeds epoch: 
,07-07 20:31:55.180   792   974 I ActivityManager: Killing 3887:com.android.settings/1000 (adj 15): empty #17
,07-07 20:31:55.234   792   896 D WifiService: Client connection lost with reason: 4
,07-07 20:31:56.335   792  2031 I ActivityManager: Killing 4000:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,07-07 20:32:03.121  1513  1600 I Finsky  : [110] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-07 20:32:03.231  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:32:03.236  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:32:03.237  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:32:04.099  1513  1513 I Finsky  : [1] com.google.android.finsky.c.c.a(311): Completed 1 account content syncs with 1 successful.
,07-07 20:32:04.099  1513  1513 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-07 20:32:31.466   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=445427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:32:37.737   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=451698, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:33:05.226   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=479187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:33:21.998   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=495959, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:33:49.466   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=523427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:34:43.298   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=577259, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:35:10.746   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=604707, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:35:43.117   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=637078, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:36:19.106   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=673067, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:36:55.567   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=709528, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:37:22.986   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=736947, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:39:54.202   792   801 I art     : Background partial concurrent mark sweep GC freed 42164(3MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 26MB/39MB, paused 992us total 135.905ms
,07-07 20:45:25.934   792   807 I UsageStatsService: User[0] Flushing usage stats to disk
,07-07 20:45:38.130  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:45:38.161  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:45:38.162  1617  1617 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:45:43.199   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1237160, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:45:59.386   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:49:43.888   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1477849, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:50:04.746   792  4501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1498707, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms)
```
