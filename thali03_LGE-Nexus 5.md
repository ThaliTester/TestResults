#### Test 75789268d2ecd3a_thali03_LGE-Nexus 5 Logs


```
--------- beginning of main
07-08 14:01:53.617   786  2781 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118228, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:01:54.337  3686  3686 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:01:54.342  3686  3686 D AndroidRuntime: CheckJNI is OFF
07-08 14:01:54.377  3686  3686 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:01:54.413  3686  3686 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:01:54.433  3686  3686 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-08 14:01:54.436   786  2118 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-08 14:01:54.456  1370  1380 W SearchService: Abort, client detached.
07-08 14:01:54.462  3686  3686 D AndroidRuntime: Shutting down VM
07-08 14:01:54.501   786  2561 I ActivityManager: Start proc 3702:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-08 14:01:54.507  1370  1552 I DeviceStateChecker: DeviceStateChecker cancelled
07-08 14:01:54.508  1370  1370 I MicroDetector: Keeping mic open: false
07-08 14:01:54.509  1370  1370 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@6df962b
07-08 14:01:54.510  1370  1473 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-08 14:01:54.563   198  1560 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-08 14:01:54.563   198  1560 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-08 14:01:54.568  1370  1551 I MicroRecognitionRunner: Stopping hotword detection.
07-08 14:01:54.570  1370  1558 I MicroRecognitionRunner: Detection finished
07-08 14:01:54.591  3702  3702 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-08 14:01:54.624  3702  3702 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 9246-9247)
07-08 14:01:54.624  3702  3702 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-08 14:01:54.638  3702  3702 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8473a86}
07-08 14:01:54.638  3702  3702 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-08 14:01:54.639  3702  3702 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-08 14:01:54.655   786   892 D WifiService: New client listening to asynchronous messages
07-08 14:01:54.665  3702  3702 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-08 14:01:54.675  3702  3702 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-08 14:01:54.675  3702  3702 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-08 14:01:54.689  3702  3702 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-08 14:01:54.733   786   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9e13ec:true
,07-08 14:01:54.763   786   797 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3702 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-08 14:01:54.772  3702  3702 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-08 14:01:54.779  3702  3702 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-08 14:01:54.781  3702  3702 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-08 14:01:54.791  3702  3702 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-08 14:01:54.808  3702  3702 I cr_Ime  : ImeThread is not enabled.
,07-08 14:01:54.818  3702  3750 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-08 14:01:54.861   786  2133 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3702 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-08 14:01:54.901  3702  3758 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:01:54.924  3702  3758 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-08 14:01:54.951  3702  3758 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-08 14:01:55.015   191   191 D SurfaceFlinger: shader cache generated - 24 shaders in 164.296982 ms
,07-08 14:01:55.037  3702  3750 I OpenGLRenderer: Initialized EGL, version 1.4
,07-08 14:01:55.099   786   811 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +613ms
,07-08 14:01:55.142  3702  3702 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3702
,07-08 14:01:55.143  3702  3702 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,07-08 14:01:55.143  3702  3702 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,07-08 14:01:55.240  3702  3702 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-08 14:01:55.242   786   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-08 14:01:55.285   786  3196 I ActivityManager: Killing 2664:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,07-08 14:01:55.464  3702  3767 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1727530704
,07-08 14:01:55.468  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-08 14:01:55.468  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-08 14:01:55.468  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-08 14:01:55.468  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-08 14:01:55.468  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-08 14:01:55.468  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@810b0d0 added. We now have 1 listener(s)
,07-08 14:01:55.471  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,07-08 14:01:55.472  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-08 14:01:55.473  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:01:55.473  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-08 14:01:55.477  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@239eaef added. We now have 1 listener(s)
07-08 14:01:55.477  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:01:55.484  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-08 14:01:55.488  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-08 14:01:55.488  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-08 14:01:55.490  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:01:55.490  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:01:55.493  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:01:55.493  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-08 14:01:55.493  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:01:55.494  3702  3767 I io.jxcore.node.LifeCycleMonitor: start: OK
07-08 14:01:55.495  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:01:55.496  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:01:55.519  3702  3702 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-08 14:01:56.211  3702  3768 W jxcore-log: Initializing JXcore engine
,07-08 14:01:56.211  3702  3768 W jxcore-log: JXcore engine is ready
,07-08 14:01:56.240  3768  3768 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8072]" dev="sockfs" ino=8072 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-08 14:01:56.240  3768  3768 W Thread-317: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-08 14:01:56.240  3768  3768 W Thread-317: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[22579]" dev="sockfs" ino=22579 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-08 14:01:56.262  3702  3768 W jxcore-log: Starting JXcore engine
,07-08 14:01:56.374  3702  3768 W jxcore-log: Platform android
07-08 14:01:56.374  3702  3768 W jxcore-log: 
,07-08 14:01:56.374  3702  3768 W jxcore-log: Process ARCH arm
07-08 14:01:56.374  3702  3768 W jxcore-log: 
,07-08 14:01:56.579  3702  3768 I jxcore-log: JXcore Cordova bridge is ready!
07-08 14:01:56.579  3702  3768 I jxcore-log: 
,07-08 14:01:56.579  3702  3768 W jxcore-log: JXcore engine is started
,07-08 14:01:56.587  3702  3767 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-08 14:01:56.591  3702  3702 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-08 14:01:57.342   786   891 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-08 14:02:04.689   786  3196 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1578 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-08 14:02:04.734  1578  3800 W DriveInitializer: Background init thread started
,07-08 14:02:04.828  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:04.828  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:04.856  1578  3800 W DriveInitializer: Background init thread ended
,07-08 14:02:06.447  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-08 14:02:06.447  3702  3768 I jxcore-log: 
,07-08 14:02:06.449  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-08 14:02:06.449  3702  3768 I jxcore-log: 
,07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:06.453  3702  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:06.455  3702  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:02:06.457  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-08 14:02:06.457  3702  3768 I jxcore-log: 
,07-08 14:02:06.458  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-08 14:02:06.458  3702  3768 I jxcore-log: 
,07-08 14:02:06.827  3702  3768 I jxcore-log: Unit Test app is loaded
07-08 14:02:06.827  3702  3768 I jxcore-log: 
,07-08 14:02:06.831  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:06.831  3702  3768 I jxcore-log: 
,07-08 14:02:06.836  3702  3768 I jxcore-log: My device name is: LGE-Nexus 5
07-08 14:02:06.836  3702  3768 I jxcore-log: 
,07-08 14:02:06.837  3702  3702 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-08 14:02:06.837  3702  3767 D JX-Cordova: Running tests
,07-08 14:02:06.839  3702  3768 I jxcore-log: WARN testUtils: myNameCallback not set!
07-08 14:02:06.839  3702  3768 I jxcore-log: 
,07-08 14:02:06.897  3702  3767 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-08 14:02:06.897  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:02:06.897  3702  3767 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-08 14:02:06.897  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:02:06.897  3702  3767 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,07-08 14:02:06.897  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-08 14:02:06.898  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-08 14:02:06.898  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-08 14:02:06.898  3702  3767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-08 14:02:06.899  3702  3767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-08 14:02:06.899  3702  3767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-08 14:02:06.899  3702  3767 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-08 14:02:06.900  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:06.900  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a59359f added. We now have 2 listener(s)
07-08 14:02:06.900  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:06.902  3702  3767 D BluetoothAdapter: enable(): BT is already enabled..!
07-08 14:02:06.902   786  3196 D WifiService: setWifiEnabled: true pid=3702, uid=10026
,07-08 14:02:06.902   786  3196 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:06.903  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:06.903  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4c76ec added. We now have 3 listener(s),
,07-08 14:02:06.903  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:06.906  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:06.906  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@952bab5 added. We now have 4 listener(s)
07-08 14:02:06.907  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:06.908  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:06.908  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1ad54a added. We now have 5 listener(s)
07-08 14:02:06.908  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:06.909   786  2133 D WifiService: setWifiEnabled: false pid=3702, uid=10026
07-08 14:02:06.909   786  2133 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:06.911   786   891 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-08 14:02:06.911   786   891 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-08 14:02:06.911   786   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:02:06.911   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:06.912  1798  1866 D BluetoothAdapterState: Current state: ON, message: 23
07-08 14:02:06.912  1798  1866 D BluetoothAdapterProperties: Setting state to 13
07-08 14:02:06.912  1798  1866 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-08 14:02:06.913  1798  1866 D BluetoothAdapterProperties: onBluetoothDisable()
07-08 14:02:06.913  1798  1866 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:02:06.914  1798  1798 D BluetoothMapService: onReceive
07-08 14:02:06.914  1798  1798 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:02:06.915  1798  1798 D BluetoothMapService: STATE_TURNING_OFF
07-08 14:02:06.915  1798  1798 D BluetoothMapService: MAP Service closeService in
07-08 14:02:06.915  1798  1798 D BluetoothMapMasInstance0: MAP Service shutdown
07-08 14:02:06.915  1798  1798 D ObexServerSockets0: shutdown(block = true)
,07-08 14:02:06.915  1798  1798 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:02:06.915  1798  1798 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:02:06.915  1798  2069 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-08 14:02:06.916  1798  2030 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-08 14:02:06.916  1798  2070 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-08 14:02:06.921  1798  1798 I BtOppRfcommListener: stopping Accept Thread
07-08 14:02:06.921  1798  2628 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-08 14:02:06.921  1798  2628 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-08 14:02:06.925   786   806 I ActivityManager: Start proc 3818:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-08 14:02:06.926   786  2782 D DhcpClient: Clearing IP address
07-08 14:02:06.926   194   698 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:06.927  1798  1871 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:06.927  1798  1866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:06.934  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:06.935  1798  1798 D HeadsetService: Received stop request...Stopping profile...
07-08 14:02:06.936  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:06.937   786   786 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:06.938  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:06.939  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:06.939  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:06.940  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:02:06.942  2848  3020 V NativeCrypto: Read error: ssl=0x98dd7a00: I/O error during system call, Connection timed out
07-08 14:02:06.942  2848  3020 V NativeCrypto: Write error: ssl=0x98dd7a00: I/O error during system call, Broken pipe
07-08 14:02:06.942  2848  3020 V NativeCrypto: Write error: ssl=0x98dd7a00: I/O error during system call, Broken pipe
07-08 14:02:06.942  2848  3020 V NativeCrypto: SSL shutdown failed: ssl=0x98dd7a00: I/O error during system call, Broken pipe
07-08 14:02:06.945  1298  1313 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:06.945   933   951 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:06.946   933   933 D HeadsetProfile: Bluetooth service disconnected
,07-08 14:02:06.946   786   786 D BluetoothHeadset: Proxy object disconnected
,07-08 14:02:06.946   786   786 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:06.946  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:06.947  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:06.951  1798  1798 D A2dpService: Received stop request...Stopping profile...
07-08 14:02:06.952  1798  2048 D A2dpStateMachine: Exit Disconnected: -1
07-08 14:02:06.952   933   933 D BluetoothA2dp: Proxy object disconnected
07-08 14:02:06.953   786   786 D BluetoothA2dp: Proxy object disconnected
07-08 14:02:06.953  1798  1798 D HidService: Received stop request...Stopping profile...
07-08 14:02:06.953  1798  1798 D HidService: Stopping Bluetooth HidService
07-08 14:02:06.954   933   933 D BluetoothInputDevice: Proxy object disconnected
,07-08 14:02:06.954   933   933 D HidProfile: Bluetooth service disconnected
07-08 14:02:06.954  1798  1798 D HealthService: Received stop request...Stopping profile...
07-08 14:02:06.955  1798  1798 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:06.955  1798  1798 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:06.955  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:06.955  1798  1798 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:06.958  1798  1798 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:02:06.958  1798  1798 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-08 14:02:06.958  1798  1871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-08 14:02:06.958  1798  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:06.958  1798  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:06.959  1798  1871 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,07-08 14:02:06.959  1798  1798 D PanService: Received stop request...Stopping profile...
,07-08 14:02:06.960   933   933 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:02:06.960   933   933 D PanProfile: Bluetooth service disconnected
,07-08 14:02:06.966  1798  1798 D BluetoothMapService: Received stop request...Stopping profile...
,07-08 14:02:06.966  1798  1798 D BluetoothMapService: stop()
,07-08 14:02:06.966  1798  1798 D BluetoothMapAppObserver: deinitObservers()
,07-08 14:02:06.966  1798  1798 D BluetoothMapAppObserver: removeReceiver()
,07-08 14:02:06.967  2848  3082 V NativeCrypto: Read error: ssl=0x986d8c00: I/O error during system call, Connection timed out
,07-08 14:02:06.967  2848  3082 V NativeCrypto: Write error: ssl=0x986d8c00: I/O error during system call, Broken pipe
07-08 14:02:06.967  2848  3082 V NativeCrypto: Write error: ssl=0x986d8c00: I/O error during system call, Broken pipe
07-08 14:02:06.967  2848  3082 V NativeCrypto: SSL shutdown failed: ssl=0x986d8c00: I/O error during system call, Broken pipe
07-08 14:02:06.968   933   933 D BluetoothMap: Proxy object disconnected
07-08 14:02:06.968   933   933 D MapProfile: Bluetooth service disconnected
07-08 14:02:06.968  1798  1798 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:06.968  1798  1798 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:06.968  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:06.968  1798  1798 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:06.970  1798  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:06.970  1798  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:06.970  1798  1980 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-08 14:02:06.970  1798  1980 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:02:06.970  1798  1980 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:02:06.970  1798  1980 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:02:06.970  1798  1871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:06.974  1798  1798 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:02:06.974  1798  1798 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:06.974  1798  1798 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:06.974  1798  1798 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:02:06.974  1798  1798 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-08 14:02:06.975  1798  1871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:02:06.975  1798  1871 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-08 14:02:06.975  1798  1798 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:06.975  1798  1798 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:06.975  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:02:06.975  1798  1798 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:06.975  1798  1798 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-08 14:02:06.976  1798  1798 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:02:06.976  1798  1798 D BluetoothMapService: MAP Service closeService in
07-08 14:02:06.976  1798  1798 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:06.976  1798  1798 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:06.976  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:06.977  1798  1798 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:06.977  1798  1866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:02:06.977  1798  1866 D BluetoothAdapterProperties: Setting state to 15
,07-08 14:02:06.977  1798  1866 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-08 14:02:06.977  1798  1798 D BluetoothMapService: cleanup()
07-08 14:02:06.977  1798  1798 D BluetoothMapService: MAP Service closeService in
07-08 14:02:06.977   933   951 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:02:06.978   786   810 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:06.978  1298  1448 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:06.978   786   810 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:06.978   786   810 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:06.978  1798  1866 I BluetoothAdapterState: Entering BleOnState
07-08 14:02:06.978   933   945 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:06.978   933  1387 D BluetoothPbap: onBluetoothStateChange: up=false
,07-08 14:02:06.984  1566  2913 V NativeCrypto: Read error: ssl=0xaa724400: I/O error during system call, Connection timed out
07-08 14:02:06.983   933   951 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:02:06.986   786   810 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:06.986   933   945 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:02:06.986   933  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:06.987  1566  2913 V NativeCrypto: SSL shutdown failed: ssl=0xaa724400: I/O error during system call, Broken pipe
07-08 14:02:06.988  1798  1866 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-08 14:02:06.988  1798  1866 D BluetoothAdapterProperties: Setting state to 16
,07-08 14:02:06.988  1798  1866 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-08 14:02:06.988  1566  2913 E GCM     : Wifi connection closed with errorCode 20
07-08 14:02:06.989   786  2133 D ConnectivityService: reportNetworkConnectivity(100, false) by 10007
07-08 14:02:06.989   786  2780 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10007
07-08 14:02:06.990  1798  1866 D BluetoothAdapterProperties: onBleDisable
07-08 14:02:06.990  1798  1866 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:06.991  1798  1868 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:02:06.991  1798  1980 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-08 14:02:06.991  1798  1980 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:06.991   786  2780 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-08 14:02:06.992  1798  1871 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:06.992   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-08 14:02:06.992   786   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-08 14:02:07.000   194   698 D CommandListener: Setting iface cfg
,07-08 14:02:07.001   786  2783 D DhcpClient: Receive thread stopped
07-08 14:02:07.008   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:07.009   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-08 14:02:07.009   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-08 14:02:07.009   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 5
07-08 14:02:07.014   786   786 D RttService: SCAN_AVAILABLE : 1
07-08 14:02:07.015   786   908 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-08 14:02:07.018   786   891 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-08 14:02:07.020   786   893 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-08 14:02:07.020   786   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:07.032  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:07.033  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:07.044  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:07.045  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:07.052   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
07-08 14:02:07.063  3818  3818 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-08 14:02:07.069   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:07.080   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
07-08 14:02:07.081   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-08 14:02:07.082  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:02:07.083   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-08 14:02:07.091   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-08 14:02:07.092   786   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ffced7b:true
,07-08 14:02:07.095   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-08 14:02:07.096   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:07.097   194   698 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:07.097   786   893 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-08 14:02:07.097   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:02:07.098   786   810 D Tethering: MasterInitialState.processMessage what=3
,07-08 14:02:07.101   786   891 D DhcpClient: doQuit
,07-08 14:02:07.101   786   891 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:02:07.101  3702  3702 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-08 14:02:07.102   786  2782 D DhcpClient: onQuitting
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:07.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:07.106  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:07.107  1370  1370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:07.109  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:07.110  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:07.110  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:07.111  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:07.112   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-08 14:02:07.115  1798  1871 I bt_hci  : shut_down
,07-08 14:02:07.115  1798  1875 D bt_hwcfg: hw_epilog_process
,07-08 14:02:07.122  1798  1875 I bt_vendor: low_power_mode_cb
,07-08 14:02:07.124  3818  3818 D LocalBluetoothProfileManager: Adding local MAP profile
,07-08 14:02:07.127  3818  3818 D BluetoothMap: Create BluetoothMap proxy object
,07-08 14:02:07.133  3818  3818 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-08 14:02:07.138  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:07.149  1798  1875 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-08 14:02:07.149  1798  1875 I bt_vendor: epilog_cb
07-08 14:02:07.149  1798  1875 I bt_hci  : epilog_finished_callback
,07-08 14:02:07.151  1798  1871 I bt_hci_h4: hal_close
,07-08 14:02:07.151  1798  1871 I bt_userial_vendor: device fd = 49 close
,07-08 14:02:07.156  1798  1868 D bt_stack_manager: event_shut_down_stack finished.
,07-08 14:02:07.156  1798  1866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-08 14:02:07.157  1798  1798 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:02:07.157  1798  1798 D BtGatt.GattService: Received stop request...Stopping profile...
,07-08 14:02:07.157  1798  1798 D BtGatt.GattService: stop()
07-08 14:02:07.158  1798  1798 D BtGatt.AdvertiseManager: advertise clients cleared
07-08 14:02:07.158  1798  1866 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-08 14:02:07.159  1798  1798 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:07.159  1798  1798 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:07.159  1798  1798 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:07.159  1798  1798 V BluetoothAdapterState: isBleTurningOff()=true
07-08 14:02:07.159  1798  1866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:02:07.159  1798  1866 D BluetoothAdapterProperties: Setting state to 10
07-08 14:02:07.159  1798  1866 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-08 14:02:07.159  1798  1866 I BluetoothAdapterState: Entering OffState
07-08 14:02:07.160   786   810 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-08 14:02:07.166  1365  1365 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-08 14:02:07.167   194   698 E Netd    : netlink response contains error (No such file or directory)
07-08 14:02:07.167   786   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-08 14:02:07.168  1798  1798 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-08 14:02:07.168  1798  1798 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:02:07.168  1798  1798 I BluetoothServiceJni: cleanupNative: return from cleanup
07-08 14:02:07.169  1798  1868 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-08 14:02:07.170  1798  1868 D bt_stack_manager: event_clean_up_stack finished.
,07-08 14:02:07.171  1798  1798 I art     : System.exit called, status: 0
07-08 14:02:07.171  1798  1798 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:02:07.176   786   892 D WifiService: New client listening to asynchronous messages
,07-08 14:02:07.217  1365  1365 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-08 14:02:07.236  1365  1365 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-08 14:02:07.246   786  1476 I ActivityManager: Process com.android.bluetooth (pid 1798) has died
,07-08 14:02:07.275   786   959 I ActivityManager: Start proc 3864:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,07-08 14:02:07.277   786   959 I ActivityManager: Killing 3255:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-08 14:02:07.318  1365  1365 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-08 14:02:07.367  1365  1365 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-08 14:02:07.392  3864  3864 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:02:07.392  3864  3864 D AdapterServiceConfig: Adding A2dpService
07-08 14:02:07.392  3864  3864 D AdapterServiceConfig: Adding HidService
,07-08 14:02:07.392  3864  3864 D AdapterServiceConfig: Adding HealthService
07-08 14:02:07.393  3864  3864 D AdapterServiceConfig: Adding PanService
07-08 14:02:07.393  3864  3864 D AdapterServiceConfig: Adding GattService
07-08 14:02:07.393  3864  3864 D AdapterServiceConfig: Adding BluetoothMapService
,07-08 14:02:07.395   786  2133 I ActivityManager: Killing 2350:com.google.android.talk/u0a51 (adj 15): empty #17
,07-08 14:02:07.538   786   891 D wifi    : In wifi stop Hal
,07-08 14:02:07.538   786   891 D wifi    : halHandle = 0xa07cfb10, mVM = 0xb4d7c000, mCls = 0x100aea
,07-08 14:02:07.539   786  1360 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-08 14:02:07.539   786  1360 D WifiHAL : Got a signal to exit!!!
07-08 14:02:07.539   786  1360 I WifiHAL : Exit wifi_event_loop
07-08 14:02:07.539   786   891 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-08 14:02:07.539   786   891 E WifiHAL : Event processing terminated
,07-08 14:02:07.539   786   891 D wifi    : In wifi cleaned up handler
07-08 14:02:07.539   786   891 I WifiHAL : Internal cleanup completed
07-08 14:02:07.540  1566  1663 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-08 14:02:07.540  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:07.541  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:07.541  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:07.544  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:07.546  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:07.551  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:07.563  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.,
,07-08 14:02:07.572  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:07.573  1566  3883 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:02:07.596   786  1212 I ActivityManager: Start proc 3884:com.google.android.talk/u0a51 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-08 14:02:07.616  1566  3883 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-08 14:02:07.668   786  1360 D wifi    : set interface wlan0 flags (DOWN)
07-08 14:02:07.668   786   891 D WifiNative-HAL: HAL event thread stopped successfully
,07-08 14:02:07.871   786   810 D Tethering: InitialState.processMessage what=4
,07-08 14:02:07.873   786   810 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-08 14:02:07.989  3884  3884 I Babel_telephony: TeleModule.onApplicationCreate
,07-08 14:02:07.997  3884  3913 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-08 14:02:07.997  3884  3913 I Babel_SMS: MmsConfig.loadMmsSettings
,07-08 14:02:07.998  3884  3913 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
07-08 14:02:07.998  3884  3913 I Babel_SMS: MmsConfig.loadFromDatabase
,07-08 14:02:08.010  3884  3913 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-08 14:02:08.010  3884  3913 I Babel_SMS: MmsConfig.loadFromResources
07-08 14:02:08.011  3884  3913 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-08 14:02:08.011  3884  3913 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-08 14:02:08.021  3884  3916 I Babel_SMS: ApnsOta: OTA version -1
,07-08 14:02:08.025  3884  3884 I Babel_Crash: Startup - clean
,07-08 14:02:08.075   786  2133 I ActivityManager: Start proc 3919:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-08 14:02:08.106  3919  3919 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-08 14:02:08.155  3919  3919 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-08 14:02:08.160   786  1476 I ActivityManager: Start proc 3934:com.google.android.apps.plus/u0a63 for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver
,07-08 14:02:08.161   786  1476 I ActivityManager: Killing 2336:com.google.android.keep/u0a52 (adj 15): empty #17
,07-08 14:02:08.352  3919  3931 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-08 14:02:08.555   786  1212 I ActivityManager: Killing 3456:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,07-08 14:02:08.665  1578  1578 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-08 14:02:08.667  1578  2882 I iu.UploadsManager: num queued entries: 0
07-08 14:02:08.668  1578  2882 I iu.UploadsManager: num updated entries: 0
07-08 14:02:08.668  1578  2882 I iu.SyncManager: NEXT; no task
,07-08 14:02:08.680   786   797 I ActivityManager: Start proc 3959:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-08 14:02:08.727  3959  3959 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-08 14:02:08.736  3959  3959 I MultiDex: VM with version 2.1.0 has multidex support
,07-08 14:02:08.736  3959  3959 I MultiDex: install
07-08 14:02:08.736  3959  3959 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-08 14:02:08.792  3959  3959 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-08 14:02:08.792  3959  3959 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:02:08.792  3959  3959 I GAv4    :   adb logcat -s GAv4
,07-08 14:02:08.804  3959  3959 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:08.815  3959  3977 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:08.946  3959  3959 I NSApplication: Starting up...
,07-08 14:02:08.959   786  3196 I ActivityManager: Start proc 4000:com.google.android.apps.photos/u0a83 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-08 14:02:08.961   786  3196 I ActivityManager: Killing 3411:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-08 14:02:09.137  1578  1578 V Herrevad: NQAS connected
,07-08 14:02:09.177  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:09.186  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:09.247  3959  3959 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-08 14:02:09.342   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6cca030
,07-08 14:02:09.342   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-08 14:02:09.342   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
07-08 14:02:09.342   192   442 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229190864)
,07-08 14:02:09.419   192   442 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-08 14:02:09.419   192   442 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-08 14:02:09.419   192   442 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229190864) wakelock released: 1, error no: 0
07-08 14:02:09.419   192   442 I rmt_storage: 
,07-08 14:02:09.421   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6cca030
,07-08 14:02:09.503   786  2561 I ActivityManager: Killing 1916:com.android.providers.calendar/u0a1 (adj 15): empty #17
,07-08 14:02:09.606   786  2133 I ActivityManager: Start proc 4017:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,07-08 14:02:09.696  4017  4017 W InstanceID/Rpc: Found 10007
,07-08 14:02:09.718   786   798 I ActivityManager: Killing 2988:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,07-08 14:02:10.966  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-08 14:02:10.966  3702  3768 I jxcore-log: 
,07-08 14:02:11.362  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-08 14:02:11.362  3702  3768 I jxcore-log: 
,07-08 14:02:11.386  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-08 14:02:11.386  3702  3768 I jxcore-log: 
,07-08 14:02:11.390  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-08 14:02:11.390  3702  3768 I jxcore-log: 
,07-08 14:02:11.405  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-08 14:02:11.405  3702  3768 I jxcore-log: 
,07-08 14:02:11.409  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-08 14:02:11.409  3702  3768 I jxcore-log: 
,07-08 14:02:11.940   786   798 D WifiService: setWifiEnabled: true pid=3702, uid=10026
,07-08 14:02:11.940   786   798 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:02:11.944   194   698 D SoftapController: Softap fwReload - Ok
07-08 14:02:11.945   194   698 D CommandListener: Setting iface cfg
07-08 14:02:11.945   194   698 D CommandListener: Trying to bring down wlan0
07-08 14:02:11.946   194   698 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:11.948   786   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:02:12.619   786  3196 I ActivityManager: Killing 3114:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-08 14:02:12.705   786   891 D wifi    : set interface wlan0 flags (UP)
07-08 14:02:12.705   786   891 I WifiHAL : Initializing wifi
07-08 14:02:12.705   786   891 I WifiHAL : Creating socket
,07-08 14:02:12.706   786   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-08 14:02:12.706   786   891 D wifi    : Did set static halHandle = 0xa07cfb10
07-08 14:02:12.706   786   891 D wifi    : halHandle = 0xa07cfb10, mVM = 0xb4d7c000, mCls = 0x1af6
07-08 14:02:12.706   786   891 D wifi    : array field set
07-08 14:02:12.706   786   891 I WifiNative-HAL: interface[0] = p2p0
07-08 14:02:12.706   786   891 I WifiNative-HAL: interface[1] = wlan0
07-08 14:02:12.707   786   810 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-08 14:02:12.711   786   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-08 14:02:12.713  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:12.713  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:12.715   786  4064 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602422000
07-08 14:02:12.715   786  4064 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x1af6, env = 0x9342d640
,07-08 14:02:12.751  4065  4065 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-08 14:02:12.772  4065  4065 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:02:12.827  4065  4065 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:12.892  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:12.892  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:12.892  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:12.895   786   891 D WifiConfigStore: Loading config and enabling all networks 
07-08 14:02:12.904   786   891 D WifiConfigStore: loaded 0 passpoint configs
07-08 14:02:12.904   786   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-08 14:02:12.905   786   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:02:12.905   786   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1,
07-08 14:02:12.905   786   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-08 14:02:12.913   786   891 D WifiNative-HAL: Setting external_sim to 1
,07-08 14:02:12.913   786   891 D wifi    : setting dfs flag to true, 0x9915a308
07-08 14:02:12.913   786   891 D WifiStateMachine: Setting OUI to DA-A1-19,
07-08 14:02:12.913   786   891 D wifi    : setting scan oui 0x9915a308
07-08 14:02:12.913   786   891 D WifiHAL : Sending mac address OUI
,07-08 14:02:12.921   786   891 E native  : do suspend false
,07-08 14:02:12.926   786   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-08 14:02:12.926   786   786 D RttService: SCAN_AVAILABLE : 3
07-08 14:02:12.926   786   908 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-08 14:02:12.929   194   698 D CommandListener: Setting iface cfg
,07-08 14:02:12.930   194   698 D CommandListener: Trying to bring up p2p0
07-08 14:02:12.930   786   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:02:12.931   786   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-08 14:02:12.934   786   890 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:02:12.934   786   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-08 14:02:13.371  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-08 14:02:13.371  3702  3768 I jxcore-log: 
,07-08 14:02:13.381  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-08 14:02:13.381  3702  3768 I jxcore-log: 
,07-08 14:02:13.391  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-08 14:02:13.391  3702  3768 I jxcore-log: 
,07-08 14:02:13.548  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-08 14:02:13.548  3702  3768 I jxcore-log: 
,07-08 14:02:13.631  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-08 14:02:13.631  3702  3768 I jxcore-log: 
,07-08 14:02:13.684  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-08 14:02:13.684  3702  3768 I jxcore-log: 
,07-08 14:02:13.690  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-08 14:02:13.690  3702  3768 I jxcore-log: 
,07-08 14:02:13.885  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-08 14:02:13.885  3702  3768 I jxcore-log: 
,07-08 14:02:13.905  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-08 14:02:13.905  3702  3768 I jxcore-log: 
,07-08 14:02:13.910  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-08 14:02:13.910  3702  3768 I jxcore-log: 
,07-08 14:02:13.915  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-08 14:02:13.915  3702  3768 I jxcore-log: 
,07-08 14:02:13.930  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-08 14:02:13.930  3702  3768 I jxcore-log: 
,07-08 14:02:13.948  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-08 14:02:13.948  3702  3768 I jxcore-log: 
,07-08 14:02:14.032  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-08 14:02:14.032  3702  3768 I jxcore-log: 
,07-08 14:02:14.037  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-08 14:02:14.037  3702  3768 I jxcore-log: 
,07-08 14:02:14.062  3702  3768 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-08 14:02:14.062  3702  3768 I jxcore-log: 
,07-08 14:02:14.069  3702  3768 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-08 14:02:14.070  3702  3768 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-08 14:02:14.070  3702  3768 I jxcore-log: 
,07-08 14:02:14.115  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:14.115  3702  3768 I jxcore-log: 
,07-08 14:02:14.116  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:14.116  3702  3768 I jxcore-log: 
,07-08 14:02:14.117  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:14.117  3702  3768 I jxcore-log: 
,07-08 14:02:14.118  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:14.118  3702  3768 I jxcore-log: 
,07-08 14:02:14.119  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:14.119  3702  3768 I jxcore-log: 
,07-08 14:02:14.120  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:14.120  3702  3768 I jxcore-log: 
,07-08 14:02:14.121  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:14.121  3702  3768 I jxcore-log: 
07-08 14:02:14.121  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:14.121  3702  3768 I jxcore-log: 
,07-08 14:02:14.594   786   891 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-08 14:02:14.596   786   891 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
07-08 14:02:14.596   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:02:14.605   786   891 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-08 14:02:14.692   786   891 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-08 14:02:14.692  4065  4065 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-08 14:02:14.772  4065  4065 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:02:14.809  4065  4065 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-08 14:02:14.809  4065  4065 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-08 14:02:14.810   786   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:02:14.820   786   891 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:02:14.820   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:14.820   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:02:14.834   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:02:14.841   194   698 D CommandListener: Setting iface cfg
,07-08 14:02:14.844   786   891 D WifiStateMachine: Start Dhcp Watchdog 2
07-08 14:02:14.852   786   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-08 14:02:14.852   786   893 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-08 14:02:14.854   786   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-08 14:02:14.861   786  4080 D DhcpClient: Receive thread started
,07-08 14:02:14.929   786   891 E native  : do suspend false
,07-08 14:02:14.935   786  4079 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:02:14.943   786  4080 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172702, domain null
,07-08 14:02:14.944   786  4079 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172702 seconds
07-08 14:02:14.945   786  4079 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-08 14:02:14.958   786  4080 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-08 14:02:14.959   786  4079 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-08 14:02:14.961   194   698 D CommandListener: Setting iface cfg
07-08 14:02:14.968   786   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
07-08 14:02:14.976   786  4079 D DhcpClient: Scheduling renewal in 86399s
07-08 14:02:14.980   786   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-08 14:02:14.985   786   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-08 14:02:14.985   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-08 14:02:14.987   786   893 D ConnectivityService: Adding iface wlan0 to network 101
07-08 14:02:15.047   786   891 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-08 14:02:15.090   786   893 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-08 14:02:15.090   786   893 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-08 14:02:15.091   786   893 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-08 14:02:15.091   786   893 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-08 14:02:15.092   786   893 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-08 14:02:15.099   786   893 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-08 14:02:15.103   786   893 D ConnectivityService: scheduleUnvalidatedPrompt 101
07-08 14:02:15.103   786   893 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-08 14:02:15.103   786   891 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:02:15.103   786   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:02:15.103   786   893 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-08 14:02:15.103   786   893 D ConnectivityService:    accepting network in place of null
07-08 14:02:15.104   786   893 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-08 14:02:15.126   786  4078 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139738, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:02:15.146   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:15.202   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:15.205   786   893 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-08 14:02:15.206   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:02:15.207   786   810 D Tethering: MasterInitialState.processMessage what=3
,07-08 14:02:15.209   786  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.110,2a00:1450:4001:817::200e
,07-08 14:02:15.212   786   893 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-08 14:02:15.214  3702  3702 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:15.220  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:15.220  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:02:15.221  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:15.221  3702  3768 I jxcore-log: 
,07-08 14:02:15.228  1370  1370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-08 14:02:15.229  3919  3919 E SetupWizard: tickleCheckinService called after completing user setup
,07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:15.230  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:15.230  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:02:15.232  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:15.232  3702  3768 I jxcore-log: 
,07-08 14:02:15.230  2557  2557 W ChromiumNet: type=1400 audit(0.0:10): avc: denied { ioctl } for path="socket:[22294]" dev="sockfs" ino=22294 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-08 14:02:15.248  1578  1578 V Herrevad: NQAS connected
,07-08 14:02:15.266   786  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jul 2016 12:02:15 GMT], X-Android-Received-Millis=[1467979335266], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467979335240]}
,07-08 14:02:15.267   786   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-08 14:02:15.267   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-08 14:02:15.267   786   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:02:15.268   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:02:15.286  1578  1578 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-08 14:02:15.288  1578  2882 I iu.UploadsManager: num queued entries: 0
,07-08 14:02:15.289  1578  2882 I iu.UploadsManager: num updated entries: 0
,07-08 14:02:15.291  1578  2882 I iu.SyncManager: NEXT; no task
,07-08 14:02:15.333  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:15.334  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:15.507  1566  1566 D WearableService: callingUid 10007, callindPid: 1566
,07-08 14:02:15.553  1566  4129 I CheckinUtil: Classify the device as Phone.
,07-08 14:02:15.566  1578  1578 I GCM     : Message from null null
07-08 14:02:15.566  1578  1578 E GCM     : Dropping message from null
,07-08 14:02:15.630  1566  4132 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-08 14:02:15.631  1566  4123 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-08 14:02:15.648  1566  4132 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-08 14:02:15.648  1566  4123 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-08 14:02:15.666  1566  4132 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-08 14:02:15.666  1566  4123 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-08 14:02:15.666  1566  4123 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-08 14:02:15.668  1566  4123 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:02:15.831  1578  4120 D ChimeraConfigService: Fetched value, gms:chimera:dogfoods = null
,07-08 14:02:15.836  1578  4120 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
,07-08 14:02:15.836  1578  4120 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,07-08 14:02:16.084  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:16.084  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:16.206   786   893 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-08 14:02:16.945   786  1211 D WifiService: setWifiEnabled: false pid=3702, uid=10026
,07-08 14:02:16.945   786  1211 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:16.964   786   891 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-08 14:02:16.965   786   891 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-08 14:02:16.965   786   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:02:16.965   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:16.993   786  4079 D DhcpClient: Clearing IP address
,07-08 14:02:16.995   194   698 D CommandListener: Setting iface cfg
07-08 14:02:17.015   786  4080 D DhcpClient: Receive thread stopped
07-08 14:02:17.021   194   698 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:17.047  1566  4119 V NativeCrypto: Read error: ssl=0x99f3f000: I/O error during system call, Connection timed out
07-08 14:02:17.048  1566  4119 V NativeCrypto: SSL shutdown failed: ssl=0x99f3f000: I/O error during system call, Broken pipe
07-08 14:02:17.050  1566  4119 E GCM     : Wifi connection closed with errorCode 20
,07-08 14:02:17.050   786  1003 D ConnectivityService: reportNetworkConnectivity(101, false) by 10007
07-08 14:02:17.050   786  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10007
07-08 14:02:17.050   786  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.110,2a00:1450:4001:817::200e
07-08 14:02:17.057   786  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
07-08 14:02:17.057   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
07-08 14:02:17.058   786   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-08 14:02:17.059   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:02:17.073   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:02:17.074   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-08 14:02:17.074   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 5
07-08 14:02:17.083   786   893 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-08 14:02:17.087   786   786 D RttService: SCAN_AVAILABLE : 1
,07-08 14:02:17.087   786   908 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-08 14:02:17.089   786   891 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-08 14:02:17.093   786   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:02:17.094   194   698 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:17.098   786   891 D DhcpClient: doQuit
07-08 14:02:17.100   786  4079 D DhcpClient: onQuitting
,07-08 14:02:17.100   786   891 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:17.104  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:17.104  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:17.105  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:17.105  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:17.108  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:17.108  3702  3768 I jxcore-log: 
07-08 14:02:17.110  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:17.110  3702  3768 I jxcore-log: 
,07-08 14:02:17.146   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:17.154  1566  4123 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.214.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,07-08 14:02:17.157  4065  4065 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-08 14:02:17.166   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:17.166   786   893 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-08 14:02:17.167   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:02:17.168   786   810 D Tethering: MasterInitialState.processMessage what=3
,07-08 14:02:17.169  1370  1370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-08 14:02:17.170  3702  3702 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-08 14:02:17.173  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:17.173  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:17.178  4065  4065 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-08 14:02:17.189  4065  4065 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-08 14:02:17.198  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:17.199  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:17.205  3959  3959 E NetworkQualityMonitor: Failed to fetch PredictedNetworkQuality
,07-08 14:02:17.222   194   698 E Netd    : netlink response contains error (No such file or directory)
,07-08 14:02:17.224   786   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-08 14:02:17.228  4065  4065 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-08 14:02:17.246  4065  4065 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-08 14:02:17.254  1578  1578 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-08 14:02:17.255  1578  2882 I iu.UploadsManager: num queued entries: 0
,07-08 14:02:17.256  1578  2882 I iu.UploadsManager: num updated entries: 0
,07-08 14:02:17.258  1578  2882 I iu.SyncManager: NEXT; no task
,07-08 14:02:17.347   786   891 D wifi    : In wifi stop Hal
07-08 14:02:17.348   786   891 D wifi    : halHandle = 0xa07cfb10, mVM = 0xb4d7c000, mCls = 0x1af6
07-08 14:02:17.348   786  4064 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-08 14:02:17.348   786  4064 D WifiHAL : Got a signal to exit!!!
07-08 14:02:17.348   786  4064 I WifiHAL : Exit wifi_event_loop
07-08 14:02:17.348   786   891 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-08 14:02:17.348   786   891 E WifiHAL : Event processing terminated
,07-08 14:02:17.348   786   891 D wifi    : In wifi cleaned up handler
07-08 14:02:17.348   786   891 I WifiHAL : Internal cleanup completed
07-08 14:02:17.349  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:17.349  1566  1663 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-08 14:02:17.349  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:17.458   786  4064 D wifi    : set interface wlan0 flags (DOWN)
,07-08 14:02:17.458   786   891 D WifiNative-HAL: HAL event thread stopped successfully
,07-08 14:02:17.673   786   810 D Tethering: InitialState.processMessage what=4
,07-08 14:02:17.702   786   810 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-08 14:02:17.784  1578  1578 I art     : Waiting for a blocking GC DisableMovingGc
,07-08 14:02:17.788  1578  1578 I art     : Starting a blocking GC DisableMovingGc
,07-08 14:02:22.021   786   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41971c1:true
,07-08 14:02:22.022  3864  3864 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:02:22.024  3864  3864 I bt_bluedroid: init
,07-08 14:02:22.025  3864  4188 I BluetoothAdapterState: Entering OffState
,07-08 14:02:22.026  3864  4189 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-08 14:02:22.026  3864  4189 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:02:22.026  3864  4189 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-08 14:02:22.027  3864  4189 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-08 14:02:22.027  3864  3864 I bt_bluedroid: get_profile_interface socket
07-08 14:02:22.028  3864  3864 I bt_bluedroid: get_profile_interface sdp
07-08 14:02:22.029  3864  3875 I bt_bluedroid: config_hci_snoop_log
07-08 14:02:22.030   786   810 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-08 14:02:22.032  3864  4188 D BluetoothAdapterState: Current state: OFF, message: 0
,07-08 14:02:22.032  3864  4188 D BluetoothAdapterProperties: Setting state to 14
07-08 14:02:22.032  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-08 14:02:22.033  3864  4188 D BluetoothBondStateMachine: make
,07-08 14:02:22.035  3864  4192 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-08 14:02:22.036  3864  4192 D BluetoothAdapterProperties: Name is: Nexus 5
07-08 14:02:22.039  3864  3864 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-08 14:02:22.040  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:22.041  3864  4188 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:22.041  3864  3864 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:02:22.041  3864  3864 D BtGatt.GattService: Received start request. Starting profile...
07-08 14:02:22.041  3864  3864 D BtGatt.GattService: start()
,07-08 14:02:22.041  3864  3864 I bt_bluedroid: get_profile_interface gatt
07-08 14:02:22.042  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:22.042  3864  3864 D BtGatt.AdvertiseManager: advertise manager created
,07-08 14:02:22.042  3864  4193 I BluetoothBondStateMachine: StableState(): Entering Off State
07-08 14:02:22.045  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:22.045  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:22.046  3864  3864 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:02:22.046  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:22.046  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:02:22.046  3864  4188 I bt_bluedroid: enable
,07-08 14:02:22.046  3864  4189 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:02:22.046  3864  4189 I bt_hci  : start_up
07-08 14:02:22.050  3864  4189 I bt_vendor: alloc value 0xb39b9631
07-08 14:02:22.050  3864  4189 I bt_vendor: init
07-08 14:02:22.050  3864  4189 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-08 14:02:22.050  3864  4189 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-08 14:02:22.086  3864  4189 D bt_hci  : start_up starting async portion
,07-08 14:02:22.087  3864  4196 I bt_hci  : event_finish_startup
07-08 14:02:22.087  3864  4196 I bt_hci_h4: hal_open
07-08 14:02:22.087  3864  4196 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-08 14:02:22.089  3864  4196 I bt_userial_vendor: device fd = 49 open
,07-08 14:02:22.174  3864  4196 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:02:22.201  3864  4196 D bt_hwcfg: Chipset BCM4335C0
,07-08 14:02:22.201  3864  4196 D bt_hwcfg: Target name = [BCM4335C0]
07-08 14:02:22.202  3864  4196 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-08 14:02:22.628  3864  4196 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:02:22.628  3864  4196 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:02:22.628  3864  4196 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:02:22.744  3864  4196 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:02:22.744  3864  4196 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-08 14:02:22.774  3864  4196 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:02:22.774  3864  4196 I bt_vendor: firmware callback
07-08 14:02:22.774  3864  4196 I bt_hci  : firmware_config_callback
,07-08 14:02:22.778  3864  4200 I bt_btu  : btu_task pending for preload complete event
,07-08 14:02:22.778  3864  4200 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:02:22.778  3864  4200 I bt_btu  : btu_task received preload complete event
,07-08 14:02:22.784  3864  4200 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:02:22.784  3864  4200 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-08 14:02:22.784  3864  4200 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-08 14:02:22.784  3864  4200 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-08 14:02:22.784  3864  4200 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_A2D
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_BTM
07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_GAP
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_PAN
07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_SDP
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_GATT
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_SMP
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-08 14:02:22.785  3864  4200 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:02:22.990  3884  3908 W Babel   : bcq TOOK TOO LONG! (15002ms > 10000ms)
,07-08 14:02:22.995  3884  3910 W Babel   : bcq TOOK TOO LONG! (15001ms > 10000ms)
,07-08 14:02:23.014  3864  4200 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39379b5
,07-08 14:02:23.014  3864  4200 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39379b5 
,07-08 14:02:23.116   786   893 D ConnectivityService: handlePromptUnvalidated 101
07-08 14:02:23.117  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:02:23.117  3864  4192 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-08 14:02:23.118  3864  4192 D BluetoothAdapterProperties: Name is: Nexus 5
07-08 14:02:23.119  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:23.120  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:23.120  3864  4192 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:23.120  3864  4192 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-08 14:02:23.121  3864  4192 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
,07-08 14:02:23.121  3864  4192 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
,07-08 14:02:23.121  3864  4192 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
,07-08 14:02:23.122  3864  4192 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-08 14:02:23.122  3864  4192 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-08 14:02:23.122  3864  4192 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-08 14:02:23.122  3864  4192 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-08 14:02:23.124  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,07-08 14:02:23.125  3864  3864 I BluetoothHidServiceJni: classInitNative: succeeds
07-08 14:02:23.125  3864  3864 D HidService: getHidService(): service is NULL
,07-08 14:02:23.129  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-08 14:02:23.130  3864  3864 D HidService: getHidService(): service is NULL
07-08 14:02:23.132  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-08 14:02:23.132  3864  3864 D HidService: getHidService(): service is NULL
07-08 14:02:23.134  3884  3918 W Babel   : bcq TOOK TOO LONG! (15071ms > 10000ms)
07-08 14:02:23.135  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-08 14:02:23.135  3864  3864 D HidService: getHidService(): service is NULL
07-08 14:02:23.137  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-08 14:02:23.138  3864  3864 D HidService: getHidService(): service is NULL
07-08 14:02:23.140  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-08 14:02:23.141  3864  3864 D HidService: getHidService(): service is NULL
07-08 14:02:23.143  3864  4192 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-08 14:02:23.144  3864  3864 D HidService: getHidService(): service is NULL
07-08 14:02:23.144  3864  4192 D bt_hci  : do_postload posting postload work item
07-08 14:02:23.144  3864  4196 I bt_hci  : event_postload
07-08 14:02:23.145  3864  4196 I bt_vendor: sco_config_cb
07-08 14:02:23.145  3864  4196 I bt_hci  : sco_config_callback postload finished.
07-08 14:02:23.146  3864  4196 I bt_vendor: low_power_mode_cb
07-08 14:02:23.146  3864  4192 D bt_bte_conf: Device ID record 1 : primary
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   vendorId            = 000f
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   vendorIdSource      = 0001
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   product             = 1200
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   version             = 1436
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   clientExecutableURL = 
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   serviceDescription  = 
07-08 14:02:23.146  3864  4192 D bt_bte_conf:   documentationURL    = 
07-08 14:02:23.146  3864  4192 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-08 14:02:23.146  3864  4189 D bt_stack_manager: event_start_up_stack finished
07-08 14:02:23.146  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-08 14:02:23.146  3864  4188 D BluetoothAdapterProperties: Setting state to 15
07-08 14:02:23.146  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:02:23.148  3864  4188 I BluetoothAdapterState: Entering BleOnState
07-08 14:02:23.148  3864  4188 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:02:23.148  3864  4188 D BluetoothAdapterProperties: Setting state to 11
07-08 14:02:23.148  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-08 14:02:23.150  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:23.161  3864  3864 D HeadsetService: Received start request. Starting profile...
07-08 14:02:23.161  3864  3864 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-08 14:02:23.161  3864  3864 D HeadsetStateMachine: make
07-08 14:02:23.165  3864  4188 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:23.171  3864  3864 D HeadsetStateMachine: max_hf_connections = 1
07-08 14:02:23.172  3864  3864 I bt_bluedroid: get_profile_interface handsfree
07-08 14:02:23.172  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-08 14:02:23.172  3864  4192 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-08 14:02:23.174  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.,android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:23.174  3864  3864 D A2dpService: Received start request. Starting profile...
07-08 14:02:23.174  3864  3864 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-08 14:02:23.175  3864  3864 I bt_bluedroid: get_profile_interface avrcp
07-08 14:02:23.187  3864  3864 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-08 14:02:23.187  3864  3864 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-08 14:02:23.187  3864  3864 D A2dpStateMachine: make
07-08 14:02:23.188  3864  3864 I bt_bluedroid: get_profile_interface a2dp
07-08 14:02:23.190  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-08 14:02:23.193  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:23.194  3864  4223 D A2dpStateMachine: Enter Disconnected: -2
07-08 14:02:23.194  3864  3864 D HidService: Received start request. Starting profile...
07-08 14:02:23.194  3864  3864 I bt_bluedroid: get_profile_interface hidhost
07-08 14:02:23.194  3864  3864 D HidService: setHidService(): set to: null
07-08 14:02:23.195  3864  3864 I BluetoothHealthServiceJni: classInitNative: succeeds
07-08 14:02:23.195  3818  3818 D BluetoothInputDevice: Proxy object connected
07-08 14:02:23.195  3864  4192 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3919099
07-08 14:02:23.195  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-08 14:02:23.195  3818  3818 D HidProfile: Bluetooth service connected
07-08 14:02:23.196  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:23.196  3864  3864 D HealthService: Received start request. Starting profile...
07-08 14:02:23.198  3864  3864 I bt_bluedroid: get_profile_interface health
07-08 14:02:23.200  3864  3864 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-08 14:02:23.200  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:23.202  3864  3864 D PanService: Received start request. Starting profile...
07-08 14:02:23.202  3864  3864 D BluetoothPanServiceJni: initializeNative(L110): pan
07-08 14:02:23.202  3864  3864 I bt_bluedroid: get_profile_interface pan
07-08 14:02:23.202  3864  4192 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-08 14:02:23.205  3864  3864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:23.205  3818  3818 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:02:23.206  3864  3864 D BluetoothMapService: Received start request. Starting profile...
07-08 14:02:23.206  3864  3864 D BluetoothMapService: start()
07-08 14:02:23.208  3864  3864 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-08 14:02:23.209  3864  3864 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-08 14:02:23.209  3864  3864 D BluetoothMapAppObserver: createReceiver()
07-08 14:02:23.209  3864  3864 D BluetoothMapAppObserver: initObservers()
07-08 14:02:23.210  3864  3864 D BluetoothMapAppObserver: getEnabledAccountItems()
07-08 14:02:23.217  3818  3818 D PanProfile: Bluetooth service connected
07-08 14:02:23.217  3818  3818 D BluetoothMap: Proxy object connected
07-08 14:02:23.217  3818  3818 D MapProfile: Bluetooth service connected
07-08 14:02:23.217  3818  3818 D BluetoothMap: getConnectedDevices()
07-08 14:02:23.218  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:23.218  3864  3864 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:23.218  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:23.218  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:23.218  3864  4207 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:23.219  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:23.220  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:23.220  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-08 14:02:23.220  3864  4188 D BluetoothAdapterProperties: ScanMode =  20
07-08 14:02:23.220  3864  4188 D BluetoothAdapterProperties: State =  11
07-08 14:02:23.221  3864  4192 D BluetoothAdapterProperties: Scan Mode:21
07-08 14:02:23.221  3864  4192 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:02:23.221  3864  4188 D BluetoothAdapterProperties: Setting state to 12
07-08 14:02:23.221  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-08 14:02:23.221  3864  4188 I BluetoothAdapterState: Entering OnState
07-08 14:02:23.222   933   945 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:02:23.224   786   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:23.224  1298  1419 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:23.225   933   933 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:02:23.225   933   933 D PanProfile: Bluetooth service connected
07-08 14:02:23.226  3818  3834 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:02:23.228   786   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:23.228   786   810 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:23.229  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:23.229   933   951 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:23.229   786   786 D BluetoothA2dp: Proxy object connected
07-08 14:02:23.231   933  1387 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:02:23.235  3818  3839 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:02:23.235   933  3842 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:02:23.235  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:23.236  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:02:23.236  3702  3768 I jxcore-log: 
07-08 14:02:23.239   786   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:23.239   933   945 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:02:23.239   933   933 D BluetoothInputDevice: Proxy object connected
07-08 14:02:23.239   933   933 D HidProfile: Bluetooth service connected
07-08 14:02:23.239  3864  3864 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:02:23.240  3864  3864 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-08 14:02:23.241  3818  3834 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:02:23.243  3864  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:02:23.243  3818  3839 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:02:23.248  3864  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:23.248  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:23.248   933   933 D BluetoothMap: Proxy object connected
07-08 14:02:23.248   933   933 D MapProfile: Bluetooth service connected
07-08 14:02:23.248   933   933 D BluetoothMap: getConnectedDevices()
07-08 14:02:23.249  3864  3864 D ObexServerSockets: Succeed to create listening sockets 
07-08 14:02:23.249   933   951 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:02:23.249  3864  3864 D ObexServerSockets0: startAccept()
07-08 14:02:23.249  3864  3864 D ObexServerSockets0: prepareForNewConnect()
07-08 14:02:23.251  3864  3864 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-08 14:02:23.251  3864  3864 D BluetoothSdpJni: SDP Create record success - handle: 0
07-08 14:02:23.253  3864  4237 D ObexServerSockets0: Accepting socket connection...
07-08 14:02:23.254   786   786 I Telecom : BluetoothPhoneService: queryPhoneState
07-08 14:02:23.254  3864  4238 D ObexServerSockets0: Accepting socket connection...
07-08 14:02:23.255  3864  3864 D BluetoothMapService: onReceive
07-08 14:02:23.256  3864  3864 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:02:23.256  3864  3864 D BluetoothMapService: STATE_ON
07-08 14:02:23.257  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:23.258  3818  3818 D LocalBluetoothProfileManager: Adding local A2DP profile
07-08 14:02:23.258  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:02:23.258  3702  3768 I jxcore-log: 
07-08 14:02:23.262   786  2561 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
07-08 14:02:23.263   933   933 D BluetoothA2dp: Proxy object connected
07-08 14:02:23.263  3818  3818 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-08 14:02:23.272  3884  3884 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
07-08 14:02:23.273   933  1133 D BluetoothMap: getConnectedDevices()
07-08 14:02:23.273  3884  3884 W Babel   : BAM#gBA: invalid account id: -1
07-08 14:02:23.273  3884  3884 W Babel   : BAM#gBA: invalid account id: -1
07-08 14:02:23.273  3884  3884 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
07-08 14:02:23.276  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-08 14:02:23.278  3864  3864 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:02:23.278  3864  3864 D ObexServerSockets0: prepareForNewConnect()
07-08 14:02:23.279   933  1133 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
07-08 14:02:23.282  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-08 14:02:23.285   786  3196 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
07-08 14:02:23.286   933  1133 D MapProfile: getConnectionStatus: status is: 0
07-08 14:02:23.295  3818  3818 D BluetoothMap: getConnectedDevices()
07-08 14:02:23.297  3818  3818 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
07-08 14:02:23.298  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.314  3818  3818 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.316   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.317  3818  3818 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-08 14:02:23.320  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.322   933  1133 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-08 14:02:23.326   786   786 D BluetoothHeadset: Proxy object connected
,07-08 14:02:23.327  1298  1309 D BluetoothHeadset: Proxy object connected
,07-08 14:02:23.327   933  1387 D BluetoothHeadset: Proxy object connected
07-08 14:02:23.327   786   786 D BluetoothHeadset: Proxy object connected
07-08 14:02:23.328   786   786 D BluetoothHeadset: Proxy object connected
07-08 14:02:23.328   786   810 D BluetoothHeadset: Proxy object connected
,07-08 14:02:23.329   933  3842 D BluetoothHeadset: Proxy object connected
,07-08 14:02:23.330   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.334   933   933 D HeadsetProfile: Bluetooth service connected
,07-08 14:02:23.337  3818  3818 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.338   933   933 D HeadsetProfile: Bluetooth service connected
,07-08 14:02:23.339   786   810 D BluetoothHeadset: Proxy object connected
,07-08 14:02:23.339  3818  3818 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-08 14:02:23.341  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.358  3818  3818 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.360  3818  3818 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-08 14:02:23.362  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.368  3818  4236 D BluetoothHeadset: Proxy object connected
,07-08 14:02:23.372  1566  1566 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-08 14:02:23.377  3818  3818 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.379  3818  3818 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-08 14:02:23.381  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.382  1566  1566 I BeaconBle: BLE 'JB+' software access layer enabled
,07-08 14:02:23.382   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.387   933  1133 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-08 14:02:23.389   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.393  3818  3818 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.395  3818  3818 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-08 14:02:23.400  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.407  3818  3818 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.408  3818  3818 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-08 14:02:23.410  3818  3818 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.410  3818  3818 D BluetoothA2dp: Proxy object connected
,07-08 14:02:23.414  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:23.417  3818  3818 D HeadsetProfile: Bluetooth service connected
,07-08 14:02:23.424  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:23.425   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.430   933   933 D BluetoothPbap: Proxy object connected
,07-08 14:02:23.430   933   933 D PbapServerProfile: Bluetooth service connected
07-08 14:02:23.430  3864  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:02:23.431   933  1133 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-08 14:02:23.434   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.439  3818  3818 D BluetoothPbap: Proxy object connected
,07-08 14:02:23.440  3818  3818 D PbapServerProfile: Bluetooth service connected
,07-08 14:02:23.444  1566  4260 D BluetoothAdapter: startLeScan(): null
,07-08 14:02:23.448  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:23.454  1566  4260 D BluetoothAdapter: STATE_ON
,07-08 14:02:23.457  1566  4263 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:02:23.459  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-08 14:02:23.460  3864  4232 D BtGatt.GattService: registerClient() - UUID=8adead86-035c-4498-8fcc-9dc0b55732fc
07-08 14:02:23.460  3864  4192 D BtGatt.GattService: onClientRegistered() - UUID=8adead86-035c-4498-8fcc-9dc0b55732fc, clientIf=5
07-08 14:02:23.461  1566  1623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:02:23.461  3864  4226 D BtGatt.GattService: start scan with filters
07-08 14:02:23.468  3864  4195 D BtGatt.ScanManager: handling starting scan
,07-08 14:02:23.474  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-08 14:02:23.474  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-08 14:02:23.474  3864  4195 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-08 14:02:23.474  3864  4192 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-08 14:02:23.483   786  1211 I ActivityManager: Start proc 4268:com.google.android.talk:matchstick/u0a51 for broadcast com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,07-08 14:02:23.485  3864  4267 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:02:23.487  3864  4267 I BtOppRfcommListener: Accept thread started.
,07-08 14:02:23.499  1566  4263 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-08 14:02:23.505   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.506   933  1133 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-08 14:02:23.512   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.536   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.537   933  1133 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-08 14:02:23.538   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.569   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:23.576   933  1133 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-08 14:02:23.577   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:23.922  4268  4288 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService } isPeriodic:false
,07-08 14:02:23.951  4268  4288 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-08 14:02:23.964  4268  4288 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-08 14:02:23.964  4268  4288 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-08 14:02:23.968  4268  4288 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-08 14:02:23.993  4268  4288 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:02:23.994  4268  4288 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,07-08 14:02:24.973  1566  4260 D BluetoothAdapter: stopLeScan()
,07-08 14:02:24.974  1566  4260 D BluetoothAdapter: STATE_ON
,07-08 14:02:24.979  3864  4226 D BtGatt.GattService: stopScan() - queue size =1
,07-08 14:02:24.980  3864  4195 D BtGatt.ScanManager: stop scan
07-08 14:02:24.980  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-08 14:02:24.980  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-08 14:02:24.980  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-08 14:02:24.999  3864  3874 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-08 14:02:25.170  1566  4260 D BluetoothAdapter: startLeScan(): null
,07-08 14:02:25.172  1566  4260 D BluetoothAdapter: STATE_ON
07-08 14:02:25.174  3864  3874 D BtGatt.GattService: registerClient() - UUID=5d6fe1dd-0bcc-40dc-91fb-2013727bd97c
07-08 14:02:25.174  3864  4192 D BtGatt.GattService: onClientRegistered() - UUID=5d6fe1dd-0bcc-40dc-91fb-2013727bd97c, clientIf=5
07-08 14:02:25.174  1566  1622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:02:25.174  3864  4232 D BtGatt.GattService: start scan with filters
07-08 14:02:25.176  3864  4195 D BtGatt.ScanManager: handling starting scan
07-08 14:02:25.182  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-08 14:02:25.182  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-08 14:02:25.182  3864  4195 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-08 14:02:25.188  3864  4192 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-08 14:02:26.465  1566  4260 D BluetoothAdapter: stopLeScan()
,07-08 14:02:26.469  1566  4260 D BluetoothAdapter: STATE_ON
,07-08 14:02:26.471  3864  4233 D BtGatt.GattService: stopScan() - queue size =1
,07-08 14:02:26.472  3864  4195 D BtGatt.ScanManager: stop scan
,07-08 14:02:26.472  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-08 14:02:26.472  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
,07-08 14:02:26.472  3864  4195 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-08 14:02:26.516  3864  3875 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-08 14:02:26.517  1566  4260 I BeaconBle: Scan : No clients left, canceling alarm.
,07-08 14:02:26.964  3864  4188 D BluetoothAdapterState: Current state: ON, message: 23
07-08 14:02:26.964  3864  4188 D BluetoothAdapterProperties: Setting state to 13
,07-08 14:02:26.964  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-08 14:02:26.965  3864  4188 D BluetoothAdapterProperties: onBluetoothDisable()
07-08 14:02:26.976  3864  4188 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:26.992  3864  3864 D BluetoothMapService: onReceive
07-08 14:02:26.992  3864  3864 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-08 14:02:26.992  3864  3864 D BluetoothMapService: STATE_TURNING_OFF
07-08 14:02:26.993  3864  3864 D BluetoothMapService: MAP Service closeService in
07-08 14:02:26.993  3864  3864 D BluetoothMapMasInstance0: MAP Service shutdown
07-08 14:02:26.993  3864  3864 D ObexServerSockets0: shutdown(block = true)
07-08 14:02:26.994   786   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-08 14:02:26.997  3864  3864 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:02:26.998  3864  4238 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-08 14:02:26.999  3864  4237 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-08 14:02:27.021  3864  4203 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,07-08 14:02:27.021  3864  3864 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:02:27.021  3864  3864 I BtOppRfcommListener: stopping Accept Thread
07-08 14:02:27.021  3864  4267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-08 14:02:27.031  3864  4192 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:27.031  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:02:27.033   786   813 I PowerManagerService: Sleeping (uid 1000)...
,07-08 14:02:27.035   191   881 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
07-08 14:02:27.040  3864  4267 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-08 14:02:27.053   786   813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-08 14:02:27.062  3702  3702 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-08 14:02:27.062  3702  3702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-08 14:02:27.098  3864  3864 D HeadsetService: Received stop request...Stopping profile...
07-08 14:02:27.103  3864  3864 D A2dpService: Received stop request...Stopping profile...
,07-08 14:02:27.103  3864  4223 D A2dpStateMachine: Exit Disconnected: -1
,07-08 14:02:27.104  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
,07-08 14:02:27.105   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:G3s-1
,07-08 14:02:27.105   786   786 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:27.106  3818  3839 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:27.106  1298  1313 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:27.107  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:27.108   933  1387 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:27.108   933   933 D HeadsetProfile: Bluetooth service disconnected
07-08 14:02:27.108   933   933 D BluetoothA2dp: Proxy object disconnected
07-08 14:02:27.109   786   786 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:27.109   786   786 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:27.109   786   786 D BluetoothA2dp: Proxy object disconnected
07-08 14:02:27.109  3864  3864 D HidService: Received stop request...Stopping profile...
,07-08 14:02:27.109  3864  3864 D HidService: Stopping Bluetooth HidService
,07-08 14:02:27.110  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:27.111  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:27.111  3702  3768 I jxcore-log: 
07-08 14:02:27.112  3864  3864 D HealthService: Received stop request...Stopping profile...
07-08 14:02:27.114  3864  3864 D PanService: Received stop request...Stopping profile...
07-08 14:02:27.115   933   933 D BluetoothInputDevice: Proxy object disconnected
07-08 14:02:27.115   933   933 D HidProfile: Bluetooth service disconnected
07-08 14:02:27.117   933   933 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:02:27.117   933   933 D PanProfile: Bluetooth service disconnected
07-08 14:02:27.117  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-08 14:02:27.119  3864  3864 D BluetoothMapService: Received stop request...Stopping profile...
07-08 14:02:27.119  3864  3864 D BluetoothMapService: stop()
,07-08 14:02:27.119  3864  3864 D BluetoothMapAppObserver: deinitObservers()
07-08 14:02:27.119  3864  3864 D BluetoothMapAppObserver: removeReceiver()
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:27.119  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:27.120  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:27.121  3702  3702 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5c3d72b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a0015d8, 16908290=android.view.AbsSavedState$1@a0015d8}, android:focusedViewId=100}]}]
,07-08 14:02:27.121  3702  3702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-08 14:02:27.121  3702  3702 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-08 14:02:27.121  3702  3702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-08 14:02:27.121  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:27.121  3702  3768 I jxcore-log: 
,07-08 14:02:27.122   933   933 D BluetoothMap: Proxy object disconnected
,07-08 14:02:27.122   933   933 D MapProfile: Bluetooth service disconnected
07-08 14:02:27.123  3864  3864 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:27.123  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:27.123  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:27.123   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:Thali Test (Galaxy A3)
,07-08 14:02:27.123  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:27.124  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-08 14:02:27.125  3864  3864 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:02:27.126  3864  3864 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-08 14:02:27.126  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:27.126  3864  4200 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:27.126  3864  4200 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:27.126  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:27.126  3864  4192 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,07-08 14:02:27.127  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-08 14:02:27.127  3864  4200 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:27.127  3864  4200 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:27.127  3864  4200 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:02:27.127  3864  4200 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:02:27.127  3864  4200 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:02:27.127  3864  4200 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:02:27.127  3864  3864 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:02:27.127  3864  3864 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-08 14:02:27.127  3864  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:02:27.128  3864  3864 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:27.128  3864  3864 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:27.128  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:27.128  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:27.128  3864  3864 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-08 14:02:27.128  3864  4192 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-08 14:02:27.128  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-08 14:02:27.129  3864  3864 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-08 14:02:27.129  3864  3864 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:27.129  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:27.129  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:27.129  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:27.129  3864  3864 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-08 14:02:27.129  3864  3864 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:02:27.131  3864  3864 D BluetoothMapService: MAP Service closeService in
07-08 14:02:27.131  3864  3864 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:27.131  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:27.131  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:27.131  3864  3864 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:27.131  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:02:27.131  3864  4188 D BluetoothAdapterProperties: Setting state to 15
07-08 14:02:27.131  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-08 14:02:27.131  3864  3864 D BluetoothMapService: cleanup()
07-08 14:02:27.131  3864  3864 D BluetoothMapService: MAP Service closeService in
07-08 14:02:27.132  3864  4188 I BluetoothAdapterState: Entering BleOnState
07-08 14:02:27.132   933   951 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:02:27.139   786   810 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:27.139  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
07-08 14:02:27.140  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
07-08 14:02:27.140   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:G4-1
07-08 14:02:27.140  1298  1419 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:27.141  3818  4236 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:02:27.141   786   810 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:27.141   786   810 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:27.141   933   945 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:27.142  3818  3839 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:27.142   933  3842 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:02:27.143  3818  3834 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:02:27.143  3818  3818 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
07-08 14:02:27.145  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:02:27.145   933  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:02:27.147   786   810 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:27.147   933   951 D BluetoothMap: onBluetoothStateChange: up=false
,07-08 14:02:27.157  3818  3834 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:27.158  3818  3818 D HeadsetProfile: Bluetooth service disconnected
07-08 14:02:27.158  3818  3818 D BluetoothInputDevice: Proxy object disconnected
07-08 14:02:27.158  3818  3818 D HidProfile: Bluetooth service disconnected
07-08 14:02:27.158  3818  3839 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-08 14:02:27.161  3818  4236 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:02:27.161   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:XT1039
,07-08 14:02:27.168  3818  3818 D DockEventReceiver: finishStartingService: stopping service
07-08 14:02:27.168   933   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-08 14:02:27.169   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:S5mini-1
,07-08 14:02:27.181   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:Note3-1
,07-08 14:02:27.181  3864  4188 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-08 14:02:27.181  3864  4188 D BluetoothAdapterProperties: Setting state to 16
07-08 14:02:27.181  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-08 14:02:27.184  3864  4188 D BluetoothAdapterProperties: onBleDisable
07-08 14:02:27.185  3864  4188 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:02:27.185  3864  4189 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:02:27.186  3864  4200 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-08 14:02:27.186  3864  4200 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:27.186  3864  4192 D BluetoothAdapterProperties: Scan Mode:20
,07-08 14:02:27.187   933  1133 D CachedBluetoothDevice:  Clearing all connection state for dev:ALE-L21
,07-08 14:02:27.192  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:27.193  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:27.200  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:27.204  1566  1566 E ActivityThread: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@9d8e8e8 that was originally bound here
07-08 14:02:27.204  1566  1566 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.nearby.discovery.service.DiscoveryService has leaked ServiceConnection rbs@9d8e8e8 that was originally bound here
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at rbx.run(:com.google.android.gms:94)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:27.204  1566  1566 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:27.208  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:27.209  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:27.211  1566  4206 E NearbyDiscovery: Failed to unbind NearbyDirect
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: java.lang.IllegalArgumentException: Service not registered: rbs@9d8e8e8
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at rbr.c(:com.google.android.gms:181)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at rca.run(:com.google.android.gms:1023)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:27.211  1566  4206 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:27.215  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:27.223  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:27.226  1566  4339 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:02:27.227  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:27.237  1566  4339 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-08 14:02:27.272  1566  1573 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f62249a)
,07-08 14:02:27.298  3864  4192 I bt_hci  : shut_down
,07-08 14:02:27.302  3864  4196 I bt_vendor: low_power_mode_cb
,07-08 14:02:27.303  3864  4196 D bt_hwcfg: hw_epilog_process
,07-08 14:02:27.327  3864  4196 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-08 14:02:27.327  3864  4196 I bt_vendor: epilog_cb
,07-08 14:02:27.327  3864  4196 I bt_hci  : epilog_finished_callback
,07-08 14:02:27.328  3864  4192 I bt_hci_h4: hal_close
07-08 14:02:27.328  3864  4192 I bt_userial_vendor: device fd = 49 close
,07-08 14:02:27.332  3864  4189 D bt_stack_manager: event_shut_down_stack finished.
,07-08 14:02:27.332  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-08 14:02:27.334  3864  3864 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:02:27.334  3864  4188 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-08 14:02:27.334  3864  3864 D BtGatt.GattService: Received stop request...Stopping profile...
07-08 14:02:27.334  3864  3864 D BtGatt.GattService: stop()
07-08 14:02:27.334  3864  3864 D BtGatt.AdvertiseManager: advertise clients cleared
,07-08 14:02:27.335  3864  3864 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:27.335  3864  3864 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:27.335  3864  3864 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:27.335  3864  3864 V BluetoothAdapterState: isBleTurningOff()=true
07-08 14:02:27.335  3864  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:02:27.335  3864  4188 D BluetoothAdapterProperties: Setting state to 10
07-08 14:02:27.335  3864  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-08 14:02:27.336  3864  4188 I BluetoothAdapterState: Entering OffState
,07-08 14:02:27.336   786   810 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-08 14:02:27.340  3864  3864 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-08 14:02:27.340  3864  3864 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:02:27.340  3864  3864 I BluetoothServiceJni: cleanupNative: return from cleanup
07-08 14:02:27.340  3864  4189 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-08 14:02:27.342  3864  3864 I art     : System.exit called, status: 0
,07-08 14:02:27.342  3864  3864 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:02:27.342  1566  1566 I BeaconBle: Scan : No clients left, canceling alarm.
,07-08 14:02:27.357   786  2118 I ActivityManager: Process com.android.bluetooth (pid 3864) has died
,07-08 14:02:27.418  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:27.418  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:27.418  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:27.620   786   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-08 14:02:27.671   786   813 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-08 14:02:27.675   786   811 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-08 14:02:27.678   191   191 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
07-08 14:02:27.678   191   191 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-08 14:02:27.720  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:27.720  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:27.720  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:27.947   191   191 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-08 14:02:27.950   786   911 D SurfaceControl: Excessive delay in setPowerMode(): 275ms
,07-08 14:02:27.951  1804  1821 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-08 14:02:27.965   198   198 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-08 14:02:27.968   786   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:02:27.969   786   891 E WifiNative-wlan0: Update priority failed for :0
,07-08 14:02:27.969   786   891 E WifiStateMachine:  Fail to set up pno, want false now false
,07-08 14:02:27.990   786   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:02:27.991   786   891 E WifiNative-wlan0: Update priority failed for :0
07-08 14:02:27.991   786   891 E WifiStateMachine:  Fail to set up pno, want false now false
07-08 14:02:27.992   198   900 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-08 14:02:27.998  1237  1237 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-08 14:02:28.023  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.023  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:28.023  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:28.326  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.326  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:28.326  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:28.630  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.630  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:28.630  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:28.931  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.931  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:28.931  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:29.234  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.234  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at akll.a(:com.google.android.gms:93)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:262)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at akmw.a(:com.google.android.gms:294)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at aknc.run(:com.google.android.gms:126)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:29.234  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:29.239  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.239  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at aksp.c(:com.google.android.gms:36)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at akrf.c(:com.google.android.gms:175)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:29.239  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:29.445  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.445  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at aklk.a(:com.google.android.gms:129)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:29.445  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:29.452  1566  4248 W MessageQueue: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.452  1566  4248 W MessageQueue: java.lang.IllegalStateException: Handler (akgv) {d0cb1cb} sending message to a Handler on a dead thread
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:543)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at rbv.a(:com.google.android.gms:1065)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akox.a(:com.google.android.gms:140)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akuj.a(:com.google.android.gms:374)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at aksn.a(:com.google.android.gms:2077)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akrj.run(:com.google.android.gms:98)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at aksp.a(:com.google.android.gms:71)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at aksp.d(:com.google.android.gms:44)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akrh.a(:com.google.android.gms:65)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at aklk.a(:com.google.android.gms:130)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akrf.c(:com.google.android.gms:177)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akrk.run(:com.google.android.gms:3021)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at akgv.handleMessage(:com.google.android.gms:233)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:29.452  1566  4248 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:02:31.965  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:02:31.965  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:02:31.972  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:31.972  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c14d31 added. We now have 6 listener(s)
,07-08 14:02:31.973  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:31.977  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:31.977  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db8fc16 added. We now have 7 listener(s)
07-08 14:02:31.978  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:31.979  3702  3767 I System.out: IsBluetoothEnabled
,07-08 14:02:31.993  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:32.028   786   810 I ActivityManager: Start proc 4357:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding A2dpService
07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding HidService
07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding HealthService
07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding PanService
07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding GattService
07-08 14:02:32.079  4357  4357 D AdapterServiceConfig: Adding BluetoothMapService
,07-08 14:02:32.088   786   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f5c247:true
,07-08 14:02:32.089  4357  4357 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:02:32.091  4357  4357 I bt_bluedroid: init
,07-08 14:02:32.092  4357  4369 I BluetoothAdapterState: Entering OffState
,07-08 14:02:32.093  4357  4370 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-08 14:02:32.093  4357  4370 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:02:32.093  4357  4370 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-08 14:02:32.094  4357  4370 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-08 14:02:32.094  4357  4357 I bt_bluedroid: get_profile_interface socket
,07-08 14:02:32.095  4357  4357 I bt_bluedroid: get_profile_interface sdp
,07-08 14:02:32.097  4357  4367 I bt_bluedroid: config_hci_snoop_log
,07-08 14:02:32.098   786   810 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-08 14:02:32.100  4357  4369 D BluetoothAdapterState: Current state: OFF, message: 0
07-08 14:02:32.100  4357  4369 D BluetoothAdapterProperties: Setting state to 14
07-08 14:02:32.100  4357  4369 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-08 14:02:32.101  4357  4369 D BluetoothBondStateMachine: make
,07-08 14:02:32.103  4357  4373 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-08 14:02:32.105  4357  4373 D BluetoothAdapterProperties: Name is: Nexus 5
07-08 14:02:32.108  4357  4357 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-08 14:02:32.109  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:32.109  4357  4369 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:02:32.110  4357  4357 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:02:32.110  4357  4357 D BtGatt.GattService: Received start request. Starting profile...
07-08 14:02:32.110  4357  4357 D BtGatt.GattService: start()
07-08 14:02:32.110  4357  4357 I bt_bluedroid: get_profile_interface gatt
07-08 14:02:32.111  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:32.111  4357  4357 D BtGatt.AdvertiseManager: advertise manager created
07-08 14:02:32.111  4357  4374 I BluetoothBondStateMachine: StableState(): Entering Off State
07-08 14:02:32.116  4357  4357 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:32.116  4357  4357 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:32.116  4357  4357 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:02:32.116  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:32.116  4357  4369 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:02:32.116  4357  4369 I bt_bluedroid: enable
07-08 14:02:32.117  4357  4370 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:02:32.117  4357  4370 I bt_hci  : start_up
,07-08 14:02:32.124  4357  4370 I bt_vendor: alloc value 0xb39ee631
,07-08 14:02:32.124  4357  4370 I bt_vendor: init
07-08 14:02:32.124  4357  4370 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-08 14:02:32.124  4357  4370 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-08 14:02:32.156  4357  4370 D bt_hci  : start_up starting async portion
,07-08 14:02:32.156  4357  4381 I bt_hci  : event_finish_startup
07-08 14:02:32.156  4357  4381 I bt_hci_h4: hal_open
07-08 14:02:32.156  4357  4381 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-08 14:02:32.159  4357  4381 I bt_userial_vendor: device fd = 49 open
,07-08 14:02:32.245  4357  4381 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:02:32.272  4357  4381 D bt_hwcfg: Chipset BCM4335C0
07-08 14:02:32.272  4357  4381 D bt_hwcfg: Target name = [BCM4335C0]
,07-08 14:02:32.272  4357  4381 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-08 14:02:32.659  4357  4381 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:02:32.659  4357  4381 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:02:32.659  4357  4381 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:02:32.774  4357  4381 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:02:32.774  4357  4381 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-08 14:02:32.805  4357  4381 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:02:32.805  4357  4381 I bt_vendor: firmware callback
07-08 14:02:32.805  4357  4381 I bt_hci  : firmware_config_callback
,07-08 14:02:32.812  4357  4389 I bt_btu  : btu_task pending for preload complete event
,07-08 14:02:32.812  4357  4389 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:02:32.812  4357  4389 I bt_btu  : btu_task received preload complete event
,07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_A2D
,07-08 14:02:32.817  4357  4389 I         : BTE_InitTraceLevels -- TRC_BNEP
07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_BTM
,07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_GAP
07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_PAN
,07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_SDP
07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_GATT
,07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_SMP
07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-08 14:02:32.818  4357  4389 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:02:33.053  4357  4389 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396c9b5
,07-08 14:02:33.053  4357  4389 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396c9b5 
,07-08 14:02:33.130  4357  4373 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:02:33.130  4357  4373 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-08 14:02:33.166  4357  4373 D BluetoothAdapterProperties: Name is: Nexus 5
07-08 14:02:33.167  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:33.168  4357  4373 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:33.168  4357  4373 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:02:33.169  4357  4373 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-08 14:02:33.169  4357  4373 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
,07-08 14:02:33.169  4357  4373 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
,07-08 14:02:33.169  4357  4373 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
,07-08 14:02:33.169  4357  4373 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
,07-08 14:02:33.169  4357  4373 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
,07-08 14:02:33.170  4357  4373 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-08 14:02:33.171  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-08 14:02:33.173  4357  4357 I BluetoothHidServiceJni: classInitNative: succeeds
,07-08 14:02:33.173  4357  4357 D HidService: getHidService(): service is NULL
,07-08 14:02:33.176  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,07-08 14:02:33.177  4357  4357 D HidService: getHidService(): service is NULL
,07-08 14:02:33.179  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-08 14:02:33.180  4357  4357 D HidService: getHidService(): service is NULL
,07-08 14:02:33.184  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-08 14:02:33.185  4357  4357 D HidService: getHidService(): service is NULL
,07-08 14:02:33.188  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,07-08 14:02:33.189  4357  4357 D HidService: getHidService(): service is NULL
,07-08 14:02:33.191  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,07-08 14:02:33.192  4357  4357 D HidService: getHidService(): service is NULL
,07-08 14:02:33.193  4357  4373 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-08 14:02:33.194  4357  4357 D HidService: getHidService(): service is NULL
07-08 14:02:33.195  4357  4373 D bt_hci  : do_postload posting postload work item
07-08 14:02:33.195  4357  4381 I bt_hci  : event_postload
07-08 14:02:33.195  4357  4381 I bt_vendor: sco_config_cb
07-08 14:02:33.195  4357  4381 I bt_hci  : sco_config_callback postload finished.
07-08 14:02:33.197  4357  4381 I bt_vendor: low_power_mode_cb
07-08 14:02:33.200  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.200  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.203  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.203  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.207  4357  4373 D bt_bte_conf: Device ID record 1 : primary
07-08 14:02:33.207  4357  4373 D bt_bte_conf:   vendorId            = 000f
,07-08 14:02:33.207  4357  4373 D bt_bte_conf:   vendorIdSource      = 0001
,07-08 14:02:33.207  4357  4373 D bt_bte_conf:   product             = 1200
,07-08 14:02:33.207  4357  4373 D bt_bte_conf:   version             = 1436
,07-08 14:02:33.207  4357  4373 D bt_bte_conf:   clientExecutableURL = 
07-08 14:02:33.207  4357  4373 D bt_bte_conf:   serviceDescription  = 
07-08 14:02:33.207  4357  4373 D bt_bte_conf:   documentationURL    = 
07-08 14:02:33.208  4357  4373 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-08 14:02:33.208  4357  4370 D bt_stack_manager: event_start_up_stack finished
,07-08 14:02:33.208  4357  4369 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-08 14:02:33.208  4357  4369 D BluetoothAdapterProperties: Setting state to 15
07-08 14:02:33.208  4357  4369 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:02:33.208  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.209  4357  4369 I BluetoothAdapterState: Entering BleOnState
07-08 14:02:33.210  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-08 14:02:33.210  4357  4369 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:02:33.210  4357  4369 D BluetoothAdapterProperties: Setting state to 11
07-08 14:02:33.210  4357  4369 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-08 14:02:33.213  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
,07-08 14:02:33.214  4357  4357 D HeadsetService: Received start request. Starting profile...
,07-08 14:02:33.214  4357  4357 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-08 14:02:33.214  4357  4357 D HeadsetStateMachine: make
,07-08 14:02:33.225  4357  4369 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:33.227  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
,07-08 14:02:33.227  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.231  4357  4357 D HeadsetStateMachine: max_hf_connections = 1
,07-08 14:02:33.231  4357  4357 I bt_bluedroid: get_profile_interface handsfree
,07-08 14:02:33.234   933  1133 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.234   933  1133 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.236  4357  4373 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-08 14:02:33.236  4357  4373 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-08 14:02:33.240  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:33.240  4357  4357 D A2dpService: Received start request. Starting profile...
07-08 14:02:33.241  4357  4357 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-08 14:02:33.241  4357  4357 I bt_bluedroid: get_profile_interface avrcp
07-08 14:02:33.248  4357  4357 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-08 14:02:33.249  4357  4357 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-08 14:02:33.249  4357  4357 D A2dpStateMachine: make
07-08 14:02:33.253  4357  4357 I bt_bluedroid: get_profile_interface a2dp
07-08 14:02:33.253  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.254  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.254  4357  4373 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-08 14:02:33.256  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:33.256  4357  4407 D A2dpStateMachine: Enter Disconnected: -2
07-08 14:02:33.257  4357  4357 D HidService: Received start request. Starting profile...
07-08 14:02:33.257  4357  4357 I bt_bluedroid: get_profile_interface hidhost
,07-08 14:02:33.257  4357  4357 D HidService: setHidService(): set to: null
07-08 14:02:33.258  4357  4373 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394e099
07-08 14:02:33.258  4357  4373 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-08 14:02:33.258  4357  4357 I BluetoothHealthServiceJni: classInitNative: succeeds
07-08 14:02:33.259  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:33.259  4357  4357 D HealthService: Received start request. Starting profile...
07-08 14:02:33.261  4357  4357 I bt_bluedroid: get_profile_interface health
07-08 14:02:33.261  4357  4357 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-08 14:02:33.262  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:33.263  4357  4357 D PanService: Received start request. Starting profile...
07-08 14:02:33.263  4357  4357 D BluetoothPanServiceJni: initializeNative(L110): pan
07-08 14:02:33.263  4357  4357 I bt_bluedroid: get_profile_interface pan
,07-08 14:02:33.263  4357  4373 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-08 14:02:33.269  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.269  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.273  4357  4357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17292e0
07-08 14:02:33.273  4357  4357 D BluetoothMapService: Received start request. Starting profile...
07-08 14:02:33.273  4357  4357 D BluetoothMapService: start()
07-08 14:02:33.276  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.277  4357  4357 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-08 14:02:33.277  4357  4357 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-08 14:02:33.277  4357  4357 D BluetoothMapAppObserver: createReceiver()
07-08 14:02:33.278  4357  4357 D BluetoothMapAppObserver: initObservers()
07-08 14:02:33.278  4357  4357 D BluetoothMapAppObserver: getEnabledAccountItems()
07-08 14:02:33.279  3818  3818 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.283  4357  4357 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:33.283  4357  4357 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:33.283  4357  4357 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:33.283  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:33.284  4357  4402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:33.285  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:33.286  4357  4357 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:02:33.286  4357  4357 V BluetoothAdapterState: isTurningOn()=true
07-08 14:02:33.286  4357  4357 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:33.286  4357  4357 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:33.287  4357  4369 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-08 14:02:33.287  4357  4369 D BluetoothAdapterProperties: ScanMode =  20
07-08 14:02:33.287  4357  4369 D BluetoothAdapterProperties: State =  11
07-08 14:02:33.287  4357  4369 D BluetoothAdapterProperties: Setting state to 12
07-08 14:02:33.287  4357  4369 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-08 14:02:33.288  4357  4369 I BluetoothAdapterState: Entering OnState
07-08 14:02:33.288   933  3842 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:02:33.288  4357  4373 D BluetoothAdapterProperties: Scan Mode:21
07-08 14:02:33.288  4357  4373 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:02:33.287   933  1133 E BluetoothDevice: BT not enabled. Cannot get remote device Uuids
07-08 14:02:33.290   786   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:33.290  1298  1313 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:33.292  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:33.293  3818  3839 D BluetoothMap: onBluetoothStateChange: up=true
,07-08 14:02:33.294   786   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:33.294   786   810 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:02:33.295   933   945 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:33.295  3818  4236 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:33.296   933   951 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:02:33.297  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:33.298   786   786 D BluetoothA2dp: Proxy object connected
07-08 14:02:33.298  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:02:33.298  3702  3768 I jxcore-log: 
07-08 14:02:33.299  3818  3839 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:02:33.301   933  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:02:33.303  3818  3818 D BluetoothMap: Proxy object connected
07-08 14:02:33.303  4357  4357 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:02:33.304  3818  3818 D MapProfile: Bluetooth service connected
07-08 14:02:33.304  3818  3818 D BluetoothMap: getConnectedDevices()
07-08 14:02:33.304  4357  4357 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-08 14:02:33.306   786   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:02:33.306  4357  4357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:02:33.306   933   933 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:02:33.306   933   933 D PanProfile: Bluetooth service connected
07-08 14:02:33.307   933   951 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:02:33.308  3818  3839 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:02:33.309  4357  4357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:02:33.309  3818  3818 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:02:33.309  3818  3818 D PanProfile: Bluetooth service connected
07-08 14:02:33.310  3818  3818 D BluetoothA2dp: Proxy object connected
07-08 14:02:33.310  3818  3834 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:02:33.311  4357  4357 D ObexServerSockets: Succeed to create listening sockets 
07-08 14:02:33.311  4357  4357 D ObexServerSockets0: startAccept()
07-08 14:02:33.311  4357  4357 D ObexServerSockets0: prepareForNewConnect()
07-08 14:02:33.311  3818  4236 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:02:33.312   933  1387 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:02:33.313  4357  4357 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-08 14:02:33.313  4357  4357 D BluetoothSdpJni: SDP Create record success - handle: 0
07-08 14:02:33.314  4357  4423 D ObexServerSockets0: Accepting socket connection...
07-08 14:02:33.314  4357  4424 D ObexServerSockets0: Accepting socket connection...
07-08 14:02:33.314   786   786 I Telecom : BluetoothPhoneService: queryPhoneState
07-08 14:02:33.317  4357  4357 D BluetoothMapService: onReceive
07-08 14:02:33.317  4357  4357 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:02:33.317  4357  4357 D BluetoothMapService: STATE_ON
07-08 14:02:33.317   933   933 D BluetoothMap: Proxy object connected
07-08 14:02:33.317   933   933 D MapProfile: Bluetooth service connected
07-08 14:02:33.317   933   933 D BluetoothMap: getConnectedDevices()
07-08 14:02:33.319   933   933 D BluetoothA2dp: Proxy object connected
07-08 14:02:33.321   933   933 D BluetoothInputDevice: Proxy object connected
07-08 14:02:33.321   933   933 D HidProfile: Bluetooth service connected
07-08 14:02:33.322  3818  3818 D BluetoothInputDevice: Proxy object connected
07-08 14:02:33.322  3818  3818 D HidProfile: Bluetooth service connected
,07-08 14:02:33.333   933  1133 D BluetoothMap: getConnectedDevices()
07-08 14:02:33.334   933  1133 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
07-08 14:02:33.336  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-08 14:02:33.338  4357  4357 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:02:33.338  4357  4357 D ObexServerSockets0: prepareForNewConnect()
07-08 14:02:33.339   933  1133 D MapProfile: getConnectionStatus: status is: 0
07-08 14:02:33.339  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-08 14:02:33.341  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:02:33.348  3818  3818 D DockEventReceiver: finishStartingService: stopping service
07-08 14:02:33.356  4357  4430 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:02:33.359  3818  3818 D BluetoothPbap: Proxy object connected
07-08 14:02:33.359  3818  3818 D PbapServerProfile: Bluetooth service connected
07-08 14:02:33.362  1566  4260 D BluetoothAdapter: startLeScan(): null
07-08 14:02:33.363  1566  4260 D BluetoothAdapter: STATE_ON
07-08 14:02:33.365  4357  4391 D BtGatt.GattService: registerClient() - UUID=fffce971-a6b4-425f-974e-afe1fd4a23b3
07-08 14:02:33.365  4357  4373 D BtGatt.GattService: onClientRegistered() - UUID=fffce971-a6b4-425f-974e-afe1fd4a23b3, clientIf=5
,07-08 14:02:33.366  1566  1633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:02:33.366   933   933 D BluetoothPbap: Proxy object connected
07-08 14:02:33.366  4357  4367 D BtGatt.GattService: start scan with filters
07-08 14:02:33.366   933   933 D PbapServerProfile: Bluetooth service connected
07-08 14:02:33.368  4357  4376 D BtGatt.ScanManager: handling starting scan
,07-08 14:02:33.370  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-08 14:02:33.370  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-08 14:02:33.370  4357  4376 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-08 14:02:33.370  4357  4373 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-08 14:02:33.376  1566  1566 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:33.381  1566  4437 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:02:33.382  1566  1566 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:33.383  4357  4438 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:02:33.389  4357  4438 I BtOppRfcommListener: Accept thread started.
,07-08 14:02:33.394   786   786 D BluetoothHeadset: Proxy object connected
,07-08 14:02:33.394  3818  3839 D BluetoothHeadset: Proxy object connected
07-08 14:02:33.394  3818  3818 D HeadsetProfile: Bluetooth service connected
07-08 14:02:33.395   786   810 D BluetoothHeadset: Proxy object connected
,07-08 14:02:33.395  1298  1419 D BluetoothHeadset: Proxy object connected
07-08 14:02:33.395   933   945 D BluetoothHeadset: Proxy object connected
07-08 14:02:33.396   933  3842 D BluetoothHeadset: Proxy object connected
,07-08 14:02:33.396   786   786 D BluetoothHeadset: Proxy object connected
07-08 14:02:33.396   786   786 D BluetoothHeadset: Proxy object connected
,07-08 14:02:33.397  3818  3834 D BluetoothHeadset: Proxy object connected
07-08 14:02:33.397  1566  4437 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-08 14:02:33.400  3818  3818 D HeadsetProfile: Bluetooth service connected
,07-08 14:02:33.402   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:33.403   933  1133 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-08 14:02:33.405   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:33.405   933   933 D HeadsetProfile: Bluetooth service connected
07-08 14:02:33.405   786   810 D BluetoothHeadset: Proxy object connected
,07-08 14:02:33.407   933   933 D HeadsetProfile: Bluetooth service connected
,07-08 14:02:33.419   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:33.420   933  1133 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-08 14:02:33.421   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:33.435   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:33.436   933  1133 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-08 14:02:33.437   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:33.449   933  1133 D BluetoothMap: getConnectedDevices()
,07-08 14:02:33.451   933  1133 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-08 14:02:33.453   933  1133 D MapProfile: getConnectionStatus: status is: 0
,07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:34.040  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:34.046  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:34.049  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:34.049  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3963997 added. We now have 8 listener(s)
,07-08 14:02:34.050  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:34.055  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:02:34.055  3702  3768 I jxcore-log: 
,07-08 14:02:34.062   786  3196 D WifiService: setWifiEnabled: false pid=3702, uid=10026
,07-08 14:02:34.062   786  3196 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:34.075  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:34.076   786   797 D WifiService: setWifiEnabled: true pid=3702, uid=10026
,07-08 14:02:34.076   786   797 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:02:34.090   194   698 D SoftapController: Softap fwReload - Ok
,07-08 14:02:34.091   194   698 D CommandListener: Setting iface cfg
,07-08 14:02:34.091   194   698 D CommandListener: Trying to bring down wlan0
,07-08 14:02:34.091   194   698 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:02:34.093   786   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:02:34.876  1566  4260 D BluetoothAdapter: stopLeScan()
,07-08 14:02:34.878  1566  4260 D BluetoothAdapter: STATE_ON
,07-08 14:02:34.880  4357  4391 D BtGatt.GattService: stopScan() - queue size =1
,07-08 14:02:34.881  4357  4368 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-08 14:02:34.882  4357  4376 D BtGatt.ScanManager: stop scan
07-08 14:02:34.883  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-08 14:02:34.883  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-08 14:02:34.883  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-08 14:02:34.948   786   891 D wifi    : set interface wlan0 flags (UP)
,07-08 14:02:34.948   786   891 I WifiHAL : Initializing wifi
07-08 14:02:34.948   786   891 I WifiHAL : Creating socket
,07-08 14:02:34.956   786   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-08 14:02:34.956   786   891 D wifi    : Did set static halHandle = 0xa07cfb10
,07-08 14:02:34.957   786   891 D wifi    : halHandle = 0xa07cfb10, mVM = 0xb4d7c000, mCls = 0x101302
07-08 14:02:34.957   786   810 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-08 14:02:34.957   786   891 D wifi    : array field set
,07-08 14:02:34.957   786   891 I WifiNative-HAL: interface[0] = p2p0
07-08 14:02:34.957   786   891 I WifiNative-HAL: interface[1] = wlan0
07-08 14:02:34.960   786  4479 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602422000
,07-08 14:02:34.960   786  4479 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x101302, env = 0x9342c0e0
,07-08 14:02:35.001  4480  4480 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-08 14:02:35.021  4480  4480 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:02:35.030  4480  4480 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:02:35.058  1566  4260 D BluetoothAdapter: startLeScan(): null
,07-08 14:02:35.060  1566  4260 D BluetoothAdapter: STATE_ON
,07-08 14:02:35.062  4357  4399 D BtGatt.GattService: registerClient() - UUID=f9a23d2f-06e7-4141-a1f4-29c911894865
,07-08 14:02:35.062  4357  4373 D BtGatt.GattService: onClientRegistered() - UUID=f9a23d2f-06e7-4141-a1f4-29c911894865, clientIf=5
,07-08 14:02:35.062  1566  1576 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:02:35.062  4357  4367 D BtGatt.GattService: start scan with filters
07-08 14:02:35.064  4357  4376 D BtGatt.ScanManager: handling starting scan
,07-08 14:02:35.065  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-08 14:02:35.066  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-08 14:02:35.066  4357  4376 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-08 14:02:35.066  4357  4373 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-08 14:02:35.068   786   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-08 14:02:35.071  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:35.078  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:35.080  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:35.081  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:35.081  3702  3768 I jxcore-log: 
,07-08 14:02:35.082   786   891 D WifiConfigStore: Loading config and enabling all networks 
07-08 14:02:35.088   786   891 D WifiConfigStore: loaded 0 passpoint configs
,07-08 14:02:35.089   786   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-08 14:02:35.090   786   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:02:35.090   786   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-08 14:02:35.090   786   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-08 14:02:35.093   786   891 D WifiNative-HAL: Setting external_sim to 1
07-08 14:02:35.093   786   891 D wifi    : setting dfs flag to true, 0x9915a8a8
07-08 14:02:35.093   786   891 D WifiStateMachine: Setting OUI to DA-A1-19
07-08 14:02:35.093   786   891 D wifi    : setting scan oui 0x9915a8a8
07-08 14:02:35.093   786   891 D WifiHAL : Sending mac address OUI
,07-08 14:02:35.102   786   891 E native  : do suspend true
,07-08 14:02:35.107   786   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-08 14:02:35.107   786   891 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 1
07-08 14:02:35.107   786   786 D RttService: SCAN_AVAILABLE : 3
07-08 14:02:35.108   786   908 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-08 14:02:35.108   194   698 D CommandListener: Setting iface cfg
07-08 14:02:35.108   194   698 D CommandListener: Trying to bring up p2p0
07-08 14:02:35.108   786   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-08 14:02:35.119   786   890 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:02:35.119   786   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-08 14:02:35.125   786   891 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 10, 12 -> obsolete
,07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.116  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:36.122  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:36.130  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-08 14:02:36.131  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-08 14:02:36.139  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.139  3702  3768 I jxcore-log: 
,07-08 14:02:36.158  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5c3d72b Bundle[{}]
,07-08 14:02:36.161  3702  3767 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:02:36.162  3702  3767 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-08 14:02:36.162  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-08 14:02:36.162  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-08 14:02:36.163  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-08 14:02:36.163  3702  3767 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-08 14:02:36.167  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-08 14:02:36.167  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,07-08 14:02:36.168  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-08 14:02:36.168  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-08 14:02:36.168  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-08 14:02:36.168  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:02:36.173  3702  3767 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 344)
,07-08 14:02:36.173  3702  3767 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 344)
,07-08 14:02:36.173  3702  3767 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 344)
,07-08 14:02:36.173  3702  3767 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 344)
,07-08 14:02:36.174  3702  3767 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 350)
07-08 14:02:36.174  3702  3767 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 350)
,07-08 14:02:36.175  3702  3767 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 350)
,07-08 14:02:36.175  3702  3767 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 351)
,07-08 14:02:36.176  3702  3767 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 353)
,07-08 14:02:36.178  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:02:36.178  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4cb784 added. We now have 2 listener(s)
,07-08 14:02:36.179  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-08 14:02:36.179  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.179  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.179  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.180  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aac8b6d added. We now have 9 listener(s)
07-08 14:02:36.180  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.181  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:36.181  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:02:36.183  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.184  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.185  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.185  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.186  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.186  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.187  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.187  3702  3768 I jxcore-log: 
07-08 14:02:36.187  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.187  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57ad833 added. We now have 3 listener(s)
,07-08 14:02:36.188  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.188  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.188  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:02:36.188  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.188  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9fc7f0 added. We now have 10 listener(s)
07-08 14:02:36.189  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.189  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.189  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.189  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.189  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.189  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.189  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.189  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.189  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4cb784 removed from the list
07-08 14:02:36.189  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.189  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aac8b6d removed from the list
07-08 14:02:36.189  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.189  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.190  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.190  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.190  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.190  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aac8b6d not in the list
07-08 14:02:36.190  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.190  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.190  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.190  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9fc7f0 removed from the list
07-08 14:02:36.190  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.190  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.190  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.190  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07,-08 14:02:36.190  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57ad833 removed from the list
07-08 14:02:36.191  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.191  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f937169 added. We now have 2 listener(s)
07-08 14:02:36.192  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.193  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.193  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.193  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.193  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8b77ee added. We now have 9 listener(s)
07-08 14:02:36.193  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.194  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:36.194  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:02:36.196  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.198  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.200  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.200  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.200  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.201  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.202  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.202  3702  3768 I jxcore-log: 
07-08 14:02:36.202  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.202  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d1731c added. We now have 3 listener(s)
07-08 14:02:36.204  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.204  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.204  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.204  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.204  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae8bb25 added. We now have 10 listener(s)
07-08 14:02:36.204  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.204  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.204  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:02:36.204  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.204  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:02:36.218  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.219  3702  3767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:02:36.219  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.219  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.220  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.220  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.220  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.220  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.220  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.220  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:02:36.220  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.220  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f937169 removed from the list
07-08 14:02:36.220  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.220  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8b77ee removed from the list
07-08 14:02:36.220  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.220  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.221  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.221  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:02:36.221  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.221  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.221  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.221  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8b77ee not in the list
07-08 14:02:36.221  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.221  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.221  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.221  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae8bb25 removed from the list
07-08 14:02:36.221  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.221  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.221  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.221  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.221  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d1731c removed from the list
07-08 14:02:36.222  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.222  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54f1aab added. We now have 2 listener(s)
07-08 14:02:36.223  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.223  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.223  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.223  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.223  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810a508 added. We now have 9 listener(s)
07-08 14:02:36.223  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.225  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:36.225  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:02:36.226  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.228  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.229  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.229  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.229  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.230  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50696c6 added. We now have 3 listener(s)
07-08 14:02:36.230  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.231  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.232  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.232  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.232  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.232  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.232  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e2b687 added. We now have 10 listener(s)
07-08 14:02:36.232  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.232  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.232  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.232  3702  3768 I jxcore-log: 
07-08 14:02:36.232  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.232  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:02:36.232  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.232  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:02:36.235  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.235  3702  3767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:02:36.235  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.235  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.235  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.235  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.235  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.235  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:02:36.235  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.235  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54f1aab removed from the list
07-08 14:02:36.235  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.235  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810a508 removed from the list
07-08 14:02:36.235  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.235  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.235  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.235  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:02:36.236  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.236  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.236  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.236  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810a508 not in the list
07-08 14:02:36.236  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.236  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.236  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.236  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e2b687 removed from the list
07-08 14:02:36.236  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.236  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.236  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.236  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.236  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50696c6 removed from the list
07-08 14:02:36.237  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.237  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1429dd added. We now have 2 listener(s)
07-08 14:02:36.238  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.238  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.238  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.238  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.238  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d455952 added. We now have 9 listener(s)
07-08 14:02:36.238  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.239  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:36.239  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:02:36.241  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.243  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.244  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.244  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.244  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.244  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ed0d20 added. We now have 3 listener(s)
07-08 14:02:36.245  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.245  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.246  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.246  3702  3768 I jxcore-log: 
07-08 14:02:36.246  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.246  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.246  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.246  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.246  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae86d9 added. We now have 10 listener(s)
07-08 14:02:36.246  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.247  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.247  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:02:36.247  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.247  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:02:36.249  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.249  3702  3767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:02:36.250  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.251  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.251  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.251  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.251  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.251  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1429dd removed from the list
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.251  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d455952 removed from the list
07-08 14:02:36.251  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.251  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.251  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.251  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:02:36.251  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.251  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.251  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d455952 not in the list
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.251  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.251  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae86d9 removed from the list
07-08 14:02:36.251  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.251  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.252  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.252  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.252  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ed0d20 removed from the list
07-08 14:02:36.252  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.252  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae1ef7f added. We now have 2 listener(s)
07-08 14:02:36.254  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.254  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.254  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.254  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.254  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@465db4c added. We now have 9 listener(s)
07-08 14:02:36.254  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.255  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:36.255  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-08 14:02:36.257  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.259  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.260  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.260  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.260  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.260  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a6c0aa added. We now have 3 listener(s)
07-08 14:02:36.261  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.261  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.262  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.262  3702  3768 I jxcore-log: 
07-08 14:02:36.263  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.263  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.263  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.263  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.263  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430049b added. We now have 10 listener(s)
07-08 14:02:36.263  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.263  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.263  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.263  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.263  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.263  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.263  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.263  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.263  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae1ef7f removed from the list
07-08 14:02:36.263  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.263  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@465db4c removed from the list
07-08 14:02:36.263  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.263  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.263  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.264  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.264  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.264  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@465db4c not in the list
07-08 14:02:36.264  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.264  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.264  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.264  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430049b removed from the list
07-08 14:02:36.264  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.264  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.264  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.264  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.264  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a6c0aa removed from the list
07-08 14:02:36.264  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:02:36.264  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 added. We now have 2 listener(s)
07-08 14:02:36.266  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-08 14:02:36.266  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:36.266  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:36.266  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:36.266  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 added. We now have 9 listener(s)
07-08 14:02:36.266  3702  3767 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:36.267  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:36.267  3702  3767 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:02:36.269  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.271  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.272  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.272  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.273  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.274  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.274  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:02:36.274  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:02:36.274  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:02:36.274  3702  3767 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-08 14:02:36.275  3702  3767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-08 14:02:36.275  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:02:36.275  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:02:36.275  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:02:36.275  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.275  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.275  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.275  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.275  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.275  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.275  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:36.276  3702  3767 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 removed from the list
07-08 14:02:36.276  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.276  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.276  3702  3768 I jxcore-log: 
07-08 14:02:36.276  3702  3767 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 removed from the list
07-08 14:02:36.276  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.276  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.276  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.276  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.276  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.277  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.278  3702  3767 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-08 14:02:36.278  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.278  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.278  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.278  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.278  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.278  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.278  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.278  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.278  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.278  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.279  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.279  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.279  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.279  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.279  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.279  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.280  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:02:36.280  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-08 14:02:36.281  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:02:36.281  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.281  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.282  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.282  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.282  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.282  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.282  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.282  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.282  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.282  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.282  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.282  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.282  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.282  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.282  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.282  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.282  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.282  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.282  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.282  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.282  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.282  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.282  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.282  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.282  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.282  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.282  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.282  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.282  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.282  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.282  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.283  3702  3767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:02:36.284  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.287  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:36.288  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.288  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.289  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.289  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.289  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:02:36.289  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.289  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:02:36.290  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.290  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.290  3702  3768 I jxcore-log: 
07-08 14:02:36.292  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.292  3702  3767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:02:36.292  3702  3767 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:02:36.293  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.293  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.293  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.293  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.293  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.293  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:02:36.293  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.293  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.293  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.293  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.294  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.294  3702  3767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:02:36.295  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.297  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:36.298  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:36.298  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.299  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:36.299  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.299  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-08 14:02:36.300  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:36.301  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.301  3702  3768 I jxcore-log: 
07-08 14:02:36.301  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.301  3702  3767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:02:36.301  3702  3767 I io.jxcore.node.ConnectionHelper: start: OK
,07-08 14:02:36.302  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.302  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.302  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.302  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:02:36.302  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.302  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:02:36.303  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.303  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.303  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.303  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.303  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.303  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.303  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.303  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:02:36.303  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.303  3702  3767 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:02:36.304  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:36.306  3702  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:36.307  3702  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:36.307  3702  3767 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:36.307  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:02:36.307  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:02:36.307  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.307  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-08 14:02:36.309  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:36.309  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:36.310  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:02:36.310  3702  3768 I jxcore-log: 
,07-08 14:02:36.310  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-08 14:02:36.310  3702  3767 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:02:36.311  3702  3767 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:02:36.311  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.311  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.311  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.311  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.311  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.311  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.311  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.311  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.311  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:02:36.311  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.311  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:02:36.311  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.311  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.311  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.311  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.312  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.312  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.312  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.312  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.312  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.312  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.312  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.312  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.312  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.312  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.312  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:02:36.312  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.312  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.312  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.312  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.312  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.312  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.312  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.312  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.313  3702  3767 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-08 14:02:36.313  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.313  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.313  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.313  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:02:36.313  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.313  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.313  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.313  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.313  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.313  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.313  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.313  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.313  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.313  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.313  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.313  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.313  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-08 14:02:36.314  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:02:36.314  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.314  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.314  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.314  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.314  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.314  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.314  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.314  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.314  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.314  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.314  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.314  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:02:36.314  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.314  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.314  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.314  3702  3767 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-08 14:02:36.314  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.314  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.314  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.314  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.314  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.314  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.314  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.314  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.314  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
,07-08 14:02:36.314  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.314  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.314  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.314  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.314  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.314  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.314  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.315  3702  3767 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-08 14:02:36.315  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.315  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.315  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.315  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.315  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:02:36.315  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.315  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.315  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.315  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.315  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.315  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.315  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.315  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.315  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.315  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.315  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.315  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:02:36.315  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-08 14:02:36.315  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:02:36.315  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:02:36.316  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:02:36.316  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:02:36.316  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.316  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.316  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.316  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.316  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.316  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.316  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.316  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.316  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
,07-08 14:02:36.316  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.316  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.316  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.316  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.316  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.316  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.316  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.317  3702  3767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:02:36.317  3702  3767 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-08 14:02:36.317  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:02:36.318  3702  3767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:02:36.318  3702  3767 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-08 14:02:36.318  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:02:36.319  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-08 14:02:36.319  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:02:36.319  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-08 14:02:36.319  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:02:36.319  3702  3767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-08 14:02:36.319  3702  3767 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-08 14:02:36.319  3702  3767 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-08 14:02:36.319  3702  3767 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:02:36.319  3702  3767 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-08 14:02:36.320  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.320  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.320  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:02:36.320  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.320  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.320  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.320  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.320  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.320  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.320  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.320  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.320  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.320  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.320  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.321  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.321  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.321  3702  3767 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-08 14:02:36.321  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.321  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.321  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.321  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.321  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.322  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.322  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.322  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.322  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.322  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.322  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.322  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.322  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.322  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.322  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:02:36.322  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.322  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.322  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.322  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.322  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.322  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.322  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.322  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.322  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.322  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.322  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.322  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.322  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.322  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:02:36.322  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.322  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.322  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.323  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.323  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.323  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.323  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.323  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.323  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.323  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.323  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.323  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
,07-08 14:02:36.323  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.323  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.323  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.323  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.323  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.323  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.323  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.323  3702  3767 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-08 14:02:36.324  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.324  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.324  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.324  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.324  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.324  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.324  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.324  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:02:36.324  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.324  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.324  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.324  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.324  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.324  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.324  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.325  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.325  3702  3767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-08 14:02:36.325  3702  3767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-08 14:02:36.325  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-08 14:02:36.325  3702  3767 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-08 14:02:36.325  3702  3767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-08 14:02:36.325  3702  3767 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-08 14:02:36.325  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-08 14:02:36.325  3702  3767 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-08 14:02:36.325  3702  3767 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-08 14:02:36.325  3702  3767 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-08 14:02:36.325  3702  3767 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:02:36.325  3702  3767 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-08 14:02:36.325  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.325  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-08 14:02:36.325  3702  3768 I jxcore-log: 
07-08 14:02:36.325  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.325  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.325  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.326  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.326  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.326  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.326  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.326  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.326  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.326  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.326  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.326  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.326  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.326  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.326  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.326  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.326  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.326  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:02:36.326  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.326  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.326  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.326  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.326  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:02:36.326  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.326  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.326  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.326  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.326  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.327  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.327  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.327  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.327  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.327  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:02:36.327  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.327  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.327  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.327  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.327  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.327  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.327  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.327  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.327  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.327  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.327  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.327  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.327  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.328  3702  3767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-08 14:02:36.328  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.328  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-08 14:02:36.329  3702  3767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-08 14:02:36.329  3702  3767 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-08 14:02:36.330  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-08 14:02:36.330  3702  3702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-08 14:02:36.330  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.330  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:02:36.330  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-08 14:02:36.330  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-08 14:02:36.330  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-08 14:02:36.330  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.330  3702  4507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-08 14:02:36.330  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.330  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.330  3702  37,67 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:02:36.330  3702  4507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-08 14:02:36.330  3702  3767 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:02:36.330  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:02:36.331  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.331  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.331  3702  3767 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:02:36.331  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:02:36.331  3702  3702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.331  3702  3702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:02:36.332  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.332  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.332  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.332  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:02:36.332  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.332  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.334  3702  3702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.334  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.334  3702  3702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-08 14:02:36.334  3702  3702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-08 14:02:36.334  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.334  3702  3702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:02:36.335  3702  3702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:36.335  3702  3702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:02:36.335  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.335  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.335  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.335  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSetting,s: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.335  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.335  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.335  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.335  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.335  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:02:36.337  3702  3702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:02:36.337  3702  3767 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:02:36.337  3702  3702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:02:36.337  3702  3702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-08 14:02:36.337  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.337  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.337  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.338  3702  3767 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-08 14:02:36.338  3702  3767 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-08 14:02:36.338  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:02:36.338  3702  3767 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:02:36.338  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.338  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.338  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.338  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.338  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.338  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.338  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.338  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.338  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.338  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.338  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.338  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.338  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.338  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.338  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:02:36.338  3702  3768 I jxcore-log: 
07-08 14:02:36.338  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.338  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.341  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.341  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.341  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.341  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.341  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.341  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.341  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.341  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.341  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.341  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.341  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.341  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.341  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.341  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.341  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.341  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.341  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.341  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.341  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.342  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.342  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.342  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.342  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.342  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.342  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.342  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.342  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.342  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.342  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.342  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.342  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.342  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.342  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.342  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.342  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.342  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.342  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.342  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.342  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.342  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.342  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.342  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.342  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.342  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.342  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.342  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.342  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.342  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.343  3702  3767 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-08 14:02:36.343  3702  3767 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-08 14:02:36.343  3702  3702 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-08 14:02:36.344  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-08 14:02:36.344  3702  3768 I jxcore-log: 
07-08 14:02:36.346  3702  3767 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-08 14:02:36.346  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.346  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.346  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.347  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.347  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.347  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.347  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.347  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.347  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.347  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.347  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.347  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.347  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.347  3702  3767 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:02:36.347  3702  3767 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:02:36.347  3702  3767 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:36.347  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.347  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.347  3702  3767 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bb6038 not in the list
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.347  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.347  3702  3767 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:36.347  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.347  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.347  3702  3767 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:36.347  3702  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:36.347  3702  3767 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:36.347  3702  3767 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e693811 not in the list
07-08 14:02:36.348  3702  3767 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-08 14:02:36.348  3702  3767 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-08 14:02:36.348  3702  3767 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-08 14:02:36.348  3702  3767 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-08 14:02:36.348  3702  3767 E com.test.thalitest.ThaliTestRunner: Total duration: 29456 ms
07-08 14:02:36.348  3702  3767 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 29511ms. Plugin should use CordovaInterface.getThreadPool().
,07-08 14:02:36.376  1566  4260 D BluetoothAdapter: stopLeScan()
07-08 14:02:36.379  1566  4260 D BluetoothAdapter: STATE_ON
07-08 14:02:36.379  4357  4368 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:02:36.380  4357  4376 D BtGatt.ScanManager: stop scan
07-08 14:02:36.380  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-08 14:02:36.380  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-08 14:02:36.380  4357  4399 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:02:36.380  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-08 14:02:36.380  1566  4260 I BeaconBle: Scan : No clients left, canceling alarm.
,07-08 14:02:36.974  4480  4480 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-08 14:02:37.022   786   891 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-08 14:02:37.031   786   891 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,07-08 14:02:37.031   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:02:37.042   786   891 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-08 14:02:37.075   786   891 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-08 14:02:37.077  4480  4480 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:02:37.098  4480  4480 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-08 14:02:37.098  4480  4480 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-08 14:02:37.102   786   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:02:37.109   786   891 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-08 14:02:37.109   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:37.109   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:02:37.121   786   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:02:37.130   194   698 D CommandListener: Setting iface cfg
,07-08 14:02:37.133   786   891 D WifiStateMachine: Start Dhcp Watchdog 3
,07-08 14:02:37.138   786   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-08 14:02:37.148   786  4522 D DhcpClient: Receive thread started
,07-08 14:02:37.218   786   891 E native  : do suspend false
,07-08 14:02:37.223   786  4520 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:02:37.231   786  4522 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172778, domain null
,07-08 14:02:37.231   786  4520 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172778 seconds
,07-08 14:02:37.232   786  4520 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-08 14:02:37.240   786  4522 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-08 14:02:37.240   786  4520 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-08 14:02:37.241   194   698 D CommandListener: Setting iface cfg
07-08 14:02:37.243   786   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-08 14:02:37.246   786  4520 D DhcpClient: Scheduling renewal in 86399s
07-08 14:02:37.246   786   891 E native  : do suspend true
,07-08 14:02:37.253   786   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-08 14:02:37.253   786   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-08 14:02:37.253   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-08 14:02:37.254   786   893 D ConnectivityService: Adding iface wlan0 to network 102
07-08 14:02:37.257   786   891 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-08 14:02:37.298   786   893 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-08 14:02:37.298   786   893 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-08 14:02:37.300   786   893 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-08 14:02:37.300   786   893 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-08 14:02:37.301   786   893 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-08 14:02:37.308   786   893 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:02:37.314   786   893 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-08 14:02:37.314   786   893 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-08 14:02:37.314   786   893 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-08 14:02:37.314   786   891 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:02:37.314   786   893 D ConnectivityService:    accepting network in place of null
,07-08 14:02:37.315   786   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:02:37.316   786   893 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:02:37.327   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=161939, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:02:37.346   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:37.376   194   698 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:02:37.379   786   893 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-08 14:02:37.379   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:02:37.379   786   893 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-08 14:02:37.382   786   810 D Tethering: MasterInitialState.processMessage what=3
,07-08 14:02:37.391  3702  3702 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-08 14:02:37.392  3919  3919 E SetupWizard: tickleCheckinService called after completing user setup
,07-08 14:02:37.394  1370  1370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-08 14:02:37.395   786  4514 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:815::200e
,07-08 14:02:37.400  2557  2557 W ChromiumNet: type=1400 audit(0.0:11): avc: denied { ioctl } for path="socket:[25614]" dev="sockfs" ino=25614 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-08 14:02:37.415  1578  1578 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:37.419  3702  3702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:37.422  3702  3702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:02:37.423  3702  3768 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:37.423  3702  3768 I jxcore-log: 
,07-08 14:02:37.426  1578  2882 I iu.UploadsManager: num queued entries: 0
,07-08 14:02:37.428  1578  1578 V Herrevad: NQAS connected
,07-08 14:02:37.431  1578  2882 I iu.UploadsManager: num updated entries: 0
,07-08 14:02:37.432  1578  2882 I iu.SyncManager: NEXT; no task
,07-08 14:02:37.455   786  4514 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jul 2016 12:02:37 GMT], X-Android-Received-Millis=[1467979357453], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467979357426]}
,07-08 14:02:37.456   786   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-08 14:02:37.456   786   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-08 14:02:37.456   786   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:02:37.461   786   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:02:37.489  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:37.491  1578  1612 W Herrevad: Invalid mccmnc 
,07-08 14:02:37.859  1566  4554 I GCM     : Ack for not saved message 49
,07-08 14:02:38.380   786   893 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,07-08 14:02:39.378  1566  4429 I BeaconBle: Scan : No clients left, canceling alarm.
,07-08 14:02:40.223  1566  1703 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:02:45.315   786   893 D ConnectivityService: handlePromptUnvalidated 102
,07-08 14:03:42.977   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227588, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:04:04.891  1578  1643 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:04:42.557   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287168, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:05:20.836  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:05:20.871  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:05:20.872  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:05:40.128  1566  2964 V NativeCrypto: SSL shutdown failed: ssl=0x9a296600: I/O error during system call, Connection timed out
,07-08 14:05:42.399  1578  3111 V NativeCrypto: SSL shutdown failed: ssl=0x92d9d000: I/O error during system call, Connection timed out
,07-08 14:05:42.928  1578  3111 V NativeCrypto: SSL shutdown failed: ssl=0xab44f000: I/O error during system call, Connection timed out
,07-08 14:05:45.019  1566  2964 V NativeCrypto: SSL shutdown failed: ssl=0x9a896400: I/O error during system call, Connection timed out
,07-08 14:06:00.035  1355  1355 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.onStartJob(142): JobScheduler invoked, loading libraries.
,07-08 14:06:00.126  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.j.a(469): Request install of com.google.android.apps.docs.editors.docs v=62321835 pri=3 for auto_update
,07-08 14:06:00.136  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1258): Installer kick - starting com.google.android.apps.docs.editors.docs
,07-08 14:06:00.140  1355  1355 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.a(186): auto-updates finished successfully.
,07-08 14:06:00.147  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:00.151  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:00.152  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:00.159  1355  1512 I Finsky  : [75] com.google.android.finsky.installer.y.b(204): Created session 350272296 for com.google.android.apps.docs.editors.docs
,07-08 14:06:00.498  1355  1512 I Finsky  : [75] com.google.android.finsky.installer.ah.run(127): Session for com.google.android.apps.docs.editors.docs already exists, skipping creation
,07-08 14:06:00.938  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.ai.onPostExecute(5001): Downloading patch for com.google.android.apps.docs.editors.docs (com.google.android.apps.docs.editors.docs)
,07-08 14:06:00.942  1355  1355 I Finsky  : [1] com.google.android.finsky.download.e.a(256): Duplicate state set for 'com.google.android.apps.docs.editors.docs' (0). Already in that state
,07-08 14:06:00.943  1355  1355 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.apps.docs.editors.docs added to DownloadQueue
,07-08 14:06:00.945  1355  1355 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.apps.docs.editors.docs from 0 to 1.
,07-08 14:06:00.950   199   199 I installd: free_cache(7296442) avail 10654683136
,07-08 14:06:00.957  1355  1355 I Finsky  : [1] com.google.android.finsky.download.ai.run(5554): Download com.google.android.apps.docs.editors.docs starting
,07-08 14:06:00.990  1355  1514 I Finsky  : [76] com.google.android.finsky.download.ae.a(1567): Enqueued com.google.android.apps.docs.editors.docs as content://downloads/my_downloads/978
,07-08 14:06:00.991  1355  1355 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.apps.docs.editors.docs from 1 to 2.
,07-08 14:06:00.993  1355  1355 I Finsky  : [1] com.google.android.finsky.download.x.a(632): com.google.android.apps.docs.editors.docs: onStart
,07-08 14:06:01.019  1355  1355 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.apps.docs.editors.docs: onProgress 0/-1 Status: 192.
,07-08 14:06:01.060   946  4584 D DownloadManager: [978] Starting
,07-08 14:06:01.066   946  4584 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-08 14:06:01.079  1566  2964 V NativeCrypto: SSL shutdown failed: ssl=0x98de0800: I/O error during system call, Connection timed out
,07-08 14:06:01.151  1566  2964 V NativeCrypto: SSL shutdown failed: ssl=0xb36f8400: I/O error during system call, Connection timed out
,07-08 14:06:03.226   946  4584 D DownloadManager: [978] Finished with status SUCCESS
,07-08 14:06:03.258  1355  1355 I Finsky  : [1] com.google.android.finsky.download.x.b(401): com.google.android.apps.docs.editors.docs: onProgress 7296442/7296442 Status: 200.
,07-08 14:06:03.262  1355  1355 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(46): Intent received at DownloadBroadcastReceiver
,07-08 14:06:03.271  1355  1355 I Finsky  : [1] com.google.android.finsky.download.e.a(258): com.google.android.apps.docs.editors.docs from 2 to 3.
,07-08 14:06:03.271  1355  1355 I Finsky  : [1] com.google.android.finsky.download.x.b(600): com.google.android.apps.docs.editors.docs: onComplete
07-08 14:06:03.271  1355  1355 I Finsky  : [1] com.google.android.finsky.download.x.i(341): Download com.google.android.apps.docs.editors.docs removed from DownloadQueue
07-08 14:06:03.273   199   199 I installd: free_cache(0) avail 10647379968
,07-08 14:06:03.280  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.x.c(36121): Prepare to patch com.google.android.apps.docs.editors.docs (com.google.android.apps.docs.editors.docs) from content://downloads/my_downloads/978 format 2
,07-08 14:06:03.290   199   199 I installd: free_cache(34856048) avail 10647379968
,07-08 14:06:04.346  1355  1564 I Finsky  : [89] com.google.android.finsky.receivers.ab.a(3193): Patch apply task for com.google.android.apps.docs.editors.docs (com.google.android.apps.docs.editors.docs) (format 2) completed in 1064 ms
,07-08 14:06:04.351  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.ab.onPostExecute(4243): Successfully applied patch to update com.google.android.apps.docs.editors.docs (com.google.android.apps.docs.editors.docs)
,07-08 14:06:04.355  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.x.c(42122): Begin install of com.google.android.apps.docs.editors.docs
,07-08 14:06:04.358   946   966 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/downloadfile.bin via provider delete
,07-08 14:06:06.015  1355  1355 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2102): Skipping verification because own installation
,07-08 14:06:07.823   786   817 I PackageManager.DexOptimizer: Running dexopt (dex2oat) on: /data/app/vmdl350272296.tmp/base.apk pkg=com.google.android.apps.docs.editors.docs isa=arm vmSafeMode=false debuggable=false oatDir = /data/app/vmdl350272296.tmp/oat bootComplete=true
,07-08 14:06:07.860  4599  4599 I dex2oat : Starting dex2oat.
,07-08 14:06:12.138  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.SpannableStringBuilder.toString()
,07-08 14:06:13.409  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
,07-08 14:06:13.410  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
07-08 14:06:13.410  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
07-08 14:06:13.410  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
,07-08 14:06:13.723  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
,07-08 14:06:14.360  4599  4599 I dex2oat : Skipping compilation of void com.google.android.libraries.flowlayoutmanager.FlowLayoutManager.a(android.support.v7.widget.RecyclerView$j, com.google.android.libraries.flowlayoutmanager.FlowLayoutManager$i, int, int, int, int): it contains a non natural loop
,07-08 14:06:14.842  4599  4601 I dex2oat : Skipping compilation of void com.qo.android.metafile.picture.j.a(com.qo.android.metafile.gdi.i[], int[]): it contains a non natural loop
,07-08 14:06:14.920  4599  4603 W dex2oat : Compilation of void com.qo.android.metafile.wmf.a.a(com.qo.android.metafile.gdi.a, float, float) took 108.115ms
,07-08 14:06:15.180  4599  4603 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.SpannableStringBuilder.toString()
,07-08 14:06:15.430  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString()
,07-08 14:06:16.575  4599  4599 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.SpannableStringBuilder.toString()
,07-08 14:06:16.840  4599  4599 W dex2oat : No verified method for method calling String.<init>: java.lang.String android.text.TextUtils.substring(java.lang.CharSequence, int, int)
,07-08 14:06:16.977  4599  4603 W dex2oat : No verified method for method calling String.<init>: void android.provider.SearchRecentSuggestions.<init>(android.content.Context, java.lang.String, int)
,07-08 14:06:16.977  4599  4601 W dex2oat : No verified method for method calling String.<init>: void android.provider.SearchRecentSuggestions.<init>(android.content.Context, java.lang.String, int)
,07-08 14:06:17.390  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString(java.lang.String)
,07-08 14:06:18.056  4599  4602 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString(java.lang.String)
,07-08 14:06:18.064  4599  4601 W dex2oat : No verified method for method calling String.<init>: java.lang.String java.io.ByteArrayOutputStream.toString(java.lang.String)
,07-08 14:06:18.417  4357  4402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,07-08 14:06:19.231  4599  4599 W dex2oat : Compilation of mvz mvz.b(nrj) took 894.664ms
,07-08 14:06:21.221  4599  4599 I dex2oat : dex2oat took 13.361s (threads: 4) arena alloc=45MB java alloc=20MB native alloc=109MB free=36MB
,07-08 14:06:21.255   786   806 I ActivityManager: Force stopping com.google.android.apps.docs.editors.docs appid=10079 user=-1: replace sys pkg
,07-08 14:06:21.260   786   817 W PackageManager: Trying to update system app code path from /data/app/com.google.android.apps.docs.editors.docs-1 to /data/app/com.google.android.apps.docs.editors.docs-2
,07-08 14:06:21.261   786   806 I ActivityManager: Force stopping com.google.android.apps.docs.editors.docs appid=10079 user=-1: replace pkg
07-08 14:06:21.261   786   817 W PackageManager: Code path for com.google.android.apps.docs.editors.docs changing from /data/app/com.google.android.apps.docs.editors.docs-1 to /data/app/com.google.android.apps.docs.editors.docs-2
07-08 14:06:21.261   786   817 W PackageManager: Resource path for com.google.android.apps.docs.editors.docs changing from /data/app/com.google.android.apps.docs.editors.docs-1 to /data/app/com.google.android.apps.docs.editors.docs-2
,07-08 14:06:21.263   786   817 W PackageManager: Permission com.google.android.apps.docs.editors.kix.permission.READ_MY_DATA from package com.google.android.apps.docs.editors.docs in an unknown group android.permission-group.PERSONAL_INFO
07-08 14:06:21.263   786   817 W PackageManager: Permission com.google.android.apps.docs.editors.kix.permission.SYNC_STATUS from package com.google.android.apps.docs.editors.docs in an unknown group android.permission-group.PERSONAL_INFO
,07-08 14:06:21.329   786   817 W PackageSettings: Skipping PackageSetting{411c04a com.example.hello/10116} due to missing metadata
,07-08 14:06:21.363   786   817 W PackageManager: Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs.editors.docs
07-08 14:06:21.363   786   817 W PackageManager: Not granting permission com.google.android.gm.permission.READ_GMAIL to package com.google.android.apps.docs.editors.docs (protectionLevel=2 flags=0x38183ec5)
07-08 14:06:21.363   786   817 W PackageManager: Not granting permission com.google.android.googleapps.permission.GOOGLE_AUTH to package com.google.android.apps.docs.editors.docs (protectionLevel=2 flags=0x38183ec5)
07-08 14:06:21.363   786   817 W PackageManager: Not granting permission com.google.android.googleapps.permission.GOOGLE_AUTH.OTHER_SERVICES to package com.google.android.apps.docs.editors.docs (protectionLevel=2 flags=0x38183ec5)
,07-08 14:06:21.363   786   817 W PackageManager: Not granting permission com.google.android.googleapps.permission.GOOGLE_AUTH.ALL_SERVICES to package com.google.android.apps.docs.editors.docs (protectionLevel=2 flags=0x38183ec5)
,07-08 14:06:21.363   786   817 W PackageManager: Not granting permission com.google.android.googleapps.permission.GOOGLE_AUTH.writely to package com.google.android.apps.docs.editors.docs (protectionLevel=2 flags=0x38183ec5)
07-08 14:06:21.363   786   817 W PackageManager: Not granting permission com.google.android.googleapps.permission.GOOGLE_AUTH.wise to package com.google.android.apps.docs.editors.docs (protectionLevel=2 flags=0x38183ec5)
,07-08 14:06:21.423   786   817 W PackageSettings: Skipping PackageSetting{411c04a com.example.hello/10116} due to missing metadata
,07-08 14:06:21.453   786   817 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
07-08 14:06:21.453   786   817 I art     : Starting a blocking GC Explicit
,07-08 14:06:21.517   786   817 I art     : Explicit concurrent mark sweep GC freed 214702(10MB) AllocSpace objects, 9(1168KB) LOS objects, 33% free, 25MB/38MB, paused 854us total 63.807ms
,07-08 14:06:21.547   786   817 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.google.android.apps.docs.editors.docs-1/base.apk, retcode=-1
,07-08 14:06:21.547   199   199 E installd: Couldn't opendir /data/app/vmdl350272296.tmp: No such file or directory
,07-08 14:06:21.550   786   817 I ActivityManager: Force stopping com.google.android.apps.docs.editors.docs appid=10079 user=0: pkg removed
,07-08 14:06:21.557   786   786 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-08 14:06:21.561  1355  1355 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2142): Successful install of com.google.android.apps.docs.editors.docs
,07-08 14:06:21.564   786   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-08 14:06:21.568  4357  4357 D BluetoothMapAppObserver: onReceive
07-08 14:06:21.569  4357  4357 D BluetoothMapAppObserver: The removed package is: com.google.android.apps.docs.editors.docs
,07-08 14:06:21.614  1298  1298 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-08 14:06:21.614  1298  1298 D CarrierServiceBindHelper: mHandler: 3
,07-08 14:06:21.626  4357  4357 D BluetoothMapAppObserver: onReceive
,07-08 14:06:21.626  4357  4357 D BluetoothMapAppObserver: The installed package is: com.google.android.apps.docs.editors.docs
07-08 14:06:21.629  4357  4357 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-08 14:06:21.632   786   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-08 14:06:21.632  4357  4357 D BluetoothMapAppObserver: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-08 14:06:21.639   786  2561 I ActivityManager: Start proc 4637:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,07-08 14:06:21.663   786   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-08 14:06:21.680  1355  1355 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(277): Wear auto install disabled for package com.google.android.apps.docs.editors.docs
,07-08 14:06:21.688  1298  1298 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_ADDED
07-08 14:06:21.688  1298  1298 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REPLACED
,07-08 14:06:21.689  1298  1298 D CarrierServiceBindHelper: mHandler: 3
07-08 14:06:21.689  1298  1298 D CarrierServiceBindHelper: mHandler: 3
07-08 14:06:21.689  1298  1298 D CarrierConfigLoader: mHandler: 9 phoneId: 0
,07-08 14:06:21.699  4637  4637 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,07-08 14:06:21.702  4637  4637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,07-08 14:06:21.717   786   959 I ActivityManager: Killing 3604:com.quickoffice.android/u0a65 (adj 15): empty #17
,07-08 14:06:22.384  1566  1566 E NetworkScheduler.SR: Invalid parameter app
07-08 14:06:22.384  1566  1566 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-08 14:06:22.399  1578  4661 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.400  1578  4661 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.419   786  2561 I ActivityManager: Start proc 4663:com.quickoffice.android/u0a65 for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver
,07-08 14:06:22.437  1578  1612 E Drive.UninstallOperation: Package still installed com.google.android.apps.docs.editors.docs
,07-08 14:06:22.452  1578  4661 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.477  1578  4675 D gH_CompatibleDatabase: Open irg@8dbac87, release reference: 1
,07-08 14:06:22.481  1578  4675 D gH_CompatibleDatabase: Acquire reference of irg@8dbac87: 2
,07-08 14:06:22.481  1578  4675 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.android.apps.docs.editors.docs.
,07-08 14:06:22.481  1578  4675 D gH_CompatibleDatabase: Release reference of irg@8dbac87: 1
07-08 14:06:22.482  1578  4675 D gH_CompatibleDatabase: Open irg@b83c7b4, release reference: 1
,07-08 14:06:22.486  1578  4675 D gH_CompatibleDatabase: Acquire reference of irg@b83c7b4: 2
,07-08 14:06:22.486  1578  4675 D gH_CompatibleDatabase: Release reference of irg@b83c7b4: 1
07-08 14:06:22.486  1578  4675 D gH_CompatibleDatabase: Open irg@72d0fdd, release reference: 1
,07-08 14:06:22.490  1578  4675 D gH_CompatibleDatabase: Acquire reference of irg@72d0fdd: 2
,07-08 14:06:22.491  1578  4675 D gH_CompatibleDatabase: Release reference of irg@72d0fdd: 1
,07-08 14:06:22.491  1578  4675 D gH_CompatibleDatabase: Close irg@8dbac87, release reference: 0
07-08 14:06:22.492  1578  4675 D gH_CompatibleDatabase: Close irg@b83c7b4, release reference: 0
07-08 14:06:22.492  1578  4675 D gH_CompatibleDatabase: Close irg@72d0fdd, release reference: 0
,07-08 14:06:22.503  4663  4663 W Quickoffice: Cleanup of storage: done
,07-08 14:06:22.505  4663  4691 D com.google.android.apps.docs.quickoffice.X: Loading recent documents list
,07-08 14:06:22.508  4663  4692 D Quickoffice: The number of lines present in  /proc/mount 22
,07-08 14:06:22.510  4663  4692 D Quickoffice: Parsing the storagedefinition.xml.
,07-08 14:06:22.516  4663  4692 D Quickoffice: # of Storagedefinitions - 35
07-08 14:06:22.516  4663  4692 D Quickoffice: The # of storage definitions available - 35
,07-08 14:06:22.516  4663  4692 D Quickoffice: Processing mountline rootfs / rootfs ro,seclabel,relatime 0 0
07-08 14:06:22.516  4663  4692 D Quickoffice: Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
,07-08 14:06:22.517  4663  4692 D Quickoffice: Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
07-08 14:06:22.517  4663  4692 D Quickoffice: Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
,07-08 14:06:22.517  4663  4692 D Quickoffice: Processing mountline proc /proc proc rw,relatime 0 0
07-08 14:06:22.517  4663  4692 D Quickoffice: Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
07-08 14:06:22.517  4663  4692 D Quickoffice: Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
07-08 14:06:22.518  4663  4692 D Quickoffice: Processing mountline debugfs /sys/kernel/debug debugfs rw,seclabel,relatime 0 0
07-08 14:06:22.518  4663  4692 D Quickoffice: Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
07-08 14:06:22.519  4663  4692 D Quickoffice: Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
,07-08 14:06:22.519  4663  4692 D Quickoffice: Processing mountline tmpfs /mnt tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,07-08 14:06:22.519  4663  4692 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/default/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-08 14:06:22.519  4663  4692 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/read/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-08 14:06:22.519  4663  4692 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/write/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-08 14:06:22.520  4663  4692 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,relatime 0 0
,07-08 14:06:22.520  4663  4692 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
07-08 14:06:22.520  4663  4692 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
07-08 14:06:22.521  4663  4692 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
07-08 14:06:22.521  4663  4692 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,context=u:object_r:firmware_file:s0,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
,07-08 14:06:22.521  4663  4692 D Quickoffice: Processing mountline tmpfs /storage tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
07-08 14:06:22.521  4663  4692 D Quickoffice: Processing mountline /dev/fuse /storage/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
07-08 14:06:22.522  4663  4692 D Quickoffice: Processing mountline tmpfs /storage/self tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,07-08 14:06:22.527  4663  4692 E Quickoffice: An exception occured in getAllMountedStorages method.
07-08 14:06:22.527  4663  4692 E Quickoffice: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.qo.android.filesystem.h.a(com.qo.android.filesystem.StorageDefinition)' on a null object reference
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at com.quickoffice.mx.engine.a.e(AndroidLocalFileSystems.java:432)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at com.quickoffice.mx.engine.a.a(AndroidLocalFileSystems.java:92)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at com.quickoffice.mx.S.b(MxPlugin.java:59)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at com.quickoffice.mx.engine.q.f(MxEngine.java:1225)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at com.quickoffice.mx.engine.q.a(MxEngine.java:1219)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at com.qo.android.b.call(AsyncTask.java:217)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:06:22.527  4663  4692 E Quickoffice: 	at java.lang.Thread.run(Thread.java:818)
,07-08 14:06:22.527  4663  4692 D Quickoffice: The # of mounts identified -  0
07-08 14:06:22.527  4663  4692 D Quickoffice: Failed to get moto storage state.
,07-08 14:06:22.529  4663  4692 D Quickoffice: Failed to get moto storage dir.
,07-08 14:06:22.536  4663  4695 D com.google.android.apps.docs.quickoffice.X: Checking validity of 0 items
,07-08 14:06:22.545   786  3196 I ActivityManager: Start proc 4696:com.google.android.partnersetup/u0a11 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,07-08 14:06:22.546   786  1211 W ActivityManager: No permission grants found for com.quickoffice.android
07-08 14:06:22.546  4663  4695 D ContentResolverUtil: There are 0 persisted uri permissions.
07-08 14:06:22.546  4663  4695 D com.google.android.apps.docs.quickoffice.X: 0 items were valid
,07-08 14:06:22.547  4663  4694 W Quickoffice: Could not load clipboard.
,07-08 14:06:22.561  4663  4705 W Quickoffice: Could not store clipboard.
,07-08 14:06:22.574  4696  4696 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-08 14:06:22.596   786  1211 I ActivityManager: Killing 4268:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-08 14:06:22.780  1355  1355 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.google.android.apps.docs.editors.docs
,07-08 14:06:22.839  1578  4675 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.840  1578  4659 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-08 14:06:22.842  1578  4675 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.843  1578  1578 D AsyncTaskServiceImpl: Submit a task: nwp
,07-08 14:06:22.851  1578  4675 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.855  1578  1612 D nwp     : Processing package: com.google.android.apps.docs.editors.docs
,07-08 14:06:22.874  1578  1612 D nwe     : Look up (com.google.android.apps.docs.editors.docs:62321835) returned no result
,07-08 14:06:22.875  1578  1612 D nwp     : Starting Hash for package com.google.android.apps.docs.editors.docs:1.6.232.18.35
,07-08 14:06:22.883  1370  4723 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.apps.docs.editors.docs, CONTACTS=MAYBE
,07-08 14:06:22.914  1578  4675 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.apps.docs.editors.docs
,07-08 14:06:22.917  1578  1578 D AsyncTaskServiceImpl: Submit a task: nwp
,07-08 14:06:22.920   786   797 I BroadcastQueue: Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,07-08 14:06:22.928   786   798 I BroadcastQueue: Resuming delayed broadcast
,07-08 14:06:22.942   786  2561 I ActivityManager: Start proc 4727:com.google.android.apps.docs.editors.docs/u0a79 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.editors.shared.services.PackageReplacedGcmTaskService
,07-08 14:06:22.943  1566  1566 E NetworkScheduler.SR: Invalid parameter app
07-08 14:06:22.943  1566  1566 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-08 14:06:22.962   786  1003 I ActivityManager: Start proc 4739:com.google.android.apps.cloudprint/u0a32 for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver
,07-08 14:06:23.010  1578  4726 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-08 14:06:23.079  1370  4723 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 196 ms] updated apps [took 195 ms] 
,07-08 14:06:23.150  4727  4776 I GAv4    : Google Analytics 8.4.87 is starting up. To enable debug logging on a device run:
07-08 14:06:23.150  4727  4776 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:06:23.150  4727  4776 I GAv4    :   adb logcat -s GAv4
,07-08 14:06:23.168  4727  4776 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:06:23.181  4727  4776 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:06:23.185  4727  4784 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:06:23.306  1578  1612 D nwp     : Package com.google.android.apps.docs.editors.docs's hash: 6a209660423443881ea997b1fe40693020ac854b3d2f210a537f06d73e6e82a6
,07-08 14:06:23.307  1578  1612 D nwe     : Look up (com.google.android.apps.docs.editors.docs:62321835) returned no result
,07-08 14:06:23.324  1578  1612 D nwp     : Saved the app info in cache for package:com.google.android.apps.docs.editors.docs.
07-08 14:06:23.324  1578  1612 D nwp     : Processing package: com.google.android.apps.docs.editors.docs
,07-08 14:06:23.330  4727  4727 W InstanceID/Rpc: Found 10007
,07-08 14:06:23.346   786   798 I ActivityManager: Killing 3818:com.android.settings/1000 (adj 15): empty #17
,07-08 14:06:23.348  1578  1612 D GassUtils: Found app info for package com.google.android.apps.docs.editors.docs:62321835. Hash: 6a209660423443881ea997b1fe40693020ac854b3d2f210a537f06d73e6e82a6
07-08 14:06:23.348  1578  1612 D nwp     : Found info for package com.google.android.apps.docs.editors.docs in db.
,07-08 14:06:23.355   786   892 D WifiService: Client connection lost with reason: 4
,07-08 14:06:24.095  1578  1612 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-08 14:06:24.189  1578  1612 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
,07-08 14:06:24.214  1578  1612 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-08 14:06:24.226  1578  1612 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,07-08 14:06:28.242   786   959 I ActivityManager: Killing 3919:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,07-08 14:06:29.944   786  3196 I ActivityManager: Killing 3934:com.google.android.apps.plus/u0a63 (adj 15): empty #17
,07-08 14:06:32.607   786   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-08 14:06:32.650  1370  4818 I UpdateIcingCorporaServi: Updating corpora: APPS=com.quickoffice.android, CONTACTS=MAYBE
,07-08 14:06:32.677  1578  4819 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.quickoffice.android
,07-08 14:06:32.703  1578  4819 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.quickoffice.android
,07-08 14:06:32.720  1370  4818 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 69 ms] updated apps [took 69 ms] 
,07-08 14:06:32.753  1578  4841 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-08 14:06:33.783  1578  1638 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-08 14:06:33.854  1578  1638 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-08 14:06:35.221  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:35.221  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:35.235  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:35.315  4727  4779 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-08 14:06:35.327  4727  4779 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-08 14:06:35.327  4727  4779 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-08 14:06:35.331  4727  4779 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-08 14:06:35.353  4727  4779 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:06:37.641  1355  1550 I Finsky  : [86] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-08 14:06:37.763  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:38.534  1355  1355 I Finsky  : [1] com.google.android.finsky.c.c.a(311): Completed 1 account content syncs with 1 successful.
,07-08 14:06:38.538  1355  1355 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-08 14:07:15.804  1566  4135 V NativeCrypto: SSL shutdown failed: ssl=0x9a789600: I/O error during system call, Connection timed out
,07-08 14:07:23.377   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=447988, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:07:28.407   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=453018, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:08:08.497   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=493108, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:08:38.709   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=523320, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:09:23.697   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=568308, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:10:10.373  4357  4402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-08 14:10:10.487   786   795 I art     : Background partial concurrent mark sweep GC freed 49076(3MB) AllocSpace objects, 7(156KB) LOS objects, 33% free, 25MB/38MB, paused 878us total 121.501ms
,07-08 14:10:26.116   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=630728, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:11:11.057   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=675668, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:11:28.689   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=693300, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:12:13.617   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=738228, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:15:20.121  1578  4883 I EventLogChimeraService: Aggregate from 1467979238523 (log), 1467977815249 (data)
,07-08 14:15:20.150  1370  4881 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-08 14:15:20.229  1370  4881 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,07-08 14:15:20.229  1370  4881 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-08 14:15:20.237  1578  4885 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-08 14:15:20.245  1370  4881 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,07-08 14:15:20.245  1370  4881 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-08 14:15:20.266  1370  4881 I ContextCompilationHandl: Recognition context unchanged for CONTACT_NAMES en-US
,07-08 14:15:20.266  1370  4881 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-08 14:15:20.314  1578  4898 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-08 14:15:20.319  1578  1641 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.gms start 0 num 1000
,07-08 14:15:20.767  1370  4881 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-08 14:15:20.809  1578  4767 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-08 14:15:20.828  1578  4767 E Icing   : No scoring data for corpus [21]
,07-08 14:15:20.847  1578  1639 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-08 14:15:20.876  1578  1639 E Icing   : No scoring data for corpus [15]
,07-08 14:15:20.917  1578  4767 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-08 14:15:20.971  1578  1639 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-08 14:15:20.985  1578  1639 E Icing   : No scoring data for corpus [22]
,07-08 14:15:20.991  1370  4881 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-08 14:16:28.327   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=992938, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:16:39.337   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1003948, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:20:16.407   786   805 I UsageStatsService: User[0] Flushing usage stats to disk
,07-08 14:20:21.118  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:20:21.151  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:20:21.151  1566  1566 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:20:26.187   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1230799, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:20:32.337   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1236948, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:24:26.769   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1471379, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:24:37.737   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1482348, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:25:02.965   786   883 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-08 14:25:02.967   786   786 V KeyguardServiceDelegate: onStartedWakingUp()
07-08 14:25:02.971   786   813 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-08 14:25:03.003  3702  3702 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-08 14:25:03.003  3702  3702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-08 14:25:03.003  3702  3702 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-08 14:25:03.003  3702  3702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-08 14:25:03.014   786   813 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@bd7e261)
,07-08 14:25:03.021   198   829 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-08 14:25:03.021   786  1476 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-08 14:25:03.026   786   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:03.031   786   891 E native  : do suspend false
,07-08 14:25:03.031   786   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:25:03.041   786   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-08 14:25:03.090  1566  1566 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-08 14:25:03.096  1804  1821 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-08 14:25:03.096   786   811 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-08 14:25:03.098   191   191 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
07-08 14:25:03.098   191   191 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-08 14:25:03.109   786  2561 I ActivityManager: Start proc 4980:com.google.android.apps.fitness/u0a82 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-08 14:25:03.156  4980  4980 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.fitness-2/lib/arm
,07-08 14:25:03.248   786   813 I DisplayPowerController: Unblocked screen on after 277 ms
,07-08 14:25:03.249   786   813 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-08 14:25:03.309  4980  4980 W Fit     : No acount yet, skipping caching values.
,07-08 14:25:03.331   191   191 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-08 14:25:03.331   786   911 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,07-08 14:25:03.954  1566  1566 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-08 14:25:03.956  1566  1566 I BeaconBle: BLE 'JB+' software access layer enabled
,07-08 14:25:03.967  1566  5044 D BluetoothAdapter: startLeScan(): null
,07-08 14:25:03.969  1566  5044 D BluetoothAdapter: STATE_ON
,07-08 14:25:03.970  4357  4399 D BtGatt.GattService: registerClient() - UUID=b2bf380a-1a13-4991-a874-465689c0b7df
07-08 14:25:03.971  4357  4373 D BtGatt.GattService: onClientRegistered() - UUID=b2bf380a-1a13-4991-a874-465689c0b7df, clientIf=5
07-08 14:25:03.971  1566  1576 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-08 14:25:03.972  4357  4367 D BtGatt.GattService: start scan with filters
,07-08 14:25:03.973  4357  4376 D BtGatt.ScanManager: handling starting scan
,07-08 14:25:03.974  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-08 14:25:03.974  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
,07-08 14:25:03.975  4357  4376 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-08 14:25:03.975  4357  4373 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-08 14:25:05.370  4727  4976 D JSContext: wrote snapshot /data/user/0/com.google.android.apps.docs.editors.docs/files/kix_mobile-2-55d06111-en_US-1.6.232.18.35.v8snapshot; snapshot size 4838348
,07-08 14:25:05.381   786  3196 I ActivityManager: Killing 3884:com.google.android.talk/u0a51 (adj 15): empty #17
,07-08 14:25:05.479  1566  5044 D BluetoothAdapter: stopLeScan()
,07-08 14:25:05.480  1566  5044 D BluetoothAdapter: STATE_ON
,07-08 14:25:05.481  4357  4399 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:25:05.481  4357  4367 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:25:05.481  4357  4376 D BtGatt.ScanManager: stop scan
07-08 14:25:05.481  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-08 14:25:05.481  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
,07-08 14:25:05.481  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-08 14:25:05.654  1566  5044 D BluetoothAdapter: startLeScan(): null
,07-08 14:25:05.655  1566  5044 D BluetoothAdapter: STATE_ON
,07-08 14:25:05.657  4357  4391 D BtGatt.GattService: registerClient() - UUID=ccf6ae9b-4dda-456f-b23b-de4b366a182c
,07-08 14:25:05.657  4357  4373 D BtGatt.GattService: onClientRegistered() - UUID=ccf6ae9b-4dda-456f-b23b-de4b366a182c, clientIf=5
,07-08 14:25:05.658  1566  1622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:25:05.658  4357  4368 D BtGatt.GattService: start scan with filters
,07-08 14:25:05.660  4357  4376 D BtGatt.ScanManager: handling starting scan
,07-08 14:25:05.662  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-08 14:25:05.662  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
,07-08 14:25:05.662  4357  4376 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-08 14:25:05.663  4357  4373 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-08 14:25:06.048   786   893 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-08 14:25:07.019  1566  5044 D BluetoothAdapter: stopLeScan()
,07-08 14:25:07.029  1566  5044 D BluetoothAdapter: STATE_ON
07-08 14:25:07.032  4357  4367 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:25:07.034  4357  4376 D BtGatt.ScanManager: stop scan
07-08 14:25:07.034  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-08 14:25:07.034  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-08 14:25:07.034  4357  4376 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-08 14:25:07.071  4357  4391 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-08 14:25:07.071  1566  5044 I BeaconBle: Scan : No clients left, canceling alarm.
,07-08 14:25:08.007   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1512618, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:25:09.977  1566  5041 I BeaconBle: Scan : No clients left, canceling alarm.
,07-08 14:25:16.496   786  4515 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1521108, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),07-08 14:25:25.374  5054  5054 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:25:25.380  5054  5054 D AndroidRuntime: CheckJNI is OFF
07-08 14:25:25.431  5054  5054 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:25:25.481  5054  5054 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:25:25.503  5054  5054 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-08 14:25:25.510   786   806 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
07-08 14:25:25.510   786   806 I ActivityManager: Killing 3702:com.test.thalitest/u0a26 (adj 0): stop com.test.thalitest
07-08 14:25:25.545   786  2133 I WindowState: WIN DEATH: Window{3da8bc6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-08 14:25:25.545   786  1211 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@cc04228)
07-08 14:25:25.546   786   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-08 14:25:25.546   786   892 D WifiService: Client connection lost with reason: 4
07-08 14:25:25.546   786   893 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-08 14:25:25.547   786   959 D GraphicsStats: Buffer count: 2
07-08 14:25:25.576   786   806 W ActivityManager: Force removing ActivityRecord{1b56878 u0 com.test.thalitest/.MainActivity t44}: app died, no saved state
07-08 14:25:25.588   786   817 W PackageSettings: Skipping PackageSetting{411c04a com.example.hello/10116} due to missing metadata
07-08 14:25:25.622   786   817 I art     : Starting a blocking GC Explicit
07-08 14:25:25.629   786  1211 W ActivityManager: Spurious death for ProcessRecord{4f48b41 0:com.test.thalitest/u0a26}, curProc for 3702: null
07-08 14:25:25.661   786  3196 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3702 uid 10026
07-08 14:25:25.693  1370  1370 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
07-08 14:25:25.715  1370  5083 I MicroRecognitionRunner: Starting detection.
07-08 14:25:25.716  1370  1370 W LocationOracle: Best location was null
07-08 14:25:25.721  1370  5084 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ah@149fffe
07-08 14:25:25.723   198  5087 I AudioFlinger: AudioFlinger's thread 0xb24c0000 ready to run
07-08 14:25:25.729  1370  5084 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ah@149fffe
07-08 14:25:25.738   198  5087 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
07-08 14:25:25.738   198  5087 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
07-08 14:25:25.738   198  5087 D         : Failed to fetch the lookup information of the device 0000003E 
07-08 14:25:25.738   198  5087 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
07-08 14:25:25.738   198  5087 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
07-08 14:25:25.742   198  5087 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
07-08 14:25:25.755   786   817 I art     : Explicit concurrent mark sweep GC freed 41763(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 25MB/38MB, paused 1.087ms total 132.595ms
07-08 14:25:25.785   786   817 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-08 14:25:25.788  5054  5054 I art     : System.exit called, status: 0
07-08 14:25:25.788  5054  5054 I AndroidRuntime: VM exiting with result code 0.
07-08 14:25:25.797   786   817 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
07-08 14:25:25.820  4357  4357 D BluetoothMapAppObserver: onReceive
07-08 14:25:25.820  4357  4357 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-08 14:25:25.820  1566  1615 W GCoreFlp: No location to return for getLastLocation()
07-08 14:25:25.822  1566  1645 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-08 14:25:25.826  1370  1370 I MicroDetectionWorker: onReady
07-08 14:25:25.826   786   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-08 14:25:25.837  1566  1615 W GCoreFlp: No location to return for getLastLocation()
07-08 14:25:25.885  1298  1298 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-08 14:25:25.887  2093  5101 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-08 14:25:25.899  1566  1615 W GCoreFlp: No location to return for getLastLocation()
07-08 14:25:25.900  4637  4637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
07-08 14:25:25.914  1355  1355 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(280): Wear auto uninstall disabled for package com.test.thalitest
07-08 14:25:25.919   786   786 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-08 14:25:25.935  1566  1615 W GCoreFlp: No location to return for getLastLocation()
07-08 14:25:25.942  1566  1566 E NetworkScheduler.SR: Invalid parameter app
07-08 14:25:25.942  1566  1566 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-08 14:25:25.943  1578  5106 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-08 14:25:25.943  1578  5106 D AccountUtils: Clearing selected account for com.test.thalitest
07-08 14:25:25.950  1566  1615 W GCoreFlp: No location to return for getLastLocation()
07-08 14:25:25.964  1578  5106 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-08 14:25:25.965  2093  5101 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
07-08 14:25:25.972  1578  5106 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
--------- beginning of crash
07-08 14:25:25.977  2093  5101 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-08 14:25:25.977  2093  5101 E AndroidRuntime: Process: android.process.acore, PID: 2093
07-08 14:25:25.977  2093  5101 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:25:25.977  2093  5101 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:25:25.978  1578  5108 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:25:25.990  1578  1638 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:25:25.991  1578  5111 D gH_CompatibleDatabase: Open irg@f9994f9, release reference: 1
07-08 14:25:26.008  1312  1513 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/reflection_multi_process.xml to backup file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/reflection_multi_process.xml.bak
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:560)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at irl.c(:com.google.android.gms:216)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at irl.d(:com.google.android.gms:187)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at irg.m(:com.google.android.gms:35519)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at ogk.b(:com.google.android.gms:64)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at okk.c(:com.google.android.gms:278)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentOperation.onHandleIntent(:com.google.android.gms:36)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:82)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at bev.run(:com.google.android.gms:1846)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:25:26.010  1578  5111 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:25:26.025   786  5109 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:25:26.025   786  5109 E DropBoxManagerService: 	... 5 more
07-08 14:25:26.029  1578  1638 E DriveAsyncService: disk I/O error (code 3850)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at irg.a(:com.google.android.gms:47)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at jzk.l(:com.google.android.gms:487)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at jzk.b(:com.google.android.gms:462)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at jzf.i(:com.google.android.gms:1512)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at jvt.a(:com.google.android.gms:1033)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at gpq.run(:com.google.android.gms:188)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at itt.run(:com.google.android.gms:453)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at iyg.run(:com.google.android.gms:17)
07-08 14:25:26.029  1578  1638 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:25:26.031  1578  1794 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:25:26.031  1578  1794 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:25:26.032  1578  1794 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-08 14:25:26.032  1578  1794 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:25:26.033  1578  1794 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:25:26.033  1578  1794 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-08 14:25:26.037   786  5113 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-08 14:25:26.044  1578  1794 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:25:26.044  1578  1794 E GAv4-SVC: Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-08 14:25:26.045   786  4799 I BroadcastQueue: Delay finish: com.google.android.googlequicksearchbox/com.google.android.apps.gsa.search.core.icingsync.IcingCorporaChangedReceiver
07-08 14:25:26.048  1370  5114 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-08 14:25:26.048  1578  1638 I Icing   : doRemovePackageData com.test.thalitest
07-08 14:25:26.049  1578  1794 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:25:26.050  1578  1794 E GAv4-SVC: Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-08 14:25:26.051  1578  5111 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQpL84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-08 14:25:26.051  1578  5111 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDM4KRjWq-AR
07-08 14:25:26.051  1578  5111 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-08 14:25:26.051  1578  5111 I GCore-Chimera-Crash: ==
07-08 14:25:26.051  1578  5111 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-08 14:25:26.051  1578  5108 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQpL84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-08 14:25:26.051  1578  5108 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDM4KRjWq-AR
07-08 14:25:26.051  1578  5108 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-08 14:25:26.051  1578  5108 I GCore-Chimera-Crash: ==
07-08 14:25:26.051  1578  5108 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-08 14:25:26.195  1312  1493 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
07-08 14:25:26.195  1312  1493 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
07-08 14:25:26.206   191   191 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
07-08 14:25:26.206   191   191 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
07-08 14:25:26.206   191   191 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
07-08 14:25:26.206   191   191 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
07-08 14:25:26.206   191   191 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-08 14:25:26.206   191   191 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920

```
