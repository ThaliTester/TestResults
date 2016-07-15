#### Test 75789268514fc25_thali03_LGE-Nexus 5 Logs


```
--------- beginning of system
07-15 15:20:57.562   788   948 I ActivityManager: Killing 2735:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,--------- beginning of main
07-15 15:20:58.217  3599  3599 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-15 15:20:58.221  3599  3599 D AndroidRuntime: CheckJNI is OFF
07-15 15:20:58.258  3599  3599 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-15 15:20:58.295  3599  3599 I Radio-JNI: register_android_hardware_Radio DONE
07-15 15:20:58.314  3599  3599 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-15 15:20:58.317   788  1357 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-15 15:20:58.331  1386  1397 W SearchService: Abort, client detached.
07-15 15:20:58.353  3599  3599 D AndroidRuntime: Shutting down VM
07-15 15:20:58.372   788  1365 I ActivityManager: Start proc 3615:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-15 15:20:58.379  1386  1386 I MicroDetector: Keeping mic open: false
07-15 15:20:58.379  1386  1386 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@f9df3a6
07-15 15:20:58.379  1386  1508 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-15 15:20:58.380  1386  1587 I DeviceStateChecker: DeviceStateChecker cancelled
07-15 15:20:58.431   198  1592 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-15 15:20:58.431   198  1592 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-15 15:20:58.437  1386  1586 I MicroRecognitionRunner: Stopping hotword detection.
07-15 15:20:58.437  1386  1590 I MicroRecognitionRunner: Detection finished
07-15 15:20:58.476  3615  3615 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-15 15:20:58.504  3615  3615 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 2958-2960)
07-15 15:20:58.504  3615  3615 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-15 15:20:58.518  3615  3615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {76d4bbe}
07-15 15:20:58.518  3615  3615 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-15 15:20:58.519  3615  3615 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-15 15:20:58.540   788   893 D WifiService: New client listening to asynchronous messages
07-15 15:20:58.555  3615  3615 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-15 15:20:58.570  3615  3615 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-15 15:20:58.570  3615  3615 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-15 15:20:58.585  3615  3615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-15 15:20:58.643   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b247e7:true
07-15 15:20:58.657   788   948 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3615 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-15 15:20:58.667  3615  3615 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
07-15 15:20:58.674  3615  3615 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-15 15:20:58.675  3615  3615 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
07-15 15:20:58.685  3615  3615 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-15 15:20:58.705  3615  3615 I cr_Ime  : ImeThread is not enabled.
07-15 15:20:58.716  3615  3662 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-15 15:20:58.786  3615  3667 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-15 15:20:58.815  3615  3667 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-15 15:20:58.850  3615  3667 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-15 15:20:58.864   191   191 D SurfaceFlinger: shader cache generated - 24 shaders in 145.802139 ms
07-15 15:20:58.886   788  1322 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3615 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-15 15:20:58.939  3615  3662 I OpenGLRenderer: Initialized EGL, version 1.4
07-15 15:20:59.007   788   809 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +649ms
07-15 15:20:59.081  3615  3615 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3615
07-15 15:20:59.082  3615  3615 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
07-15 15:20:59.083  3615  3615 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
07-15 15:20:59.169  3615  3615 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-15 15:20:59.170   788   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-15 15:20:59.172   788  1000 I ActivityManager: Killing 2338:com.google.android.keep/u0a52 (adj 15): empty #17
07-15 15:20:59.356  3615  3684 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1725441744
07-15 15:20:59.360  3615  3684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-15 15:20:59.360  3615  3684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:20:59.360  3615  3684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:20:59.360  3615  3684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:20:59.360  3615  3684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-15 15:20:59.360  3615  3684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3c7e48 added. We now have 1 listener(s)
07-15 15:20:59.363  3615  3684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
07-15 15:20:59.363  3615  3684 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:20:59.364  3615  3684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:20:59.364  3615  3684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-15 15:20:59.368  3615  3684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae50c7 added. We now have 1 listener(s)
07-15 15:20:59.369  3615  3684 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:20:59.371  3615  3684 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-15 15:20:59.372  3615  3684 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:20:59.372  3615  3684 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:20:59.373  3615  3684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:20:59.373  3615  3684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:20:59.382  3615  3684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:20:59.382  3615  3684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:20:59.382  3615  3684 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:20:59.383  3615  3684 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:20:59.383  3615  3684 D io.jxcore.node.JXcoreExtension: Unit Tests on
07-15 15:20:59.385  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:20:59.386  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:20:59.423  3615  3615 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-15 15:21:00.150  3615  3688 W jxcore-log: Initializing JXcore engine
,07-15 15:21:00.150  3615  3688 W jxcore-log: JXcore engine is ready
,07-15 15:21:00.220  3688  3688 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7021]" dev="sockfs" ino=7021 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-15 15:21:00.220  3688  3688 W Thread-317: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-15 15:21:00.220  3688  3688 W Thread-317: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18288]" dev="sockfs" ino=18288 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-15 15:21:00.240  3615  3688 W jxcore-log: Starting JXcore engine
,07-15 15:21:00.318  3615  3688 W jxcore-log: Platform android
07-15 15:21:00.318  3615  3688 W jxcore-log: 
,07-15 15:21:00.318  3615  3688 W jxcore-log: Process ARCH arm
07-15 15:21:00.318  3615  3688 W jxcore-log: 
,07-15 15:21:00.506  3615  3688 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:21:00.506  3615  3688 I jxcore-log: 
07-15 15:21:00.507  3615  3688 W jxcore-log: JXcore engine is started
07-15 15:21:00.508  3615  3684 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-15 15:21:00.511  3615  3615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:21:10.664  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-15 15:21:10.664  3615  3688 I jxcore-log: 
,07-15 15:21:10.666  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-15 15:21:10.666  3615  3688 I jxcore-log: 
,07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:10.670  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:21:10.672  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:21:10.673  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-15 15:21:10.673  3615  3688 I jxcore-log: 
,07-15 15:21:10.675  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-15 15:21:10.675  3615  3688 I jxcore-log: 
,07-15 15:21:11.024  3615  3615 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-15 15:21:11.026  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:21:11.026  3615  3688 I jxcore-log: 
,07-15 15:21:11.030  3615  3688 D ExecuteNativeTests: Running unit tests
,07-15 15:21:11.089  3615  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-15 15:21:11.089  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-15 15:21:11.089  3615  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-15 15:21:11.089  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-15 15:21:11.089  3615  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-15 15:21:11.089  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:21:11.091  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-15 15:21:11.091  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-15 15:21:11.091  3615  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-15 15:21:11.091  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-15 15:21:11.091  3615  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-15 15:21:11.091  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-15 15:21:11.091  3615  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-15 15:21:11.091  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-15 15:21:11.092  3615  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-15 15:21:11.092  3615  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-15 15:21:11.092  3615  3688 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-15 15:21:11.092  3615  3688 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-15 15:21:11.092  3615  3688 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-15 15:21:11.092  3615  3688 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-15 15:21:11.093  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:11.093  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7e7a5a added. We now have 2 listener(s)
07-15 15:21:11.093  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:11.094  3615  3688 D BluetoothAdapter: enable(): BT is already enabled..!
07-15 15:21:11.094   788  1357 D WifiService: setWifiEnabled: true pid=3615, uid=10026
07-15 15:21:11.094   788  1357 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:21:11.095  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:11.095  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bdb48b added. We now have 3 listener(s)
07-15 15:21:11.096  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:11.099  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:21:11.099  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34a6968 added. We now have 4 listener(s)
07-15 15:21:11.099  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:11.100  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:11.100  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13cc181 added. We now have 5 listener(s)
,07-15 15:21:11.100  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:11.102   788   799 D WifiService: setWifiEnabled: false pid=3615, uid=10026
,07-15 15:21:11.102   788   799 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-15 15:21:11.105   788   892 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-15 15:21:11.105   788   892 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-15 15:21:11.105   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:21:11.105   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:11.107  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:11.107  1797  1867 D BluetoothAdapterState: Current state: ON, message: 23
07-15 15:21:11.107  1797  1867 D BluetoothAdapterProperties: Setting state to 13
07-15 15:21:11.107  1797  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-15 15:21:11.109  1797  1867 D BluetoothAdapterProperties: onBluetoothDisable()
07-15 15:21:11.109  1797  1867 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:11.112  1797  1797 D BluetoothMapService: onReceive
07-15 15:21:11.112  1797  1797 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:21:11.113  1797  1797 D BluetoothMapService: STATE_TURNING_OFF
07-15 15:21:11.113  1797  1797 D BluetoothMapService: MAP Service closeService in
,07-15 15:21:11.113  1797  1797 D BluetoothMapMasInstance0: MAP Service shutdown
07-15 15:21:11.113  1797  1797 D ObexServerSockets0: shutdown(block = true)
07-15 15:21:11.113  1797  1797 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:21:11.113  1797  1797 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-15 15:21:11.113  1797  2076 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-15 15:21:11.114  1797  2043 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-15 15:21:11.114  1797  2075 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:11.118  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:21:11.118  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:21:11.118  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:11.120  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:11.121  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:11.123  1797  1797 I BtOppRfcommListener: stopping Accept Thread
07-15 15:21:11.124  1797  2621 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-15 15:21:11.124  1797  2621 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-15 15:21:11.128   788  2790 D DhcpClient: Clearing IP address
07-15 15:21:11.129   194   633 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:21:11.135   788   804 I ActivityManager: Start proc 3712:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-15 15:21:11.138  1797  1871 D BluetoothAdapterProperties: Scan Mode:20
,07-15 15:21:11.138  1797  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-15 15:21:11.141   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
,07-15 15:21:11.142   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:11.149  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:21:11.150  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:21:11.152  1797  1797 D HeadsetService: Received stop request...Stopping profile...
,07-15 15:21:11.153  1319  1339 D BluetoothHeadset: Proxy object disconnected
,07-15 15:21:11.154   788   788 D BluetoothHeadset: Proxy object disconnected
,07-15 15:21:11.154   929   942 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:11.154   929   929 D HeadsetProfile: Bluetooth service disconnected
07-15 15:21:11.155   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:11.155   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:11.156  1797  1797 D A2dpService: Received stop request...Stopping profile...
07-15 15:21:11.156  1797  2048 D A2dpStateMachine: Exit Disconnected: -1
07-15 15:21:11.157   929   929 D BluetoothA2dp: Proxy object disconnected
07-15 15:21:11.158   788   788 D BluetoothA2dp: Proxy object disconnected
07-15 15:21:11.158  1797  1797 D HidService: Received stop request...Stopping profile...
,07-15 15:21:11.158  1797  1797 D HidService: Stopping Bluetooth HidService
07-15 15:21:11.159   929   929 D BluetoothInputDevice: Proxy object disconnected
07-15 15:21:11.159   929   929 D HidProfile: Bluetooth service disconnected
07-15 15:21:11.159  1561  2927 V NativeCrypto: Read error: ssl=0x999fa600: I/O error during system call, Connection timed out
07-15 15:21:11.159  1797  1797 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:11.159  1797  1797 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:11.159  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:21:11.159  1797  1797 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:11.159  2869  3001 V NativeCrypto: Read error: ssl=0xaec97e00: I/O error during system call, Connection timed out
07-15 15:21:11.160  2869  3001 V NativeCrypto: Write error: ssl=0xaec97e00: I/O error during system call, Broken pipe
07-15 15:21:11.160  2869  3001 V NativeCrypto: Write error: ssl=0xaec97e00: I/O error during system call, Broken pipe
07-15 15:21:11.160  2869  3001 V NativeCrypto: SSL shutdown failed: ssl=0xaec97e00: I/O error during system call, Broken pipe
,07-15 15:21:11.161  1797  1797 D HealthService: Received stop request...Stopping profile...
07-15 15:21:11.163  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:11.164  1561  2927 V NativeCrypto: SSL shutdown failed: ssl=0x999fa600: I/O error during system call, Broken pipe
07-15 15:21:11.166  2869  3040 V NativeCrypto: Read error: ssl=0x985be000: I/O error during system call, Connection timed out
07-15 15:21:11.167  1797  1797 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-15 15:21:11.167  1797  1797 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-15 15:21:11.167  2869  3040 V NativeCrypto: Write error: ssl=0x985be000: I/O error during system call, Broken pipe
07-15 15:21:11.167  2869  3040 V NativeCrypto: Write error: ssl=0x985be000: I/O error during system call, Broken pipe
07-15 15:21:11.167  1797  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:11.167  1797  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:21:11.167  1797  1871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-15 15:21:11.167  1797  1871 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-15 15:21:11.167  1561  2927 E GCM     : Wifi connection closed with errorCode 20
07-15 15:21:11.168   788  1000 D ConnectivityService: reportNetworkConnectivity(100, false) by 10007
07-15 15:21:11.169  1797  1797 D PanService: Received stop request...Stopping profile...
07-15 15:21:11.169   929   929 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-15 15:21:11.169   929   929 D PanProfile: Bluetooth service disconnected
,07-15 15:21:11.171  1797  1797 D BluetoothMapService: Received stop request...Stopping profile...
,07-15 15:21:11.171  1797  1797 D BluetoothMapService: stop()
07-15 15:21:11.171   788  2788 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10007
07-15 15:21:11.171  1797  1797 D BluetoothMapAppObserver: deinitObservers()
07-15 15:21:11.171  1797  1797 D BluetoothMapAppObserver: removeReceiver()
07-15 15:21:11.173   929   929 D BluetoothMap: Proxy object disconnected
07-15 15:21:11.173   929   929 D MapProfile: Bluetooth service disconnected
07-15 15:21:11.173  1797  1797 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:21:11.173  1797  1797 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:11.173  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:11.173  1797  1797 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:11.174   788  2788 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-15 15:21:11.174   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-15 15:21:11.174   788   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-15 15:21:11.175  1797  1797 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:11.175  1797  1797 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:21:11.175  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:11.175  1797  1797 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:11.175  1797  1797 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-15 15:21:11.175  1797  1797 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-15 15:21:11.175  1797  1797 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:11.176  1797  1797 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-15 15:21:11.176   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-15 15:21:11.176  1797  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:11.176  1797  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:11.176  1797  1980 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:21:11.176  1797  1980 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-15 15:21:11.176  1797  1980 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:21:11.176  1797  1980 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-15 15:21:11.176  1797  1871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:21:11.176  1797  1871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-15 15:21:11.176  1797  1871 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-15 15:21:11.176  1797  1797 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:11.176  1797  1797 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:11.177  1797  1797 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-15 15:21:11.177  1797  1797 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-15 15:21:11.190   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-15 15:21:11.191  1797  1797 D BluetoothMapService: MAP Service closeService in
,07-15 15:21:11.191  1797  1797 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:11.191  1797  1797 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:11.191  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:11.191  1797  1797 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:11.192  1797  1797 D BluetoothMapService: cleanup()
07-15 15:21:11.192  1797  1797 D BluetoothMapService: MAP Service closeService in
07-15 15:21:11.192  1797  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-15 15:21:11.192  1797  1867 D BluetoothAdapterProperties: Setting state to 15
07-15 15:21:11.192  1797  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-15 15:21:11.192  1797  1867 I BluetoothAdapterState: Entering BleOnState
07-15 15:21:11.192   929  1410 D BluetoothPbap: onBluetoothStateChange: up=false
,07-15 15:21:11.200   929   940 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:21:11.201   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:11.201   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:11.201   788   808 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-15 15:21:11.201   929   942 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:11.201   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:11.201   929  1411 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:21:11.202  1319  1339 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:11.202   929  1410 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-15 15:21:11.203   194   633 D CommandListener: Setting iface cfg
07-15 15:21:11.210   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-15 15:21:11.210   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 4
07-15 15:21:11.213   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:21:11.214   788   894 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-15 15:21:11.216   929   942 D BluetoothPan: onBluetoothStateChange on: false
,07-15 15:21:11.217  2869  3040 V NativeCrypto: SSL shutdown failed: ssl=0x985be000: I/O error during system call, Broken pipe
,07-15 15:21:11.217  1797  1867 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-15 15:21:11.217  1797  1867 D BluetoothAdapterProperties: Setting state to 16
07-15 15:21:11.217  1797  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-15 15:21:11.218   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-15 15:21:11.218  1797  1867 D BluetoothAdapterProperties: onBleDisable
07-15 15:21:11.218  1797  1867 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:11.218  1797  1868 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-15 15:21:11.218  1797  1871 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:21:11.219  1797  1980 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-15 15:21:11.219  1797  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:11.226  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:21:11.226  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:11.229  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:11.229  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:11.231   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-15 15:21:11.233   788   788 D RttService: SCAN_AVAILABLE : 1
07-15 15:21:11.234   788   905 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-15 15:21:11.237   788   892 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-15 15:21:11.237  3712  3712 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-15 15:21:11.240   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-15 15:21:11.240   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:21:11.241   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-15 15:21:11.242   788  2791 D DhcpClient: Receive thread stopped
,07-15 15:21:11.251  3712  3712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:21:11.255   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:11.257   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f41aeb7:true
,07-15 15:21:11.271  3712  3712 D LocalBluetoothProfileManager: Adding local MAP profile
,07-15 15:21:11.274   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-15 15:21:11.274   194   633 D CommandListener: Clearing all IP addresses on wlan0
,07-15 15:21:11.275   788   894 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-15 15:21:11.275  3712  3712 D BluetoothMap: Create BluetoothMap proxy object
07-15 15:21:11.275   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:21:11.277   788   808 D Tethering: MasterInitialState.processMessage what=3
,07-15 15:21:11.277   788   892 D DhcpClient: doQuit
07-15 15:21:11.277   788   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-15 15:21:11.278   788  2790 D DhcpClient: onQuitting
07-15 15:21:11.279  1386  1386 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-15 15:21:11.280  3615  3615 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:11.285  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:11.285  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:11.287  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:11.287  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:11.288  3712  3712 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-15 15:21:11.289  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:11.289  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:11.294  3712  3712 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:21:11.300   788   893 D WifiService: New client listening to asynchronous messages
,07-15 15:21:11.314  1375  1375 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-15 15:21:11.319  1797  1871 I bt_hci  : shut_down
,07-15 15:21:11.320  1797  1875 D bt_hwcfg: hw_epilog_process
,07-15 15:21:11.323  1797  1875 I bt_vendor: low_power_mode_cb
,07-15 15:21:11.325  1375  1375 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-15 15:21:11.336  1375  1375 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-15 15:21:11.342   194   633 E Netd    : netlink response contains error (No such file or directory)
07-15 15:21:11.342   788   894 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-15 15:21:11.342   788   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-15 15:21:11.347  1797  1875 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-15 15:21:11.347  1797  1875 I bt_vendor: epilog_cb
07-15 15:21:11.347  1797  1875 I bt_hci  : epilog_finished_callback
,07-15 15:21:11.351  1797  1871 I bt_hci_h4: hal_close
,07-15 15:21:11.351  1797  1871 I bt_userial_vendor: device fd = 49 close
,07-15 15:21:11.355  1797  1868 D bt_stack_manager: event_shut_down_stack finished.
,07-15 15:21:11.355  1797  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-15 15:21:11.356  1797  1867 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-15 15:21:11.356  1797  1797 D BtGatt.DebugUtils: handleDebugAction() action=null
07-15 15:21:11.356  1797  1797 D BtGatt.GattService: Received stop request...Stopping profile...
,07-15 15:21:11.356  1797  1797 D BtGatt.GattService: stop()
07-15 15:21:11.356  1797  1797 D BtGatt.AdvertiseManager: advertise clients cleared
07-15 15:21:11.357  1797  1797 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:11.357  1797  1797 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:11.357  1797  1797 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:11.357  1797  1797 V BluetoothAdapterState: isBleTurningOff()=true
,07-15 15:21:11.357  1797  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-15 15:21:11.357  1797  1867 D BluetoothAdapterProperties: Setting state to 10
07-15 15:21:11.357  1797  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-15 15:21:11.358  1797  1867 I BluetoothAdapterState: Entering OffState
07-15 15:21:11.358   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-15 15:21:11.361  1797  1797 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-15 15:21:11.361  1797  1797 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-15 15:21:11.361  1797  1797 I BluetoothServiceJni: cleanupNative: return from cleanup
07-15 15:21:11.361  1797  1868 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-15 15:21:11.364  1797  1868 D bt_stack_manager: event_clean_up_stack finished.
,07-15 15:21:11.365  1797  1797 I art     : System.exit called, status: 0
07-15 15:21:11.365  1797  1797 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-15 15:21:11.375  1375  1375 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-15 15:21:11.384  1375  1375 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-15 15:21:11.393   788  1367 I ActivityManager: Process com.android.bluetooth (pid 1797) has died
,07-15 15:21:11.469  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:11.487   788   892 D wifi    : In wifi stop Hal
,07-15 15:21:11.487   788   892 D wifi    : halHandle = 0xa07d2ca0, mVM = 0xb4d7c000, mCls = 0x100ade
,07-15 15:21:11.487   788  1374 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-15 15:21:11.487   788  1374 D WifiHAL : Got a signal to exit!!!
,07-15 15:21:11.487   788  1374 I WifiHAL : Exit wifi_event_loop
07-15 15:21:11.487   788   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-15 15:21:11.487   788   892 E WifiHAL : Event processing terminated
07-15 15:21:11.487   788   892 D wifi    : In wifi cleaned up handler
07-15 15:21:11.487   788   892 I WifiHAL : Internal cleanup completed
07-15 15:21:11.488  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:11.488  1561  1656 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-15 15:21:11.489  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:11.576  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:11.594   788   798 I ActivityManager: Start proc 3764:com.google.android.talk/u0a51 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-15 15:21:11.601   788  1374 D wifi    : set interface wlan0 flags (DOWN)
07-15 15:21:11.601   788   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-15 15:21:11.643  3478  3758 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.apps.gcs
,07-15 15:21:11.644  3478  3758 I PhenotypeExpCommitSvc: [299] PhenotypeExperimentCommitService.a: Successfully committed experiments for user [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-15 15:21:11.752  1561  1561 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=515bc4a4-fae1-4cb1-9434-c4a6e1c81274
,07-15 15:21:11.759  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:21:11.759  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:21:11.802   788   808 D Tethering: InitialState.processMessage what=4
,07-15 15:21:11.807   788   808 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-15 15:21:11.841  1561  1616 W GCoreFlp: No location to return for getLastLocation()
,07-15 15:21:11.869  1571  3757 D UdcContextInitService: registered all accounts: true
,07-15 15:21:11.869  1561  1646 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-15 15:21:11.884  1561  1631 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-15 15:21:11.929   788  1325 I ActivityManager: Killing 3255:com.google.android.gms.feedback/u0a7 (adj 15): empty #17
,07-15 15:21:11.965  1561  1631 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-15 15:21:11.997  1561  1631 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-15 15:21:12.048  3764  3764 I Babel_telephony: TeleModule.onApplicationCreate
,07-15 15:21:12.058  3764  3800 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-15 15:21:12.058  3764  3800 I Babel_SMS: MmsConfig.loadMmsSettings
,07-15 15:21:12.064  3764  3800 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-15 15:21:12.064  3764  3800 I Babel_SMS: MmsConfig.loadFromDatabase
,07-15 15:21:12.077  3764  3800 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-15 15:21:12.077  3764  3800 I Babel_SMS: MmsConfig.loadFromResources
,07-15 15:21:12.078  3764  3800 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-15 15:21:12.079  3764  3800 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-15 15:21:12.084  3764  3803 I Babel_SMS: ApnsOta: OTA version -1
,07-15 15:21:12.085  3764  3764 I Babel_Crash: Startup - clean
,07-15 15:21:12.118   788  1367 I ActivityManager: Killing 3192:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-15 15:21:12.153  3712  3712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:21:12.170   788   948 I ActivityManager: Start proc 3813:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-15 15:21:12.171  3712  3712 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding HeadsetService
,07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding A2dpService
07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding HidService
,07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding HealthService
07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding PanService
07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding GattService
07-15 15:21:12.246  3813  3813 D AdapterServiceConfig: Adding BluetoothMapService
,07-15 15:21:12.254   788   798 I ActivityManager: Killing 3291:com.android.providers.calendar/u0a1 (adj 15): empty #17
,07-15 15:21:12.266  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:12.270  1561  3825 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:21:12.271  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:12.286   788  1366 I ActivityManager: Start proc 3826:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-15 15:21:12.293  1561  3825 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-15 15:21:12.312  3826  3826 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-15 15:21:12.344  3826  3826 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-15 15:21:12.349   788  1325 I ActivityManager: Start proc 3841:com.google.android.apps.plus/u0a63 for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver
,07-15 15:21:12.360  3826  3838 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-15 15:21:12.558   788  1365 I ActivityManager: Killing 3307:com.google.android.calendar/u0a28 (adj 15): empty #17
,07-15 15:21:12.672  1571  1571 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-15 15:21:12.676  1571  2896 I iu.UploadsManager: num queued entries: 0
,07-15 15:21:12.685  1571  2896 I iu.UploadsManager: num updated entries: 0
,07-15 15:21:12.688   788   948 I ActivityManager: Start proc 3866:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-15 15:21:12.692  1571  2896 I iu.SyncManager: NEXT; no task
,07-15 15:21:12.744  3866  3866 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-15 15:21:12.755  3866  3866 I MultiDex: VM with version 2.1.0 has multidex support
07-15 15:21:12.755  3866  3866 I MultiDex: install
07-15 15:21:12.755  3866  3866 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-15 15:21:12.824  3866  3866 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-15 15:21:12.824  3866  3866 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-15 15:21:12.824  3866  3866 I GAv4    :   adb logcat -s GAv4
,07-15 15:21:12.835  3866  3866 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:21:12.844  3866  3884 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:21:12.955  3866  3866 I NSApplication: Starting up...
,07-15 15:21:12.968   788   798 I ActivityManager: Start proc 3907:com.google.android.apps.photos/u0a83 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-15 15:21:12.970   788   798 I ActivityManager: Killing 3344:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-15 15:21:13.026  1571  1571 V Herrevad: NQAS connected
,07-15 15:21:13.045  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:13.046  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:13.073  3866  3866 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-15 15:21:13.343   788   948 I ActivityManager: Killing 3371:com.android.musicfx/u0a13 (adj 15): empty #17
,07-15 15:21:13.383   788  1366 I ActivityManager: Start proc 3924:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,07-15 15:21:13.476  3924  3924 W InstanceID/Rpc: Found 10007
,07-15 15:21:13.498   788   948 I ActivityManager: Killing 3396:com.quickoffice.android/u0a65 (adj 15): empty #17
,07-15 15:21:14.032  1561  1631 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-15 15:21:14.034  1561  1631 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-15 15:21:14.119   788  1322 D WifiService: setWifiEnabled: true pid=3615, uid=10026
,07-15 15:21:14.119   788  1322 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-15 15:21:14.120   194   633 D SoftapController: Softap fwReload - Ok
,07-15 15:21:14.122   194   633 D CommandListener: Setting iface cfg
,07-15 15:21:14.122   194   633 D CommandListener: Trying to bring down wlan0
07-15 15:21:14.122   194   633 D CommandListener: Clearing all IP addresses on wlan0
,07-15 15:21:14.127   788   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-15 15:21:14.888   788   892 D wifi    : set interface wlan0 flags (UP)
,07-15 15:21:14.888   788   892 I WifiHAL : Initializing wifi
,07-15 15:21:14.888   788   892 I WifiHAL : Creating socket
,07-15 15:21:14.889   788   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-15 15:21:14.889   788   892 D wifi    : Did set static halHandle = 0xa07d2ca0
07-15 15:21:14.890   788   892 D wifi    : halHandle = 0xa07d2ca0, mVM = 0xb4d7c000, mCls = 0x1012e2
07-15 15:21:14.890   788   892 D wifi    : array field set
07-15 15:21:14.890   788   892 I WifiNative-HAL: interface[0] = p2p0
07-15 15:21:14.890   788   892 I WifiNative-HAL: interface[1] = wlan0
07-15 15:21:14.891   788   808 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-15 15:21:14.894   788  3962 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602409312
07-15 15:21:14.894   788  3962 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x1012e2, env = 0x93ff2f40
,07-15 15:21:14.895   788   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-15 15:21:14.898  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:14.899  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:14.948  3963  3963 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-15 15:21:14.968  3963  3963 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:21:14.977  3963  3963 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:14.990  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:14.990  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:14.991  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:14.991  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:14.993   788   892 D WifiConfigStore: Loading config and enabling all networks 
,07-15 15:21:15.003   788   892 D WifiConfigStore: loaded 0 passpoint configs
,07-15 15:21:15.003   788   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-15 15:21:15.005   788   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-15 15:21:15.005   788   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-15 15:21:15.005   788   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-15 15:21:15.008   788   892 D WifiNative-HAL: Setting external_sim to 1
07-15 15:21:15.009   788   892 D wifi    : setting dfs flag to true, 0x9b690068
07-15 15:21:15.009   788   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-15 15:21:15.009   788   892 D wifi    : setting scan oui 0x9b690068
07-15 15:21:15.009   788   892 D WifiHAL : Sending mac address OUI
,07-15 15:21:15.013   788   892 E native  : do suspend false
,07-15 15:21:15.019   788   788 D RttService: SCAN_AVAILABLE : 3
,07-15 15:21:15.019   788   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-15 15:21:15.019   788   905 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-15 15:21:15.020   194   633 D CommandListener: Setting iface cfg
07-15 15:21:15.020   194   633 D CommandListener: Trying to bring up p2p0
,07-15 15:21:15.020   788   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-15 15:21:15.025   788   891 D WifiNative-HAL: p2pGetDeviceAddress
,07-15 15:21:15.025   788   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-15 15:21:15.026   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:21:16.683   788   892 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-15 15:21:16.685   788   892 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
07-15 15:21:16.685   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:16.694   788   892 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-15 15:21:16.731   788   892 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-15 15:21:16.732  3963  3963 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-15 15:21:16.803  3963  3963 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-15 15:21:16.836  3963  3963 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-15 15:21:16.837  3963  3963 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-15 15:21:16.839   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-15 15:21:16.847   788   892 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-15 15:21:16.847   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:21:16.847   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-15 15:21:16.858   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:16.865   194   633 D CommandListener: Setting iface cfg
,07-15 15:21:16.869   788   892 D WifiStateMachine: Start Dhcp Watchdog 2
,07-15 15:21:16.880   788   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-15 15:21:16.881   788   894 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,07-15 15:21:16.882   788   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-15 15:21:16.887   788  3984 D DhcpClient: Receive thread started
,07-15 15:21:16.963   788   892 E native  : do suspend false
,07-15 15:21:16.970   788  3971 D DhcpClient: Broadcasting DHCPDISCOVER
,07-15 15:21:16.977   788  3984 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172720, domain null
,07-15 15:21:16.978   788  3971 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172720 seconds
07-15 15:21:16.978   788  3971 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-15 15:21:16.986   788  3984 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-15 15:21:16.986   788  3971 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-15 15:21:16.987   194   633 D CommandListener: Setting iface cfg
,07-15 15:21:16.991   788   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-15 15:21:16.994   788  3971 D DhcpClient: Scheduling renewal in 86399s
,07-15 15:21:16.998   788   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-15 15:21:16.999   788   892 D WifiConfigStore: No blacklist allowed without epno enabled
07-15 15:21:16.999   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-15 15:21:17.000   788   894 D ConnectivityService: Adding iface wlan0 to network 101
,07-15 15:21:17.015   788   892 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-15 15:21:17.050   788   894 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-15 15:21:17.050   788   894 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-15 15:21:17.051   788   894 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-15 15:21:17.052   788   894 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-15 15:21:17.052   788   894 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-15 15:21:17.059   788   894 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-15 15:21:17.064   788   894 D ConnectivityService: scheduleUnvalidatedPrompt 101
07-15 15:21:17.064   788   894 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-15 15:21:17.064   788   894 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-15 15:21:17.064   788   894 D ConnectivityService:    accepting network in place of null
07-15 15:21:17.065   788   892 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-15 15:21:17.065   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:21:17.065   788   894 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -59]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-15 15:21:17.090   788  3970 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121533, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:21:17.092   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:17.110   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:17.112   788   894 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-15 15:21:17.112   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:21:17.113   788   894 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-15 15:21:17.114   788   808 D Tethering: MasterInitialState.processMessage what=3
,07-15 15:21:17.123  3615  3615 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-15 15:21:17.125   788  1365 D WifiService: setWifiEnabled: false pid=3615, uid=10026
,07-15 15:21:17.125   788  1365 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:21:17.128   788   892 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-15 15:21:17.128   788   892 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-15 15:21:17.128   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:21:17.128   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:17.134  1386  1386 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:17.136  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:21:17.136  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:17.138  3826  3826 E SetupWizard: tickleCheckinService called after completing user setup
,07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:17.142  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:21:17.142  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:21:17.143   788  3971 D DhcpClient: Clearing IP address
,07-15 15:21:17.143   194   633 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:21:17.146   194   633 D CommandListener: Setting iface cfg
07-15 15:21:17.149   788  3984 D DhcpClient: Receive thread stopped
,07-15 15:21:17.188   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-15 15:21:17.188   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 4
,07-15 15:21:17.188   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:17.192   788   894 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-15 15:21:17.198   788   788 D RttService: SCAN_AVAILABLE : 1
,07-15 15:21:17.198   788   905 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-15 15:21:17.201   788   892 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-15 15:21:17.204   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:21:17.230   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:17.246  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:17.249  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:17.257   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:17.257   194   633 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:21:17.257   788   894 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-15 15:21:17.257   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-15 15:21:17.259   788   892 D DhcpClient: doQuit
,07-15 15:21:17.259   788   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-15 15:21:17.259   788  3971 D DhcpClient: onQuitting
07-15 15:21:17.262   788   808 D Tethering: MasterInitialState.processMessage what=3
07-15 15:21:17.262  3615  3615 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:17.262  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:17.262  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:17.265  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:17.265  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:21:17.266  1386  1386 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-15 15:21:17.269  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:17.273  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:17.289  3866  3866 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-15 15:21:17.298  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:17.301  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:17.313  3963  3963 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-15 15:21:17.335  3963  3963 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-15 15:21:17.342  3963  3963 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-15 15:21:17.346   194   633 E Netd    : netlink response contains error (No such file or directory)
,07-15 15:21:17.347   788   894 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-15 15:21:17.394  3963  3963 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-15 15:21:17.414  3963  3963 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-15 15:21:17.516   788   892 D wifi    : In wifi stop Hal
,07-15 15:21:17.516   788   892 D wifi    : halHandle = 0xa07d2ca0, mVM = 0xb4d7c000, mCls = 0x1012e2
07-15 15:21:17.516   788  3962 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-15 15:21:17.516   788  3962 D WifiHAL : Got a signal to exit!!!
07-15 15:21:17.516   788  3962 I WifiHAL : Exit wifi_event_loop
07-15 15:21:17.516   788   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
07-15 15:21:17.516   788   892 E WifiHAL : Event processing terminated
07-15 15:21:17.516   788   892 D wifi    : In wifi cleaned up handler
,07-15 15:21:17.516   788   892 I WifiHAL : Internal cleanup completed
,07-15 15:21:17.518  1561  1656 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-15 15:21:17.518  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:17.519  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:17.627   788  3962 D wifi    : set interface wlan0 flags (DOWN)
,07-15 15:21:17.627   788   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-15 15:21:17.837   788   808 D Tethering: InitialState.processMessage what=4
,07-15 15:21:17.843   788   808 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-15 15:21:17.845   788  1000 I ActivityManager: Killing 3178:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-15 15:21:18.113   788   894 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-15 15:21:20.191   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5b22559:true
,07-15 15:21:20.191  3813  3813 D BluetoothAdapterState: make() - Creating AdapterState
07-15 15:21:20.193  3813  3813 I bt_bluedroid: init
07-15 15:21:20.193  3813  4032 I BluetoothAdapterState: Entering OffState
07-15 15:21:20.194  3813  4033 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-15 15:21:20.194  3813  4033 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-15 15:21:20.194  3813  4033 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-15 15:21:20.194  3813  4033 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-15 15:21:20.195  3813  3813 I bt_bluedroid: get_profile_interface socket
07-15 15:21:20.196  3813  3813 I bt_bluedroid: get_profile_interface sdp
07-15 15:21:20.197  3813  3823 I bt_bluedroid: config_hci_snoop_log
07-15 15:21:20.198   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-15 15:21:20.200  3813  4032 D BluetoothAdapterState: Current state: OFF, message: 0
07-15 15:21:20.200  3813  4032 D BluetoothAdapterProperties: Setting state to 14
07-15 15:21:20.200  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-15 15:21:20.200  3813  4032 D BluetoothBondStateMachine: make
07-15 15:21:20.202  3813  4036 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-15 15:21:20.203  3813  4036 D BluetoothAdapterProperties: Name is: Nexus 5
07-15 15:21:20.206  3813  3813 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-15 15:21:20.207  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:20.208  3813  4032 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:20.208  3813  3813 D BtGatt.DebugUtils: handleDebugAction() action=null
07-15 15:21:20.209  3813  3813 D BtGatt.GattService: Received start request. Starting profile...
,07-15 15:21:20.209  3813  3813 D BtGatt.GattService: start()
07-15 15:21:20.209  3813  3813 I bt_bluedroid: get_profile_interface gatt
07-15 15:21:20.209  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:20.209  3813  3813 D BtGatt.AdvertiseManager: advertise manager created
07-15 15:21:20.210  3813  4037 I BluetoothBondStateMachine: StableState(): Entering Off State
07-15 15:21:20.212  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:20.212  3813  3813 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:20.212  3813  3813 V BluetoothAdapterState: isBleTurningOn()=true
07-15 15:21:20.212  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:20.213  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-15 15:21:20.213  3813  4032 I bt_bluedroid: enable
07-15 15:21:20.213  3813  4033 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-15 15:21:20.213  3813  4033 I bt_hci  : start_up
,07-15 15:21:20.217  3813  4033 I bt_vendor: alloc value 0xb39b9631
07-15 15:21:20.217  3813  4033 I bt_vendor: init
07-15 15:21:20.217  3813  4033 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-15 15:21:20.217  3813  4033 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-15 15:21:20.253  3813  4033 D bt_hci  : start_up starting async portion
,07-15 15:21:20.254  3813  4040 I bt_hci  : event_finish_startup
07-15 15:21:20.254  3813  4040 I bt_hci_h4: hal_open
07-15 15:21:20.254  3813  4040 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-15 15:21:20.257  3813  4040 I bt_userial_vendor: device fd = 49 open
,07-15 15:21:20.342  3813  4040 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:21:20.369  3813  4040 D bt_hwcfg: Chipset BCM4335C0
,07-15 15:21:20.369  3813  4040 D bt_hwcfg: Target name = [BCM4335C0]
07-15 15:21:20.369  3813  4040 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-15 15:21:20.930  3813  4040 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-15 15:21:20.930  3813  4040 D bt_hwcfg: Settlement delay -- 100 ms
,07-15 15:21:20.930  3813  4040 I bt_hwcfg: Setting fw settlement delay to 100 
,07-15 15:21:21.048  3813  4040 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:21:21.049  3813  4040 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-15 15:21:21.075  3813  4040 I bt_hwcfg: vendor lib fwcfg completed
,07-15 15:21:21.076  3813  4040 I bt_vendor: firmware callback
,07-15 15:21:21.076  3813  4040 I bt_hci  : firmware_config_callback
,07-15 15:21:21.088  3813  4042 I bt_btu  : btu_task pending for preload complete event
,07-15 15:21:21.088  3813  4042 I bt_btu_task: Bluetooth chip preload is complete
,07-15 15:21:21.088  3813  4042 I bt_btu  : btu_task received preload complete event
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_HCI
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_A2D
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_BTM
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_GAP
,07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_PAN
07-15 15:21:21.098  3813  4042 I         : BTE_InitTraceLevels -- TRC_SDP
07-15 15:21:21.099  3813  4042 I         : BTE_InitTraceLevels -- TRC_GATT
07-15 15:21:21.099  3813  4042 I         : BTE_InitTraceLevels -- TRC_SMP
07-15 15:21:21.099  3813  4042 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-15 15:21:21.099  3813  4042 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-15 15:21:21.323  3813  4042 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39379b5
,07-15 15:21:21.323  3813  4042 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39379b5 
,07-15 15:21:21.444  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:21:21.444  3813  4036 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-15 15:21:21.445  3813  4036 D BluetoothAdapterProperties: Name is: Nexus 5
,07-15 15:21:21.446  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:21.447  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:21.447  3813  4036 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:21:21.447  3813  4036 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:21:21.448  3813  4036 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-15 15:21:21.448  3813  4036 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-15 15:21:21.448  3813  4036 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-15 15:21:21.448  3813  4036 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-15 15:21:21.448  3813  4036 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-15 15:21:21.448  3813  4036 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-15 15:21:21.449  3813  4036 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-15 15:21:21.450  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,07-15 15:21:21.452  3813  3813 I BluetoothHidServiceJni: classInitNative: succeeds
07-15 15:21:21.452  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.455  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-15 15:21:21.456  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.458  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-15 15:21:21.459  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.461  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-15 15:21:21.464  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.465  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-15 15:21:21.467  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.468  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-15 15:21:21.469  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.471  3813  4036 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-15 15:21:21.472  3813  3813 D HidService: getHidService(): service is NULL
07-15 15:21:21.473  3813  4036 D bt_hci  : do_postload posting postload work item
07-15 15:21:21.473  3813  4040 I bt_hci  : event_postload
07-15 15:21:21.473  3813  4040 I bt_vendor: sco_config_cb
07-15 15:21:21.473  3813  4040 I bt_hci  : sco_config_callback postload finished.
07-15 15:21:21.474  3813  4040 I bt_vendor: low_power_mode_cb
,07-15 15:21:21.479  3813  4036 D bt_bte_conf: Device ID record 1 : primary
07-15 15:21:21.479  3813  4036 D bt_bte_conf:   vendorId            = 000f
07-15 15:21:21.479  3813  4036 D bt_bte_conf:   vendorIdSource      = 0001
,07-15 15:21:21.479  3813  4036 D bt_bte_conf:   product             = 1200
07-15 15:21:21.479  3813  4036 D bt_bte_conf:   version             = 1436
07-15 15:21:21.479  3813  4036 D bt_bte_conf:   clientExecutableURL = 
07-15 15:21:21.479  3813  4036 D bt_bte_conf:   serviceDescription  = 
,07-15 15:21:21.479  3813  4036 D bt_bte_conf:   documentationURL    = 
07-15 15:21:21.480  3813  4036 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-15 15:21:21.480  3813  4033 D bt_stack_manager: event_start_up_stack finished
07-15 15:21:21.480  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-15 15:21:21.480  3813  4032 D BluetoothAdapterProperties: Setting state to 15
,07-15 15:21:21.480  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-15 15:21:21.480  3813  4032 I BluetoothAdapterState: Entering BleOnState
07-15 15:21:21.482  3813  4032 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-15 15:21:21.482  3813  4032 D BluetoothAdapterProperties: Setting state to 11
07-15 15:21:21.482  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-15 15:21:21.485  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:21.486  3813  3813 D HeadsetService: Received start request. Starting profile...
,07-15 15:21:21.487  3813  3813 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-15 15:21:21.487  3813  3813 D HeadsetStateMachine: make
,07-15 15:21:21.495  3813  3813 D HeadsetStateMachine: max_hf_connections = 1
,07-15 15:21:21.496  3813  3813 I bt_bluedroid: get_profile_interface handsfree
07-15 15:21:21.497  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-15 15:21:21.497  3813  4032 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:21.498  3813  4036 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-15 15:21:21.499   929  1117 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:21.500   929  1117 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:21.502  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:21.502  3813  3813 D A2dpService: Received start request. Starting profile...
,07-15 15:21:21.502  3813  3813 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-15 15:21:21.503  3813  3813 I bt_bluedroid: get_profile_interface avrcp
,07-15 15:21:21.511  3813  3813 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-15 15:21:21.511  3813  3813 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-15 15:21:21.511  3813  3813 D A2dpStateMachine: make
,07-15 15:21:21.512  3813  3813 I bt_bluedroid: get_profile_interface a2dp
07-15 15:21:21.512  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-15 15:21:21.513  3813  4072 D A2dpStateMachine: Enter Disconnected: -2
07-15 15:21:21.514  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:21.526  3712  3712 D BluetoothInputDevice: Proxy object connected
,07-15 15:21:21.526  3712  3712 D HidProfile: Bluetooth service connected
07-15 15:21:21.526  3813  3813 D HidService: Received start request. Starting profile...
,07-15 15:21:21.526  3813  3813 I bt_bluedroid: get_profile_interface hidhost
07-15 15:21:21.526  3813  3813 D HidService: setHidService(): set to: null
,07-15 15:21:21.527  3813  4036 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3919099
07-15 15:21:21.527  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-15 15:21:21.527  3813  3813 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-15 15:21:21.527  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:21.528  3813  3813 D HealthService: Received start request. Starting profile...
07-15 15:21:21.528  3813  3813 I bt_bluedroid: get_profile_interface health
07-15 15:21:21.529  3813  3813 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-15 15:21:21.529  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:21.530  3712  3712 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:21:21.530  3712  3712 D PanProfile: Bluetooth service connected
07-15 15:21:21.530  3813  3813 D PanService: Received start request. Starting profile...
07-15 15:21:21.530  3813  3813 D BluetoothPanServiceJni: initializeNative(L110): pan
07-15 15:21:21.530  3813  3813 I bt_bluedroid: get_profile_interface pan
07-15 15:21:21.531  3813  4036 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-15 15:21:21.532  3813  3813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:21.533  3712  3712 D BluetoothMap: Proxy object connected
,07-15 15:21:21.533  3813  3813 D BluetoothMapService: Received start request. Starting profile...
07-15 15:21:21.533  3813  3813 D BluetoothMapService: start()
07-15 15:21:21.533  3712  3712 D MapProfile: Bluetooth service connected
07-15 15:21:21.533  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.536  3813  3813 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-15 15:21:21.537  3813  3813 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:21:21.537  3813  3813 D BluetoothMapAppObserver: createReceiver()
07-15 15:21:21.537  3813  3813 D BluetoothMapAppObserver: initObservers()
07-15 15:21:21.537  3813  3813 D BluetoothMapAppObserver: getEnabledAccountItems()
07-15 15:21:21.541  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:21.541  3813  3813 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:21.541  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:21.542  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:21.542  3813  4067 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-15 15:21:21.542  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:21.543  3813  3813 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:21.543  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:21.543  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:21.543  3712  3712 D BluetoothMap: Bluetooth is Not enabled
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:21.544  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:21.544  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-15 15:21:21.544  3813  4032 D BluetoothAdapterProperties: ScanMode =  20
07-15 15:21:21.544  3813  4032 D BluetoothAdapterProperties: State =  11
07-15 15:21:21.545  3813  4032 D BluetoothAdapterProperties: Setting state to 12
07-15 15:21:21.545  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-15 15:21:21.545   929  1410 D BluetoothPbap: onBluetoothStateChange: up=true
,07-15 15:21:21.545  3813  4032 I BluetoothAdapterState: Entering OnState
07-15 15:21:21.545  3813  4036 D BluetoothAdapterProperties: Scan Mode:21
07-15 15:21:21.545  3813  4036 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-15 15:21:21.548   929   942 D BluetoothMap: onBluetoothStateChange: up=true
,07-15 15:21:21.550   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:21:21.550   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:21:21.550   788   808 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-15 15:21:21.552   929   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:21:21.553   788   788 D BluetoothA2dp: Proxy object connected
,07-15 15:21:21.553   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:21:21.554   929   929 D BluetoothMap: Proxy object connected
07-15 15:21:21.554   929  1411 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:21:21.554   929   929 D MapProfile: Bluetooth service connected
,07-15 15:21:21.554   929   929 D BluetoothMap: getConnectedDevices()
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:21.554  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:21.556  3712  3729 D BluetoothPan: onBluetoothStateChange on: true
,07-15 15:21:21.557  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:21.557  3712  3726 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-15 15:21:21.558  1319  3744 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:21:21.559   929  1410 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-15 15:21:21.561   929  1411 D BluetoothPan: onBluetoothStateChange on: true
,07-15 15:21:21.562  3813  3813 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:21:21.562  3813  3813 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:21.562  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:21.563  3712  3729 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:21:21.564  3813  3813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:21:21.565  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:21.565  3712  3726 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:21:21.566  3813  3813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:21:21.566   788   788 I Telecom : BluetoothPhoneService: queryPhoneState
,07-15 15:21:21.568  3813  3813 D ObexServerSockets: Succeed to create listening sockets 
07-15 15:21:21.568  3813  3813 D ObexServerSockets0: startAccept()
07-15 15:21:21.568  3813  3813 D ObexServerSockets0: prepareForNewConnect()
07-15 15:21:21.569   929   929 D BluetoothA2dp: Proxy object connected
07-15 15:21:21.569  3813  3813 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-15 15:21:21.569  3813  3813 D BluetoothSdpJni: SDP Create record success - handle: 0
07-15 15:21:21.570  3712  3712 D LocalBluetoothProfileManager: Adding local A2DP profile
07-15 15:21:21.570   929   929 D BluetoothInputDevice: Proxy object connected
07-15 15:21:21.570   929   929 D HidProfile: Bluetooth service connected
07-15 15:21:21.570  3813  3813 D BluetoothMapService: onReceive
07-15 15:21:21.570  3813  3813 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:21:21.570  3813  3813 D BluetoothMapService: STATE_ON
07-15 15:21:21.571  3813  4081 D ObexServerSockets0: Accepting socket connection...
07-15 15:21:21.571  3813  4080 D ObexServerSockets0: Accepting socket connection...
,07-15 15:21:21.572   929   929 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:21:21.572   929   929 D PanProfile: Bluetooth service connected
,07-15 15:21:21.572   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.574   929  1117 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-15 15:21:21.574  3712  3712 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-15 15:21:21.575   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.587  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:21.591  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:21.592  3813  3813 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:21:21.592  3813  3813 D ObexServerSockets0: prepareForNewConnect()
,07-15 15:21:21.593  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.594  3712  3712 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-15 15:21:21.596  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.610  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.611   929  1117 D BluetoothMap: getConnectedDevices()
07-15 15:21:21.611  3712  3712 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-15 15:21:21.614  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.615   929  1117 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-15 15:21:21.617   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.622  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.623  3712  3712 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-15 15:21:21.624  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.631  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.632  3712  3712 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-15 15:21:21.633  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.640  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.641  3712  3712 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-15 15:21:21.642  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.653  1319  1339 D BluetoothHeadset: Proxy object connected
,07-15 15:21:21.653   788   788 D BluetoothHeadset: Proxy object connected
07-15 15:21:21.654   929   942 D BluetoothHeadset: Proxy object connected
07-15 15:21:21.654   929  1411 D BluetoothHeadset: Proxy object connected
07-15 15:21:21.654   788   788 D BluetoothHeadset: Proxy object connected
,07-15 15:21:21.654   788   788 D BluetoothHeadset: Proxy object connected
07-15 15:21:21.654   788   808 D BluetoothHeadset: Proxy object connected
,07-15 15:21:21.656  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.661  1319  1340 D BluetoothHeadset: Proxy object connected
,07-15 15:21:21.661   929   929 D HeadsetProfile: Bluetooth service connected
07-15 15:21:21.661  3712  3712 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-15 15:21:21.665  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.665   929   929 D HeadsetProfile: Bluetooth service connected
,07-15 15:21:21.669   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.671   929  1117 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-15 15:21:21.672   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.676  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.677  3712  4079 D BluetoothHeadset: Proxy object connected
,07-15 15:21:21.678  3712  3712 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-15 15:21:21.678  1561  1561 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-15 15:21:21.681  3712  3712 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.684  3712  3712 D BluetoothA2dp: Proxy object connected
,07-15 15:21:21.688  1561  1561 I BeaconBle: BLE 'JB+' software access layer enabled
,07-15 15:21:21.688  3712  3712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:21:21.691  3712  3712 D HeadsetProfile: Bluetooth service connected
,07-15 15:21:21.706  3712  3712 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:21:21.708  3813  4097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:21:21.714  3712  3712 D BluetoothPbap: Proxy object connected
,07-15 15:21:21.714  3712  3712 D PbapServerProfile: Bluetooth service connected
,07-15 15:21:21.721   929   929 D BluetoothPbap: Proxy object connected
,07-15 15:21:21.721   929   929 D PbapServerProfile: Bluetooth service connected
,07-15 15:21:21.728  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:21.735  1561  4100 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:21:21.737   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.738  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:21.742  3813  4104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:21:21.743   929  1117 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-15 15:21:21.744  3813  4104 I BtOppRfcommListener: Accept thread started.
,07-15 15:21:21.749   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.750  1561  4105 D BluetoothAdapter: startLeScan(): null
,07-15 15:21:21.756  1561  4105 D BluetoothAdapter: STATE_ON
,07-15 15:21:21.757  1561  4100 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-15 15:21:21.762  3813  3824 D BtGatt.GattService: registerClient() - UUID=63e3930e-e761-412b-b423-7582fbbfd4d1
,07-15 15:21:21.762  3813  4036 D BtGatt.GattService: onClientRegistered() - UUID=63e3930e-e761-412b-b423-7582fbbfd4d1, clientIf=5
07-15 15:21:21.762  1561  1625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-15 15:21:21.763  3813  4078 D BtGatt.GattService: start scan with filters
,07-15 15:21:21.765  3813  4039 D BtGatt.ScanManager: handling starting scan
,07-15 15:21:21.767  3813  4039 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-15 15:21:21.767  3813  4039 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-15 15:21:21.767  3813  4039 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-15 15:21:21.768  3813  4036 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-15 15:21:21.780   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.781   929  1117 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-15 15:21:21.782   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:21.794   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:21.795   929  1117 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-15 15:21:21.796   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:22.128   788  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=2a00:1450:4001:80c::200e
,07-15 15:21:22.129   788  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: ENONET (Machine is not on the network)
07-15 15:21:22.130   788   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-15 15:21:22.274  3813  4036 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:22.408  1561  4068 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-15 15:21:22.410  1561  4068 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: java.io.IOException: Not connected
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:22.410  1561  4068 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:22.575  3813  4036 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:22.673  3813  4036 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:22.867  3813  4036 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:22.950  3813  4036 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:23.148  3813  4032 D BluetoothAdapterState: Current state: ON, message: 23
,07-15 15:21:23.149  3813  4032 D BluetoothAdapterProperties: Setting state to 13
,07-15 15:21:23.149  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-15 15:21:23.150  3813  4032 D BluetoothAdapterProperties: onBluetoothDisable()
07-15 15:21:23.179  3813  4032 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:23.190  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:23.192  3813  4036 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:21:23.192  3813  4036 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
07-15 15:21:23.196  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:23.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:23.198  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:21:23.200  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-15 15:21:23.206  3813  3813 D HeadsetService: Received stop request...Stopping profile...
07-15 15:21:23.212  3813  3813 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:23.212  3813  3813 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:23.213  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:21:23.213  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:23.213  3813  3813 D BluetoothMapService: onReceive
07-15 15:21:23.213  3813  3813 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:21:23.213  3813  3813 D BluetoothMapService: STATE_TURNING_OFF
07-15 15:21:23.213  3813  3813 D BluetoothMapService: MAP Service closeService in
07-15 15:21:23.213  3813  3813 D BluetoothMapMasInstance0: MAP Service shutdown
07-15 15:21:23.213  3813  3813 D ObexServerSockets0: shutdown(block = true)
07-15 15:21:23.213  3813  3813 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:21:23.213  3813  3813 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-15 15:21:23.213  3813  4080 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-15 15:21:23.214  3813  4049 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-15 15:21:23.214  3813  4081 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-15 15:21:23.214  3813  3813 I BtOppRfcommListener: stopping Accept Thread
07-15 15:21:23.215  3813  4104 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-15 15:21:23.215  3813  4104 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-15 15:21:23.216  1319  1339 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:23.217   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:23.217   929  1410 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:23.218  3813  3813 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-15 15:21:23.218  3813  3813 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-15 15:21:23.218   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:23.218   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:23.218  3712  3726 D BluetoothHeadset: Proxy object disconnected
07-15 15:21:23.220  3813  3813 D A2dpService: Received stop request...Stopping profile...
07-15 15:21:23.220  3813  4072 D A2dpStateMachine: Exit Disconnected: -1
07-15 15:21:23.222   788   788 D BluetoothA2dp: Proxy object disconnected
07-15 15:21:23.222  3813  3813 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:23.222  3813  3813 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:21:23.222  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:23.222  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:23.230  3813  3813 D HidService: Received stop request...Stopping profile...
07-15 15:21:23.230  3813  3813 D HidService: Stopping Bluetooth HidService
07-15 15:21:23.232  3813  3813 D HealthService: Received stop request...Stopping profile...
07-15 15:21:23.234  3813  4042 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:23.234  3813  4042 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:21:23.254  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-15 15:21:23.254  3813  4042 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:23.254  3813  4042 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:23.294  1561  4105 D BluetoothAdapter: stopLeScan()
07-15 15:21:23.337  3813  3813 D PanService: Received stop request...Stopping profile...
07-15 15:21:23.337  3813  4042 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:21:23.337  3813  4042 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-15 15:21:23.337  3813  4042 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:21:23.337  3813  4042 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:21:23.337  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-15 15:21:23.337  3813  4036 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-15 15:21:23.338  3813  3813 D BluetoothMapService: Received stop request...Stopping profile...
07-15 15:21:23.338  3813  3813 D BluetoothMapService: stop()
07-15 15:21:23.339  3813  3813 D BluetoothMapAppObserver: deinitObservers()
07-15 15:21:23.339  3813  3813 D BluetoothMapAppObserver: removeReceiver()
,07-15 15:21:23.339   929   929 D HeadsetProfile: Bluetooth service disconnected
07-15 15:21:23.340   929   929 D BluetoothA2dp: Proxy object disconnected
07-15 15:21:23.340   929   929 D BluetoothInputDevice: Proxy object disconnected
07-15 15:21:23.340   929   929 D HidProfile: Bluetooth service disconnected
07-15 15:21:23.340  3813  3813 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:23.340  3813  3813 V BluetoothAdapterState: isTurningOn()=false
,07-15 15:21:23.340  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:23.340  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:23.340   929   929 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-15 15:21:23.340   929   929 D PanProfile: Bluetooth service disconnected
07-15 15:21:23.341   929   929 D BluetoothMap: Proxy object disconnected
07-15 15:21:23.341   929   929 D MapProfile: Bluetooth service disconnected
07-15 15:21:23.341  3813  3813 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-15 15:21:23.341  3813  3813 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-15 15:21:23.341  3813  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:21:23.341  3813  3813 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:23.341  3813  3813 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:23.341  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:23.341  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:23.341  3813  3813 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-15 15:21:23.341  3813  4036 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-15 15:21:23.341  3813  3813 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-15 15:21:23.342  3813  3813 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:23.342  3813  3813 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:23.342  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:23.342  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:23.342  3813  3813 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-15 15:21:23.364  3813  3813 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-15 15:21:23.365  3813  3813 D BluetoothMapService: MAP Service closeService in
07-15 15:21:23.365  3813  3813 V BluetoothAdapterState: isTurningOff()=true
07-15 15:21:23.365  3813  3813 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:23.366  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:23.366  3813  3813 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:23.366  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-15 15:21:23.366  3813  4032 D BluetoothAdapterProperties: Setting state to 15
,07-15 15:21:23.366  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-15 15:21:23.367   929  1411 D BluetoothPbap: onBluetoothStateChange: up=false
07-15 15:21:23.368   929   940 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:21:23.368   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:23.368   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:23.368   788   808 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-15 15:21:23.369   929  1410 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:23.369  3813  4032 I BluetoothAdapterState: Entering BleOnState
07-15 15:21:23.369   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:23.369   929   942 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:21:23.370  3712  3726 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:21:23.370  3712  3729 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-15 15:21:23.371  3712  4079 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:23.371  1319  1340 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:21:23.372   929  1411 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-15 15:21:23.382  3813  3813 D BluetoothMapService: cleanup()
07-15 15:21:23.382  3813  3813 D BluetoothMapService: MAP Service closeService in
07-15 15:21:23.382   929   940 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:21:23.383  3712  3726 D BluetoothPbap: onBluetoothStateChange: up=false
07-15 15:21:23.384  3712  3729 D BluetoothMap: onBluetoothStateChange: up=false
,07-15 15:21:23.385  3712  4079 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:21:23.385  3813  4032 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-15 15:21:23.385  3813  4032 D BluetoothAdapterProperties: Setting state to 16
07-15 15:21:23.385  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-15 15:21:23.386  3813  4032 D BluetoothAdapterProperties: onBleDisable
07-15 15:21:23.386  3813  4032 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:23.386  3813  4033 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,07-15 15:21:23.388  3813  4042 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-15 15:21:23.388  3813  4042 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:21:23.397  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:23.398  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:23.398  3813  4036 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:21:23.399  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
,07-15 15:21:23.400  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-15 15:21:23.401  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-15 15:21:23.402  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
07-15 15:21:23.403  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
07-15 15:21:23.404  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
07-15 15:21:23.406  3712  3712 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-15 15:21:23.408  3712  3712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:21:23.411  3712  3712 D HeadsetProfile: Bluetooth service disconnected
,07-15 15:21:23.413   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-15 15:21:23.414  3712  3712 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:21:23.415   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-15 15:21:23.424   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
,07-15 15:21:23.425  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:23.429  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:23.431  1561  4068 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-15 15:21:23.433  3712  3712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:21:23.433   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-15 15:21:23.436   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-15 15:21:23.439  3712  3712 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:21:23.439   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-15 15:21:23.441  1561  4068 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: java.io.IOException: Not connected
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:23.441  1561  4068 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:23.444  1561  1561 E ActivityThread: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@6cea168 that was originally bound here
07-15 15:21:23.444  1561  1561 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@6cea168 that was originally bound here
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at rbx.run(:com.google.android.gms:94)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:23.444  1561  1561 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:23.448   929  1117 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-15 15:21:23.455  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:23.459  1561  4068 E NearbyDiscovery: Failed to unbind NearbyDirect
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: java.lang.IllegalArgumentException: Service not registered: rbs@6cea168
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at rbr.c(:com.google.android.gms:181)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at rca.run(:com.google.android.gms:1023)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:23.459  1561  4068 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:23.460  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:23.461  1561  4140 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:21:23.469  1561  4140 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-15 15:21:23.487  3813  4036 I bt_hci  : shut_down
,07-15 15:21:23.487  3813  4040 D bt_hwcfg: hw_epilog_process
,07-15 15:21:23.504  3813  4040 I bt_vendor: low_power_mode_cb
,07-15 15:21:23.506  1561  4105 D BluetoothAdapter: startLeScan(): null
,07-15 15:21:23.507  1561  4105 E BluetoothAdapter: startLeScan: cannot get BluetoothLeScanner
,07-15 15:21:23.517  3813  4040 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-15 15:21:23.517  3813  4040 I bt_vendor: epilog_cb
07-15 15:21:23.517  3813  4040 I bt_hci  : epilog_finished_callback
,07-15 15:21:23.518  3813  4036 I bt_hci_h4: hal_close
,07-15 15:21:23.518  3813  4036 I bt_userial_vendor: device fd = 49 close
,07-15 15:21:23.522  3813  4033 D bt_stack_manager: event_shut_down_stack finished.
07-15 15:21:23.522  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-15 15:21:23.523  3813  4032 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-15 15:21:23.523  3813  3813 D BtGatt.DebugUtils: handleDebugAction() action=null
07-15 15:21:23.524  3813  3813 D BtGatt.GattService: Received stop request...Stopping profile...
07-15 15:21:23.524  3813  3813 D BtGatt.GattService: stop()
,07-15 15:21:23.524  3813  3813 D BtGatt.AdvertiseManager: advertise clients cleared
,07-15 15:21:23.525  3813  3813 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:23.525  3813  3813 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:23.525  3813  3813 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:21:23.525  3813  3813 V BluetoothAdapterState: isBleTurningOff()=true
07-15 15:21:23.525  3813  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-15 15:21:23.525  3813  4032 D BluetoothAdapterProperties: Setting state to 10
,07-15 15:21:23.525  3813  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-15 15:21:23.525  3813  4032 I BluetoothAdapterState: Entering OffState
07-15 15:21:23.525   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-15 15:21:23.530  1561  1561 I BeaconBle: Scan : No clients left, canceling alarm.
,07-15 15:21:23.531  3813  3813 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-15 15:21:23.531  3813  3813 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-15 15:21:23.531  3813  3813 I BluetoothServiceJni: cleanupNative: return from cleanup
07-15 15:21:23.531  3813  4033 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-15 15:21:23.533  3813  4033 D bt_stack_manager: event_clean_up_stack finished.
,07-15 15:21:23.534  3813  3813 I art     : System.exit called, status: 0
07-15 15:21:23.534  3813  3813 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-15 15:21:23.540  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:23.540  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:23.540  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:23.553   788  1366 I ActivityManager: Process com.android.bluetooth (pid 3813) has died
,07-15 15:21:23.557  1561  4105 D BluetoothAdapter: stopLeScan()
,07-15 15:21:23.557  1561  4105 I BeaconBle: Scan : No clients left, canceling alarm.
,07-15 15:21:23.842  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:23.842  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:23.842  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:24.146  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.146  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:24.146  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:24.460  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.460  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:24.460  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:24.776  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.776  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:24.776  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:24.778  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.778  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at aksp.c(:com.google.android.gms:36)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at akrf.c(:com.google.android.gms:175)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:24.778  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:24.986  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.986  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at aklk.a(:com.google.android.gms:129)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:24.986  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:24.989  1561  4087 W MessageQueue: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.989  1561  4087 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {e2043c2} sending message to a Handler on a dead thread
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at aksp.d(:com.google.android.gms:44)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akrh.a(:com.google.android.gms:65)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at aklk.a(:com.google.android.gms:130)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:24.989  1561  4087 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:25.067   788   894 D ConnectivityService: handlePromptUnvalidated 101
,07-15 15:21:26.146  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:21:26.146  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:27.090  3764  3795 W Babel   : bcq TOOK TOO LONG! (15037ms > 10000ms)
,07-15 15:21:27.092  3764  3797 W Babel   : bcq TOOK TOO LONG! (15038ms > 10000ms)
,07-15 15:21:27.153   788   804 I ActivityManager: Start proc 4146:com.google.android.talk:matchstick/u0a51 for broadcast com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,07-15 15:21:27.155  3764  3805 W Babel   : bcq TOOK TOO LONG! (15037ms > 10000ms)
,07-15 15:21:27.169   788  1365 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-15 15:21:27.190  3764  3764 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-15 15:21:27.190  3764  3764 W Babel   : BAM#gBA: invalid account id: -1
07-15 15:21:27.190  3764  3764 W Babel   : BAM#gBA: invalid account id: -1
07-15 15:21:27.190  3764  3764 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-15 15:21:27.194   788  1367 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-15 15:21:27.553  4146  4170 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService } isPeriodic:false
,07-15 15:21:27.591  4146  4170 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-15 15:21:27.602  4146  4170 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-15 15:21:27.602  4146  4170 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-15 15:21:27.606  4146  4170 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-15 15:21:27.629  4146  4170 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-15 15:21:27.630  4146  4170 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,07-15 15:21:29.159  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:21:29.159  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d10e67 added. We now have 6 listener(s)
07-15 15:21:29.159  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:29.162  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:29.163  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@110b414 added. We now have 7 listener(s)
,07-15 15:21:29.163  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:29.166  3615  3688 I System.out: IsBluetoothEnabled
,07-15 15:21:29.181  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:29.221   788   808 I ActivityManager: Start proc 4180:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding HeadsetService
07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding A2dpService
07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding HidService
07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding HealthService
07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding PanService
07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding GattService
07-15 15:21:29.281  4180  4180 D AdapterServiceConfig: Adding BluetoothMapService
07-15 15:21:29.289   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ba90c0:true
07-15 15:21:29.289  4180  4180 D BluetoothAdapterState: make() - Creating AdapterState
,07-15 15:21:29.291  4180  4180 I bt_bluedroid: init
07-15 15:21:29.291  4180  4208 I BluetoothAdapterState: Entering OffState
,07-15 15:21:29.293  4180  4209 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-15 15:21:29.293  4180  4209 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-15 15:21:29.293  4180  4209 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-15 15:21:29.293  4180  4209 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-15 15:21:29.294  4180  4180 I bt_bluedroid: get_profile_interface socket
,07-15 15:21:29.295  4180  4212 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-15 15:21:29.295  4180  4180 I bt_bluedroid: get_profile_interface sdp
07-15 15:21:29.295  4180  4212 D BluetoothAdapterProperties: Name is: Nexus 5
,07-15 15:21:29.297  4180  4191 I bt_bluedroid: config_hci_snoop_log
,07-15 15:21:29.298   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-15 15:21:29.300  4180  4208 D BluetoothAdapterState: Current state: OFF, message: 0
,07-15 15:21:29.300  4180  4208 D BluetoothAdapterProperties: Setting state to 14
07-15 15:21:29.300  4180  4208 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-15 15:21:29.301  4180  4208 D BluetoothBondStateMachine: make
07-15 15:21:29.303  4180  4217 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-15 15:21:29.305  4180  4208 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:21:29.306  4180  4180 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-15 15:21:29.309  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:29.309  4180  4180 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-15 15:21:29.309  4180  4180 D BtGatt.GattService: Received start request. Starting profile...
07-15 15:21:29.310  4180  4180 D BtGatt.GattService: start()
,07-15 15:21:29.310  4180  4180 I bt_bluedroid: get_profile_interface gatt
07-15 15:21:29.310  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:29.310  4180  4180 D BtGatt.AdvertiseManager: advertise manager created
,07-15 15:21:29.315  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:21:29.315  4180  4180 V BluetoothAdapterState: isTurningOn()=false
07-15 15:21:29.315  4180  4180 V BluetoothAdapterState: isBleTurningOn()=true
07-15 15:21:29.315  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:29.315  4180  4208 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-15 15:21:29.315  4180  4208 I bt_bluedroid: enable
07-15 15:21:29.316  4180  4209 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-15 15:21:29.316  4180  4209 I bt_hci  : start_up
,07-15 15:21:29.319  4180  4209 I bt_vendor: alloc value 0xb3a2b631
07-15 15:21:29.319  4180  4209 I bt_vendor: init
07-15 15:21:29.319  4180  4209 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-15 15:21:29.319  4180  4209 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-15 15:21:29.353  4180  4209 D bt_hci  : start_up starting async portion
,07-15 15:21:29.353  4180  4220 I bt_hci  : event_finish_startup
07-15 15:21:29.353  4180  4220 I bt_hci_h4: hal_open
07-15 15:21:29.353  4180  4220 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-15 15:21:29.357  4180  4220 I bt_userial_vendor: device fd = 49 open
,07-15 15:21:29.442  4180  4220 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:21:29.469  4180  4220 D bt_hwcfg: Chipset BCM4335C0
,07-15 15:21:29.469  4180  4220 D bt_hwcfg: Target name = [BCM4335C0]
07-15 15:21:29.469  4180  4220 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-15 15:21:29.868  4180  4220 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-15 15:21:29.869  4180  4220 D bt_hwcfg: Settlement delay -- 100 ms
07-15 15:21:29.869  4180  4220 I bt_hwcfg: Setting fw settlement delay to 100 
,07-15 15:21:29.986  4180  4220 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:21:29.986  4180  4220 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-15 15:21:30.018  4180  4220 I bt_hwcfg: vendor lib fwcfg completed
,07-15 15:21:30.018  4180  4220 I bt_vendor: firmware callback
,07-15 15:21:30.018  4180  4220 I bt_hci  : firmware_config_callback
,07-15 15:21:30.030  4180  4231 I bt_btu  : btu_task pending for preload complete event
,07-15 15:21:30.030  4180  4231 I bt_btu_task: Bluetooth chip preload is complete
,07-15 15:21:30.030  4180  4231 I bt_btu  : btu_task received preload complete event
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_HCI
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_A2D
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_BTM
07-15 15:21:30.039  4180  4231 I         : BTE_InitTraceLevels -- TRC_GAP
07-15 15:21:30.040  4180  4231 I         : BTE_InitTraceLevels -- TRC_PAN
07-15 15:21:30.040  4180  4231 I         : BTE_InitTraceLevels -- TRC_SDP
07-15 15:21:30.040  4180  4231 I         : BTE_InitTraceLevels -- TRC_GATT
,07-15 15:21:30.040  4180  4231 I         : BTE_InitTraceLevels -- TRC_SMP
07-15 15:21:30.040  4180  4231 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-15 15:21:30.040  4180  4231 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-15 15:21:30.263  4180  4231 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a99b5
,07-15 15:21:30.263  4180  4231 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a99b5 
,07-15 15:21:30.329  4180  4212 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-15 15:21:30.329  4180  4212 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-15 15:21:30.364  4180  4212 D BluetoothAdapterProperties: Name is: Nexus 5
07-15 15:21:30.365  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:30.365  4180  4212 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:21:30.365  4180  4212 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:21:30.366  4180  4212 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-15 15:21:30.366  4180  4212 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-15 15:21:30.367  4180  4212 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-15 15:21:30.367  4180  4212 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-15 15:21:30.367  4180  4212 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-15 15:21:30.367  4180  4212 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-15 15:21:30.367  4180  4212 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-15 15:21:30.369  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-15 15:21:30.370  4180  4180 I BluetoothHidServiceJni: classInitNative: succeeds
07-15 15:21:30.370  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.374  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-15 15:21:30.375  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.376  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-15 15:21:30.377  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.379  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-15 15:21:30.381  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.383  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-15 15:21:30.384  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.386  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-15 15:21:30.387  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.388  4180  4212 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-15 15:21:30.389  4180  4180 D HidService: getHidService(): service is NULL
07-15 15:21:30.390  4180  4212 D bt_hci  : do_postload posting postload work item
07-15 15:21:30.390  4180  4220 I bt_hci  : event_postload
07-15 15:21:30.390  4180  4220 I bt_vendor: sco_config_cb
07-15 15:21:30.390  4180  4220 I bt_hci  : sco_config_callback postload finished.
07-15 15:21:30.391  4180  4220 I bt_vendor: low_power_mode_cb
07-15 15:21:30.391  4180  4212 D bt_bte_conf: Device ID record 1 : primary
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   vendorId            = 000f
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   vendorIdSource      = 0001
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   product             = 1200
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   version             = 1436
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   clientExecutableURL = 
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   serviceDescription  = 
07-15 15:21:30.391  4180  4212 D bt_bte_conf:   documentationURL    = 
,07-15 15:21:30.391  4180  4212 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-15 15:21:30.391  4180  4209 D bt_stack_manager: event_start_up_stack finished
07-15 15:21:30.392  4180  4208 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-15 15:21:30.392  4180  4208 D BluetoothAdapterProperties: Setting state to 15
07-15 15:21:30.392  4180  4208 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-15 15:21:30.392  4180  4208 I BluetoothAdapterState: Entering BleOnState
07-15 15:21:30.394  4180  4208 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-15 15:21:30.394  4180  4208 D BluetoothAdapterProperties: Setting state to 11
07-15 15:21:30.394  4180  4208 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-15 15:21:30.402  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:30.408  4180  4180 D HeadsetService: Received start request. Starting profile...
07-15 15:21:30.408  4180  4180 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-15 15:21:30.409  4180  4180 D HeadsetStateMachine: make
07-15 15:21:30.410  4180  4208 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:21:30.423  4180  4180 D HeadsetStateMachine: max_hf_connections = 1
07-15 15:21:30.423  4180  4180 I bt_bluedroid: get_profile_interface handsfree
,07-15 15:21:30.427  4180  4212 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-15 15:21:30.427  4180  4212 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
,07-15 15:21:30.428  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.428  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.430  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.431  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:30.433  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:30.433  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:30.436  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.436  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.439  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.439  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:30.442  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:30.442  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.447  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:30.447  4180  4180 D A2dpService: Received start request. Starting profile...
07-15 15:21:30.447  4180  4180 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-15 15:21:30.448  4180  4180 I bt_bluedroid: get_profile_interface avrcp
07-15 15:21:30.454  4180  4180 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-15 15:21:30.454  4180  4180 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-15 15:21:30.454  4180  4180 D A2dpStateMachine: make
07-15 15:21:30.456  4180  4180 I bt_bluedroid: get_profile_interface a2dp
07-15 15:21:30.456  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-15 15:21:30.456  3712  3712 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-15 15:21:30.457  4180  4212 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-15 15:21:30.464  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:30.464  4180  4250 D A2dpStateMachine: Enter Disconnected: -2
,07-15 15:21:30.465  4180  4180 D HidService: Received start request. Starting profile...
07-15 15:21:30.465  4180  4180 I bt_bluedroid: get_profile_interface hidhost
,07-15 15:21:30.465  4180  4180 D HidService: setHidService(): set to: null
07-15 15:21:30.465  4180  4180 I BluetoothHealthServiceJni: classInitNative: succeeds
07-15 15:21:30.466  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:30.466  4180  4212 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb398b099
07-15 15:21:30.466  4180  4212 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-15 15:21:30.467  4180  4180 D HealthService: Received start request. Starting profile...
,07-15 15:21:30.468  4180  4180 I bt_bluedroid: get_profile_interface health
07-15 15:21:30.468  4180  4180 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-15 15:21:30.469  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
07-15 15:21:30.469  4180  4180 D PanService: Received start request. Starting profile...
07-15 15:21:30.469  4180  4180 D BluetoothPanServiceJni: initializeNative(L110): pan
07-15 15:21:30.469  4180  4180 I bt_bluedroid: get_profile_interface pan
07-15 15:21:30.470  4180  4212 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-15 15:21:30.471  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1735a58
,07-15 15:21:30.471  4180  4180 D BluetoothMapService: Received start request. Starting profile...
07-15 15:21:30.471  4180  4180 D BluetoothMapService: start()
07-15 15:21:30.473  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-15 15:21:30.474  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:21:30.474  4180  4180 D BluetoothMapAppObserver: createReceiver()
07-15 15:21:30.475  4180  4180 D BluetoothMapAppObserver: initObservers()
07-15 15:21:30.475  4180  4180 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-15 15:21:30.480  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:21:30.480  4180  4180 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:30.480  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:30.480  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:21:30.480  4180  4239 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:21:30.481  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isTurningOff()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isTurningOn()=true
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:21:30.482  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:21:30.482  4180  4208 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-15 15:21:30.482  4180  4208 D BluetoothAdapterProperties: ScanMode =  20
07-15 15:21:30.482  4180  4208 D BluetoothAdapterProperties: State =  11
,07-15 15:21:30.483  4180  4212 D BluetoothAdapterProperties: Scan Mode:21
07-15 15:21:30.483  4180  4212 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:21:30.483  4180  4208 D BluetoothAdapterProperties: Setting state to 12
07-15 15:21:30.483  4180  4208 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-15 15:21:30.483   929  1411 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:21:30.484  4180  4208 I BluetoothAdapterState: Entering OnState
07-15 15:21:30.485   929  1410 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:21:30.486   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:21:30.486   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:21:30.486   788   808 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:21:30.487   929   940 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:21:30.487   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:21:30.487   929   942 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:30.489  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:30.491   929   929 D BluetoothMap: Proxy object connected
07-15 15:21:30.491   929   929 D MapProfile: Bluetooth service connected
07-15 15:21:30.491   929   929 D BluetoothMap: getConnectedDevices()
07-15 15:21:30.491   788   788 D BluetoothA2dp: Proxy object connected
07-15 15:21:30.493  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:21:30.495  3712  3726 D BluetoothPan: onBluetoothStateChange on: true
,07-15 15:21:30.497  3712  3726 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:21:30.499  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:21:30.499  4180  4180 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-15 15:21:30.500  3712  3729 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:21:30.501  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:21:30.501  1319  1340 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:21:30.501   929   929 D BluetoothA2dp: Proxy object connected
07-15 15:21:30.501   929   940 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:21:30.508   929   940 D BluetoothPan: onBluetoothStateChange on: true
07-15 15:21:30.509  3712  3726 D BluetoothPbap: onBluetoothStateChange: up=true
,07-15 15:21:30.510  3712  3729 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:21:30.511  3712  3729 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:21:30.512  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:21:30.513   788   788 I Telecom : BluetoothPhoneService: queryPhoneState
07-15 15:21:30.513  3712  3712 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:21:30.513  3712  3712 D PanProfile: Bluetooth service connected
07-15 15:21:30.513  3712  3712 D BluetoothMap: Proxy object connected
07-15 15:21:30.513  3712  3712 D MapProfile: Bluetooth service connected
07-15 15:21:30.513  3712  3712 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.515  4180  4180 D ObexServerSockets: Succeed to create listening sockets 
07-15 15:21:30.515  4180  4180 D ObexServerSockets0: startAccept()
07-15 15:21:30.515  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,07-15 15:21:30.516   929   929 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:21:30.516   929   929 D PanProfile: Bluetooth service connected
07-15 15:21:30.516  4180  4180 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-15 15:21:30.516  4180  4180 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-15 15:21:30.517  4180  4267 D ObexServerSockets0: Accepting socket connection...
07-15 15:21:30.518  4180  4266 D ObexServerSockets0: Accepting socket connection...
,07-15 15:21:30.518  4180  4180 D BluetoothMapService: onReceive
07-15 15:21:30.518  4180  4180 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-15 15:21:30.518  4180  4180 D BluetoothMapService: STATE_ON
,07-15 15:21:30.519  3712  3712 D BluetoothA2dp: Proxy object connected
,07-15 15:21:30.521   929   929 D BluetoothInputDevice: Proxy object connected
,07-15 15:21:30.521   929   929 D HidProfile: Bluetooth service connected
,07-15 15:21:30.524  3712  3712 D BluetoothInputDevice: Proxy object connected
,07-15 15:21:30.524  3712  3712 D HidProfile: Bluetooth service connected
,07-15 15:21:30.530   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.531   929  1117 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-15 15:21:30.531  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:21:30.533   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.536  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:30.539  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-15 15:21:30.539  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,07-15 15:21:30.540  3712  3712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:21:30.548  3712  3712 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:21:30.553  4180  4273 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:21:30.554  1561  1561 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-15 15:21:30.556   929   929 D BluetoothPbap: Proxy object connected
,07-15 15:21:30.556   929   929 D PbapServerProfile: Bluetooth service connected
07-15 15:21:30.557  1561  1561 I BeaconBle: BLE 'JB+' software access layer enabled
,07-15 15:21:30.560  3712  3712 D BluetoothPbap: Proxy object connected
07-15 15:21:30.560  3712  3712 D PbapServerProfile: Bluetooth service connected
,07-15 15:21:30.566  1561  4278 D BluetoothAdapter: startLeScan(): null
,07-15 15:21:30.569  1561  4278 D BluetoothAdapter: STATE_ON
,07-15 15:21:30.569  1561  1561 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-15 15:21:30.572  4180  4190 D BtGatt.GattService: registerClient() - UUID=9310be28-02e8-4a54-a29e-c78febe09891
07-15 15:21:30.573  4180  4212 D BtGatt.GattService: onClientRegistered() - UUID=9310be28-02e8-4a54-a29e-c78febe09891, clientIf=5
07-15 15:21:30.573  1561  1635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-15 15:21:30.574  4180  4264 D BtGatt.GattService: start scan with filters
,07-15 15:21:30.576  1561  4279 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:21:30.577  1561  1561 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:21:30.579  4180  4219 D BtGatt.ScanManager: handling starting scan
,07-15 15:21:30.583  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-15 15:21:30.583  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-15 15:21:30.583  4180  4219 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
,07-15 15:21:30.584  4180  4212 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-15 15:21:30.588  1319  3744 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.588   788   788 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.590   929  1410 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.590   788   788 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.590   788   788 D BluetoothHeadset: Proxy object connected
07-15 15:21:30.589  4180  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:21:30.591  3712  3726 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.592  3712  3712 D HeadsetProfile: Bluetooth service connected
,07-15 15:21:30.595  4180  4283 I BtOppRfcommListener: Accept thread started.
,07-15 15:21:30.597   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.599   929  1117 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-15 15:21:30.600  1561  4279 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-15 15:21:30.601   929   929 D HeadsetProfile: Bluetooth service connected
,07-15 15:21:30.603  3712  4079 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.603  3712  3712 D HeadsetProfile: Bluetooth service connected
07-15 15:21:30.603  1319  1339 D BluetoothHeadset: Proxy object connected
,07-15 15:21:30.605   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.622   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.623   929  1117 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-15 15:21:30.624   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.635   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.637   929  1117 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-15 15:21:30.638   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.651   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.653   929  1117 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-15 15:21:30.656   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.670   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.671   929  1117 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-15 15:21:30.674   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.687   929  1117 D BluetoothMap: getConnectedDevices()
,07-15 15:21:30.689   929  1117 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-15 15:21:30.691   929  1117 D MapProfile: getConnectionStatus: status is: 0
,07-15 15:21:30.956  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:31.049  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:31.190  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:31.211  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:31.212  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:31.213  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:21:31.213  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@672f4bd added. We now have 8 listener(s)
,07-15 15:21:31.213  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:31.214   788  1366 D WifiService: setWifiEnabled: false pid=3615, uid=10026
07-15 15:21:31.214   788  1366 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:21:31.216  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:31.216   788  1367 D WifiService: setWifiEnabled: true pid=3615, uid=10026
07-15 15:21:31.216   788  1367 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-15 15:21:31.218   194   633 D SoftapController: Softap fwReload - Ok
07-15 15:21:31.219   194   633 D CommandListener: Setting iface cfg
07-15 15:21:31.219   194   633 D CommandListener: Trying to bring down wlan0
07-15 15:21:31.220   194   633 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:21:31.221   788   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-15 15:21:31.284  1561  4238 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-15 15:21:31.286  1561  4238 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: java.io.IOException: Not connected
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:31.286  1561  4238 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:31.438  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:31.542  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:31.552  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:32.039   788   892 D wifi    : set interface wlan0 flags (UP)
,07-15 15:21:32.039   788   892 I WifiHAL : Initializing wifi
07-15 15:21:32.039   788   892 I WifiHAL : Creating socket
,07-15 15:21:32.047   788   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-15 15:21:32.047   788   892 D wifi    : Did set static halHandle = 0xa07d2ca0
07-15 15:21:32.048   788   892 D wifi    : halHandle = 0xa07d2ca0, mVM = 0xb4d7c000, mCls = 0xdd2
,07-15 15:21:32.048   788   892 D wifi    : array field set
07-15 15:21:32.048   788   892 I WifiNative-HAL: interface[0] = p2p0
,07-15 15:21:32.048   788   892 I WifiNative-HAL: interface[1] = wlan0
,07-15 15:21:32.052   788   808 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-15 15:21:32.059   788  4333 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602409312
,07-15 15:21:32.059   788  4333 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0xdd2, env = 0x93ff1320
,07-15 15:21:32.087  1561  4278 D BluetoothAdapter: stopLeScan()
,07-15 15:21:32.088  1561  4278 D BluetoothAdapter: STATE_ON
,07-15 15:21:32.093  4180  4191 D BtGatt.GattService: stopScan() - queue size =1
,07-15 15:21:32.093  4180  4219 D BtGatt.ScanManager: stop scan
,07-15 15:21:32.093  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-15 15:21:32.093  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-15 15:21:32.093  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-15 15:21:32.093  4180  4264 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-15 15:21:32.117  4334  4334 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-15 15:21:32.137  4334  4334 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:21:32.155   788   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-15 15:21:32.157  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.174  4334  4334 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:21:32.196   788   892 D WifiConfigStore: Loading config and enabling all networks 
,07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.198  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.200  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.204   788   892 D WifiConfigStore: loaded 0 passpoint configs
,07-15 15:21:32.205   788   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-15 15:21:32.206   788   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-15 15:21:32.206   788   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,07-15 15:21:32.206   788   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-15 15:21:32.210   788   892 D WifiNative-HAL: Setting external_sim to 1
,07-15 15:21:32.211   788   892 D wifi    : setting dfs flag to true, 0x9a02b500
07-15 15:21:32.211   788   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-15 15:21:32.211   788   892 D wifi    : setting scan oui 0x9a02b500
07-15 15:21:32.211   788   892 D WifiHAL : Sending mac address OUI
,07-15 15:21:32.218   788   892 E native  : do suspend false
,07-15 15:21:32.226   788   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-15 15:21:32.226   788   788 D RttService: SCAN_AVAILABLE : 3
07-15 15:21:32.226   788   905 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-15 15:21:32.228   194   633 D CommandListener: Setting iface cfg
07-15 15:21:32.228   194   633 D CommandListener: Trying to bring up p2p0
,07-15 15:21:32.228   788   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-15 15:21:32.231   788   891 D WifiNative-HAL: p2pGetDeviceAddress
,07-15 15:21:32.232   788   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.238  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.240  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.242  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-15 15:21:32.242  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-15 15:21:32.244  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@da23683 Bundle[{}]
,07-15 15:21:32.245  3615  3688 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:21:32.245  3615  3688 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:21:32.246  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-15 15:21:32.246  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-15 15:21:32.247  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-15 15:21:32.248  3615  3688 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-15 15:21:32.253   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:21:32.256  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-15 15:21:32.256  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-15 15:21:32.256  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-15 15:21:32.256  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-15 15:21:32.256  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-15 15:21:32.257  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:21:32.266  3615  3688 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 344)
07-15 15:21:32.266  3615  3688 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 344)
07-15 15:21:32.266  3615  3688 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 344)
07-15 15:21:32.266  3615  3688 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 344)
07-15 15:21:32.269  3615  3688 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 349)
07-15 15:21:32.269  3615  3688 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 349)
07-15 15:21:32.269  3615  3688 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 349)
07-15 15:21:32.270  3615  3688 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 350)
07-15 15:21:32.271  3615  3688 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 352)
,07-15 15:21:32.275  1561  4278 D BluetoothAdapter: startLeScan(): null
,07-15 15:21:32.276  3615  4351 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 358, name: My test thread name)
,07-15 15:21:32.276  3615  4351 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 358, thread name: My test thread name)
07-15 15:21:32.276  3615  4351 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 358, name: My test thread name)
07-15 15:21:32.276  1561  4278 D BluetoothAdapter: STATE_ON
,07-15 15:21:32.277  4180  4284 D BtGatt.GattService: registerClient() - UUID=86d59912-b8f4-4bee-8a92-eb2fccb86c09
,07-15 15:21:32.278  4180  4212 D BtGatt.GattService: onClientRegistered() - UUID=86d59912-b8f4-4bee-8a92-eb2fccb86c09, clientIf=5
07-15 15:21:32.278  1561  1635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-15 15:21:32.278  4180  4190 D BtGatt.GattService: start scan with filters
,07-15 15:21:32.279  3615  4353 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 360, name: My test thread name)
,07-15 15:21:32.279  3615  4353 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 360, thread name: My test thread name)
07-15 15:21:32.279  3615  4353 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 360, name: My test thread name)
07-15 15:21:32.279  4180  4219 D BtGatt.ScanManager: handling starting scan
,07-15 15:21:32.281  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-15 15:21:32.281  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-15 15:21:32.281  4180  4219 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-15 15:21:32.281  4180  4212 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-15 15:21:32.282  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-15 15:21:32.282  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb1fab2 added. We now have 2 listener(s)
07-15 15:21:32.283  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.283  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.283  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:21:32.283  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.283  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d62a03 added. We now have 9 listener(s)
07-15 15:21:32.283  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.285  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-15 15:21:32.285  3615  3688 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-15 15:21:32.287  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.288  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.289  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.289  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:32.290  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.290  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddf1fb9 added. We now have 3 listener(s)
07-15 15:21:32.291  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.291  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.291  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.291  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.291  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c10ffe added. We now have 10 listener(s)
07-15 15:21:32.291  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.291  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.291  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.291  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:21:32.291  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.291  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.291  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.291  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.291  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb1fab2 removed from the list
07-15 15:21:32.291  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.291  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d62a03 removed from the list
,07-15 15:21:32.292  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.292  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.292  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.292  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.292  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.292  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:21:32.292  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d62a03 not in the list
07-15 15:21:32.292  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.292  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.292  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.292  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c10ffe removed from the list
07-15 15:21:32.292  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:21:32.292  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.293  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.293  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.293  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddf1fb9 removed from the list
07-15 15:21:32.293  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.293  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.293  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@287635f added. We now have 2 listener(s)
07-15 15:21:32.294  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.294  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.294  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:21:32.294  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.294  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6671ac added. We now have 9 listener(s)
07-15 15:21:32.294  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.296  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:21:32.296  3615  3688 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:21:32.297  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.299  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.300  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.300  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:21:32.300  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.300  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a2e0a added. We now have 3 listener(s)
07-15 15:21:32.301  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.301  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:21:32.301  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.301  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.301  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8d67b added. We now have 10 listener(s)
07-15 15:21:32.301  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.301  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.301  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-15 15:21:32.301  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.301  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.302  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.305  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.305  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:21:32.305  3615  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:21:32.305  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.305  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-15 15:21:32.306  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.306  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.306  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.306  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:21:32.306  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.306  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:21:32.306  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:21:32.306  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@287635f removed from the list
07-15 15:21:32.306  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.306  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6671ac removed from the list
07-15 15:21:32.306  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.306  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-15 15:21:32.306  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.307  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:21:32.307  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.307  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.307  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.307  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6671ac not in the list
07-15 15:21:32.307  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-15 15:21:32.307  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.307  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.307  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8d67b removed from the list
07-15 15:21:32.307  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.307  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.307  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.307  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.307  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a2e0a removed from the list
07-15 15:21:32.307  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.307  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d380cf1 added. We now have 2 listener(s)
07-15 15:21:32.308  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-15 15:21:32.308  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.308  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.309  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.309  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83520d6 added. We now have 9 listener(s)
07-15 15:21:32.309  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.310  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-15 15:21:32.310  3615  3688 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:21:32.312  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.314  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.315  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.315  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:21:32.315  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.315  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad34a44 added. We now have 3 listener(s)
,07-15 15:21:32.316  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.316  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:21:32.316  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.316  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.316  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f872d added. We now have 10 listener(s)
07-15 15:21:32.316  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:32.316  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.317  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.317  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:21:32.317  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.317  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.318  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.319  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.320  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:21:32.320  3615  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:21:32.320  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.320  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.320  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.320  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.320  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.320  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-15 15:21:32.320  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.320  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d380cf1 removed from the list
,07-15 15:21:32.320  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.320  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83520d6 removed from the list
07-15 15:21:32.320  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.321  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-15 15:21:32.321  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.321  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:21:32.321  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.321  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-15 15:21:32.321  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.321  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83520d6 not in the list
07-15 15:21:32.321  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:21:32.321  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.321  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.321  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f872d removed from the list
07-15 15:21:32.321  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.321  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.321  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.321  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.321  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad34a44 removed from the list
,07-15 15:21:32.322  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.322  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2599f3 added. We now have 2 listener(s)
07-15 15:21:32.323  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.323  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.323  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.323  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.323  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dcc6b0 added. We now have 9 listener(s)
,07-15 15:21:32.323  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.324  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-15 15:21:32.324  3615  3688 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:21:32.326  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.328  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.329  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.329  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:21:32.329  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.329  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f74ae added. We now have 3 listener(s)
07-15 15:21:32.330  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.330  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.330  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:21:32.330  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.330  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5e24f added. We now have 10 listener(s)
07-15 15:21:32.331  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.331  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.331  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-15 15:21:32.331  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.331  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.332  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.334  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.335  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:21:32.335  3615  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:21:32.336  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.336  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.336  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.336  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.336  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.336  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:21:32.336  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:21:32.336  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2599f3 removed from the list
,07-15 15:21:32.336  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.336  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dcc6b0 removed from the list
07-15 15:21:32.336  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.336  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-15 15:21:32.337  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.337  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:21:32.337  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.337  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.337  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:21:32.337  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dcc6b0 not in the list
07-15 15:21:32.337  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:21:32.337  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.337  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.337  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5e24f removed from the list
,07-15 15:21:32.337  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.337  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.337  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.337  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.337  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f74ae removed from the list
,07-15 15:21:32.337  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.338  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd76ee5 added. We now have 2 listener(s)
07-15 15:21:32.338  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.339  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.339  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.339  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:21:32.339  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca22dba added. We now have 9 listener(s)
07-15 15:21:32.339  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.340  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:21:32.340  3615  3688 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-15 15:21:32.341  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.343  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.344  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.344  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:32.344  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.344  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@596bbc8 added. We now have 3 listener(s)
,07-15 15:21:32.345  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-15 15:21:32.345  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.345  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.345  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.346  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3151461 added. We now have 10 listener(s)
07-15 15:21:32.346  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.346  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:21:32.346  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.346  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.346  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.346  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.346  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd76ee5 removed from the list
07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.346  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca22dba removed from the list
07-15 15:21:32.346  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.346  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.346  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.346  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.346  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca22dba not in the list
07-15 15:21:32.346  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.346  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.346  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3151461 removed from the list
07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.346  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.346  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.346  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:32.346  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@596bbc8 removed from the list
07-15 15:21:32.347  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:21:32.347  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 added. We now have 2 listener(s)
,07-15 15:21:32.348  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-15 15:21:32.348  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:32.348  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:32.348  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:21:32.348  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 added. We now have 9 listener(s)
,07-15 15:21:32.348  3615  3688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:21:32.349  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.350  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:21:32.350  3615  3688 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:21:32.351  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.353  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:32.354  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.354  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:32.354  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:21:32.354  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-15 15:21:32.354  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:21:32.355  3615  3688 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-15 15:21:32.355  3615  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-15 15:21:32.355  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:21:32.355  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:21:32.355  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:21:32.355  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.355  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.355  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.355  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.355  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.355  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.355  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:21:32.355  3615  3688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 removed from the list
07-15 15:21:32.355  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.355  3615  3688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 removed from the list
07-15 15:21:32.356  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.356  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.356  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.356  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.356  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.356  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.356  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.357  3615  3688 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-15 15:21:32.357  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.357  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.357  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:21:32.357  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.357  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.357  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.357  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.357  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.357  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.357  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
,07-15 15:21:32.357  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.357  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.357  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.357  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.357  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.357  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.357  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-15 15:21:32.359  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-15 15:21:32.359  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.359  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.359  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.359  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.359  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.359  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.359  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.360  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.360  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.360  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.360  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.360  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.360  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.360  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.360  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.360  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.360  3615  3688 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:21:32.361  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.364  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:32.365  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.365  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:32.365  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.365  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:21:32.365  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.365  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.366  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.368  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:32.369  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:21:32.369  3615  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-15 15:21:32.369  3615  3688 I io.jxcore.node.ConnectionHelper: start: OK
07-15 15:21:32.371  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.371  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.371  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.371  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.371  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.371  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:21:32.371  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
,07-15 15:21:32.371  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.371  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.371  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.371  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.371  3615  3688 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:21:32.372  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.375  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.376  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.376  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:32.376  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.376  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-15 15:21:32.377  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.378  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.379  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:21:32.379  3615  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:21:32.379  3615  3688 I io.jxcore.node.ConnectionHelper: start: OK
,07-15 15:21:32.380  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:21:32.380  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.380  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.380  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:21:32.380  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.380  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:21:32.380  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.380  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.380  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.380  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:21:32.380  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.381  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:21:32.381  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.381  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:21:32.381  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.382  3615  3688 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:21:32.383  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:32.385  3615  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:21:32.387  3615  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:21:32.387  3615  3688 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:21:32.387  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:21:32.387  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:21:32.387  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.387  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.387  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.388  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:32.390  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:21:32.390  3615  3688 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:21:32.390  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
07-15 15:21:32.390  3615  3688 I io.jxcore.node.ConnectionHelper: start: OK
,07-15 15:21:32.390  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.390  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.390  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.391  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.391  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.391  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.391  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.391  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.391  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:21:32.391  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.391  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.391  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.391  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.391  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.391  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:21:32.392  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.392  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.392  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.393  3615  3688 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-15 15:21:32.394  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.394  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.394  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.394  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.394  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.394  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.394  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.394  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.394  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.394  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.394  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.394  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.394  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.394  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.394  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.394  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.395  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-15 15:21:32.395  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.395  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.395  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.395  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.395  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.395  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.395  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.395  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.395  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.395  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.395  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.395  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.395  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.395  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.395  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.395  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.396  3615  3688 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-15 15:21:32.396  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.396  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.396  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.396  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.396  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.396  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.396  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.396  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.396  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.396  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.396  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.396  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.397  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.397  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.397  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.397  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.397  3615  3688 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-15 15:21:32.397  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.397  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.397  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.397  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.397  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.397  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.397  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.397  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.397  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.398  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.398  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.398  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.398  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.398  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.398  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.398  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.398  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:21:32.398  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:21:32.398  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:21:32.398  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:21:32.399  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:21:32.399  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-15 15:21:32.399  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:21:32.399  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.399  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.399  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.399  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.399  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.399  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.399  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.399  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
,07-15 15:21:32.399  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.399  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.399  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.399  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.399  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.399  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.399  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.400  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:21:32.400  3615  3688 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-15 15:21:32.400  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-15 15:21:32.401  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:21:32.401  3615  3688 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-15 15:21:32.401  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-15 15:21:32.402  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-15 15:21:32.402  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-15 15:21:32.403  3615  3688 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:21:32.403  3615  3688 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-15 15:21:32.403  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-15 15:21:32.403  3615  3688 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:21:32.403  3615  3688 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-15 15:21:32.404  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:21:32.404  3615  3688 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:21:32.404  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-15 15:21:32.406  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,07-15 15:21:32.406  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,07-15 15:21:32.406  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-15 15:21:32.407  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-15 15:21:32.407  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-15 15:21:32.407  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-15 15:21:32.408  3615  3688 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:21:32.408  3615  3688 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-15 15:21:32.408  3615  4356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
07-15 15:21:32.408  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:21:32.408  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.408  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.409  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.409  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.409  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.409  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.410  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.410  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.410  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.410  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.410  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.410  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.410  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.410  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.410  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.410  3615  4356 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:21:32.411  3615  3688 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-15 15:21:32.411  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.411  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.411  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.411  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.411  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.411  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.411  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.411  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.411  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.411  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.411  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.411  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.411  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.412  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:21:32.412  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.412  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.412  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.412  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.412  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.412  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.413  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.413  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.413  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.413  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.413  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.413  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.413  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.413  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.413  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.413  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.413  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.413  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.413  3615  3688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,07-15 15:21:32.414  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:21:32.414  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:21:32.414  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.414  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:21:32.414  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:32.414  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.414  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.414  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:21:32.414  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.414  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.414  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.414  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.414  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.414  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.414  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:21:32.414  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.415  3615  3688 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-15 15:21:32.415  3615  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-15 15:21:32.415  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-15 15:21:32.415  3615  3688 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,07-15 15:21:32.415  3615  3688 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-15 15:21:32.415  3615  3688 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-15 15:21:32.415  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:21:32.415  3615  3688 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-15 15:21:32.415  3615  3688 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-15 15:21:32.415  3615  3688 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-15 15:21:32.415  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:21:32.416  3615  3688 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,07-15 15:21:32.416  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.416  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.416  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.416  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.416  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.416  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.416  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.416  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.416  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.416  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.416  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.416  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.416  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.416  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.416  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.416  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.417  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.417  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.417  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.417  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.417  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.417  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.417  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.417  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.417  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.417  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.417  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.417  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.417  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.417  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.417  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.417  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.417  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.417  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.417  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.417  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.417  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.417  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.417  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.417  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.417  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.418  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.418  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.418  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.418  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.418  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.418  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.419  3615  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-15 15:21:32.419  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.419  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-15 15:21:32.420  3615  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-15 15:21:32.420  3615  3688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-15 15:21:32.421  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-15 15:21:32.421  3615  3615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-15 15:21:32.421  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.421  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:21:32.421  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-15 15:21:32.421  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-15 15:21:32.421  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-15 15:21:32.421  3615  4358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-15 15:21:32.421  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.421  3615  4358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-15 15:21:32.421  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.421  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.421  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-15 15:21:32.421  3615  3688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:21:32.421  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:21:32.421  3615  3615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-15 15:21:32.421  3615  3615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-15 15:21:32.421  3615  3615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-15 15:21:32.421  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.421  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.422  3615  3688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:21:32.422  3615  3615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:21:32.422  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.422  3615  3615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.422  3615  3615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.422  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.422  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.422  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.422  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.422  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.422  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.422  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.422  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.422  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.422  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.422  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.422  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.424  3615  3615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:21:32.424  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:21:32.425  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.425  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.425  3615  3615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:21:32.425  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.425  3615  3615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:32.425  3615  3615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:21:32.426  3615  3688 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-15 15:21:32.426  3615  3688 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-15 15:21:32.426  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:21:32.426  3615  3688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:21:32.426  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.426  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.426  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.426  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.426  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.426  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.426  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.426  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.427  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.427  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.427  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.427  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:21:32.435  3615  3615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:21:32.435  3615  3688 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:21:32.435  3615  3615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:21:32.436  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.436  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.436  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.438  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.438  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.438  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.438  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.438  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.438  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.439  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.439  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.439  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.439  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.439  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.439  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.439  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.439  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.439  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.439  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.439  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.439  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.439  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.439  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.439  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.439  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.439  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.439  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.439  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.439  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.439  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.439  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.439  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.439  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.439  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.439  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.440  3615  3688 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-15 15:21:32.440  3615  3688 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-15 15:21:32.440  3615  3615 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-15 15:21:32.444  3615  3688 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-15 15:21:32.444  3615  3688 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:21:32.444  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.444  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.444  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.444  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.444  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.444  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.444  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.444  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.444  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.444  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.444  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.444  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.444  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.444  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.444  3615  3688 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-15 15:21:32.444  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.444  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.444  3615  3688 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:21:32.444  3615  3688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:21:32.444  3615  3688 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:21:32.444  3615  3688 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:32.444  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.444  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.444  3615  3688 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@356b86 not in the list
07-15 15:21:32.444  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.445  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.445  3615  3688 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:32.445  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.445  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.445  3615  3688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:32.445  3615  3688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:32.445  3615  3688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:32.445  3615  3688 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25cc47 not in the list
07-15 15:21:32.445  3615  3688 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 85
07-15 15:21:32.445  3615  3688 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 85
07-15 15:21:32.445  3615  3688 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-15 15:21:32.445  3615  3688 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-15 15:21:32.445  3615  3688 D com.test.thalitest.ThaliTestRunner: Total duration: 21360 ms
07-15 15:21:32.447  3615  3688 I jxcore-log: true
07-15 15:21:32.447  3615  3688 I jxcore-log: 
07-15 15:21:32.447  3615  3688 I jxcore-log: Total number of executed tests:  85
07-15 15:21:32.447  3615  3688 I jxcore-log: 
07-15 15:21:32.447  3615  3688 I jxcore-log: Number of passed tests:  85
07-15 15:21:32.447  3615  3688 I jxcore-log: 
07-15 15:21:32.448  3615  3688 I jxcore-log: Number of failed tests:  0
07-15 15:21:32.448  3615  3688 I jxcore-log: 
07-15 15:21:32.448  3615  3688 I jxcore-log: Number of ignored tests:  0
07-15 15:21:32.448  3615  3688 I jxcore-log: 
07-15 15:21:32.448  3615  3688 I jxcore-log: Total duration:  21360
07-15 15:21:32.448  3615  3688 I jxcore-log: 
07-15 15:21:32.449  3615  3688 I jxcore-log: My device name is: LGE-Nexus 5
07-15 15:21:32.449  3615  3688 I jxcore-log: 
07-15 15:21:32.454  1561  4238 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: java.io.IOException: Not connected
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:32.455  1561  4238 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:33.446  4180  4212 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-15 15:21:33.493  1561  4238 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-15 15:21:33.493  1561  4238 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: java.io.IOException: Not connected
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:21:33.493  1561  4238 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:33.587  1561  4278 D BluetoothAdapter: stopLeScan()
,07-15 15:21:33.588  1561  4278 D BluetoothAdapter: STATE_ON
07-15 15:21:33.588  4180  4191 D BtGatt.GattService: stopScan() - queue size =1
07-15 15:21:33.588  4180  4219 D BtGatt.ScanManager: stop scan
07-15 15:21:33.589  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-15 15:21:33.589  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-15 15:21:33.589  4180  4219 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-15 15:21:33.589  4180  4190 D BtGatt.GattService: unregisterClient() - clientIf=5
07-15 15:21:33.589  1561  4278 I BeaconBle: Scan : No clients left, canceling alarm.
,07-15 15:21:36.529  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-15 15:21:36.529  3615  3688 I jxcore-log: 
,07-15 15:21:36.596  1561  4271 I BeaconBle: Scan : No clients left, canceling alarm.
,07-15 15:21:36.931  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-15 15:21:36.931  3615  3688 I jxcore-log: 
,07-15 15:21:36.953  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-15 15:21:36.953  3615  3688 I jxcore-log: 
,07-15 15:21:36.957  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-15 15:21:36.957  3615  3688 I jxcore-log: 
,07-15 15:21:36.973  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-15 15:21:36.973  3615  3688 I jxcore-log: 
,07-15 15:21:36.976  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-15 15:21:36.976  3615  3688 I jxcore-log: 
,07-15 15:21:37.053   788   892 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 9, 10 -> obsolete
,07-15 15:21:37.534  4180  4231 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,07-15 15:21:37.535  4180  4235 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,07-15 15:21:37.535  3615  4356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 426)
,07-15 15:21:37.535  3615  4356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 426)
07-15 15:21:37.535  3615  4356 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 426)
07-15 15:21:37.535  3615  4356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 426
07-15 15:21:37.535  3615  4356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
,07-15 15:21:37.536  3615  3615 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
07-15 15:21:37.536  3615  3615 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
07-15 15:21:37.536  3615  3615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:21:37.536  3615  3615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:21:37.536  3615  4357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
,07-15 15:21:37.536  3615  4357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 426)
07-15 15:21:37.536  3615  4357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 426)
,07-15 15:21:38.942  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-15 15:21:38.942  3615  3688 I jxcore-log: 
,07-15 15:21:38.953  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-15 15:21:38.953  3615  3688 I jxcore-log: 
,07-15 15:21:38.961  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-15 15:21:38.961  3615  3688 I jxcore-log: 
,07-15 15:21:39.116  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-15 15:21:39.116  3615  3688 I jxcore-log: 
,07-15 15:21:39.839  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-15 15:21:39.839  3615  3688 I jxcore-log: 
,07-15 15:21:39.895  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-15 15:21:39.895  3615  3688 I jxcore-log: 
,07-15 15:21:39.901  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-15 15:21:39.901  3615  3688 I jxcore-log: 
,07-15 15:21:40.102  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-15 15:21:40.102  3615  3688 I jxcore-log: 
,07-15 15:21:40.123  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-15 15:21:40.123  3615  3688 I jxcore-log: 
,07-15 15:21:40.127  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-15 15:21:40.127  3615  3688 I jxcore-log: 
,07-15 15:21:40.133  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-15 15:21:40.133  3615  3688 I jxcore-log: 
,07-15 15:21:40.148  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-15 15:21:40.148  3615  3688 I jxcore-log: 
,07-15 15:21:40.167  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-15 15:21:40.167  3615  3688 I jxcore-log: 
,07-15 15:21:40.254  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-15 15:21:40.254  3615  3688 I jxcore-log: 
,07-15 15:21:40.259  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-15 15:21:40.259  3615  3688 I jxcore-log: 
,07-15 15:21:40.284  3615  3688 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-15 15:21:40.284  3615  3688 I jxcore-log: 
,07-15 15:21:40.293  3615  3688 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-15 15:21:40.295  3615  3688 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-15 15:21:40.295  3615  3688 I jxcore-log: 
,07-15 15:21:40.339  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:21:40.339  3615  3688 I jxcore-log: 
,07-15 15:21:40.339  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:21:40.339  3615  3688 I jxcore-log: 
07-15 15:21:40.340  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.340  3615  3688 I jxcore-log: 
07-15 15:21:40.340  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.340  3615  3688 I jxcore-log: 
07-15 15:21:40.342  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.342  3615  3688 I jxcore-log: 
,07-15 15:21:40.343  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.343  3615  3688 I jxcore-log: 
,07-15 15:21:40.344  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.344  3615  3688 I jxcore-log: 
,07-15 15:21:40.344  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.344  3615  3688 I jxcore-log: 
07-15 15:21:40.345  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:21:40.345  3615  3688 I jxcore-log: 
07-15 15:21:40.345  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:21:40.345  3615  3688 I jxcore-log: 
07-15 15:21:40.346  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.346  3615  3688 I jxcore-log: 
,07-15 15:21:40.346  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.346  3615  3688 I jxcore-log: 
,07-15 15:21:40.347  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.347  3615  3688 I jxcore-log: 
07-15 15:21:40.347  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.347  3615  3688 I jxcore-log: 
07-15 15:21:40.348  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.348  3615  3688 I jxcore-log: 
07-15 15:21:40.348  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.348  3615  3688 I jxcore-log: 
,07-15 15:21:40.348  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.348  3615  3688 I jxcore-log: 
07-15 15:21:40.349  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:21:40.349  3615  3688 I jxcore-log: 
07-15 15:21:40.349  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.349  3615  3688 I jxcore-log: 
07-15 15:21:40.350  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.350  3615  3688 I jxcore-log: 
,07-15 15:21:40.350  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.350  3615  3688 I jxcore-log: 
07-15 15:21:40.350  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.350  3615  3688 I jxcore-log: 
07-15 15:21:40.351  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.351  3615  3688 I jxcore-log: 
07-15 15:21:40.351  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.351  3615  3688 I jxcore-log: 
,07-15 15:21:40.352  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.352  3615  3688 I jxcore-log: 
07-15 15:21:40.352  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.352  3615  3688 I jxcore-log: 
07-15 15:21:40.352  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.352  3615  3688 I jxcore-log: 
07-15 15:21:40.353  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.353  3615  3688 I jxcore-log: 
,07-15 15:21:40.353  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:21:40.353  3615  3688 I jxcore-log: 
07-15 15:21:40.354  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-15 15:21:40.354  3615  3688 I jxcore-log: 
07-15 15:21:40.355  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:21:40.355  3615  3688 I jxcore-log: 
07-15 15:21:40.355  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-15 15:21:40.355  3615  3688 I jxcore-log: 
,07-15 15:21:46.832   788   811 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...,
,07-15 15:21:46.860   788   811 I PowerManagerService: Sleeping (uid 1000)...
07-15 15:21:46.871   191   516 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1314 us)
,07-15 15:21:46.898  3615  3615 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-15 15:21:46.898  3615  3615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-15 15:21:46.905   788   811 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-15 15:21:46.952  3615  3615 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@da23683 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bdadb55, 16908290=android.view.AbsSavedState$1@bdadb55}, android:focusedViewId=100}]}]
,07-15 15:21:46.953  3615  3615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-15 15:21:46.953  3615  3615 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-15 15:21:46.953  3615  3615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-15 15:21:47.264   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:21:47.451   788   811 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-15 15:21:47.468   788   811 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-15 15:21:47.473   191   191 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,07-15 15:21:47.474   191   191 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-15 15:21:47.475   788   809 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-15 15:21:47.765   191   191 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-15 15:21:47.767   788   908 D SurfaceControl: Excessive delay in setPowerMode(): 294ms
,07-15 15:21:47.769  1803  1821 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
07-15 15:21:47.779   198   198 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-15 15:21:47.785   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:21:47.787   788   892 E native  : do suspend false
,07-15 15:21:47.791   788   892 D WifiConfigStore: No blacklist allowed without epno enabled
,07-15 15:21:47.827   788   892 E native  : do suspend true
,07-15 15:21:47.843   198  1066 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-15 15:21:47.850  1239  1239 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-15 15:21:48.288   788   892 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 13, 14 -> obsolete
,07-15 15:21:48.601   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
,07-15 15:21:48.723   788   892 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-15 15:21:48.740   788   892 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-15 15:21:48.740   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:48.749   788   892 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-15 15:21:48.780   788   892 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-15 15:21:48.782  4334  4334 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-15 15:21:48.863  4334  4334 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-15 15:21:48.897  4334  4334 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-15 15:21:48.897  4334  4334 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-15 15:21:48.898   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-15 15:21:48.908   788   892 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-15 15:21:48.908   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:21:48.908   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-15 15:21:48.916   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:21:48.926   194   633 D CommandListener: Setting iface cfg
,07-15 15:21:48.930   788   892 D WifiStateMachine: Start Dhcp Watchdog 3
,07-15 15:21:48.933   788   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-15 15:21:48.940   788  4426 D DhcpClient: Receive thread started
,07-15 15:21:49.012   788   892 E native  : do suspend false
,07-15 15:21:49.026   788  4425 D DhcpClient: Broadcasting DHCPDISCOVER
,07-15 15:21:49.036   788  4426 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172768, domain null
,07-15 15:21:49.036   788  4425 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172768 seconds
07-15 15:21:49.039   788  4425 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-15 15:21:49.047   788  4426 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-15 15:21:49.048   788  4425 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-15 15:21:49.051   194   633 D CommandListener: Setting iface cfg
07-15 15:21:49.058   788   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
07-15 15:21:49.069   788   892 E native  : do suspend true
07-15 15:21:49.077   788  4425 D DhcpClient: Scheduling renewal in 86399s
,07-15 15:21:49.087   788   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-15 15:21:49.087   788   892 D WifiConfigStore: No blacklist allowed without epno enabled
07-15 15:21:49.092   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-15 15:21:49.094   788   894 D ConnectivityService: Adding iface wlan0 to network 102
,07-15 15:21:49.097   788   892 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-15 15:21:49.137   788   894 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-15 15:21:49.138   788   894 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-15 15:21:49.138   788   894 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-15 15:21:49.139   788   894 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-15 15:21:49.140   788   894 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-15 15:21:49.152   788   894 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-15 15:21:49.158   788   894 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-15 15:21:49.158   788   894 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-15 15:21:49.158   788   892 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-15 15:21:49.158   788   894 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-15 15:21:49.158   788   894 D ConnectivityService:    accepting network in place of null
07-15 15:21:49.158   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:21:49.159   788   894 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-15 15:21:49.168   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153612, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:21:49.205   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:49.229   788  4423 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:812::200e
,07-15 15:21:49.231   194   633 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-15 15:21:49.234   788   894 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-15 15:21:49.234   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-15 15:21:49.235   788   894 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-15 15:21:49.236   788   808 D Tethering: MasterInitialState.processMessage what=3
,07-15 15:21:49.239  3826  3826 E SetupWizard: tickleCheckinService called after completing user setup
,07-15 15:21:49.242  3615  3615 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-15 15:21:49.243  1386  1386 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:49.250  3615  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:21:49.253  3615  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:21:49.253  3615  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:21:49.253  3615  3688 I jxcore-log: 
,07-15 15:21:49.240  2555  2555 W ChromiumNet: type=1400 audit(0.0:10): avc: denied { ioctl } for path="socket:[23755]" dev="sockfs" ino=23755 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-15 15:21:49.277  1571  1571 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-15 15:21:49.280  1571  1571 V Herrevad: NQAS connected
,07-15 15:21:49.283  1571  2896 I iu.UploadsManager: num queued entries: 0
,07-15 15:21:49.284  1571  2896 I iu.UploadsManager: num updated entries: 0
07-15 15:21:49.288  1571  2896 I iu.SyncManager: NEXT; no task
,07-15 15:21:49.293   788  4423 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jul 2016 13:21:49 GMT], X-Android-Received-Millis=[1468588909292], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468588909263]}
,07-15 15:21:49.293   788   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-15 15:21:49.293   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-15 15:21:49.294   788   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-15 15:21:49.296   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-15 15:21:49.326  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:49.328  1571  1644 W Herrevad: Invalid mccmnc 
,07-15 15:21:49.441   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c8a030
07-15 15:21:49.441   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,07-15 15:21:49.442   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
07-15 15:21:49.442   192   494 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229453008)
,07-15 15:21:49.512   192   494 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,07-15 15:21:49.512   192   494 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-15 15:21:49.512   192   494 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229453008) wakelock released: 1, error no: 0
07-15 15:21:49.512   192   494 I rmt_storage: 
,07-15 15:21:49.514   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c8a030
,07-15 15:21:49.526  1561  1561 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-15 15:21:49.564  1571  1571 I GCM     : Message from null null
,07-15 15:21:49.565  1571  1571 E GCM     : Dropping message from null
,07-15 15:21:49.618  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:21:49.618  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:21:49.664  1561  4472 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-15 15:21:49.665  1561  4467 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-15 15:21:49.681  1561  4472 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-15 15:21:49.682  1561  4467 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-15 15:21:49.698  1561  4472 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-15 15:21:49.698  1561  4467 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-15 15:21:49.698  1561  4467 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-15 15:21:49.712  1561  4467 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-15 15:21:50.080  1561  4465 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-15 15:21:50.087  1561  4465 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-15 15:21:52.027   788  1325 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1571 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-15 15:21:52.081  1571  4494 W DriveInitializer: Background init thread started
,07-15 15:21:52.171  1571  4494 W DriveInitializer: Background init thread ended
,07-15 15:21:57.158   788   894 D ConnectivityService: handlePromptUnvalidated 102
,07-15 15:22:02.267   788   892 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,07-15 15:22:46.904   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:22:51.243  1561  1703 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-15 15:24:02.865   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287308, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:24:31.704   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=316147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:24:40.422  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:24:40.459  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-15 15:24:40.460  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:24:45.494   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329937, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:24:59.822  1561  3026 V NativeCrypto: SSL shutdown failed: ssl=0xab17d000: I/O error during system call, Connection timed out
,07-15 15:25:02.705  1571  3112 V NativeCrypto: SSL shutdown failed: ssl=0x9340d400: I/O error during system call, Connection timed out
,07-15 15:25:09.544   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=353987, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:25:20.107  1278  1278 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.onStartJob(142): JobScheduler invoked, loading libraries.
,07-15 15:25:20.208  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.j.a(469): Request install of com.google.android.youtube v=112559134 pri=3 for auto_update
,07-15 15:25:20.216  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1258): Installer kick - starting com.google.android.youtube
,07-15 15:25:20.221  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.j.a(469): Request install of com.google.earth v=161661104 pri=3 for auto_update
,07-15 15:25:20.224  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:20.226  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.j.a(469): Request install of com.google.android.calendar v=2015187843 pri=3 for auto_update
,07-15 15:25:20.228  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.y.b(204): Created session 1195116043 for com.google.android.youtube
,07-15 15:25:20.229  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-15 15:25:20.231  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-15 15:25:20.231  1278  1278 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.a(186): auto-updates finished successfully.
,07-15 15:25:20.254  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.y.b(204): Created session 1302477671 for com.google.earth
,07-15 15:25:20.265  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.y.b(204): Created session 201028662 for com.google.android.calendar
,07-15 15:25:20.503  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.ah.run(127): Session for com.google.android.youtube already exists, skipping creation
,07-15 15:25:20.658  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.ai.onPostExecute(5001): Downloading patch for com.google.android.youtube (com.google.android.youtube)
,07-15 15:25:20.662  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(256): Duplicate state set for 'com.google.android.youtube' (0). Already in that state
,07-15 15:25:20.662  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.youtube added to DownloadQueue
,07-15 15:25:20.664  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.youtube from 0 to 1.
,07-15 15:25:20.666   199   199 I installd: free_cache(6130776) avail 10597687296
,07-15 15:25:20.671  1278  1278 I Finsky  : [1] com.google.android.finsky.download.ai.run(5554): Download com.google.android.youtube starting
,07-15 15:25:20.698  1278  1539 I Finsky  : [60] com.google.android.finsky.download.ae.a(1567): Enqueued com.google.android.youtube as content://downloads/my_downloads/984
,07-15 15:25:20.700  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.youtube from 1 to 2.
,07-15 15:25:20.701  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.a(632): com.google.android.youtube: onStart
,07-15 15:25:20.736   943  4537 D DownloadManager: [984] Starting
,07-15 15:25:20.749  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.youtube: onProgress 0/-1 Status: 192.
,07-15 15:25:20.753   943  4537 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-15 15:25:23.043   943  4537 D DownloadManager: [984] Finished with status SUCCESS
,07-15 15:25:23.079  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.youtube: onProgress 6130776/6130776 Status: 200.
,07-15 15:25:23.088  1278  1278 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(46): Intent received at DownloadBroadcastReceiver
,07-15 15:25:23.116  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.youtube from 2 to 3.
,07-15 15:25:23.117  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(600): com.google.android.youtube: onComplete
07-15 15:25:23.117  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.i(341): Download com.google.android.youtube removed from DownloadQueue
07-15 15:25:23.118   199   199 I installd: free_cache(0) avail 10591555584
,07-15 15:25:23.121  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.x.c(36121): Prepare to patch com.google.android.youtube (com.google.android.youtube) from content://downloads/my_downloads/984 format 3
,07-15 15:25:23.129   199   199 I installd: free_cache(17823252) avail 10591555584
,07-15 15:25:24.921  1278  1560 I Finsky  : [73] com.google.android.finsky.receivers.ab.a(3193): Patch apply task for com.google.android.youtube (com.google.android.youtube) (format 3) completed in 1800 ms
,07-15 15:25:24.925  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.ab.onPostExecute(4243): Successfully applied patch to update com.google.android.youtube (com.google.android.youtube)
,07-15 15:25:24.928  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.x.c(42122): Begin install of com.google.android.youtube
,07-15 15:25:24.930   943   965 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/downloadfile.bin via provider delete
,07-15 15:25:25.283   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=369727, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:25:26.032   788   815 I ActivityManager: Start proc 4569:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,07-15 15:25:26.073  1278  1278 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2102): Skipping verification because own installation
,07-15 15:25:27.291   788   815 I PackageManager.DexOptimizer: Running dexopt (dex2oat) on: /data/app/vmdl1195116043.tmp/base.apk pkg=com.google.android.youtube isa=arm vmSafeMode=false debuggable=false oatDir = /data/app/vmdl1195116043.tmp/oat bootComplete=true
,07-15 15:25:27.327  4591  4591 I dex2oat : Starting dex2oat.
,07-15 15:25:31.096  4591  4591 W dex2oat : No verified method for method calling String.<init>: void android.provider.SearchRecentSuggestions.<init>(android.content.Context, java.lang.String, int)
,07-15 15:25:38.474  4591  4591 I dex2oat : dex2oat took 11.147s (threads: 4) arena alloc=11MB java alloc=16MB native alloc=66MB free=5MB
,07-15 15:25:38.499   788   804 I ActivityManager: Force stopping com.google.android.youtube appid=10071 user=-1: replace sys pkg
,07-15 15:25:38.504   788   815 W PackageManager: Trying to update system app code path from /data/app/com.google.android.youtube-2 to /data/app/com.google.android.youtube-1
,07-15 15:25:38.505   788   804 I ActivityManager: Force stopping com.google.android.youtube appid=10071 user=-1: replace pkg
07-15 15:25:38.506   788   815 W PackageManager: Code path for com.google.android.youtube changing from /data/app/com.google.android.youtube-2 to /data/app/com.google.android.youtube-1
,07-15 15:25:38.506   788   815 W PackageManager: Resource path for com.google.android.youtube changing from /data/app/com.google.android.youtube-2 to /data/app/com.google.android.youtube-1
,07-15 15:25:38.579   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
,07-15 15:25:38.616   788   815 W PackageManager: Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0x38583ec5)
,07-15 15:25:38.674   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
,07-15 15:25:38.708   788   799 I ActivityManager: Killing 2869:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,07-15 15:25:38.712   788   815 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
07-15 15:25:38.713   788   815 I art     : Starting a blocking GC Explicit
,07-15 15:25:38.769   788   815 I art     : Explicit concurrent mark sweep GC freed 130333(6MB) AllocSpace objects, 8(928KB) LOS objects, 33% free, 25MB/38MB, paused 938us total 55.351ms
,07-15 15:25:38.794   788   815 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.google.android.youtube-2/base.apk, retcode=-1
,07-15 15:25:38.795   199   199 E installd: Couldn't opendir /data/app/vmdl1195116043.tmp: No such file or directory
,07-15 15:25:38.797   788   815 I ActivityManager: Force stopping com.google.android.youtube appid=10071 user=0: pkg removed
,07-15 15:25:38.808   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:38.808   788   788 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-15 15:25:38.809  4180  4180 D BluetoothMapAppObserver: onReceive
,07-15 15:25:38.810  4180  4180 D BluetoothMapAppObserver: The removed package is: com.google.android.youtube
,07-15 15:25:38.838   788  1000 I ActivityManager: Start proc 4616:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
07-15 15:25:38.847  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-15 15:25:38.847  1319  1319 D CarrierServiceBindHelper: mHandler: 3
,07-15 15:25:38.869  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2142): Successful install of com.google.android.youtube
,07-15 15:25:38.880  4180  4180 D BluetoothMapAppObserver: onReceive
,07-15 15:25:38.880  4180  4180 D BluetoothMapAppObserver: The installed package is: com.google.android.youtube
07-15 15:25:38.881  4180  4180 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-15 15:25:38.881  4180  4180 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:25:38.881   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:38.890   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:38.892  4616  4616 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-15 15:25:38.925   788   948 I ActivityManager: Start proc 4640:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,07-15 15:25:38.930  1278  1278 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(277): Wear auto install disabled for package com.google.android.youtube
,07-15 15:25:38.933  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1258): Installer kick - starting com.google.earth
,07-15 15:25:38.943  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:38.948  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_ADDED
,07-15 15:25:38.948  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REPLACED
07-15 15:25:38.948  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:38.948  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:38.948  1319  1319 D CarrierConfigLoader: mHandler: 9 phoneId: 0
,07-15 15:25:38.955   788  1322 I ActivityManager: Killing 3027:com.google.android.apps.docs.editors.slides/u0a81 (adj 15): empty #17
,07-15 15:25:38.971  4640  4640 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,07-15 15:25:38.974  4640  4640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-15 15:25:39.034  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:39.035  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:39.047   788   798 I ActivityManager: Start proc 4657:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,07-15 15:25:39.054   788  1366 I ActivityManager: Killing 3541:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,07-15 15:25:39.226  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.ah.run(127): Session for com.google.earth already exists, skipping creation
,07-15 15:25:39.279  4657  4674 I GAv4    : Google Analytics 8.4.87 is starting up. To enable debug logging on a device run:
07-15 15:25:39.279  4657  4674 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-15 15:25:39.279  4657  4674 I GAv4    :   adb logcat -s GAv4
,07-15 15:25:39.299  4657  4674 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:25:39.302  4657  4674 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:25:39.310  4657  4680 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:25:39.424  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.ai.onPostExecute(5001): Downloading patch for com.google.earth (com.google.earth)
,07-15 15:25:39.424  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(256): Duplicate state set for 'com.google.earth' (0). Already in that state
07-15 15:25:39.424  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.earth added to DownloadQueue
,07-15 15:25:39.428  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.earth from 0 to 1.
,07-15 15:25:39.429   199   199 I installd: free_cache(4332890) avail 10597949440
,07-15 15:25:39.433  1278  1278 I Finsky  : [1] com.google.android.finsky.download.ai.run(5554): Download com.google.earth starting
,07-15 15:25:39.460   788  1000 I ActivityManager: Killing 1386:com.google.android.googlequicksearchbox:search/u0a19 (adj 15): empty #17
,07-15 15:25:39.475   788   948 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ], android.os.BinderProxy@85a6e5d)
,07-15 15:25:39.475   788   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-15 15:25:39.475   788   894 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-15 15:25:39.475   788   893 D WifiService: Client connection lost with reason: 4
,07-15 15:25:39.497  1278  1539 I Finsky  : [60] com.google.android.finsky.download.ae.a(1567): Enqueued com.google.earth as content://downloads/my_downloads/985
,07-15 15:25:39.497  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.earth from 1 to 2.
07-15 15:25:39.497  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.a(632): com.google.earth: onStart
,07-15 15:25:39.508  1571  4688 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.youtube
,07-15 15:25:39.509  1561  1561 E NetworkScheduler.SR: Invalid parameter app
,07-15 15:25:39.509  1561  1561 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:25:39.514  1571  4688 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.youtube
,07-15 15:25:39.516  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.earth: onProgress 0/-1 Status: 190.
,07-15 15:25:39.521  1571  1644 E Drive.UninstallOperation: Package still installed com.google.android.youtube
,07-15 15:25:39.538   788   799 I ActivityManager: Start proc 4693:com.google.android.googlequicksearchbox:search/u0a19 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.search.core.icingsync.IcingCorporaChangedReceiver
,07-15 15:25:39.546  1571  4688 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.youtube
,07-15 15:25:39.558  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.earth: onProgress 0/-1 Status: 192.
,07-15 15:25:39.562  1571  4704 D gH_CompatibleDatabase: Open irg@6090d3b, release reference: 1
,07-15 15:25:39.569  1571  4704 D gH_CompatibleDatabase: Acquire reference of irg@6090d3b: 2
07-15 15:25:39.570  1571  4704 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.android.youtube.
,07-15 15:25:39.570  1571  4704 D gH_CompatibleDatabase: Release reference of irg@6090d3b: 1
07-15 15:25:39.570  1571  4704 D gH_CompatibleDatabase: Open irg@4de01b1, release reference: 1
07-15 15:25:39.571   943  4699 D DownloadManager: [985] Starting
,07-15 15:25:39.583  1571  4704 D gH_CompatibleDatabase: Acquire reference of irg@4de01b1: 2
,07-15 15:25:39.583  1571  4704 D gH_CompatibleDatabase: Release reference of irg@4de01b1: 1
07-15 15:25:39.583  1571  4704 D gH_CompatibleDatabase: Open irg@6f0d696, release reference: 1
,07-15 15:25:39.588  1571  4704 D gH_CompatibleDatabase: Acquire reference of irg@6f0d696: 2
07-15 15:25:39.589  1571  4704 D gH_CompatibleDatabase: Release reference of irg@6f0d696: 1
07-15 15:25:39.590  1571  4704 D gH_CompatibleDatabase: Close irg@6090d3b, release reference: 0
07-15 15:25:39.590  1571  4704 D gH_CompatibleDatabase: Close irg@4de01b1, release reference: 0
07-15 15:25:39.590  1571  4704 D gH_CompatibleDatabase: Close irg@6f0d696, release reference: 0
,07-15 15:25:39.743   788   798 I ActivityManager: Start proc 4716:com.quickoffice.android/u0a65 for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver
,07-15 15:25:39.812  4716  4716 W Quickoffice: Cleanup of storage: done
,07-15 15:25:39.817  4716  4730 D com.google.android.apps.docs.quickoffice.X: Loading recent documents list
,07-15 15:25:39.819  4716  4731 D Quickoffice: The number of lines present in  /proc/mount 22
,07-15 15:25:39.821  4716  4731 D Quickoffice: Parsing the storagedefinition.xml.
,07-15 15:25:39.827  4716  4731 D Quickoffice: # of Storagedefinitions - 35
07-15 15:25:39.827  4716  4731 D Quickoffice: The # of storage definitions available - 35
07-15 15:25:39.827  4716  4731 D Quickoffice: Processing mountline rootfs / rootfs ro,seclabel,relatime 0 0
,07-15 15:25:39.827  4716  4731 D Quickoffice: Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
,07-15 15:25:39.827  4716  4731 D Quickoffice: Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
07-15 15:25:39.827  4716  4731 D Quickoffice: Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
07-15 15:25:39.827  4716  4731 D Quickoffice: Processing mountline proc /proc proc rw,relatime 0 0
07-15 15:25:39.828  4716  4731 D Quickoffice: Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
07-15 15:25:39.828  4716  4731 D Quickoffice: Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
07-15 15:25:39.828  4716  4731 D Quickoffice: Processing mountline debugfs /sys/kernel/debug debugfs rw,seclabel,relatime 0 0
07-15 15:25:39.828  4716  4731 D Quickoffice: Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
07-15 15:25:39.828  4716  4731 D Quickoffice: Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
,07-15 15:25:39.828  4716  4731 D Quickoffice: Processing mountline tmpfs /mnt tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
07-15 15:25:39.829  4716  4731 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/default/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-15 15:25:39.829  4716  4731 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/read/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-15 15:25:39.829  4716  4731 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/write/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-15 15:25:39.829  4716  4731 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,relatime 0 0
07-15 15:25:39.829  4716  4731 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
07-15 15:25:39.829  4716  4731 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
07-15 15:25:39.830  4716  4731 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
07-15 15:25:39.830  4716  4731 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,context=u:object_r:firmware_file:s0,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
,07-15 15:25:39.830  4716  4731 D Quickoffice: Processing mountline tmpfs /storage tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
07-15 15:25:39.830  4716  4731 D Quickoffice: Processing mountline /dev/fuse /storage/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-15 15:25:39.830  4716  4731 D Quickoffice: Processing mountline tmpfs /storage/self tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
07-15 15:25:39.838  4716  4731 E Quickoffice: An exception occured in getAllMountedStorages method.
07-15 15:25:39.838  4716  4731 E Quickoffice: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.qo.android.filesystem.h.a(com.qo.android.filesystem.StorageDefinition)' on a null object reference
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at com.quickoffice.mx.engine.a.e(AndroidLocalFileSystems.java:432)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at com.quickoffice.mx.engine.a.a(AndroidLocalFileSystems.java:92)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at com.quickoffice.mx.S.b(MxPlugin.java:59)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at com.quickoffice.mx.engine.q.f(MxEngine.java:1225)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at com.quickoffice.mx.engine.q.a(MxEngine.java:1219)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at com.qo.android.b.call(AsyncTask.java:217)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-15 15:25:39.838  4716  4731 E Quickoffice: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:25:39.843  4716  4731 D Quickoffice: The # of mounts identified -  0
07-15 15:25:39.844  4716  4731 D Quickoffice: Failed to get moto storage state.
07-15 15:25:39.853  4716  4731 D Quickoffice: Failed to get moto storage dir.
,07-15 15:25:39.882  4716  4739 D com.google.android.apps.docs.quickoffice.X: Checking validity of 0 items
07-15 15:25:39.900   788  1325 I ActivityManager: Start proc 4740:com.google.android.partnersetup/u0a11 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
07-15 15:25:39.900   788  1325 I ActivityManager: Killing 3478:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,07-15 15:25:39.922  4716  4738 W Quickoffice: Could not load clipboard.
,07-15 15:25:39.937  4716  4752 W Quickoffice: Could not store clipboard.
,07-15 15:25:39.944   788   948 W ActivityManager: No permission grants found for com.quickoffice.android
,07-15 15:25:39.944  4716  4739 D ContentResolverUtil: There are 0 persisted uri permissions.
,07-15 15:25:39.944  4716  4739 D com.google.android.apps.docs.quickoffice.X: 0 items were valid
,07-15 15:25:39.955  4740  4740 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-15 15:25:39.979  1278  1278 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.google.android.youtube
,07-15 15:25:39.981  1571  4704 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.youtube
,07-15 15:25:39.987  1571  1571 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:25:39.990  1571  4687 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-15 15:25:39.991  1571  4704 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.youtube
,07-15 15:25:39.993  1571  1644 D nwp     : Processing package: com.google.android.youtube
,07-15 15:25:39.997   788  1322 I ActivityManager: Killing 4146:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-15 15:25:40.004  1571  1644 D nwe     : Look up (com.google.android.youtube:112559134) returned no result
07-15 15:25:40.004  1571  1644 D nwp     : Starting Hash for package com.google.android.youtube:11.25.59
,07-15 15:25:40.059  1561  4770 D GCM     : GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
07-15 15:25:40.059  1571  4704 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.youtube
,07-15 15:25:40.116  1571  4704 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.youtube
,07-15 15:25:40.121  1571  1571 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:25:40.156  1571  4776 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-15 15:25:40.206  1571  1644 D nwp     : Package com.google.android.youtube's hash: 43a2afb11bc56d804d7a523135b9ff4d8ec923df2856cd9ca195e072789ed2fa
,07-15 15:25:40.208  1571  1644 D nwe     : Look up (com.google.android.youtube:112559134) returned no result
,07-15 15:25:40.211   788  1357 I ActivityManager: Start proc 4783:com.google.android.youtube/u0a71 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-15 15:25:40.211  1561  1561 E NetworkScheduler.SR: Invalid parameter app
,07-15 15:25:40.211  1561  1561 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:25:40.219   788   893 D WifiService: New client listening to asynchronous messages
,07-15 15:25:40.225   788  1325 I ActivityManager: Start proc 4795:com.google.android.apps.cloudprint/u0a32 for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver
,07-15 15:25:40.227  1571  1644 D nwp     : Saved the app info in cache for package:com.google.android.youtube.
,07-15 15:25:40.228  1571  1644 D nwp     : Processing package: com.google.android.youtube
,07-15 15:25:40.245  1571  1644 D GassUtils: Found app info for package com.google.android.youtube:112559134. Hash: 43a2afb11bc56d804d7a523135b9ff4d8ec923df2856cd9ca195e072789ed2fa
,07-15 15:25:40.245  1571  1644 D nwp     : Found info for package com.google.android.youtube in db.
,07-15 15:25:40.316  4693  4781 W ModelDownloadController: Cannot find any speech config location.
07-15 15:25:40.316  4693  4781 W ModelDownloadController: Cannot find any speech config location.
,07-15 15:25:40.330  4693  4774 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.youtube, CONTACTS=MAYBE
,07-15 15:25:40.341  4783  4816 D ChimeraCfgMgr: Reading stored module config
,07-15 15:25:40.349  4783  4814 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-15 15:25:40.381  4783  4814 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-15 15:25:40.381  4783  4814 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-15 15:25:40.386  4783  4814 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-15 15:25:40.409  4783  4816 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000006/n/armeabi
,07-15 15:25:40.410  4783  4816 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-15 15:25:40.419  4783  4814 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-15 15:25:40.422  4783  4816 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-15 15:25:40.433  4783  4816 D DynamitePackage: Instantiated singleton DynamitePackage.
,07-15 15:25:40.436  4783  4816 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,07-15 15:25:40.582  4693  4774 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 250 ms] updated apps [took 250 ms] 
,07-15 15:25:40.739  4783  4783 W InstanceID/Rpc: Found 10007
,07-15 15:25:40.898   788   948 D ConnectivityService: listenForNetwork for Listen from uid/pid:10071/4783 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-15 15:25:40.924   788  1366 I ActivityManager: Killing 3712:com.android.settings/1000 (adj 15): empty #17
,07-15 15:25:40.934   788   893 D WifiService: Client connection lost with reason: 4
,07-15 15:25:40.967   788  1000 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
,07-15 15:25:41.048   943  4699 D DownloadManager: [985] Finished with status SUCCESS
,07-15 15:25:41.120  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.earth: onProgress 4332890/4332890 Status: 200.
,07-15 15:25:41.172  1278  1278 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(46): Intent received at DownloadBroadcastReceiver
,07-15 15:25:41.180  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.earth from 2 to 3.
,07-15 15:25:41.180  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(600): com.google.earth: onComplete
07-15 15:25:41.181  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.i(341): Download com.google.earth removed from DownloadQueue
,07-15 15:25:41.182   199   199 I installd: free_cache(0) avail 10594516992
,07-15 15:25:41.187  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.x.c(36121): Prepare to patch com.google.earth (com.google.earth) from content://downloads/my_downloads/985 format 2
,07-15 15:25:41.207   199   199 I installd: free_cache(9493086) avail 10594516992
,07-15 15:25:41.416  1571  1639 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-15 15:25:41.508  1571  1639 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-15 15:25:41.614  1571  1639 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
,07-15 15:25:41.664  1571  1639 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,07-15 15:25:41.884  1278  1551 I Finsky  : [71] com.google.android.finsky.receivers.ab.a(3193): Patch apply task for com.google.earth (com.google.earth) (format 2) completed in 695 ms
,07-15 15:25:41.885  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.ab.onPostExecute(4243): Successfully applied patch to update com.google.earth (com.google.earth)
,07-15 15:25:41.887  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.x.c(42122): Begin install of com.google.earth
,07-15 15:25:41.892   943  4551 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/downloadfile.bin via provider delete
,07-15 15:25:42.437  1278  1278 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2102): Skipping verification because own installation
,07-15 15:25:42.441   788   815 W PackageParser: Unknown element under <manifest>: supports-gl-texture at /data/app/vmdl1302477671.tmp/base.apk Binary XML file line #25
,07-15 15:25:42.888   788   815 I PackageManager.DexOptimizer: Running dexopt (dex2oat) on: /data/app/vmdl1302477671.tmp/base.apk pkg=com.google.earth isa=arm vmSafeMode=false debuggable=false oatDir = /data/app/vmdl1302477671.tmp/oat bootComplete=true
,07-15 15:25:42.913  4916  4916 I dex2oat : Starting dex2oat.
,07-15 15:25:43.134  4916  4920 W dex2oat : Before Android 4.1, method int android.support.v7.internal.widget.ListViewCompat.lookForSelectablePosition(int, boolean) would have incorrectly overridden the package-private method in android.widget.ListView
,07-15 15:25:44.044  4180  4239 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,07-15 15:25:44.656  4916  4918 W dex2oat : No verified method for method calling String.<init>: void org.json.JSONStringer.<init>(int)
,07-15 15:25:45.156  4916  4920 W dex2oat : No verified method for method calling String.<init>: void android.provider.SearchRecentSuggestions.<init>(android.content.Context, java.lang.String, int)
,07-15 15:25:45.841  4916  4916 I dex2oat : dex2oat took 2.928s (threads: 4) arena alloc=3MB java alloc=4MB native alloc=18MB free=3MB
,07-15 15:25:45.852   788   804 I ActivityManager: Force stopping com.google.earth appid=10044 user=-1: replace sys pkg
,07-15 15:25:45.854   788   815 W PackageManager: Trying to update system app code path from /data/app/com.google.earth-1 to /data/app/com.google.earth-2
,07-15 15:25:45.855   788   804 I ActivityManager: Force stopping com.google.earth appid=10044 user=-1: replace pkg
,07-15 15:25:45.856   788   815 W PackageManager: Code path for com.google.earth changing from /data/app/com.google.earth-1 to /data/app/com.google.earth-2
07-15 15:25:45.856   788   815 W PackageManager: Resource path for com.google.earth changing from /data/app/com.google.earth-1 to /data/app/com.google.earth-2
,07-15 15:25:45.920   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
,07-15 15:25:46.038   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
,07-15 15:25:46.074   788  1367 I ActivityManager: Killing 3826:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,07-15 15:25:46.077   788   815 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
07-15 15:25:46.077   788   815 I art     : Starting a blocking GC Explicit
,07-15 15:25:46.133   788   815 I art     : Explicit concurrent mark sweep GC freed 109530(6MB) AllocSpace objects, 40(1272KB) LOS objects, 33% free, 26MB/39MB, paused 891us total 54.577ms
,07-15 15:25:46.151   788   815 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.google.earth-1/base.apk, retcode=-1
,07-15 15:25:46.151   199   199 E installd: Couldn't opendir /data/app/vmdl1302477671.tmp: No such file or directory
,07-15 15:25:46.152   788  1357 D PackageInstaller: Ignoring abandon after commit relinquished control
07-15 15:25:46.153  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.ak.run(285): Canceling session 1302477671 for com.google.earth
,07-15 15:25:46.153  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2142): Successful install of com.google.earth
,07-15 15:25:46.156   788   815 I ActivityManager: Force stopping com.google.earth appid=10044 user=0: pkg removed
,07-15 15:25:46.170   788   788 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-15 15:25:46.176  4180  4180 D BluetoothMapAppObserver: onReceive
07-15 15:25:46.176  4180  4180 D BluetoothMapAppObserver: The removed package is: com.google.earth
07-15 15:25:46.179   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:46.203   788  1000 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
,07-15 15:25:46.207  4180  4180 D BluetoothMapAppObserver: onReceive
,07-15 15:25:46.207  4180  4180 D BluetoothMapAppObserver: The installed package is: com.google.earth
,07-15 15:25:46.207  4180  4180 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-15 15:25:46.207  4180  4180 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:25:46.209   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:46.216  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-15 15:25:46.222  4640  4640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-15 15:25:46.252   788  1365 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
,07-15 15:25:46.261  1278  1278 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(277): Wear auto install disabled for package com.google.earth
,07-15 15:25:46.261   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:46.265   788  1367 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
,07-15 15:25:46.275  1571  4704 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.earth
,07-15 15:25:46.275  1571  4704 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.earth
07-15 15:25:46.275  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1258): Installer kick - starting com.google.android.calendar
,07-15 15:25:46.281  1571  1639 E Drive.UninstallOperation: Package still installed com.google.earth
,07-15 15:25:46.289  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_ADDED
07-15 15:25:46.289  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:46.289  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REPLACED
07-15 15:25:46.290  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:46.290  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:46.290  1319  1319 D CarrierConfigLoader: mHandler: 9 phoneId: 0
07-15 15:25:46.290  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:46.292  1561  1561 E NetworkScheduler.SR: Invalid parameter app
07-15 15:25:46.292  1561  1561 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:25:46.294  1571  4704 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.earth
,07-15 15:25:46.296  1571  4704 D gH_CompatibleDatabase: Open irg@bf7c28c, release reference: 1
,07-15 15:25:46.299  1571  4704 D gH_CompatibleDatabase: Acquire reference of irg@bf7c28c: 2
,07-15 15:25:46.300  1571  4704 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.earth.
07-15 15:25:46.300  1571  4704 D gH_CompatibleDatabase: Release reference of irg@bf7c28c: 1
,07-15 15:25:46.300  1571  4704 D gH_CompatibleDatabase: Open irg@a0cadd5, release reference: 1
,07-15 15:25:46.303  1571  4704 D gH_CompatibleDatabase: Acquire reference of irg@a0cadd5: 2
07-15 15:25:46.303  1571  4704 D gH_CompatibleDatabase: Release reference of irg@a0cadd5: 1
07-15 15:25:46.303  1571  4704 D gH_CompatibleDatabase: Open irg@c1b19ea, release reference: 1
,07-15 15:25:46.308  1571  4704 D gH_CompatibleDatabase: Acquire reference of irg@c1b19ea: 2
,07-15 15:25:46.308  1571  4704 D gH_CompatibleDatabase: Release reference of irg@c1b19ea: 1
,07-15 15:25:46.309  1571  4704 D gH_CompatibleDatabase: Close irg@bf7c28c, release reference: 0
07-15 15:25:46.309  1571  4704 D gH_CompatibleDatabase: Close irg@a0cadd5, release reference: 0
07-15 15:25:46.309  1571  4704 D gH_CompatibleDatabase: Close irg@c1b19ea, release reference: 0
,07-15 15:25:46.358  1278  1278 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.google.earth
,07-15 15:25:46.361  1571  4687 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-15 15:25:46.362  1571  4704 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.earth
,07-15 15:25:46.365  1571  4704 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.earth
,07-15 15:25:46.366  1571  1571 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:25:46.372  1571  4704 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.earth
,07-15 15:25:46.378  1571  1639 D nwp     : Processing package: com.google.earth
,07-15 15:25:46.388  1571  1639 D nwe     : Look up (com.google.earth:161661104) returned no result
,07-15 15:25:46.388  1571  1639 D nwp     : Starting Hash for package com.google.earth:8.0.4.2346
,07-15 15:25:46.397  4693  4968 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.earth, CONTACTS=MAYBE
,07-15 15:25:46.425  1571  1571 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:25:46.426  1571  4704 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.earth
,07-15 15:25:46.429  1561  1561 E NetworkScheduler.SR: Invalid parameter app
07-15 15:25:46.429  1561  1561 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:25:46.438  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.ah.onPostExecute(2860): Downloading gzip for com.google.android.calendar (com.google.android.calendar)
,07-15 15:25:46.439  1278  1538 I Finsky  : [59] com.google.android.finsky.installer.ah.run(127): Session for com.google.android.calendar already exists, skipping creation
,07-15 15:25:46.440  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(256): Duplicate state set for 'com.google.android.calendar' (0). Already in that state
,07-15 15:25:46.441  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.calendar added to DownloadQueue
,07-15 15:25:46.444  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.calendar from 0 to 1.
,07-15 15:25:46.445   199   199 I installd: free_cache(13843003) avail 10598858752
,07-15 15:25:46.447   788   799 I BroadcastQueue: Delay finish: com.google.android.apps.photos/.experiments.phenotype.AppUpgradeBroadcastReceiver
,07-15 15:25:46.455   788  1357 I BroadcastQueue: Resuming delayed broadcast
,07-15 15:25:46.460  1278  1278 I Finsky  : [1] com.google.android.finsky.download.ai.run(5554): Download com.google.android.calendar starting
,07-15 15:25:46.479  1571  4971 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-15 15:25:46.516  1278  1539 I Finsky  : [60] com.google.android.finsky.download.ae.a(1567): Enqueued com.google.android.calendar as content://downloads/my_downloads/986
07-15 15:25:46.517  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.calendar from 1 to 2.
07-15 15:25:46.517  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.a(632): com.google.android.calendar: onStart
,07-15 15:25:46.523  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.calendar: onProgress 0/-1 Status: 190.
,07-15 15:25:46.543  1571  1639 D nwp     : Package com.google.earth's hash: 021fdc38e9f086c423b1088ed13642d1639117e2f1f6754671a4a0e9ae8ebe3f
07-15 15:25:46.543  4693  4968 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
,07-15 15:25:46.544  1571  1639 D nwe     : Look up (com.google.earth:161661104) returned no result
,07-15 15:25:46.573  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.calendar: onProgress 0/-1 Status: 192.
,07-15 15:25:46.574   943  4976 D DownloadManager: [986] Starting
,07-15 15:25:46.592  1571  1639 D nwp     : Saved the app info in cache for package:com.google.earth.
,07-15 15:25:46.593  1571  1639 D nwp     : Processing package: com.google.earth
,07-15 15:25:46.597  1571  1639 D GassUtils: Found app info for package com.google.earth:161661104. Hash: 021fdc38e9f086c423b1088ed13642d1639117e2f1f6754671a4a0e9ae8ebe3f
07-15 15:25:46.597  1571  1639 D nwp     : Found info for package com.google.earth in db.
,07-15 15:25:47.566  1571  1639 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-15 15:25:47.657  1571  1639 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
,07-15 15:25:47.700  1571  1639 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-15 15:25:47.720  1571  1639 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,07-15 15:25:50.012   943  4976 D DownloadManager: [986] Finished with status SUCCESS
,07-15 15:25:50.044  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.calendar: onProgress 13843003/13843003 Status: 200.,
,07-15 15:25:50.047  1278  1278 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(46): Intent received at DownloadBroadcastReceiver
,07-15 15:25:50.099  1278  1278 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.calendar from 2 to 3.
,07-15 15:25:50.099  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.b(600): com.google.android.calendar: onComplete
07-15 15:25:50.099  1278  1278 I Finsky  : [1] com.google.android.finsky.download.x.i(341): Download com.google.android.calendar removed from DownloadQueue
,07-15 15:25:50.100   199   199 I installd: free_cache(0) avail 10585018368
,07-15 15:25:50.105  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.x.c(38951): Prepare to copy com.google.android.calendar (com.google.android.calendar) from content://downloads/my_downloads/986 (expect 22943694 bytes, isGzipped: true)
,07-15 15:25:50.119   199   199 I installd: free_cache(22943694) avail 10585018368
,07-15 15:25:50.128  1571  1571 V Herrevad: NQAS connected
,07-15 15:25:50.153  1571  1639 W Herrevad: Invalid mccmnc 
,07-15 15:25:50.154  1571  1639 W Herrevad: Invalid mccmnc 
,07-15 15:25:51.098  1278  3226 I Finsky  : [83] com.google.android.finsky.receivers.aa.a(3005): com.google.android.calendar (com.google.android.calendar) (22943694 bytes) copied successfully in 974 ms
,07-15 15:25:51.246  1561  3026 V NativeCrypto: SSL shutdown failed: ssl=0x9a9b4a00: I/O error during system call, Connection timed out
,07-15 15:25:51.321  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.aa.onPostExecute(4086): Successfully copied APK to update com.google.android.calendar (com.google.android.calendar)
,07-15 15:25:51.323  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.x.c(42122): Begin install of com.google.android.calendar
,07-15 15:25:51.335   943   963 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/downloadfile.bin via provider delete
,07-15 15:25:51.343  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:51.370  4657  4677 W Flag    : Duration spec must be at least 2 characters long: 
,07-15 15:25:51.489  4657  4677 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-15 15:25:51.502  4657  4677 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-15 15:25:51.502  4657  4677 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-15 15:25:51.506  4657  4677 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-15 15:25:51.530  4657  4677 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-15 15:25:52.435  1278  1278 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2102): Skipping verification because own installation
,07-15 15:25:52.720  1561  3026 V NativeCrypto: SSL shutdown failed: ssl=0xaec34800: I/O error during system call, Connection timed out
,07-15 15:25:53.735   788   815 I PackageManager.DexOptimizer: Running dexopt (dex2oat) on: /data/app/vmdl201028662.tmp/base.apk pkg=com.google.android.calendar isa=arm vmSafeMode=false debuggable=false oatDir = /data/app/vmdl201028662.tmp/oat bootComplete=true
,07-15 15:25:53.761  5027  5027 I dex2oat : Starting dex2oat.
,07-15 15:25:54.284  5027  5030 W dex2oat : Before Android 4.1, method android.graphics.PorterDuffColorFilter android.support.graphics.drawable.VectorDrawableCompat.updateTintFilter(android.graphics.PorterDuffColorFilter, android.content.res.ColorStateList, android.graphics.PorterDuff$Mode) would have incorrectly overridden the package-private method in android.graphics.drawable.Drawable
,07-15 15:25:56.428  5027  5027 W dex2oat : No verified method for method calling String.<init>: void android.provider.SearchRecentSuggestions.<init>(android.content.Context, java.lang.String, int)
,07-15 15:25:56.998  5027  5027 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.SpannableStringBuilder.toString()
,07-15 15:25:57.423  5027  5030 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.SpannableStringBuilder.toString()
,07-15 15:25:58.242  5027  5031 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString(java.lang.String)
,07-15 15:25:59.530  5027  5027 I dex2oat : dex2oat took 5.769s (threads: 4) arena alloc=10MB java alloc=9MB native alloc=38MB free=7MB
,07-15 15:25:59.547   788   804 I ActivityManager: Force stopping com.google.android.calendar appid=10028 user=-1: replace sys pkg
,07-15 15:25:59.552   788   815 W PackageManager: Trying to update system app code path from /data/app/com.google.android.calendar-1 to /data/app/com.google.android.calendar-2
,07-15 15:25:59.552   788   815 W PackageManager: Code path for com.google.android.calendar changing from /data/app/com.google.android.calendar-1 to /data/app/com.google.android.calendar-2
,07-15 15:25:59.552   788   804 I ActivityManager: Force stopping com.google.android.calendar appid=10028 user=-1: replace pkg
07-15 15:25:59.552   788   815 W PackageManager: Resource path for com.google.android.calendar changing from /data/app/com.google.android.calendar-1 to /data/app/com.google.android.calendar-2
,07-15 15:25:59.621   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
,07-15 15:25:59.656   788   815 W PackageManager: Unknown permission com.google.android.gm.exchange.BIND in package com.google.android.calendar
,07-15 15:25:59.738   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
,07-15 15:25:59.771   788  1367 I ActivityManager: Killing 3841:com.google.android.apps.plus/u0a63 (adj 15): empty #17
,07-15 15:25:59.772   788   815 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
07-15 15:25:59.772   788   815 I art     : Starting a blocking GC Explicit
,07-15 15:25:59.833   788   815 I art     : Explicit concurrent mark sweep GC freed 202735(10MB) AllocSpace objects, 9(1704KB) LOS objects, 33% free, 25MB/38MB, paused 806us total 60.291ms
,07-15 15:25:59.848   788   815 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.google.android.calendar-1/base.apk, retcode=-1
,07-15 15:25:59.848   199   199 E installd: Couldn't opendir /data/app/vmdl201028662.tmp: No such file or directory
,07-15 15:25:59.850   788   815 I ActivityManager: Force stopping com.google.android.calendar appid=10028 user=0: pkg removed
,07-15 15:25:59.855   788   788 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-15 15:25:59.857  4180  4180 D BluetoothMapAppObserver: onReceive
07-15 15:25:59.857  4180  4180 D BluetoothMapAppObserver: The removed package is: com.google.android.calendar
07-15 15:25:59.861   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:59.865  1278  1278 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2142): Successful install of com.google.android.calendar
,07-15 15:25:59.877   788  1000 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
,07-15 15:25:59.892  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-15 15:25:59.893  1319  1319 D CarrierServiceBindHelper: mHandler: 3
,07-15 15:25:59.896  4180  4180 D BluetoothMapAppObserver: onReceive
07-15 15:25:59.896  4180  4180 D BluetoothMapAppObserver: The installed package is: com.google.android.calendar
07-15 15:25:59.897  4180  4180 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-15 15:25:59.898  4180  4180 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:25:59.898   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:59.909  4640  4640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-15 15:25:59.937   788  1366 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
07-15 15:25:59.949   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:25:59.956   788   798 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
,07-15 15:25:59.961  1278  1278 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(277): Wear auto install disabled for package com.google.android.calendar
07-15 15:25:59.962  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_ADDED
,07-15 15:25:59.962  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REPLACED
07-15 15:25:59.962  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:59.962  1319  1319 D CarrierServiceBindHelper: mHandler: 3
07-15 15:25:59.962  1319  1319 D CarrierConfigLoader: mHandler: 9 phoneId: 0
,07-15 15:25:59.981  1561  1561 E NetworkScheduler.SR: Invalid parameter app
07-15 15:25:59.981  1561  1561 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:25:59.982  1571  5066 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.calendar
,07-15 15:25:59.984  1571  5066 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.calendar
,07-15 15:26:00.003  1571  5069 D gH_CompatibleDatabase: Open irg@4ac6ff3, release reference: 1
,07-15 15:26:00.006  1571  5069 D gH_CompatibleDatabase: Acquire reference of irg@4ac6ff3: 2
,07-15 15:26:00.007  1571  5069 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.android.calendar.
07-15 15:26:00.007  1571  5069 D gH_CompatibleDatabase: Release reference of irg@4ac6ff3: 1
07-15 15:26:00.007  1571  5069 D gH_CompatibleDatabase: Open irg@79e4b0, release reference: 1
,07-15 15:26:00.011  1571  5069 D gH_CompatibleDatabase: Acquire reference of irg@79e4b0: 2
,07-15 15:26:00.011  1571  1639 E Drive.UninstallOperation: Package still installed com.google.android.calendar
07-15 15:26:00.011  1571  5069 D gH_CompatibleDatabase: Release reference of irg@79e4b0: 1
07-15 15:26:00.011  1571  5069 D gH_CompatibleDatabase: Open irg@7b42f29, release reference: 1
07-15 15:26:00.013  1571  5066 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.calendar
,07-15 15:26:00.018  1571  5069 D gH_CompatibleDatabase: Acquire reference of irg@7b42f29: 2
,07-15 15:26:00.018  1571  5069 D gH_CompatibleDatabase: Release reference of irg@7b42f29: 1
,07-15 15:26:00.020  1571  5069 D gH_CompatibleDatabase: Close irg@4ac6ff3, release reference: 0
07-15 15:26:00.021  1571  5069 D gH_CompatibleDatabase: Close irg@79e4b0, release reference: 0
07-15 15:26:00.022  1571  5069 D gH_CompatibleDatabase: Close irg@7b42f29, release reference: 0
,07-15 15:26:00.045  1278  1278 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.google.android.calendar
,07-15 15:26:00.051  1571  5069 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.calendar
,07-15 15:26:00.052  1571  5065 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-15 15:26:00.056  1571  1571 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:26:00.060  1571  5069 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.calendar
,07-15 15:26:00.064  1571  1644 D nwp     : Processing package: com.google.android.calendar
,07-15 15:26:00.065  1561  2190 D GCM     : GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,07-15 15:26:00.068  1571  1644 D nwe     : Look up (com.google.android.calendar:2015187843) returned no result
,07-15 15:26:00.069  1571  1644 D nwp     : Starting Hash for package com.google.android.calendar:5.5.9-125657303-release
,07-15 15:26:00.072  1571  5069 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.calendar
,07-15 15:26:00.086  4693  5077 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.calendar, CONTACTS=MAYBE
,07-15 15:26:00.126  1571  5069 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.calendar
,07-15 15:26:00.127  1571  1571 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:26:00.133  1561  1561 E NetworkScheduler.SR: Invalid parameter app
07-15 15:26:00.133  1561  1561 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:26:00.152   788  1325 I BroadcastQueue: Delay finish: com.google.android.apps.photos/.experiments.phenotype.AppUpgradeBroadcastReceiver
,07-15 15:26:00.154   788   948 I BroadcastQueue: Resuming delayed broadcast
,07-15 15:26:00.175   788  1367 I ActivityManager: Start proc 5083:com.google.android.calendar/u0a28 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,07-15 15:26:00.182  1571  5081 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-15 15:26:00.217  5083  5083 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.calendar-2/lib/arm
,07-15 15:26:00.246  4693  5077 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 160 ms] updated apps [took 160 ms] 
,07-15 15:26:00.315   788  1365 I ActivityManager: Start proc 5101:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,07-15 15:26:00.340  5101  5101 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-15 15:26:00.367  5101  5101 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@76d4bbe(com.android.providers.calendar.CalendarProvider2@991541f)
,07-15 15:26:00.368  1571  1644 D nwp     : Package com.google.android.calendar's hash: 1a7a763a7ea588036e9b43f1ad72249d5b7a8c13eaa788a30484d9688de401f8
,07-15 15:26:00.369  1571  1644 D nwe     : Look up (com.google.android.calendar:2015187843) returned no result
,07-15 15:26:00.382  1571  1644 D nwp     : Saved the app info in cache for package:com.google.android.calendar.
,07-15 15:26:00.383  1571  1644 D nwp     : Processing package: com.google.android.calendar
,07-15 15:26:00.386  1571  1644 D GassUtils: Found app info for package com.google.android.calendar:2015187843. Hash: 1a7a763a7ea588036e9b43f1ad72249d5b7a8c13eaa788a30484d9688de401f8
,07-15 15:26:00.386  1571  1644 D nwp     : Found info for package com.google.android.calendar in db.
,07-15 15:26:00.404  5083  5083 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-15 15:26:01.259  1571  1644 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-15 15:26:01.348  1571  1644 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
,07-15 15:26:01.381  1571  1644 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-15 15:26:01.405  1571  1644 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,07-15 15:26:01.414  5101  5101 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-15 15:26:01.414  5101  5101 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-15 15:26:05.350  5083  5113 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-15 15:26:06.530   788   799 I ActivityManager: Killing 3764:com.google.android.talk/u0a51 (adj 15): empty #17
,07-15 15:26:07.143   788  1325 I ActivityManager: Killing 3924:com.google.android.keep/u0a52 (adj 15): empty #17
,07-15 15:26:15.108  1278  1550 I Finsky  : [70] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-15 15:26:15.253  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:26:15.257  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:26:15.258  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:26:16.150  1278  1278 I Finsky  : [1] com.google.android.finsky.c.c.a(311): Completed 1 account content syncs with 1 successful.
,07-15 15:26:16.150  1278  1278 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-15 15:26:44.984   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:26:54.295   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=458738, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:27:23.224   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=487667, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:27:53.036   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=517479, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:28:21.944   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=546387, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:28:45.916   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=570359, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:29:14.744   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=599187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:29:45.686   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=630130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:30:14.333  4180  4239 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-15 15:30:14.583   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=659027, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:30:20.835   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=665278, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:31:10.024   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=714467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:34:46.446   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=930889, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:35:05.064   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=949507, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:35:46.266   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=990709, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:36:04.904   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1009347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:39:36.256   788   803 I UsageStatsService: User[0] Flushing usage stats to disk
,07-15 15:39:40.689  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:39:40.718  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:39:40.719  1561  1561 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:39:45.755   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1230198, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-15 15:39:50.904   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-15 15:43:46.486   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1470929, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-15 15:43:56.484   788  4424 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1480927, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),07-15 15:44:30.700  5210  5210 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-15 15:44:30.704  5210  5210 D AndroidRuntime: CheckJNI is OFF
07-15 15:44:30.740  5210  5210 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-15 15:44:30.855  5210  5210 I Radio-JNI: register_android_hardware_Radio DONE
07-15 15:44:30.876  5210  5210 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-15 15:44:30.881   788   804 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
07-15 15:44:30.881   788   804 I ActivityManager: Killing 3615:com.test.thalitest/u0a26 (adj 0): stop com.test.thalitest
07-15 15:44:30.918   788   893 D WifiService: Client connection lost with reason: 4
07-15 15:44:30.918   788   948 D GraphicsStats: Buffer count: 2
07-15 15:44:30.919   788   948 I WindowState: WIN DEATH: Window{9bc36a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-15 15:44:30.919   788  1357 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@4c0ab1b)
07-15 15:44:30.919   788   894 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-15 15:44:30.920   788   894 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-15 15:44:30.948   788   815 W PackageSettings: Skipping PackageSetting{99b1802 com.example.hello/10116} due to missing metadata
07-15 15:44:30.977   788   804 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-15 15:44:30.977   788   804 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-15 15:44:30.979   788   815 I art     : Starting a blocking GC Explicit
07-15 15:44:30.988   788   804 E ActivityManager: Failure starting process com.test.thalitest
07-15 15:44:30.988   788   804 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-15 15:44:30.988   788   804 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:44:30.988   788   804 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:30.988   788   804 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:30.988   788   804 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-15 15:44:30.988   788   804 I ActivityManager:   Force finishing activity ActivityRecord{66b6fa3 u0 com.test.thalitest/.MainActivity t46}
07-15 15:44:30.994   788   798 W ActivityManager: Spurious death for ProcessRecord{c0d44b8 0:com.test.thalitest/u0a26}, curProc for 3615: null
07-15 15:44:31.043   788   815 I art     : Explicit concurrent mark sweep GC freed 57896(4MB) AllocSpace objects, 13(276KB) LOS objects, 33% free, 26MB/39MB, paused 784us total 57.398ms
07-15 15:44:31.065   788   815 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-15 15:44:31.068  5210  5210 I art     : System.exit called, status: 0
07-15 15:44:31.068  5210  5210 I AndroidRuntime: VM exiting with result code 0.
07-15 15:44:31.080   788   815 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
07-15 15:44:31.135   788   804 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-15 15:44:31.139  4180  4180 D BluetoothMapAppObserver: onReceive
07-15 15:44:31.139  4180  4180 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-15 15:44:31.140  1561  1646 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-15 15:44:31.151   788   798 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4783, uid=10071 that is not exported from uid 10058
07-15 15:44:31.153   788   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-15 15:44:31.169  2077  5240 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-15 15:44:31.192  1319  1319 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-15 15:44:31.194  4640  4640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
07-15 15:44:31.205  2077  5240 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
07-15 15:44:31.208  2077  5240 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-15 15:44:31.208  2077  5240 E AndroidRuntime: Process: android.process.acore, PID: 2077
07-15 15:44:31.208  2077  5240 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.208  2077  5240 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.209   788   890 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.210  4640  5250 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
07-15 15:44:31.211  4640  5250 E AndroidRuntime: Process: com.android.keychain, PID: 4640
07-15 15:44:31.211  4640  5250 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.211  4640  5250 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.219  2077  5240 I Process : Sending signal. PID: 2077 SIG: 9
07-15 15:44:31.220  1278  1278 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(280): Wear auto uninstall disabled for package com.test.thalitest
07-15 15:44:31.223   189   189 E lowmemorykiller: Error writing /proc/2077/oom_score_adj; errno=22
07-15 15:44:31.229  4640  5250 I Process : Sending signal. PID: 4640 SIG: 9
07-15 15:44:31.231   788  5251 E DropBoxManagerService: Can't write: system_app_crash
07-15 15:44:31.231   788  5251 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.231   788  5251 E DropBoxManagerService: 	... 5 more
07-15 15:44:31.231   788  5252 E DropBoxManagerService: Can't write: system_app_crash
07-15 15:44:31.231   788  5252 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.231   788  5252 E DropBoxManagerService: 	... 5 more
07-15 15:44:31.234  1571  5254 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-15 15:44:31.235  1561  1561 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
07-15 15:44:31.235  1561  1561 D AndroidRuntime: Shutting down VM
07-15 15:44:31.236  1571  5254 D AccountUtils: Clearing selected account for com.test.thalitest
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: problem persisting pending stats
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: java.io.FileNotFoundException: /data/system/netstats/dev.1467809295103-: open failed: EROFS (Read-only file system)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.internal.util.FileRotator.writeFile(FileRotator.java:379)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.internal.util.FileRotator.rewriteSingle(FileRotator.java:252)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.internal.util.FileRotator.rewriteActive(FileRotator.java:184)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:248)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:235)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1052)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1122)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService.-wrap6(NetworkStatsService.java)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService$3.onReceive(NetworkStatsService.java:817)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.240   788   889 E NetworkStatsRecorder: 	... 16 more
07-15 15:44:31.242   788   788 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-15 15:44:31.242   788   889 E DropBoxManagerService: Can't write: system_server_wtf
07-15 15:44:31.242   788   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop39.tmp: open failed: EROFS (Read-only file system)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12334)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:348)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.util.Log$1.onTerribleFailure(Log.java:104)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.util.Log.wtf(Log.java:297)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.util.Log.wtf(Log.java:286)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:252)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:235)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1052)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1122)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.-wrap6(NetworkStatsService.java)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$3.onReceive(NetworkStatsService.java:817)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.242   788   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.242   788   889 E DropBoxManagerService: 	... 23 more
07-15 15:44:31.255  1571  5254 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-15 15:44:31.262   788   889 E DropBoxManagerService: Can't write: netstats_dump
07-15 15:44:31.262   788   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop39.tmp: open failed: EROFS (Read-only file system)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:429)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:253)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:235)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1052)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1122)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.-wrap6(NetworkStatsService.java)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$3.onReceive(NetworkStatsService.java:817)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.262   788   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.262   788   889 E DropBoxManagerService: 	... 16 more
07-15 15:44:31.263   788  1325 I ActivityManager: Process android.process.acore (pid 2077) has died
07-15 15:44:31.264   788  1325 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
07-15 15:44:31.264   189   189 E lowmemorykiller: Error opening /proc/4640/oom_score_adj; errno=2
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: problem persisting pending stats
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: java.io.FileNotFoundException: /data/system/netstats/xt.1467809295103-: open failed: EROFS (Read-only file system)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.internal.util.FileRotator.writeFile(FileRotator.java:379)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.internal.util.FileRotator.rewriteSingle(FileRotator.java:252)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.internal.util.FileRotator.rewriteActive(FileRotator.java:184)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:248)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:235)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1053)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1122)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService.-wrap6(NetworkStatsService.java)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at com.android.server.net.NetworkStatsService$3.onReceive(NetworkStatsService.java:817)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.267   788   889 E NetworkStatsRecorder: 	... 16 more
07-15 15:44:31.269   189   189 E lowmemorykiller: Error opening /proc/4640/oom_score_adj; errno=2
07-15 15:44:31.270  1571  5254 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-15 15:44:31.270   788   889 E DropBoxManagerService: Can't write: system_server_wtf
07-15 15:44:31.270   788   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop39.tmp: open failed: EROFS (Read-only file system)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12334)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:348)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.util.Log$1.onTerribleFailure(Log.java:104)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.util.Log.wtf(Log.java:297)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.util.Log.wtf(Log.java:286)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:252)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:235)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1053)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1122)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.-wrap6(NetworkStatsService.java)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$3.onReceive(NetworkStatsService.java:817)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:44:31.270   788   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:44:31.270   788   889 E DropBoxManagerService: 	... 23 more

```
