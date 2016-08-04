#### Test 798805949e36f59_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-04 12:33:44.125   871  2111 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-04 12:33:44.841  3729  3729 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 12:33:44.846  3729  3729 D AndroidRuntime: CheckJNI is OFF
08-04 12:33:44.888  3729  3729 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 12:33:44.937  3729  3729 I Radio-JNI: register_android_hardware_Radio DONE
08-04 12:33:44.959  3729  3729 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 12:33:44.963   871  1374 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 12:33:45.013   871  1374 I ActivityManager: Start proc 3738:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-04 12:33:45.024  3729  3729 D AndroidRuntime: Shutting down VM
08-04 12:33:45.187  3738  3738 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-04 12:33:45.220  3738  3738 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-04 12:33:45.231  3738  3738 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7819-7823)
08-04 12:33:45.232  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:33:45.253  3738  3738 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f1884b5}
08-04 12:33:45.254  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:33:45.254  3738  3738 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 12:33:45.266  3738  3738 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 12:33:45.268  3738  3738 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 12:33:45.295  3738  3738 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 12:33:45.307  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 12:33:45.307  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 12:33:45.307  3738  3738 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 12:33:45.307  3738  3738 I Adreno  : Build Date                       : 10/20/15
08-04 12:33:45.307  3738  3738 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 12:33:45.307  3738  3738 I Adreno  : Local Branch                     : M14
08-04 12:33:45.307  3738  3738 I Adreno  : Remote Branch                    : 
08-04 12:33:45.307  3738  3738 I Adreno  : Remote Branch                    : 
08-04 12:33:45.307  3738  3738 I Adreno  : Reconstruct Branch               : 
,08-04 12:33:45.380   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a22b4d9:true
,08-04 12:33:45.426  3738  3738 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 12:33:45.443  3738  3738 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-04 12:33:45.523  3738  3775 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 12:33:45.537  3738  3762 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-04 12:33:45.579  3738  3775 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 12:33:45.657   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms (total +669ms)
,08-04 12:33:45.660  1654  1654 I Keyboard.Facilitator: onFinishInput()
,08-04 12:33:45.703  3738  3738 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3738
,08-04 12:33:45.839  3738  3738 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 12:33:46.027  3738  3778 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1682966224
,08-04 12:33:46.034  3738  3778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 12:33:46.034  3738  3778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 12:33:46.034  3738  3778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 12:33:46.034  3738  3778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 12:33:46.034  3738  3778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-04 12:33:46.035  3738  3778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e50f6b0 added. We now have 1 listener(s)
,08-04 12:33:46.038  3738  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-04 12:33:46.039  3738  3778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:33:46.040  3738  3778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:33:46.040  3738  3778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-04 12:33:46.044  3738  3778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5bd24f added. We now have 1 listener(s)
08-04 12:33:46.044  3738  3778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:33:46.052   871  1306 D WifiService: New client listening to asynchronous messages
,08-04 12:33:46.055  3738  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:33:46.056  3738  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 12:33:46.056  3738  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 12:33:46.057  3738  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 12:33:46.057  3738  3778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-04 12:33:46.066  3738  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:33:46.067  3738  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-04 12:33:46.083  3738  3778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:33:46.084  3738  3778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:33:46.085  3738  3778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-04 12:33:46.086  3738  3778 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:33:46.088  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:33:46.089  3738  3778 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 12:33:46.094  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:33:46.120  3738  3738 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 12:33:47.151  3738  3784 W jxcore-log: Initializing JXcore engine
,08-04 12:33:47.151  3738  3784 W jxcore-log: JXcore engine is ready
,08-04 12:33:47.189  3784  3784 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-04 12:33:47.189  3784  3784 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12943]" dev="sockfs" ino=12943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-04 12:33:47.189  3784  3784 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-04 12:33:47.189  3784  3784 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27143]" dev="sockfs" ino=27143 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-04 12:33:47.205  3738  3784 W jxcore-log: Starting JXcore engine
,08-04 12:33:47.287  3738  3784 W jxcore-log: Platform android
08-04 12:33:47.287  3738  3784 W jxcore-log: 
08-04 12:33:47.287  3738  3784 W jxcore-log: Process ARCH arm
08-04 12:33:47.287  3738  3784 W jxcore-log: 
,08-04 12:33:47.507  3738  3784 I jxcore-log: JXcore Cordova bridge is ready!
08-04 12:33:47.507  3738  3784 I jxcore-log: 
08-04 12:33:47.507  3738  3784 W jxcore-log: JXcore engine is started
,08-04 12:33:47.515  3738  3778 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 12:33:47.520  3738  3738 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 12:33:49.565   871  2111 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-04 12:34:02.831  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 12:34:02.831  3738  3784 I jxcore-log: 
,08-04 12:34:02.833  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 12:34:02.833  3738  3784 I jxcore-log: 
,08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:02.845  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:34:02.849  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:34:02.851  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 12:34:02.851  3738  3784 I jxcore-log: 
,08-04 12:34:02.853  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 12:34:02.853  3738  3784 I jxcore-log: 
,08-04 12:34:03.188  3738  3784 D ExecuteNativeTests: Running unit tests
,08-04 12:34:03.245  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:03.245  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 added. We now have 2 listener(s)
08-04 12:34:03.246  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:34:03.246  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:34:03.246  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:03.246  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:03.246  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 added. We now have 2 listener(s)
08-04 12:34:03.246  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:03.247  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:34:03.252  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.269  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:34:03.271  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.272  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:34:03.274  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 12:34:03.274  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.274  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 12:34:03.274  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 12:34:03.276  3738  3784 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-04 12:34:03.276  3738  3784 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-04 12:34:03.276  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:34:03.276  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 12:34:03.276  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:34:03.276  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:03.277  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.277  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.277  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.278  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.278  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.278  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:03.278  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:03.278  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 removed from the list
08-04 12:34:03.278  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.278  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 removed from the list
08-04 12:34:03.278  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.278  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.279  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.279  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.280  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.280  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.280  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.280  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.281  3738  3784 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 12:34:03.282  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.282  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.282  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:34:03.282  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.282  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.282  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.282  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
,08-04 12:34:03.282  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.282  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.282  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.282  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.282  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.282  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.282  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.283  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.283  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.283  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.283  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 12:34:03.288  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 12:34:03.289  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-04 12:34:03.289  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.290  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.290  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.290  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.290  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.290  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.290  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.290  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.290  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.290  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.290  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.290  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.290  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.290  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.291  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.291  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:03.291  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.292  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.292  3738  3784 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:34:03.295  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.300  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:03.305  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:34:03.305  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:03.305  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:03.306  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:34:03.306  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:34:03.306  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.306  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:34:03.308  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:03.309  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:03.311  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:34:03.311  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:34:03.317  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:34:03.320  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:34:03.320  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:34:03.323  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-04 12:34:03.328  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-04 12:34:03.328  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:34:03.328  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:34:03.329  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 12:34:03.329  3738  3784 D BluetoothAdapter: STATE_ON
,08-04 12:34:03.333  2555  2568 D BtGatt.GattService: registerClient() - UUID=1bc87ea2-eaa1-4ed6-a7f8-d8d469eda388
,08-04 12:34:03.334  2555  2606 D BtGatt.GattService: onClientRegistered() - UUID=1bc87ea2-eaa1-4ed6-a7f8-d8d469eda388, clientIf=5
08-04 12:34:03.334  3738  3748 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 12:34:03.335  2555  2748 D BtGatt.GattService: start scan with filters
,08-04 12:34:03.337  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:34:03.338  2555  2611 D BtGatt.ScanManager: handling starting scan
08-04 12:34:03.338  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 12:34:03.338  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:34:03.338  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:34:03.339  2555  2611 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
08-04 12:34:03.341  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:34:03.342  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:34:03.342  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:34:03.345  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:34:03.346  2555  2606 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:34:03.346  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.346  2555  2611 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:34:03.348  3738  3784 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:34:03.351  2555  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:34:03.351  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.351  2555  2611 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 12:34:03.352  2555  2611 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 12:34:03.353  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:34:03.353  3738  3784 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:34:03.354  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.354  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:34:03.354  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.354  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:34:03.354  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:34:03.355  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:34:03.355  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 12:34:03.355  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:34:03.356  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:34:03.356  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:34:03.357  3738  3784 D BluetoothAdapter: STATE_ON
,08-04 12:34:03.358  2555  2748 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:34:03.358  2555  2570 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:34:03.359  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 12:34:03.359  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:34:03.359  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 12:34:03.360  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:34:03.360  2555  2606 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:34:03.360  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.360  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:34:03.361  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.361  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:34:03.361  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 12:34:03.362  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:34:03.362  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:03.363  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:03.363  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:34:03.364  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.364  2555  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:34:03.364  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.364  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.364  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.364  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:03.364  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.364  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.364  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.364  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:34:03.364  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.365  3738  3784 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:34:03.367  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.370  2555  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:34:03.370  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.370  2555  2611 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.372  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:03.374  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:34:03.374  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:03.374  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:03.374  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-04 12:34:03.374  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:34:03.374  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.374  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:34:03.376  2555  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:34:03.376  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.376  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.376  2555  2611 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:34:03.379  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.381  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:34:03.381  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:34:03.381  2555  2606 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:34:03.381  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.383  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:34:03.384  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:34:03.384  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:34:03.386  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:34:03.387  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-04 12:34:03.387  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:34:03.387  3738  3784 D BluetoothAdapter: STATE_ON
,08-04 12:34:03.389  2555  2570 D BtGatt.GattService: registerClient() - UUID=f94cabaf-77c1-47e3-8f14-b59d2529dda4
08-04 12:34:03.390  2555  2606 D BtGatt.GattService: onClientRegistered() - UUID=f94cabaf-77c1-47e3-8f14-b59d2529dda4, clientIf=5
08-04 12:34:03.391  3738  3749 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 12:34:03.391  2555  2761 D BtGatt.GattService: start scan with filters
,08-04 12:34:03.395  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:34:03.395  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:34:03.395  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:34:03.395  2555  2611 D BtGatt.ScanManager: handling starting scan
08-04 12:34:03.396  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:34:03.398  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:34:03.398  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 12:34:03.399  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:34:03.399  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 12:34:03.402  2555  2606 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:34:03.402  3738  3784 I io.jxcore.node.ConnectionHelper: start: OK
08-04 12:34:03.402  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.402  2555  2611 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:34:03.404  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:34:03.404  3738  3784 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 12:34:03.404  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.404  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:34:03.404  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.404  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:34:03.404  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 12:34:03.404  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:34:03.404  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:34:03.404  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:34:03.404  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:34:03.404  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:34:03.405  3738  3784 D BluetoothAdapter: STATE_ON
08-04 12:34:03.405  2555  2748 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:34:03.405  2555  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 12:34:03.406  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:34:03.406  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:34:03.406  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:34:03.406  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:34:03.406  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:34:03.406  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.407  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:34:03.407  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:34:03.407  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:34:03.407  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:03.408  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.408  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:03.408  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.408  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:03.408  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:03.408  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.408  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.408  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.408  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.408  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.408  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.408  2555  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:34:03.409  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.409  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.409  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.409  2555  2611 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:34:03.409  2555  2611 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:34:03.409  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.409  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:03.410  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.410  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.410  3738  3784 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:34:03.414  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.419  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:03.420  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.421  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:03.421  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:03.421  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:34:03.421  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:34:03.421  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.421  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:34:03.422  2555  2606 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:34:03.422  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.428  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:34:03.429  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:34:03.432  2555  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:34:03.432  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.433  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.434  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:34:03.436  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:34:03.436  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 12:34:03.436  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:03.439  2555  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:34:03.439  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.440  2555  2611 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:34:03.443  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:34:03.443  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-04 12:34:03.443  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:34:03.444  3738  3784 D BluetoothAdapter: STATE_ON
08-04 12:34:03.445  2555  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:34:03.445  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.445  2555  2611 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:34:03.450  2555  2748 D BtGatt.GattService: registerClient() - UUID=97bce4ec-1fc7-4d25-bc12-49edb5ce5422
08-04 12:34:03.450  2555  2606 D BtGatt.GattService: onClientRegistered() - UUID=97bce4ec-1fc7-4d25-bc12-49edb5ce5422, clientIf=5
,08-04 12:34:03.451  3738  3748 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:34:03.451  2555  2570 D BtGatt.GattService: start scan with filters
08-04 12:34:03.452  2555  2606 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:34:03.452  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.455  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:34:03.455  2555  2611 D BtGatt.ScanManager: handling starting scan
08-04 12:34:03.455  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:34:03.455  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:34:03.455  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:34:03.461  2555  2606 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:34:03.461  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.462  2555  2611 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:34:03.465  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:34:03.466  2555  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 12:34:03.465  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:34:03.467  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.465  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:34:03.467  2555  2611 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:34:03.467  2555  2611 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 12:34:03.474  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:34:03.475  2555  2606 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:34:03.475  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.483  2555  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 12:34:03.483  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.485  3738  3784 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:34:03.486  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.486  3738  3784 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:34:03.486  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.486  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-04 12:34:03.487  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.487  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:34:03.487  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 12:34:03.487  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:34:03.488  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:34:03.488  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:34:03.488  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:34:03.489  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 12:34:03.492  3738  3784 D BluetoothAdapter: STATE_ON
,08-04 12:34:03.493  2555  2761 D BtGatt.GattService: stopScan() - queue size =1
,08-04 12:34:03.494  2555  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 12:34:03.494  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:34:03.494  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:34:03.495  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 12:34:03.495  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-04 12:34:03.495  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-04 12:34:03.496  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.496  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:34:03.497  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:34:03.497  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:34:03.497  2555  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:34:03.497  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:03.497  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:03.497  2555  2611 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:34:03.498  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:34:03.498  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.499  3738  3784 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 12:34:03.499  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:03.499  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.499  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.499  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.499  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.499  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.499  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:03.499  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.499  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:03.500  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.500  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:34:03.500  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.500  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.501  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.501  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.501  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.501  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.501  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.502  3738  3784 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 12:34:03.502  2555  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:34:03.502  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.502  2555  2611 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:34:03.502  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.502  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.502  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.502  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:03.502  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.503  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.503  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.503  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:03.503  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.503  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.503  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.503  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.503  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.503  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.503  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.503  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.503  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:03.504  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.504  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 12:34:03.504  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.504  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.504  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.504  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:03.504  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.505  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.505  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.505  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.505  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.505  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:34:03.505  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.505  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.505  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.505  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.506  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.506  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.506  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.506  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.506  3738  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 12:34:03.506  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.506  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.506  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.506  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.507  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.507  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.507  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
,08-04 12:34:03.507  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.507  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.507  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.507  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.507  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.507  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.507  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.508  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.508  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:03.508  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.508  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.509  2555  2606 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:34:03.509  2555  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:03.509  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-04 12:34:03.509  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:34:03.509  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:34:03.509  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:34:03.509  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:03.509  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.509  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.509  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
,08-04 12:34:03.509  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.509  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.509  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.509  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.509  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.509  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.509  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.511  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.511  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:03.511  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.511  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.511  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 12:34:03.511  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 12:34:03.511  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:34:03.513  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:34:03.513  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 12:34:03.513  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 12:34:03.513  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-04 12:34:03.513  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.513  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.513  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:03.514  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.514  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.514  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
,08-04 12:34:03.514  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.514  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.514  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.514  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.514  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.514  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.514  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.515  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.515  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.515  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:03.515  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.516  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:34:03.516  3738  3784 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 12:34:03.516  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-04 12:34:03.518  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:34:03.518  3738  3784 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 12:34:03.518  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-04 12:34:03.518  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 12:34:03.518  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 12:34:03.518  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 12:34:03.518  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 12:34:03.519  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 12:34:03.520  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 12:34:03.520  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 12:34:03.520  3738  3784 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-04 12:34:03.520  3738  3784 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 12:34:03.520  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:34:03.520  3738  3784 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-04 12:34:03.520  3738  3784 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 12:34:03.520  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-04 12:34:03.521  3738  3784 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:34:03.521  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 12:34:03.523  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-04 12:34:03.524  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 12:34:03.524  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 12:34:03.524  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 12:34:03.525  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-04 12:34:03.525  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 12:34:03.525  3738  3784 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:34:03.525  3738  3784 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-04 12:34:03.525  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.526  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.526  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.526  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:03.526  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.526  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.526  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-04 12:34:03.527  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.527  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.527  3738  3788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-04 12:34:03.528  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.528  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.528  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.528  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.528  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.528  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.529  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.529  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:03.529  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.529  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.529  3738  3788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:34:03.529  3738  3784 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 12:34:03.530  3738  3789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
,08-04 12:34:03.530  3738  3789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-04 12:34:03.530  3738  3789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-04 12:34:03.530  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.530  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.530  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.531  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.531  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.531  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.531  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.531  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.531  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.531  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.531  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.531  3738  3788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-04 12:34:03.531  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.531  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.531  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.532  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.532  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.532  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.532  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.533  3738  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 12:34:03.533  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:34:03.533  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.533  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.533  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.533  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.533  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.533  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.533  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.533  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.533  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.533  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.533  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.533  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.534  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.534  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.534  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.534  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.534  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.535  3738  3784 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 12:34:03.535  3738  3784 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 12:34:03.535  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:34:03.535  3738  3784 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 12:34:03.535  3738  3784 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 12:34:03.535  3738  3784 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 12:34:03.535  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:34:03.535  3738  3784 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 12:34:03.535  3738  3784 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 12:34:03.535  3738  3784 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 12:34:03.535  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:34:03.535  3738  3784 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 12:34:03.535  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.536  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.536  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.536  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.536  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.536  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.536  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.536  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.536  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.536  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.536  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.536  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.536  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.536  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.537  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.537  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.537  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.537  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.538  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.538  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.538  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.538  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.538  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.538  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.538  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.538  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.538  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.538  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.538  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.538  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.538  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.538  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.538  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.538  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.539  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.539  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.539  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.539  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.539  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.539  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.539  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.539  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.539  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.539  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.539  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.539  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.539  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.540  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.540  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.540  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.540  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.541  3738  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 12:34:03.541  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.541  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 12:34:03.542  3738  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 12:34:03.542  3738  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 12:34:03.542  3738  3738 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 12:34:03.542  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 12:34:03.542  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:34:03.543  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.543  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 12:34:03.543  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 12:34:03.543  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 12:34:03.543  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.543  3738  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 12:34:03.543  3738  3790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:34:03.543  3738  3738 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 12:34:03.543  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.543  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.543  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:34:03.543  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:34:03.543  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:34:03.543  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.544  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.544  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.544  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:03.544  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:03.545  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:03.545  3738  3790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-04 12:34:03.545  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.545  3738  3790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 12:34:03.545  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.545  3738  3790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 12:34:03.545  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.545  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:34:03.545  3738  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-04 12:34:03.545  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.545  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.545  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.545  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
,08-04 12:34:03.545  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.545  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.545  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:34:03.546  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.546  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.546  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.546  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.546  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.546  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.546  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.546  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.547  3738  3784 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 12:34:03.547  3738  3784 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-04 12:34:03.548  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-04 12:34:03.548  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:34:03.548  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.548  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.548  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.548  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.548  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.548  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.548  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.548  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:03.548  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.548  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.548  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.548  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.549  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.549  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.549  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.550  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.550  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.550  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.552  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.552  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:34:03.552  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:34:03.552  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:03.552  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:03.552  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.552  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
,08-04 12:34:03.552  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:03.553  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.553  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.553  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.553  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.553  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.553  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.553  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.553  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.553  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.554  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
,08-04 12:34:03.554  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:03.554  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:03.554  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:03.554  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:03.554  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.555  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.555  3738  3784 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e2670 not in the list
08-04 12:34:03.555  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.555  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.555  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:03.555  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.555  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:03.555  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:03.555  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:03.555  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:03.556  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:03.556  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:03.556  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69cade9 not in the list
08-04 12:34:03.556  3738  3784 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 12:34:03.556  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:34:03.556  3738  3784 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-04 12:34:03.556  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-04 12:34:03.556  3738  3784 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 12:34:03.557  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:34:03.558  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 12:34:03.558  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 12:34:03.558  3738  3784 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 12:34:03.558  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 12:34:03.558  3738  3784 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 12:34:03.558  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 12:34:03.559  3738  3784 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 12:34:03.559  3738  3784 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 12:34:03.559  3738  3784 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-04 12:34:03.559  3738  3784 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 12:34:03.559  3738  3784 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 12:34:03.559  3738  3784 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 12:34:03.560  3738  3784 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 12:34:03.560  3738  3784 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 12:34:03.561  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:03.561  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b81ca3 added. We now have 2 listener(s)
08-04 12:34:03.561  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:03.562  3738  3784 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 12:34:03.562   871   882 D WifiService: setWifiEnabled: true pid=3738, uid=10000
08-04 12:34:03.562   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:34:03.563  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:03.563  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a300ba0 added. We now have 3 listener(s)
08-04 12:34:03.563  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:03.566  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:03.566  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7bfe359 added. We now have 4 listener(s)
08-04 12:34:03.567  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:03.568  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:03.568  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cf1b1e added. We now have 5 listener(s)
08-04 12:34:03.568  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:03.569   871  1797 D WifiService: setWifiEnabled: false pid=3738, uid=10000
08-04 12:34:03.569   871  1797 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 12:34:03.572  2555  2602 D BluetoothAdapterState: Current state: ON, message: 23
08-04 12:34:03.572  2555  2602 D BluetoothAdapterProperties: Setting state to 13
08-04 12:34:03.572  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 12:34:03.572  2555  2602 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 12:34:03.574  2555  2555 D BluetoothMapService: onReceive
08-04 12:34:03.574  2555  2555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:34:03.574  2555  2555 D BluetoothMapService: STATE_TURNING_OFF
08-04 12:34:03.574  2555  2555 D BluetoothMapService: MAP Service closeService in
08-04 12:34:03.575  2555  2555 D BluetoothMapMasInstance0: MAP Service shutdown
,08-04 12:34:03.575  2555  2555 D ObexServerSockets0: shutdown(block = true)
08-04 12:34:03.575  2555  2555 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:34:03.575  2555  2555 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:34:03.576  2555  2762 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-04 12:34:03.576  2555  2745 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 12:34:03.576  2555  2763 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 12:34:03.576  2555  2602 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:34:03.578  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.578  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:34:03.578  2555  2555 I BtOppRfcommListener: stopping Accept Thread
08-04 12:34:03.578  2555  3273 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 12:34:03.579  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.579  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.579  2555  3273 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 12:34:03.584  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 12:34:03.586   871  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 12:34:03.586   871  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-04 12:34:03.586   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:34:03.586   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:34:03.590   871   884 I ActivityManager: Start proc 3793:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-04 12:34:03.591  2555  2606 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:34:03.591  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 12:34:03.594  2555  2555 D HeadsetService: Received stop request...Stopping profile...
08-04 12:34:03.595   871   871 D BluetoothHeadset: Proxy object disconnected
,08-04 12:34:03.595   871   871 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:03.596  1750  1763 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:03.596   871  1305 E native  : do suspend true
08-04 12:34:03.596   871   871 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:03.597  1362  1373 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:03.597  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-04 12:34:03.597  2555  2555 D A2dpService: Received stop request...Stopping profile...
08-04 12:34:03.598  2555  2754 D A2dpStateMachine: Exit Disconnected: -1
08-04 12:34:03.599  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-04 12:34:03.599   871   871 D BluetoothA2dp: Proxy object disconnected
08-04 12:34:03.599  2555  2555 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:03.599  2555  2555 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:34:03.599  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:03.599  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:03.601  2555  2555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 12:34:03.601  2555  2555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 12:34:03.601  2555  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:03.601  2555  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:03.601  2555  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:03.601  2555  2606 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 12:34:03.601  2555  2606 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-04 12:34:03.601  2555  2555 D HidService: Received stop request...Stopping profile...
08-04 12:34:03.601  2555  2555 D HidService: Stopping Bluetooth HidService
08-04 12:34:03.602  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,08-04 12:34:03.602  1362  1362 D HidProfile: Bluetooth service disconnected
08-04 12:34:03.602  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:03.603  2555  2555 D HealthService: Received stop request...Stopping profile...
08-04 12:34:03.605  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.608  2555  2555 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:03.608  2555  2555 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:03.608  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:03.608  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:03.609  2555  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:03.609  2555  2606 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-04 12:34:03.610  2555  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:03.610  2555  2724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-04 12:34:03.610  2555  2724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:34:03.610  2555  2724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:34:03.610  2555  2724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:34:03.610   871  2117 D DhcpClient: Clearing IP address
08-04 12:34:03.611   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-04 12:34:03.614  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.614  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:03.614  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.614  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:03.615  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:03.615   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:03.619  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.620  2555  2745 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-04 12:34:03.620  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.621   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 12:34:03.621   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-04 12:34:03.624   394   394 E Parcel  : Reading a NULL string not supported here.
08-04 12:34:03.624  1495  2266 V NativeCrypto: Read error: ssl=0x9b2fee00: I/O error during system call, Connection timed out
08-04 12:34:03.624  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:03.625  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:03.625  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.625  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:03.625  1495  2266 V NativeCrypto: SSL shutdown failed: ssl=0x9b2fee00: I/O error during system call, Broken pipe
,08-04 12:34:03.629   871  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-04 12:34:03.630   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:34:03.630   871  1305 E native  : do suspend true
08-04 12:34:03.632   871  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-04 12:34:03.636  2555  2555 D PanService: Received stop request...Stopping profile...
08-04 12:34:03.637  2555  2555 D BluetoothMapService: Received stop request...Stopping profile...
08-04 12:34:03.637  2555  2555 D BluetoothMapService: stop()
08-04 12:34:03.638  2555  2555 D BluetoothMapAppObserver: deinitObservers()
08-04 12:34:03.638  2555  2555 D BluetoothMapAppObserver: removeReceiver()
08-04 12:34:03.639  2555  2555 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:03.639  2555  2555 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:03.639  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:03.639  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:03.641  2555  2555 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 12:34:03.641  2555  2555 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 12:34:03.641  2555  2606 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:34:03.641  2555  2555 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:03.641  2555  2555 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:03.641  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:03.641  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:03.641  2555  2555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-04 12:34:03.641  2555  2606 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-04 12:34:03.641  2555  2555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 12:34:03.642  2555  2555 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:03.642  2555  2555 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:03.642  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:03.642  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:03.643  2555  2555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 12:34:03.643  2555  2555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 12:34:03.645  2555  2555 D BluetoothMapService: MAP Service closeService in
,08-04 12:34:03.646  2555  2555 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:03.646  2555  2555 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:03.646  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:03.646  2555  2555 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:03.646  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 12:34:03.646  2555  2602 D BluetoothAdapterProperties: Setting state to 15
08-04 12:34:03.646  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 12:34:03.646  2555  2602 I BluetoothAdapterState: Entering BleOnState
,08-04 12:34:03.647  1750  1915 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:03.647  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:34:03.647  2555  2555 D BluetoothMapService: cleanup()
08-04 12:34:03.647   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:03.647  1362  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:34:03.647  2555  2555 D BluetoothMapService: MAP Service closeService in
08-04 12:34:03.648   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 12:34:03.648   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:34:03.648  1362  1839 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:34:03.648  1362  1376 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:34:03.649  1362  1373 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:34:03.651  1362  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:03.651   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 12:34:03.651  2555  2602 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-04 12:34:03.651  2555  2602 D BluetoothAdapterProperties: Setting state to 16
08-04 12:34:03.651  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-04 12:34:03.652  2555  2602 D BluetoothAdapterProperties: onBleDisable
08-04 12:34:03.652  2555  2602 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:34:03.653  2555  2603 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 12:34:03.653  2555  2606 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:34:03.654  2555  2724 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 12:34:03.654  2555  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:03.655   871  2119 D DhcpClient: Receive thread stopped
08-04 12:34:03.655  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:03.655  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:03.656  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.656  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:03.657  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:03.657  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:03.658  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.659  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.665  3793  3793 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-04 12:34:03.674  3793  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:34:03.674   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-04 12:34:03.681  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 12:34:03.690   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d6d1ba:true
,08-04 12:34:03.694   871  1375 I ActivityManager: Start proc 3809:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-04 12:34:03.705   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:34:03.705   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-04 12:34:03.706   871  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 12:34:03.706   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:03.707   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:34:03.711   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:34:03.711  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:03.713  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:03.725   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:34:03.727  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:03.727  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:03.727   871  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 12:34:03.728  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.728  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:03.729  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:03.729  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:03.729  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:03.729  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:03.729  1842  2054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:34:03.732  3258  3258 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@27c4f57 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-04 12:34:03.747  3809  3809 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-04 12:34:03.753   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-04 12:34:03.754   871  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-04 12:34:03.755  3793  3793 D LocalBluetoothProfileManager: Adding local MAP profile
,08-04 12:34:03.757  3793  3793 D BluetoothMap: Create BluetoothMap proxy object
,08-04 12:34:03.760  3793  3793 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-04 12:34:03.773  3793  3793 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:34:03.779   871  1797 I ActivityManager: Killing 3258:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-04 12:34:03.855  2555  2606 I bt_hci  : shut_down
,08-04 12:34:03.856  2555  2612 D bt_hwcfg: hw_epilog_process
,08-04 12:34:03.867  2555  2612 I bt_vendor: low_power_mode_cb
,08-04 12:34:03.887  2555  2612 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 12:34:03.887  2555  2612 I bt_vendor: epilog_cb
,08-04 12:34:03.887  2555  2612 I bt_hci  : epilog_finished_callback
,08-04 12:34:03.893  2555  2606 I bt_hci_h4: hal_close
,08-04 12:34:03.894  2555  2606 I bt_userial_vendor: device fd = 51 close,
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.k.d(PG:583)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.939  3809  3809 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:34:03.939  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:34:03.978   871  1699 I ActivityManager: Start proc 3844:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-04 12:34:03.979   871  1699 I ActivityManager: Killing 3320:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-04 12:34:04.045  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:34:04.060  2555  2603 D bt_stack_manager: event_shut_down_stack finished.
,08-04 12:34:04.061  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 12:34:04.065  2555  2602 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-04 12:34:04.066  2555  2555 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 12:34:04.066  2555  2555 D BtGatt.GattService: Received stop request...Stopping profile...
,08-04 12:34:04.066  2555  2555 D BtGatt.GattService: stop()
08-04 12:34:04.066  2555  2555 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 12:34:04.069  2555  2555 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:04.069  2555  2555 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:34:04.069  2555  2555 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:04.069  2555  2555 V BluetoothAdapterState: isBleTurningOff()=true
,08-04 12:34:04.070  2555  2602 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-04 12:34:04.071  2555  2602 D BluetoothAdapterProperties: Setting state to 10
,08-04 12:34:04.071  2555  2602 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-04 12:34:04.072  2555  2602 I BluetoothAdapterState: Entering OffState
08-04 12:34:04.073   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-04 12:34:04.081  3844  3844 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-04 12:34:04.090  2555  2555 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-04 12:34:04.090  2555  2555 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-04 12:34:04.090  2555  2603 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 12:34:04.090  2555  2555 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 12:34:04.092  2555  2603 D bt_stack_manager: event_clean_up_stack finished.
,08-04 12:34:04.105  2555  2555 I art     : System.exit called, status: 0
,08-04 12:34:04.105  2555  2555 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 12:34:04.166   871  1699 I ActivityManager: Process com.android.bluetooth (pid 2555) has died
,08-04 12:34:04.294  3844  3863 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-04 12:34:04.294  3844  3863 I Babel_SMS: MmsConfig.loadMmsSettings
,08-04 12:34:04.306  3844  3863 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-04 12:34:04.306  3844  3863 I Babel_SMS: MmsConfig.loadFromDatabase
,08-04 12:34:04.375  3844  3863 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-04 12:34:04.375  3844  3863 I Babel_SMS: MmsConfig.loadFromResources
08-04 12:34:04.377  3844  3863 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-04 12:34:04.378  3844  3863 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-04 12:34:04.402  3844  3844 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:34:04.404  3844  3844 I Babel_Crash: startup - clean
,08-04 12:34:04.436  3844  3844 I Babel_telephony: TeleModule.launchCompleted
,08-04 12:34:04.448   871  1690 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 12:34:04.463  3844  3844 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-04 12:34:04.476  3844  3844 W Babel   : BAM#gBA: invalid account id: -1
,08-04 12:34:04.476  3844  3844 W Babel   : BAM#gBA: invalid account id: -1
08-04 12:34:04.476  3844  3844 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-04 12:34:04.482  3844  3869 I Babel   : deleted: false for 0
,08-04 12:34:04.488   871  1690 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 12:34:04.520  3793  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:34:04.542  3809  3841 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-04 12:34:04.552   871   882 I ActivityManager: Start proc 3872:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-04 12:34:04.553  3793  3793 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:34:04.570  3844  3844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:34:04.625  3844  3844 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 12:34:04.633  3844  3844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:34:04.649  3844  3844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:34:04.653  3844  3844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:34:04.672  3844  3844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:34:04.691  3844  3844 I vclib   : onServiceConnected
,08-04 12:34:04.710  3872  3872 D AdapterServiceConfig: Adding HeadsetService
08-04 12:34:04.710  3872  3872 D AdapterServiceConfig: Adding A2dpService
08-04 12:34:04.711  3872  3872 D AdapterServiceConfig: Adding HidService
08-04 12:34:04.711  3872  3872 D AdapterServiceConfig: Adding HealthService
,08-04 12:34:04.711  3872  3872 D AdapterServiceConfig: Adding PanService
,08-04 12:34:04.721  3872  3872 D AdapterServiceConfig: Adding GattService
,08-04 12:34:04.721  3872  3872 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 12:34:04.726   871  1699 I ActivityManager: Killing 2955:android.process.acore/u0a5 (adj 15): empty #17
,08-04 12:34:04.742   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e75a7d:true
,08-04 12:34:04.822  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:04.848  1792  1792 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:34:04.854  1792  1792 D SystemUpdateService: onCreate
,08-04 12:34:04.860  1792  1792 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:34:04.871  1792  3884 I SystemUpdateService: active receiver: enabled
,08-04 12:34:04.878  1792  3884 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:34:04.883  1792  1792 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-04 12:34:04.883  1792  3884 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-04 12:34:04.883  1792  3884 I SystemUpdateService: now status is 0 (complete)
,08-04 12:34:04.883  1792  3884 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:34:04.884  1792  3884 I SystemUpdateService: file has been verified
,08-04 12:34:04.884  1792  2358 I iu.UploadsManager: num queued entries: 0
08-04 12:34:04.885  1792  3884 I SystemUpdateService: OTA package size = 12249756
,08-04 12:34:04.886  1792  2358 I iu.UploadsManager: num updated entries: 0
,08-04 12:34:04.888  1792  2358 I iu.SyncManager: NEXT; no task
,08-04 12:34:04.894  1792  3884 I SystemUpdateService: showing system update notification
,08-04 12:34:04.904  1792  1792 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:34:04.906  1792  1792 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:34:04.920   871  1709 I ActivityManager: Start proc 3886:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-04 12:34:04.922  1792  1792 D SystemUpdateService: onDestroy
,08-04 12:34:04.968  3886  3886 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-04 12:34:04.971  3886  3886 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:04.978  3886  3886 D SprintDMHelper: simOperator: 
,08-04 12:34:04.978  3886  3886 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:34:04.998   871  1697 I ActivityManager: Start proc 3898:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-04 12:34:04.999   871  1697 I ActivityManager: Killing 3557:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-04 12:34:05.143   871  1797 I ActivityManager: Start proc 3913:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-04 12:34:05.147  3844  3912 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-04 12:34:05.150   871  1374 I ActivityManager: Killing 3572:com.android.musicfx/u0a18 (adj 15): empty #17
,08-04 12:34:05.216  3913  3913 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-04 12:34:05.274  3913  3913 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-04 12:34:05.274  3913  3913 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-04 12:34:05.274  3913  3913 I GAv4    :   adb logcat -s GAv4
,08-04 12:34:05.289  3913  3913 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:34:05.294  3913  3913 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:34:05.327  3913  3930 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:34:05.451  3913  3913 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-04 12:34:05.494  3913  3913 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 12:34:05.502  3913  3913 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8092-8094)
,08-04 12:34:05.502  3913  3913 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 12:34:05.516  3913  3913 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5675e99}
,08-04 12:34:05.516  3913  3913 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 12:34:05.517  3913  3913 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 12:34:05.525  3913  3913 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 12:34:05.528  3913  3913 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 12:34:05.547  3913  3913 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 12:34:05.559  3913  3913 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 12:34:05.559  3913  3913 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 12:34:05.559  3913  3913 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 12:34:05.559  3913  3913 I Adreno  : Build Date                       : 10/20/15
08-04 12:34:05.559  3913  3913 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 12:34:05.559  3913  3913 I Adreno  : Local Branch                     : M14
08-04 12:34:05.559  3913  3913 I Adreno  : Remote Branch                    : 
08-04 12:34:05.559  3913  3913 I Adreno  : Remote Branch                    : 
08-04 12:34:05.559  3913  3913 I Adreno  : Reconstruct Branch               : 
,08-04 12:34:05.621  3913  3913 I NSApplication: Starting up...
,08-04 12:34:05.630  3913  3959 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 12:34:05.666   871  1375 I ActivityManager: Start proc 3964:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-04 12:34:05.673   871  1375 I ActivityManager: Killing 3303:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-04 12:34:05.741  3964  3964 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-04 12:34:05.906   871   882 I ActivityManager: Killing 3519:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-04 12:34:06.617   871   881 D WifiService: setWifiEnabled: true pid=3738, uid=10000
,08-04 12:34:06.617   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:34:06.635   871  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-04 12:34:06.641  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:06.642  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:06.642  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:06.642  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:06.645  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:06.645  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:06.645  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:06.646  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:06.667   871  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-04 12:34:06.668   871  1305 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 12:34:06.668   871  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000,
08-04 12:34:06.669   871  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 12:34:06.670   871  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-04 12:34:06.670   871  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 12:34:06.670   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 12:34:06.670   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 12:34:06.693   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:34:06.694   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 12:34:06.696   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:06.704   871  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-04 12:34:06.704   871  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 12:34:06.705   871  1305 E native  : do suspend true
,08-04 12:34:06.717   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:34:06.739   871  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 12:34:06.740   871  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 12:34:08.093   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:34:08.170   871  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.81 rxSuccessRate=10.69 delta 1000 -> 994
,08-04 12:34:08.172   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 12:34:08.172   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:34:08.186   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 12:34:08.272   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 12:34:08.276  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 12:34:08.705  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 12:34:08.731  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 12:34:08.732  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 12:34:08.741   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:34:08.758   871  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 12:34:08.758   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:34:08.758   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-04 12:34:08.770   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:34:08.779   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:08.780   871  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-04 12:34:08.790   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 12:34:08.834   871  3988 D DhcpClient: Receive thread started
,08-04 12:34:08.918   871  1305 E native  : do suspend false
,08-04 12:34:08.939   871  2117 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 12:34:08.953   871  3988 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172411, domain null
,08-04 12:34:08.954   871  2117 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172411 seconds
,08-04 12:34:08.958   871  2117 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 12:34:08.970   871  3988 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-04 12:34:08.971   871  2117 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 12:34:08.975   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:08.990   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 12:34:08.990   871  2117 D DhcpClient: Scheduling renewal in 86399s
,08-04 12:34:08.993   871  1305 E native  : do suspend true
,08-04 12:34:09.023   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 12:34:09.028   871  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 12:34:09.030   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 12:34:09.032   871  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-04 12:34:09.044   871  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 12:34:09.099   871  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 12:34:09.099   871  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-04 12:34:09.100   871  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-04 12:34:09.101   871  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-04 12:34:09.103   871  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-04 12:34:09.115   871  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 12:34:09.123   871  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-04 12:34:09.123   871  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-04 12:34:09.123   871  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-04 12:34:09.123   871  1307 D ConnectivityService:    accepting network in place of null
08-04 12:34:09.123   871  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-04 12:34:09.125   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:34:09.126   871  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:34:09.135   871  3987 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411727, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 12:34:09.171   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:34:09.202   871  3986 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:34:09.218   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:34:09.225   871  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 12:34:09.226   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:09.235   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:34:09.229   871  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-04 12:34:09.246  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:09.247  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:09.247  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.247  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:34:09.253  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:09.253  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:09.253  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.253  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:34:09.257  1792  1792 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:34:09.264  1792  1792 D SystemUpdateService: onCreate
,08-04 12:34:09.268  1792  1792 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:34:09.271  1792  4002 I SystemUpdateService: active receiver: enabled
,08-04 12:34:09.275  1792  4002 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:34:09.278  1792  4002 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-04 12:34:09.278  1792  4002 I SystemUpdateService: now status is 0 (complete)
08-04 12:34:09.278  1792  4002 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:34:09.278  1792  4002 I SystemUpdateService: file has been verified
08-04 12:34:09.278  1792  4002 I SystemUpdateService: OTA package size = 12249756
,08-04 12:34:09.283  1792  4002 I SystemUpdateService: showing system update notification
,08-04 12:34:09.292  1792  1792 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 12:34:09.296  1792  2358 I iu.UploadsManager: num queued entries: 0
,08-04 12:34:09.296  1792  4005 I MDM     : [207] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 12:34:09.296  1792  4005 W BaseAppContext: Using Auth Proxy for data requests.
08-04 12:34:09.298  1792  4005 V GoogleAuthProtoRequest: [207] a.<init>: mAccountName set to: thalitester@gmail.com
08-04 12:34:09.298  1792  1792 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-04 12:34:09.299  1792  2358 I iu.UploadsManager: num updated entries: 0
08-04 12:34:09.299  1792  1792 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:34:09.299  1792  1792 D SystemUpdateService: onDestroy
08-04 12:34:09.302  3886  3886 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:09.305   871  3986 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 10:34:09 GMT], X-Android-Received-Millis=[1470306849305], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470306849261]}
,08-04 12:34:09.306  1792  2358 I iu.SyncManager: NEXT; no task
,08-04 12:34:09.306   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-04 12:34:09.306   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-04 12:34:09.307   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 12:34:09.308   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 12:34:09.309  3886  3886 D SprintDMHelper: simOperator: 
,08-04 12:34:09.309  3886  3886 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:34:09.316  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:34:09.319  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:34:09.351  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-04 12:34:09.351  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 12:34:09.351  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 12:34:09.351  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:34:09.367  1792  4005 E MDM     : [207] SitrepService.a: Error sending sitrep.
,08-04 12:34:09.459  3844  4008 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 12:34:09.548   871  1797 I ActivityManager: Killing 3595:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-04 12:34:09.630   871  1709 D WifiService: setWifiEnabled: false pid=3738, uid=10000
,08-04 12:34:09.631   871  1709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:34:09.659  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 12:34:09.664   871  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-04 12:34:09.665   871  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-04 12:34:09.665   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:34:09.665   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:34:09.678   871  1305 E native  : do suspend true
,08-04 12:34:09.684   871  2117 D DhcpClient: Clearing IP address
08-04 12:34:09.685   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-04 12:34:09.686   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:09.699   871  3988 D DhcpClient: Receive thread stopped
,08-04 12:34:09.700   871  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
08-04 12:34:09.701   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:34:09.701   871  1305 E native  : do suspend true
,08-04 12:34:09.701   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 12:34:09.701   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-04 12:34:09.705   394   394 E Parcel  : Reading a NULL string not supported here.
08-04 12:34:09.709   871  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-04 12:34:09.719  1495  4013 V NativeCrypto: Read error: ssl=0x9add8800: I/O error during system call, Connection timed out
,08-04 12:34:09.721  1495  4013 V NativeCrypto: SSL shutdown failed: ssl=0x9add8800: I/O error during system call, Broken pipe
,08-04 12:34:09.758   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:34:09.785   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-04 12:34:09.785   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-04 12:34:09.786   871  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 12:34:09.786   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:09.789   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:34:09.792  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:09.793  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:09.793  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.793  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:09.793   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-04 12:34:09.795  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:09.795  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:09.795  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.795  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:09.809   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-04 12:34:09.812  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.812   871  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:09.812  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:09.812  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.812  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:09.813  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:09.813  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:09.813  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:09.813  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:09.815  1792  1792 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:34:09.818  1842  2054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:34:09.823  1792  1792 D SystemUpdateService: onCreate
,08-04 12:34:09.825  1792  1792 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:34:09.834  1792  1792 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 12:34:09.836  1792  2358 I iu.UploadsManager: num queued entries: 0
08-04 12:34:09.836  1792  2358 I iu.UploadsManager: num updated entries: 0
08-04 12:34:09.837  1792  2358 I iu.SyncManager: NEXT; no task
,08-04 12:34:09.842  1792  1792 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:34:09.843  1792  1792 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:34:09.846  3886  3886 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:09.851  1792  4023 I SystemUpdateService: active receiver: enabled
,08-04 12:34:09.851  3886  3886 D SprintDMHelper: simOperator: 
,08-04 12:34:09.851  3886  3886 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:34:09.864   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-04 12:34:09.872  3844  4027 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-04 12:34:09.874  1792  4023 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:34:09.879  1792  4023 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-04 12:34:09.879  1792  4023 I SystemUpdateService: now status is 0 (complete)
08-04 12:34:09.879  1792  4023 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:34:09.879  1792  4023 I SystemUpdateService: file has been verified
,08-04 12:34:09.879  1792  4023 I SystemUpdateService: OTA package size = 12249756
,08-04 12:34:09.894  1792  4023 I SystemUpdateService: showing system update notification
,08-04 12:34:09.906  1792  1792 D SystemUpdateService: onDestroy
,08-04 12:34:10.225   871  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 12:34:12.685  3872  3872 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 12:34:12.685   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@72891f4:true
,08-04 12:34:12.691  3872  3872 I bt_bluedroid: init
,08-04 12:34:12.691  3872  4031 I BluetoothAdapterState: Entering OffState
,08-04 12:34:12.696  3872  4032 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 12:34:12.697  3872  4032 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 12:34:12.697  3872  4032 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 12:34:12.698  3872  4032 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 12:34:12.699  3872  3872 I bt_bluedroid: get_profile_interface socket
,08-04 12:34:12.703  3872  4035 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:34:12.704  3872  3872 I bt_bluedroid: get_profile_interface sdp
08-04 12:34:12.705  3872  4035 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:34:12.712  3872  3882 I bt_bluedroid: config_hci_snoop_log
,08-04 12:34:12.715   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 12:34:12.726  3872  4031 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 12:34:12.727  3872  4031 D BluetoothAdapterProperties: Setting state to 14
08-04 12:34:12.727  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 12:34:12.732  3872  4031 D BluetoothBondStateMachine: make
,08-04 12:34:12.737  3872  4036 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 12:34:12.749  3872  4031 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:34:12.750  3872  3872 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 12:34:12.763  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:12.767  3872  3872 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:34:12.768  3872  3872 D BtGatt.GattService: Received start request. Starting profile...
,08-04 12:34:12.769  3872  3872 D BtGatt.GattService: start()
08-04 12:34:12.769  3872  3872 I bt_bluedroid: get_profile_interface gatt
,08-04 12:34:12.772  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
08-04 12:34:12.772  3872  3872 D BtGatt.AdvertiseManager: advertise manager created
,08-04 12:34:12.790  3872  3872 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:12.790  3872  3872 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:12.791  3872  3872 V BluetoothAdapterState: isBleTurningOn()=true
08-04 12:34:12.791  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:12.792  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-04 12:34:12.793  3872  4031 I bt_bluedroid: enable
,08-04 12:34:12.793  3872  4032 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-04 12:34:12.795  3872  4032 I bt_hci  : start_up
,08-04 12:34:12.819  3872  4032 I bt_vendor: alloc value 0xb39f9189
08-04 12:34:12.820  3872  4032 I bt_vendor: init
08-04 12:34:12.820  3872  4032 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 12:34:12.821  3872  4032 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 12:34:12.930  3872  4032 D bt_hci  : start_up starting async portion
,08-04 12:34:12.930  3872  4039 I bt_hci  : event_finish_startup
08-04 12:34:12.931  3872  4039 I bt_hci_h4: hal_open
,08-04 12:34:12.932  3872  4039 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 12:34:12.943  3872  4039 I bt_userial_vendor: device fd = 51 open
,08-04 12:34:12.972  3872  4039 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:34:13.003  3872  4039 D bt_hwcfg: Chipset BCM4354A2
,08-04 12:34:13.004  3872  4039 D bt_hwcfg: Target name = [BCM4354A2]
08-04 12:34:13.004  3872  4039 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 12:34:13.664  3872  4039 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 12:34:13.665  3872  4039 D bt_hwcfg: Settlement delay -- 100 ms
08-04 12:34:13.665  3872  4039 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 12:34:13.782  3872  4039 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:34:13.783  3872  4039 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 12:34:13.813  3872  4039 I bt_hwcfg: vendor lib fwcfg completed
,08-04 12:34:13.813  3872  4039 I bt_vendor: firmware callback
,08-04 12:34:13.813  3872  4039 I bt_hci  : firmware_config_callback
,08-04 12:34:13.824  3872  4041 I bt_btu  : btu_task pending for preload complete event
,08-04 12:34:13.825  3872  4041 I bt_btu_task: Bluetooth chip preload is complete
08-04 12:34:13.825  3872  4041 I bt_btu  : btu_task received preload complete event
,08-04 12:34:13.837  3872  4041 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 12:34:13.838  3872  4041 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 12:34:13.838  3872  4041 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-04 12:34:13.838  3872  4041 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 12:34:13.838  3872  4041 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-04 12:34:13.839  3872  4041 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 12:34:13.840  3872  4041 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-04 12:34:13.841  3872  4041 I         : BTE_InitTraceLevels -- TRC_BTM
,08-04 12:34:13.842  3872  4041 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 12:34:13.842  3872  4041 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 12:34:13.843  3872  4041 I         : BTE_InitTraceLevels -- TRC_SDP
,08-04 12:34:13.844  3872  4041 I         : BTE_InitTraceLevels -- TRC_GATT
,08-04 12:34:13.844  3872  4041 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 12:34:13.846  3872  4041 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 12:34:13.846  3872  4041 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 12:34:13.978  3872  4041 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-04 12:34:13.979  3872  4041 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-04 12:34:13.992  3872  4035 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-04 12:34:13.994  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-04 12:34:13.996  3872  4035 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:34:13.999  3872  4035 D BluetoothAdapterProperties: Name is: Nexus 6,
08-04 12:34:14.002  3872  4035 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:34:14.003  3872  4035 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:34:14.003  3872  4035 D bt_hci  : do_postload posting postload work item
08-04 12:34:14.003  3872  4039 I bt_hci  : event_postload
,08-04 12:34:14.004  3872  4039 I bt_vendor: sco_config_cb
,08-04 12:34:14.004  3872  4039 I bt_hci  : sco_config_callback postload finished.
08-04 12:34:14.008  3872  4035 D bt_bte_conf: Device ID record 1 : primary
,08-04 12:34:14.008  3872  4035 D bt_bte_conf:   vendorId            = 000f
08-04 12:34:14.008  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:14.008  3872  4035 D bt_bte_conf:   vendorIdSource      = 0001
,08-04 12:34:14.009  3872  4035 D bt_bte_conf:   product             = 1200
08-04 12:34:14.009  3872  4035 D bt_bte_conf:   version             = 1436
08-04 12:34:14.009  3872  4035 D bt_bte_conf:   clientExecutableURL = 
08-04 12:34:14.009  3872  4035 D bt_bte_conf:   serviceDescription  = 
08-04 12:34:14.009  3872  4035 D bt_bte_conf:   documentationURL    = 
08-04 12:34:14.010  3872  4035 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-04 12:34:14.010  3872  4032 D bt_stack_manager: event_start_up_stack finished
08-04 12:34:14.011  3872  4039 I bt_vendor: low_power_mode_cb
08-04 12:34:14.012  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 12:34:14.013  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:14.013  3872  4031 D BluetoothAdapterProperties: Setting state to 15
08-04 12:34:14.013  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-04 12:34:14.016  3872  4031 I BluetoothAdapterState: Entering BleOnState
,08-04 12:34:14.020  3872  4031 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-04 12:34:14.021  3872  4031 D BluetoothAdapterProperties: Setting state to 11
08-04 12:34:14.021  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 12:34:14.025  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:14.026  3872  3872 D HeadsetService: Received start request. Starting profile...
,08-04 12:34:14.029  3872  3872 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 12:34:14.029  3872  3872 D HeadsetStateMachine: make
08-04 12:34:14.032  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:14.039  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:14.044  3872  3872 D HeadsetStateMachine: max_hf_connections = 1
,08-04 12:34:14.044  3872  3872 I bt_bluedroid: get_profile_interface handsfree
,08-04 12:34:14.044  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 12:34:14.044  3872  4035 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 12:34:14.048  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:14.049  3872  3872 D A2dpService: Received start request. Starting profile...
,08-04 12:34:14.050  3872  3872 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 12:34:14.050  3872  3872 I bt_bluedroid: get_profile_interface avrcp
,08-04 12:34:14.050  3872  4031 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:34:14.056  3872  3872 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 12:34:14.056  3872  3872 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 12:34:14.056  3872  3872 D A2dpStateMachine: make
,08-04 12:34:14.057  3872  3872 I bt_bluedroid: get_profile_interface a2dp
,08-04 12:34:14.058  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 12:34:14.060  3872  4050 D A2dpStateMachine: Enter Disconnected: -2
,08-04 12:34:14.063  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:14.064  3872  3872 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 12:34:14.065  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:14.066  3872  3872 D HidService: Received start request. Starting profile...
08-04 12:34:14.066  3872  3872 I bt_bluedroid: get_profile_interface hidhost
,08-04 12:34:14.066  3793  3793 D BluetoothInputDevice: Proxy object connected
08-04 12:34:14.066  3872  4035 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-04 12:34:14.066  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 12:34:14.066  3872  3872 D HidService: setHidService(): set to: null
08-04 12:34:14.067  3793  3793 D HidProfile: Bluetooth service connected
08-04 12:34:14.067  3872  3872 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 12:34:14.068  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:14.068  3872  3872 D HealthService: Received start request. Starting profile...
,08-04 12:34:14.071  3872  3872 I bt_bluedroid: get_profile_interface health
,08-04 12:34:14.072  3872  3872 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 12:34:14.073  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:14.074  3872  3872 D PanService: Received start request. Starting profile...
,08-04 12:34:14.074  3872  3872 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-04 12:34:14.074  3872  3872 I bt_bluedroid: get_profile_interface pan
,08-04 12:34:14.075  3872  4035 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-04 12:34:14.074  3793  3793 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 12:34:14.076  3872  3872 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:14.076  3872  3872 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:14.076  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:14.076  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:14.077  3793  3793 D PanProfile: Bluetooth service connected
,08-04 12:34:14.079  3872  4047 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 12:34:14.080  3872  3872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
08-04 12:34:14.082  3872  3872 D BluetoothMapService: Received start request. Starting profile...
08-04 12:34:14.082  3872  3872 D BluetoothMapService: start()
,08-04 12:34:14.082  3793  3793 D BluetoothMap: Proxy object connected
08-04 12:34:14.082  3793  3793 D MapProfile: Bluetooth service connected
,08-04 12:34:14.082  3793  3793 D BluetoothMap: getConnectedDevices()
08-04 12:34:14.083  3793  3793 D BluetoothMap: Bluetooth is Not enabled
,08-04 12:34:14.084  3872  3872 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 12:34:14.085  3872  3872 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-04 12:34:14.085  3872  3872 D BluetoothMapAppObserver: createReceiver()
08-04 12:34:14.085  3872  3872 D BluetoothMapAppObserver: initObservers()
,08-04 12:34:14.086  3872  3872 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 12:34:14.091  3872  3872 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:14.091  3872  3872 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:14.091  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:14.091  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:14.093  3872  3872 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:14.093  3872  3872 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:14.093  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:14.093  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isTurningOff()=false
08-04 12:34:14.094  3872  3872 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:14.095  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:14.095  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:14.095  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 12:34:14.095  3872  4031 D BluetoothAdapterProperties: ScanMode =  20
,08-04 12:34:14.095  3872  4031 D BluetoothAdapterProperties: State =  11
08-04 12:34:14.097  3872  4035 D BluetoothAdapterProperties: Scan Mode:21
08-04 12:34:14.097  3872  4031 D BluetoothAdapterProperties: Setting state to 12
08-04 12:34:14.097  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 12:34:14.098  3872  4035 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:34:14.098  3872  4031 I BluetoothAdapterState: Entering OnState
,08-04 12:34:14.098  1750  1764 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:14.099  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 12:34:14.100  1362  1362 D BluetoothInputDevice: Proxy object connected
08-04 12:34:14.100  1362  1362 D HidProfile: Bluetooth service connected
,08-04 12:34:14.102   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:14.102  1362  1839 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:14.105  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:14.105  1362  1362 D BluetoothA2dp: Proxy object connected
,08-04 12:34:14.106  3793  3803 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 12:34:14.107  3793  3804 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:34:14.107   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:14.107  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:14.107  3793  3803 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 12:34:14.108  3793  3804 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:14.110  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:14.110   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:34:14.111   871   871 D BluetoothA2dp: Proxy object connected
,08-04 12:34:14.111  3872  3872 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 12:34:14.112  1362  1373 D BluetoothPan: onBluetoothStateChange on: true
,08-04 12:34:14.112  3872  3872 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-04 12:34:14.112  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:14.113  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 12:34:14.113  1362  1362 D PanProfile: Bluetooth service connected
08-04 12:34:14.113  1362  1839 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 12:34:14.114  3872  3872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:34:14.116  1362  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 12:34:14.116  1362  1362 D BluetoothMap: Proxy object connected
08-04 12:34:14.116  1362  1362 D MapProfile: Bluetooth service connected
08-04 12:34:14.116  1362  1362 D BluetoothMap: getConnectedDevices()
,08-04 12:34:14.117  3872  3872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:34:14.118  3872  3872 D ObexServerSockets: Succeed to create listening sockets 
,08-04 12:34:14.118  3872  3872 D ObexServerSockets0: startAccept()
08-04 12:34:14.118  1362  1839 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:14.118  3872  3872 D ObexServerSockets0: prepareForNewConnect()
08-04 12:34:14.119   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:34:14.120   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 12:34:14.120  3872  3872 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 12:34:14.121  3872  3872 D BluetoothSdpJni: SDP Create record success - handle: 0
08-04 12:34:14.121  3872  4056 D ObexServerSockets0: Accepting socket connection...
08-04 12:34:14.122  3872  4057 D ObexServerSockets0: Accepting socket connection...
08-04 12:34:14.122  3872  3872 D BluetoothMapService: onReceive
08-04 12:34:14.122  3872  3872 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:34:14.122  3872  3872 D BluetoothMapService: STATE_ON
,08-04 12:34:14.124  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:14.125  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:14.125  3793  3793 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-04 12:34:14.129  3793  3793 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-04 12:34:14.135  3793  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:34:14.143  3872  3872 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:34:14.143  3872  3872 D ObexServerSockets0: prepareForNewConnect()
,08-04 12:34:14.144  3793  3793 D BluetoothA2dp: Proxy object connected
,08-04 12:34:14.149  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:14.160  3793  3793 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:34:14.161  3793  3793 D BluetoothPbap: Proxy object connected
,08-04 12:34:14.162  3793  3793 D PbapServerProfile: Bluetooth service connected
08-04 12:34:14.162  1362  1362 D BluetoothPbap: Proxy object connected
08-04 12:34:14.162  1362  1362 D PbapServerProfile: Bluetooth service connected,
,08-04 12:34:14.180  3872  4061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:34:14.192  3872  4065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:34:14.194  3872  4065 I BtOppRfcommListener: Accept thread started.
,08-04 12:34:14.200   871   871 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.200   871   871 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.202   871   888 D BluetoothHeadset: Proxy object connected
08-04 12:34:14.202  1750  1763 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.202   871   871 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.203  1362  1376 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.203  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-04 12:34:14.207   871   888 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.220  1362  1373 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.220  1362  1362 D HeadsetProfile: Bluetooth service connected
08-04 12:34:14.220   871   888 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.233  3793  3803 D BluetoothHeadset: Proxy object connected
,08-04 12:34:14.234  3793  3793 D HeadsetProfile: Bluetooth service connected
,08-04 12:34:15.647  3872  4031 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 12:34:15.648  3872  4031 D BluetoothAdapterProperties: Setting state to 13
,08-04 12:34:15.648  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 12:34:15.650  3872  4031 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 12:34:15.652  3872  4031 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:34:15.659  3872  3872 D BluetoothMapService: onReceive
08-04 12:34:15.660  3872  3872 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:34:15.660  3872  3872 D BluetoothMapService: STATE_TURNING_OFF
08-04 12:34:15.661  3872  3872 D BluetoothMapService: MAP Service closeService in
08-04 12:34:15.661  3872  3872 D BluetoothMapMasInstance0: MAP Service shutdown
,08-04 12:34:15.661  3872  3872 D ObexServerSockets0: shutdown(block = true)
08-04 12:34:15.663  3872  4056 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-04 12:34:15.663  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:15.664  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:15.668  3872  3872 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:34:15.669  3872  4057 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 12:34:15.669  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:15.670  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:15.670  3872  4044 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-04 12:34:15.672  3872  4035 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:34:15.672  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-04 12:34:15.674  3872  3872 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:34:15.676  3872  3872 I BtOppRfcommListener: stopping Accept Thread
08-04 12:34:15.677  3872  4065 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 12:34:15.677  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:34:15.678  3872  4065 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:15.678  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:15.680  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:34:15.680  3793  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:34:15.680  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:15.681  3872  3872 D HeadsetService: Received stop request...Stopping profile...
08-04 12:34:15.683  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:15.684  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:15.690  3872  3872 D A2dpService: Received stop request...Stopping profile...
,08-04 12:34:15.690   871   871 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:15.690   871   871 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:15.690  1750  1915 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:15.691  3872  4050 D A2dpStateMachine: Exit Disconnected: -1
08-04 12:34:15.691  3793  3804 D BluetoothHeadset: Proxy object disconnected
,08-04 12:34:15.692   871   871 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:15.692  1362  1376 D BluetoothHeadset: Proxy object disconnected
08-04 12:34:15.692  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-04 12:34:15.693  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-04 12:34:15.693   871   871 D BluetoothA2dp: Proxy object disconnected
08-04 12:34:15.695  3872  3872 D HidService: Received stop request...Stopping profile...
08-04 12:34:15.695  3872  3872 D HidService: Stopping Bluetooth HidService
,08-04 12:34:15.696  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-04 12:34:15.696  1362  1362 D HidProfile: Bluetooth service disconnected
,08-04 12:34:15.697  3793  3793 D DockEventReceiver: finishStartingService: stopping service
08-04 12:34:15.698  3872  3872 D HealthService: Received stop request...Stopping profile...
08-04 12:34:15.699  3872  3872 V BluetoothAdapterState: isTurningOff()=true
,08-04 12:34:15.699  3872  3872 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:34:15.700  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:15.700  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:15.699  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:15.702  3793  3793 D HeadsetProfile: Bluetooth service disconnected
08-04 12:34:15.702  3793  3793 D BluetoothA2dp: Proxy object disconnected
08-04 12:34:15.702  3793  3793 D BluetoothInputDevice: Proxy object disconnected
08-04 12:34:15.702  3793  3793 D HidProfile: Bluetooth service disconnected
08-04 12:34:15.703  3872  3872 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 12:34:15.703  3872  3872 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 12:34:15.703  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 12:34:15.703  3872  4041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:15.704  3872  4041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:15.704  3872  4041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:34:15.705  3872  3872 D PanService: Received stop request...Stopping profile...
08-04 12:34:15.705  3872  4035 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-04 12:34:15.706  3793  3793 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 12:34:15.706  3793  3793 D PanProfile: Bluetooth service disconnected
,08-04 12:34:15.706  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-04 12:34:15.706  1362  1362 D PanProfile: Bluetooth service disconnected
08-04 12:34:15.707  3872  3872 D BluetoothMapService: Received stop request...Stopping profile...
08-04 12:34:15.707  3872  3872 D BluetoothMapService: stop()
,08-04 12:34:15.707  3872  3872 D BluetoothMapAppObserver: deinitObservers()
08-04 12:34:15.707  3872  3872 D BluetoothMapAppObserver: removeReceiver()
08-04 12:34:15.709  3793  3793 D BluetoothMap: Proxy object disconnected
08-04 12:34:15.709  1362  1362 D BluetoothMap: Proxy object disconnected
08-04 12:34:15.709  3872  3872 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:15.709  1362  1362 D MapProfile: Bluetooth service disconnected
08-04 12:34:15.709  3872  3872 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:34:15.709  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:15.709  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:15.709  3793  3793 D MapProfile: Bluetooth service disconnected
08-04 12:34:15.710  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-04 12:34:15.710  3872  4041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:15.710  3872  4041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:34:15.710  3872  4041 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:34:15.711  3872  4041 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-04 12:34:15.711  3872  4041 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-04 12:34:15.711  3872  4041 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:34:15.711  3872  3872 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:15.711  3872  3872 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:15.711  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:15.711  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:15.712  3872  3872 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-04 12:34:15.712  3872  3872 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 12:34:15.715  3872  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:34:15.715  1362  1362 D BluetoothPbap: Proxy object disconnected
08-04 12:34:15.715  1362  1362 D PbapServerProfile: Bluetooth service disconnected
,08-04 12:34:15.715  3872  3872 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:15.715  3793  3793 D BluetoothPbap: Proxy object disconnected
08-04 12:34:15.715  3872  3872 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:15.716  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:15.716  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:15.716  3793  3793 D PbapServerProfile: Bluetooth service disconnected
08-04 12:34:15.716  3872  3872 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 12:34:15.716  3872  4035 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 12:34:15.716  3872  3872 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 12:34:15.717  3872  3872 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:15.717  3872  3872 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:15.717  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:15.717  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:15.717  3872  3872 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 12:34:15.718  3872  3872 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 12:34:15.719  3872  3872 D BluetoothMapService: MAP Service closeService in
08-04 12:34:15.719  3872  3872 V BluetoothAdapterState: isTurningOff()=true
08-04 12:34:15.719  3872  3872 V BluetoothAdapterState: isTurningOn()=false
08-04 12:34:15.719  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:15.719  3872  3872 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:15.719  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-04 12:34:15.719  3872  3872 D BluetoothMapService: cleanup()
,08-04 12:34:15.719  3872  4031 D BluetoothAdapterProperties: Setting state to 15
08-04 12:34:15.720  3872  3872 D BluetoothMapService: MAP Service closeService in
08-04 12:34:15.720  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-04 12:34:15.720  3872  4031 I BluetoothAdapterState: Entering BleOnState
,08-04 12:34:15.723  1750  1764 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:15.723  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:34:15.725   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:15.725  1362  1839 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:34:15.726  3793  3803 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:34:15.726  3793  4069 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:34:15.727  3793  3804 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:34:15.727   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:15.727  3793  3803 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:34:15.728  3793  4069 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 12:34:15.728   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 12:34:15.728  1362  1373 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:34:15.729  1362  1376 D BluetoothMap: onBluetoothStateChange: up=false
,08-04 12:34:15.729  3793  3804 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:15.730  1362  1839 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:34:15.730  1362  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:34:15.730   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 12:34:15.731  3872  4031 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-04 12:34:15.731  3872  4031 D BluetoothAdapterProperties: Setting state to 16
08-04 12:34:15.731  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-04 12:34:15.731  3872  4031 D BluetoothAdapterProperties: onBleDisable
08-04 12:34:15.732  3872  4031 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:34:15.732  3872  4032 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 12:34:15.733  3872  4041 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 12:34:15.733  3872  4041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:34:15.733  3872  4035 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:34:15.735  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:15.736  3793  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:34:15.736  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:15.738  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:15.740  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:15.740  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:15.745  3793  3793 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:34:15.933  3872  4035 I bt_hci  : shut_down
,08-04 12:34:15.948  3872  4039 D bt_hwcfg: hw_epilog_process
,08-04 12:34:15.949  3872  4039 I bt_vendor: low_power_mode_cb
,08-04 12:34:15.969  3872  4039 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 12:34:15.969  3872  4039 I bt_vendor: epilog_cb
08-04 12:34:15.969  3872  4039 I bt_hci  : epilog_finished_callback
,08-04 12:34:15.978  3872  4035 I bt_hci_h4: hal_close
,08-04 12:34:15.979  3872  4035 I bt_userial_vendor: device fd = 51 close
,08-04 12:34:16.099  3872  4032 D bt_stack_manager: event_shut_down_stack finished.
08-04 12:34:16.100  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 12:34:16.106  3872  3872 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:34:16.108  3872  4031 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-04 12:34:16.108  3872  3872 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 12:34:16.108  3872  3872 D BtGatt.GattService: stop()
,08-04 12:34:16.109  3872  3872 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 12:34:16.117  3872  3872 V BluetoothAdapterState: isTurningOff()=false
08-04 12:34:16.118  3872  3872 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:34:16.118  3872  3872 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:16.118  3872  3872 V BluetoothAdapterState: isBleTurningOff()=true
08-04 12:34:16.119  3872  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-04 12:34:16.120  3872  4031 D BluetoothAdapterProperties: Setting state to 10
08-04 12:34:16.120  3872  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-04 12:34:16.122  3872  4031 I BluetoothAdapterState: Entering OffState
,08-04 12:34:16.125   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-04 12:34:16.152  3872  3872 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-04 12:34:16.152  3872  3872 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-04 12:34:16.152  3872  4032 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-04 12:34:16.154  3872  3872 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 12:34:16.163  3872  4032 D bt_stack_manager: event_clean_up_stack finished.
,08-04 12:34:16.167  3872  3872 I art     : System.exit called, status: 0
,08-04 12:34:16.168  3872  3872 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 12:34:16.221   871  1709 I ActivityManager: Process com.android.bluetooth (pid 3872) has died,
,08-04 12:34:17.130   871  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-04 12:34:18.645  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:34:18.645  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:21.653  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:34:21.653  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1a41cc added. We now have 6 listener(s)
08-04 12:34:21.653  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:21.658  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:34:21.659  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e025c15 added. We now have 7 listener(s)
08-04 12:34:21.659  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:21.660  3738  3784 I System.out: IsBluetoothEnabled
,08-04 12:34:21.672  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:21.722   871   888 I ActivityManager: Start proc 4076:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 12:34:21.860  4076  4076 D AdapterServiceConfig: Adding HeadsetService
,08-04 12:34:21.861  4076  4076 D AdapterServiceConfig: Adding A2dpService
08-04 12:34:21.862  4076  4076 D AdapterServiceConfig: Adding HidService
,08-04 12:34:21.864  4076  4076 D AdapterServiceConfig: Adding HealthService
,08-04 12:34:21.865  4076  4076 D AdapterServiceConfig: Adding PanService
,08-04 12:34:21.867  4076  4076 D AdapterServiceConfig: Adding GattService
,08-04 12:34:21.868  4076  4076 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 12:34:21.886   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c50a9a1:true
,08-04 12:34:21.888  4076  4076 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 12:34:21.898  4076  4088 I BluetoothAdapterState: Entering OffState
,08-04 12:34:21.898  4076  4076 I bt_bluedroid: init
,08-04 12:34:21.901  4076  4089 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 12:34:21.901  4076  4089 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 12:34:21.901  4076  4089 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 12:34:21.901  4076  4089 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 12:34:21.904  4076  4076 I bt_bluedroid: get_profile_interface socket
,08-04 12:34:21.910  4076  4092 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:34:21.911  4076  4076 I bt_bluedroid: get_profile_interface sdp
,08-04 12:34:21.913  4076  4092 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:34:21.921  4076  4087 I bt_bluedroid: config_hci_snoop_log
,08-04 12:34:21.924   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 12:34:21.935  4076  4088 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 12:34:21.935  4076  4088 D BluetoothAdapterProperties: Setting state to 14
,08-04 12:34:21.936  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 12:34:21.941  4076  4088 D BluetoothBondStateMachine: make
,08-04 12:34:21.946  4076  4093 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 12:34:21.954  4076  4088 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:34:21.959  4076  4076 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 12:34:21.970  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:21.972  4076  4076 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:34:21.976  4076  4076 D BtGatt.GattService: Received start request. Starting profile...
,08-04 12:34:21.976  4076  4076 D BtGatt.GattService: start()
,08-04 12:34:21.977  4076  4076 I bt_bluedroid: get_profile_interface gatt
,08-04 12:34:21.978  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:21.979  4076  4076 D BtGatt.AdvertiseManager: advertise manager created
,08-04 12:34:21.993  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:21.994  4076  4076 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:34:21.994  4076  4076 V BluetoothAdapterState: isBleTurningOn()=true
,08-04 12:34:21.994  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:21.996  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-04 12:34:21.997  4076  4088 I bt_bluedroid: enable
,08-04 12:34:21.997  4076  4089 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-04 12:34:21.998  4076  4089 I bt_hci  : start_up
,08-04 12:34:22.009  4076  4089 I bt_vendor: alloc value 0xb3a57189
,08-04 12:34:22.009  4076  4089 I bt_vendor: init
08-04 12:34:22.009  4076  4089 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 12:34:22.009  4076  4089 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 12:34:22.116  4076  4089 D bt_hci  : start_up starting async portion
,08-04 12:34:22.116  4076  4096 I bt_hci  : event_finish_startup
08-04 12:34:22.117  4076  4096 I bt_hci_h4: hal_open
,08-04 12:34:22.117  4076  4096 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 12:34:22.127  4076  4096 I bt_userial_vendor: device fd = 51 open
,08-04 12:34:22.158  4076  4096 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:34:22.190  4076  4096 D bt_hwcfg: Chipset BCM4354A2
08-04 12:34:22.190  4076  4096 D bt_hwcfg: Target name = [BCM4354A2]
,08-04 12:34:22.191  4076  4096 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 12:34:22.851  4076  4096 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 12:34:22.853  4076  4096 D bt_hwcfg: Settlement delay -- 100 ms
08-04 12:34:22.853  4076  4096 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 12:34:22.970  4076  4096 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:34:22.971  4076  4096 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 12:34:23.001  4076  4096 I bt_hwcfg: vendor lib fwcfg completed
,08-04 12:34:23.001  4076  4096 I bt_vendor: firmware callback
08-04 12:34:23.001  4076  4096 I bt_hci  : firmware_config_callback
,08-04 12:34:23.012  4076  4098 I bt_btu  : btu_task pending for preload complete event
,08-04 12:34:23.013  4076  4098 I bt_btu_task: Bluetooth chip preload is complete
08-04 12:34:23.013  4076  4098 I bt_btu  : btu_task received preload complete event
,08-04 12:34:23.023  4076  4098 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 12:34:23.023  4076  4098 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 12:34:23.023  4076  4098 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-04 12:34:23.024  4076  4098 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 12:34:23.024  4076  4098 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 12:34:23.024  4076  4098 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 12:34:23.025  4076  4098 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 12:34:23.025  4076  4098 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 12:34:23.025  4076  4098 I         : BTE_InitTraceLevels -- TRC_GAP
,08-04 12:34:23.025  4076  4098 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 12:34:23.026  4076  4098 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 12:34:23.026  4076  4098 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 12:34:23.026  4076  4098 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 12:34:23.026  4076  4098 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-04 12:34:23.027  4076  4098 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 12:34:23.162  4076  4098 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d4d9d
,08-04 12:34:23.162  4076  4098 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d4d9d 
,08-04 12:34:23.173  4076  4092 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 12:34:23.175  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-04 12:34:23.176  4076  4092 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-04 12:34:23.182  4076  4092 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:34:23.187  4076  4092 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:34:23.188  4076  4092 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:34:23.189  4076  4092 D bt_hci  : do_postload posting postload work item
,08-04 12:34:23.189  4076  4096 I bt_hci  : event_postload
08-04 12:34:23.189  4076  4096 I bt_vendor: sco_config_cb
,08-04 12:34:23.189  4076  4096 I bt_hci  : sco_config_callback postload finished.
08-04 12:34:23.191  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:23.192  4076  4092 D bt_bte_conf: Device ID record 1 : primary
08-04 12:34:23.192  4076  4092 D bt_bte_conf:   vendorId            = 000f
,08-04 12:34:23.193  4076  4092 D bt_bte_conf:   vendorIdSource      = 0001
08-04 12:34:23.193  4076  4092 D bt_bte_conf:   product             = 1200
,08-04 12:34:23.193  4076  4092 D bt_bte_conf:   version             = 1436
,08-04 12:34:23.193  4076  4092 D bt_bte_conf:   clientExecutableURL = 
08-04 12:34:23.193  4076  4092 D bt_bte_conf:   serviceDescription  = 
,08-04 12:34:23.194  4076  4092 D bt_bte_conf:   documentationURL    = 
08-04 12:34:23.194  4076  4092 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-04 12:34:23.195  4076  4089 D bt_stack_manager: event_start_up_stack finished
,08-04 12:34:23.197  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 12:34:23.197  4076  4096 I bt_vendor: low_power_mode_cb
,08-04 12:34:23.198  4076  4088 D BluetoothAdapterProperties: Setting state to 15
,08-04 12:34:23.198  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-04 12:34:23.199  4076  4088 I BluetoothAdapterState: Entering BleOnState,
,08-04 12:34:23.205  4076  4088 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-04 12:34:23.206  4076  4088 D BluetoothAdapterProperties: Setting state to 11
08-04 12:34:23.206  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 12:34:23.215  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:23.217  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:23.218  4076  4076 D HeadsetService: Received start request. Starting profile...
08-04 12:34:23.221  4076  4076 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 12:34:23.221  4076  4076 D HeadsetStateMachine: make
,08-04 12:34:23.225  4076  4088 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:34:23.236  4076  4076 D HeadsetStateMachine: max_hf_connections = 1
,08-04 12:34:23.236  4076  4076 I bt_bluedroid: get_profile_interface handsfree
,08-04 12:34:23.237  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 12:34:23.237  4076  4092 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 12:34:23.243  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:23.244  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:23.244  4076  4076 D A2dpService: Received start request. Starting profile...
08-04 12:34:23.245  4076  4076 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 12:34:23.245  4076  4076 I bt_bluedroid: get_profile_interface avrcp
,08-04 12:34:23.253  4076  4076 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 12:34:23.253  4076  4076 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 12:34:23.253  4076  4076 D A2dpStateMachine: make
,08-04 12:34:23.255  4076  4076 I bt_bluedroid: get_profile_interface a2dp
,08-04 12:34:23.256  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 12:34:23.258  4076  4108 D A2dpStateMachine: Enter Disconnected: -2
,08-04 12:34:23.260  4076  4076 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 12:34:23.261  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:23.262  4076  4076 D HidService: Received start request. Starting profile...
,08-04 12:34:23.262  4076  4076 I bt_bluedroid: get_profile_interface hidhost
,08-04 12:34:23.262  4076  4076 D HidService: setHidService(): set to: null
,08-04 12:34:23.262  4076  4092 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b63e5
,08-04 12:34:23.263  4076  4076 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 12:34:23.263  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-04 12:34:23.263  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:23.264  4076  4076 D HealthService: Received start request. Starting profile...
,08-04 12:34:23.266  4076  4076 I bt_bluedroid: get_profile_interface health
08-04 12:34:23.266  4076  4076 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 12:34:23.267  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:23.268  4076  4076 D PanService: Received start request. Starting profile...
08-04 12:34:23.268  4076  4076 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 12:34:23.268  4076  4076 I bt_bluedroid: get_profile_interface pan
08-04 12:34:23.269  4076  4092 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 12:34:23.271  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
08-04 12:34:23.272  4076  4076 D BluetoothMapService: Received start request. Starting profile...
,08-04 12:34:23.272  4076  4076 D BluetoothMapService: start()
08-04 12:34:23.275  4076  4076 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 12:34:23.276  4076  4076 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-04 12:34:23.276  4076  4076 D BluetoothMapAppObserver: createReceiver()
08-04 12:34:23.277  4076  4076 D BluetoothMapAppObserver: initObservers()
,08-04 12:34:23.277  4076  4076 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 12:34:23.286  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:23.286  4076  4076 V BluetoothAdapterState: isTurningOn()=true
,08-04 12:34:23.286  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:23.286  4076  4106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 12:34:23.286  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:23.289  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isTurningOff()=false,
,08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isTurningOn()=true
,08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-04 12:34:23.290  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:23.291  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:23.291  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:34:23.291  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-04 12:34:23.291  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:23.291  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:23.291  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:23.292  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:34:23.292  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-04 12:34:23.292  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:34:23.292  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:34:23.293  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-04 12:34:23.293  4076  4088 D BluetoothAdapterProperties: ScanMode =  20
08-04 12:34:23.293  4076  4088 D BluetoothAdapterProperties: State =  11
,08-04 12:34:23.293  4076  4088 D BluetoothAdapterProperties: Setting state to 12
08-04 12:34:23.293  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 12:34:23.295  4076  4088 I BluetoothAdapterState: Entering OnState
08-04 12:34:23.297  1750  1915 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:23.298  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 12:34:23.295  4076  4092 D BluetoothAdapterProperties: Scan Mode:21
,08-04 12:34:23.299  4076  4092 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:34:23.300   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:23.300  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 12:34:23.302  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-04 12:34:23.302  1362  1362 D HidProfile: Bluetooth service connected
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:23.303  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:23.305  3793  3803 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 12:34:23.306  4076  4076 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 12:34:23.307  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:23.307  4076  4076 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-04 12:34:23.307  3793  4069 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 12:34:23.311  3793  3803 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:34:23.311  4076  4076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:34:23.312  3793  3793 D BluetoothInputDevice: Proxy object connected
,08-04 12:34:23.312  3793  3793 D HidProfile: Bluetooth service connected
,08-04 12:34:23.318   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:34:23.319  3793  3804 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 12:34:23.319  4076  4076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:34:23.320  4076  4076 D ObexServerSockets: Succeed to create listening sockets 
08-04 12:34:23.320  4076  4076 D ObexServerSockets0: startAccept()
08-04 12:34:23.320  4076  4076 D ObexServerSockets0: prepareForNewConnect()
,08-04 12:34:23.323  3793  4069 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 12:34:23.324  4076  4076 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 12:34:23.324  4076  4076 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-04 12:34:23.326  1362  1362 D BluetoothA2dp: Proxy object connected
,08-04 12:34:23.326  4076  4114 D ObexServerSockets0: Accepting socket connection...
08-04 12:34:23.326  3793  3793 D BluetoothA2dp: Proxy object connected
08-04 12:34:23.327   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:34:23.327  4076  4115 D ObexServerSockets0: Accepting socket connection...
,08-04 12:34:23.328  1362  1839 D BluetoothPan: onBluetoothStateChange on: true
,08-04 12:34:23.328   871   871 D BluetoothA2dp: Proxy object connected
,08-04 12:34:23.329  3793  3793 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 12:34:23.329  3793  3793 D PanProfile: Bluetooth service connected
08-04 12:34:23.329  3793  3793 D BluetoothMap: Proxy object connected
,08-04 12:34:23.330  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:34:23.330  1362  1373 D BluetoothMap: onBluetoothStateChange: up=true
08-04 12:34:23.330  3793  3793 D MapProfile: Bluetooth service connected
08-04 12:34:23.330  1362  1362 D PanProfile: Bluetooth service connected
,08-04 12:34:23.330  3793  3793 D BluetoothMap: getConnectedDevices()
,08-04 12:34:23.331  1362  1362 D BluetoothMap: Proxy object connected
,08-04 12:34:23.331  1362  1362 D MapProfile: Bluetooth service connected
08-04 12:34:23.331  1362  1362 D BluetoothMap: getConnectedDevices()
08-04 12:34:23.331  3793  3804 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:23.332  1362  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 12:34:23.334  1362  1839 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:23.334   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:34:23.335   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-04 12:34:23.337  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:23.338  4076  4076 D BluetoothMapService: onReceive
08-04 12:34:23.338  4076  4076 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:34:23.338  4076  4076 D BluetoothMapService: STATE_ON
,08-04 12:34:23.343  3793  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:34:23.349  3793  3793 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:34:23.350  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:34:23.361  1362  1362 D BluetoothPbap: Proxy object connected
08-04 12:34:23.361  3793  3793 D BluetoothPbap: Proxy object connected
08-04 12:34:23.361  1362  1362 D PbapServerProfile: Bluetooth service connected
08-04 12:34:23.361  3793  3793 D PbapServerProfile: Bluetooth service connected
,08-04 12:34:23.367  4076  4076 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:34:23.367  4076  4076 D ObexServerSockets0: prepareForNewConnect()
08-04 12:34:23.370  4076  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:34:23.385  4076  4123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:34:23.386  4076  4123 I BtOppRfcommListener: Accept thread started.
,08-04 12:34:23.399   871   871 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.399   871   871 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.400   871   888 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.400  1750  1764 D BluetoothHeadset: Proxy object connected
08-04 12:34:23.400  3793  3803 D BluetoothHeadset: Proxy object connected
08-04 12:34:23.401  3793  3793 D HeadsetProfile: Bluetooth service connected
08-04 12:34:23.401   871   871 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.402  1362  1373 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.402  1362  1362 D HeadsetProfile: Bluetooth service connected,
,08-04 12:34:23.418   871   888 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.433  3793  4069 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.433  3793  3793 D HeadsetProfile: Bluetooth service connected
,08-04 12:34:23.434  1362  1376 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.434  1362  1362 D HeadsetProfile: Bluetooth service connected
08-04 12:34:23.434   871   888 D BluetoothHeadset: Proxy object connected
,08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:23.692  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:23.699  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:23.703  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:34:23.704  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c4dcb2a added. We now have 8 listener(s)
,08-04 12:34:23.704  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:23.711   871  1375 D WifiService: setWifiEnabled: false pid=3738, uid=10000
,08-04 12:34:23.711   871  1375 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:34:23.723  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:23.724   871  1699 D WifiService: setWifiEnabled: true pid=3738, uid=10000
08-04 12:34:23.725   871  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:34:23.740   871  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:23.760  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:23.766  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:23.772   871  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-04 12:34:23.772   871  1305 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 12:34:23.773   871  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-04 12:34:23.774   871  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-04 12:34:23.774   871  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 12:34:23.775   871  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 12:34:23.775   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-04 12:34:23.775   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 12:34:23.790   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 12:34:23.791   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-04 12:34:23.792   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:23.793   871  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-04 12:34:23.793   871  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 12:34:23.847   871  1305 E native  : do suspend true
,08-04 12:34:23.861   871  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 12:34:23.862   871  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 12:34:23.876   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:24.746  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:24.753  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:24.766  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 12:34:24.769  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 12:34:24.775  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@47ff233 Bundle[{}]
,08-04 12:34:24.776  3738  3784 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 12:34:24.776  3738  3784 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 12:34:24.777  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-04 12:34:24.778  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-04 12:34:24.779  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 12:34:24.780  3738  3784 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-04 12:34:24.785  3738  3784 I System.out: Running OutgoingSocketThread
,08-04 12:34:24.787  3738  4130 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-04 12:34:24.789  3738  4130 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48211
,08-04 12:34:24.790  3738  4130 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 12:34:25.286   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:34:25.418   871  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.44 rxSuccessRate=12.12 delta 1000 -> 994
,08-04 12:34:25.420   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-04 12:34:25.421   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:34:25.434   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 12:34:25.473   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 12:34:25.475  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 12:34:25.788  3738  3784 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-04 12:34:25.788  3738  3784 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-04 12:34:25.800  3738  3784 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-04 12:34:25.802  3738  3784 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 12:34:25.803  3738  3784 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-04 12:34:25.813  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:34:25.813  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d827d1b added. We now have 2 listener(s)
,08-04 12:34:25.817  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:25.817  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:25.817  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:25.817  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:34:25.818  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8faeb8 added. We now have 9 listener(s)
08-04 12:34:25.818  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:25.818  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:34:25.822  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:25.827  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:25.829  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:25.830  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:25.830  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:34:25.831  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e556ff6 added. We now have 3 listener(s)
,08-04 12:34:25.834  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:25.837  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:25.837  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:34:25.837  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:34:25.838  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:25.838  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:25.838  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1cff7 added. We now have 10 listener(s)
,08-04 12:34:25.838  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:25.839  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:25.839  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:34:25.839  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:25.840  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:25.840  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.840  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:25.840  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:25.841  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d827d1b removed from the list
,08-04 12:34:25.841  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:25.841  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8faeb8 removed from the list
,08-04 12:34:25.842  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:25.842  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:25.843  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.843  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:25.846  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:34:25.846  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:25.846  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:25.846  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8faeb8 not in the list
,08-04 12:34:25.847  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.847  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:25.849  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:25.849  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:25.850  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:25.850  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1cff7 removed from the list
08-04 12:34:25.850  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:25.851  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.851  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:25.851  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:25.851  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e556ff6 removed from the list
,08-04 12:34:25.853  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:34:25.854  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fecfe64 added. We now have 2 listener(s)
,08-04 12:34:25.856  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:25.856  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:25.856  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:34:25.856  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:34:25.856  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c2f8cd added. We now have 9 listener(s)
08-04 12:34:25.857  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:25.857  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:34:25.860  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:25.865  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:25.868  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:34:25.868  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:34:25.868  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:25.868  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b397493 added. We now have 3 listener(s)
,08-04 12:34:25.870  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:25.870  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:25.870  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:34:25.870  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:25.871  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ad9cd0 added. We now have 10 listener(s)
,08-04 12:34:25.871  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:25.871  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-04 12:34:25.871  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:34:25.871  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 12:34:25.871  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:34:25.871  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:34:25.871  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:25.875  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:25.876  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 12:34:25.876  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:34:25.881  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:34:25.882  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:34:25.882  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:34:25.887  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:34:25.887  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:34:25.887  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 12:34:25.887  3738  3784 D BluetoothAdapter: STATE_ON
,08-04 12:34:25.893  4076  4113 D BtGatt.GattService: registerClient() - UUID=0b3289a9-514c-4d50-9589-fbb946e4c7db
,08-04 12:34:25.894  4076  4092 D BtGatt.GattService: onClientRegistered() - UUID=0b3289a9-514c-4d50-9589-fbb946e4c7db, clientIf=5
,08-04 12:34:25.895  3738  3748 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:34:25.897  4076  4087 D BtGatt.GattService: start scan with filters
,08-04 12:34:25.903  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:34:25.904  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:34:25.904  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:34:25.904  4076  4095 D BtGatt.ScanManager: handling starting scan
,08-04 12:34:25.904  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:34:25.905  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e,
,08-04 12:34:25.909  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:34:25.909  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 12:34:25.909  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:34:25.909  4076  4095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9db397
,08-04 12:34:25.916  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:34:25.918  4076  4092 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:34:25.918  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:25.919  3738  3784 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:34:25.920  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:34:25.919  4076  4095 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:34:25.920  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-04 12:34:25.920  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:25.920  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:34:25.920  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 12:34:25.920  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-04 12:34:25.920  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 12:34:25.920  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-04 12:34:25.920  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 12:34:25.921  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:34:25.922  3738  3784 D BluetoothAdapter: STATE_ON
08-04 12:34:25.923  4076  4113 D BtGatt.GattService: stopScan() - queue size =1
,08-04 12:34:25.923  4076  4087 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 12:34:25.924  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 12:34:25.924  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:34:25.925  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:34:25.925  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-04 12:34:25.925  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:34:25.928  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:34:25.928  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:34:25.928  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:34:25.928  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:34:25.929  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:25.932  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:25.932  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:25.932  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:34:25.935  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:25.935  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:25.935  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:25.935  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:25.935  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.936  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:25.936  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:25.936  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fecfe64 removed from the list
08-04 12:34:25.936  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:25.936  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c2f8cd removed from the list
08-04 12:34:25.936  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:25.936  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:25.936  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.937  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:25.938  4076  4092 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:34:25.938  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:25.938  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:25.938  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:25.938  4076  4095 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:34:25.938  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:25.939  4076  4095 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:34:25.939  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c2f8cd not in the list
08-04 12:34:25.939  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.939  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:25.940  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:25.940  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:25.940  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:25.940  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ad9cd0 removed from the list
,08-04 12:34:25.940  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:25.940  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.940  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:25.940  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:25.940  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b397493 removed from the list
08-04 12:34:25.941  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:25.942  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@497b5fc added. We now have 2 listener(s)
08-04 12:34:25.944  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:25.944  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:25.944  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:25.944  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:25.944  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af37485 added. We now have 9 listener(s)
,08-04 12:34:25.945  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:25.945  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:34:25.947  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 12:34:25.947  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:25.947  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:25.952  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:34:25.952  4076  4092 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:34:25.952  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:25.953   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:34:25.957  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:25.957  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:25.958  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:25.958  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:25.959  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf8e30b added. We now have 3 listener(s)
08-04 12:34:25.959  4076  4092 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:34:25.959  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:25.959  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:34:25.960  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:25.960  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:25.960  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:25.961  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:25.961  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a835e8 added. We now have 10 listener(s)
08-04 12:34:25.961  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:25.961  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:25.961  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:25.962  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:34:25.962  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:34:25.962  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:25.962   871  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 12:34:25.962   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:34:25.962   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 12:34:25.962  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:34:25.964  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:34:25.964  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:34:25.968  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:34:25.969  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:34:25.969  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 12:34:25.975  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:34:25.975  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No serv,ice UUID, use manufacturer ID: true
08-04 12:34:25.975  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:34:25.975  3738  3784 D BluetoothAdapter: STATE_ON
08-04 12:34:25.977  4076  4105 D BtGatt.GattService: registerClient() - UUID=c1178905-0232-4a2c-afab-5893d44055b8
08-04 12:34:25.977  4076  4092 D BtGatt.GattService: onClientRegistered() - UUID=c1178905-0232-4a2c-afab-5893d44055b8, clientIf=5
08-04 12:34:25.977  3738  3748 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:34:25.978  4076  4087 D BtGatt.GattService: start scan with filters
,08-04 12:34:25.983  4076  4092 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:34:25.983  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:25.983   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:34:25.984  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:34:25.984  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 12:34:25.984  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 12:34:25.984  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 12:34:25.984  4076  4095 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:34:25.986  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:34:25.986  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:34:25.986  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:34:25.988  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:34:25.990  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:25.990  3738  3784 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-04 12:34:25.990  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:25.990  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:25.991  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:34:25.991  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:25.991  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.991  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:34:25.991  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:25.991  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@497b5fc removed from the list
08-04 12:34:25.991  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:25.991  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af37485 removed from the list
08-04 12:34:25.991  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:25.991  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:25.992  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:25.992  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 12:34:25.992  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:25.992  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:25.992  4076  4092 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 12:34:25.995  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:25.995   371   869 D CommandListener: Setting iface cfg
08-04 12:34:25.995  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:25.995  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:25.995  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:25.995  4076  4095 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:34:25.995  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af37485 not in the list
08-04 12:34:25.995  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-04 12:34:25.995  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:34:25.995  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:34:25.995  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:34:25.995   871  1305 D WifiStateMachine: Start Dhcp Watchdog 3
08-04 12:34:25.995  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:34:25.996  3738  3784 D BluetoothAdapter: STATE_ON
08-04 12:34:25.997  4076  4087 D BtGatt.GattService: stopScan() - queue size =0
08-04 12:34:25.997  4076  4113 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:34:25.998  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:34:25.998  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:34:25.998  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:34:25.998  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:34:25.998  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:34:25.998  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:25.998  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:34:25.998  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:34:25.999  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:34:25.999  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:26.000  4076  4092 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:34:26.000  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:26.000  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:26.000  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:26.000  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:26.000  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:26.000  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a835e8 removed from the list
08-04 12:34:26.000  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:26.000  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:26.000  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:26.000  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:26.000  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:26.000  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:34:26.000  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf8e30b removed from the list
08-04 12:34:26.001  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:26.001  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abec894 added. We now have 2 listener(s)
08-04 12:34:26.001  4076  4095 D BtGatt.ScanManager: handling starting scan
08-04 12:34:26.002  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:34:26.002  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:26.002  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:26.003  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:26.003  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0af3d added. We now have 9 listener(s)
08-04 12:34:26.003  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:26.003  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:34:26.005  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:26.006  4076  4092 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:34:26.006  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:26.006  4076  4095 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:34:26.007   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:26.008  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:26.010  4076  4092 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:34:26.010  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:26.010  4076  4095 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 12:34:26.010  4076  4095 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 12:34:26.010  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:26.010  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:34:26.010  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:26.010  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b78a883 added. We now have 3 listener(s)
08-04 12:34:26.011  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-04 12:34:26.012  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:26.012  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:34:26.012  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:34:26.012  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:34:26.013  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:26.013  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09da00 added. We now have 10 listener(s)
08-04 12:34:26.013  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:26.013  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:26.013  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:34:26.013  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:34:26.013  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:26.013  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:34:26.016  3738  3784 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:34:26.016  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:34:26.017  4076  4092 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:34:26.017  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.019  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:34:26.019   871  4133 D DhcpClient: Receive thread started
08-04 12:34:26.020  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:34:26.020  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:34:26.021  4076  4092 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:34:26.021  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.022  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:34:26.022  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-04 12:34:26.022  3738  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:34:26.023  3738  3784 D BluetoothAdapter: STATE_ON
,08-04 12:34:26.025  4076  4087 D BtGatt.GattService: registerClient() - UUID=3c835358-80c3-431a-8cb2-28640e617524
,08-04 12:34:26.025  4076  4092 D BtGatt.GattService: onClientRegistered() - UUID=3c835358-80c3-431a-8cb2-28640e617524, clientIf=5
,08-04 12:34:26.025  3738  3748 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:34:26.025  4076  4086 D BtGatt.GattService: start scan with filters
08-04 12:34:26.026  4076  4092 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:34:26.026  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.026  4076  4095 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:34:26.027  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:34:26.027  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:34:26.027  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 12:34:26.027  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:34:26.030  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:34:26.030  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-04 12:34:26.030  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:34:26.031  4076  4092 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 12:34:26.031  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.031  4076  4095 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:34:26.031  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:34:26.034  4076  4092 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:34:26.034  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:26.034  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:26.035  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:34:26.035  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:34:26.035  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:26.035  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:26.035  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:34:26.035  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:26.035  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abec894 removed from the list
08-04 12:34:26.035  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:34:26.035  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0af3d removed from the list
08-04 12:34:26.035  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:34:26.035  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:26.035  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:26.035  4076  4095 D BtGatt.ScanManager: handling starting scan
,08-04 12:34:26.035  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 12:34:26.036  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:26.036  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:34:26.036  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:26.036  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:26.036  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:26.036  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0af3d not in the list
08-04 12:34:26.036  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-04 12:34:26.037  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:34:26.037  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:34:26.037  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 12:34:26.037  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 12:34:26.037  3738  3784 D BluetoothAdapter: STATE_ON
08-04 12:34:26.038  4076  4113 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:34:26.038  4076  4087 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:34:26.039  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 12:34:26.039  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:34:26.039  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:34:26.039  4076  4092 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:34:26.039  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.039  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:34:26.040  4076  4095 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:34:26.040  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:34:26.040  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:34:26.041  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:34:26.041  3738  3784 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:34:26.041  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:34:26.041  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:26.042  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:26.042  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:34:26.042  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:34:26.042  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:26.042  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:34:26.042  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:26.042  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09da00 removed from the list
08-04 12:34:26.042  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:34:26.043  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:26.043  4076  4092 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:34:26.043  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.043  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:26.043  4076  4095 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:34:26.043  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:34:26.043  4076  4095 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:34:26.043  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b78a883 removed from the list
,08-04 12:34:26.044  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:34:26.044  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@432962c added. We now have 2 listener(s)
08-04 12:34:26.046  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:34:26.046  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:34:26.046  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:26.046  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:26.046  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55388f5 added. We now have 9 listener(s)
08-04 12:34:26.046  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:34:26.046  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:34:26.048  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:34:26.050  4076  4092 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:34:26.050  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:34:26.053  3738  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:34:26.054  3738  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:34:26.054  4076  4092 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:34:26.054  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.055  3738  3784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:34:26.055  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:34:26.055  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88ca4fb added. We now have 3 listener(s)
,08-04 12:34:26.056  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:26.057  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:34:26.058  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:34:26.058  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:34:26.058  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:34:26.058  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:34:26.058  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@348e918 added. We now have 10 listener(s)
,08-04 12:34:26.058  3738  3784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:34:26.058  3738  3784 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:34:26.058  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:26.059  3738  3784 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:34:26.059  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:26.059  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:26.059  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:34:26.059  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:34:26.059  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@432962c removed from the list
08-04 12:34:26.059  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:26.059  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55388f5 removed from the list
08-04 12:34:26.059  4076  4092 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:34:26.059  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:26.059  4076  4095 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:34:26.059  3738  3784 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:34:26.059  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:34:26.060  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:34:26.060  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:26.060  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:34:26.060  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:34:26.060  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:26.060  3738  3784 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55388f5 not in the list
08-04 12:34:26.061  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:26.061  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:26.061  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:34:26.061  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:34:26.061  3738  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:34:26.061  3738  3784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@348e918 removed from the list
08-04 12:34:26.061  3738  3784 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:34:26.061  3738  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:34:26.061  3738  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:34:26.061  3738  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:34:26.062  3738  3784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88ca4fb removed from the list
08-04 12:34:26.062  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-04 12:34:26.062  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 12:34:26.062  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 12:34:26.062  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:34:26.062  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 12:34:26.062  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:34:26.063  4076  4092 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 12:34:26.063  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:34:26.063  4076  4095 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:34:26.067  3738  4134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
08-04 12:34:26.067  3738  4134 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name),
08-04 12:34:26.067  3738  4134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 12:34:26.067  4076  4092 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:34:26.068  4076  4092 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:34:26.068  3738  4135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
08-04 12:34:26.069  3738  4135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
,08-04 12:34:26.069  3738  4135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 12:34:26.070  3738  3784 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-04 12:34:26.070  3738  3784 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-04 12:34:26.070  3738  3784 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 12:34:26.070  3738  3784 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 12:34:26.070  3738  3784 D com.test.thalitest.ThaliTestRunner: Total duration: 22827 ms,
08-04 12:34:26.071  3738  3784 I jxcore-log: Total number of executed tests:  80
08-04 12:34:26.071  3738  3784 I jxcore-log: 
,08-04 12:34:26.071  3738  3784 I jxcore-log: Number of passed tests:  80
08-04 12:34:26.071  3738  3784 I jxcore-log: 
08-04 12:34:26.071  3738  3784 I jxcore-log: Number of failed tests:  0
08-04 12:34:26.071  3738  3784 I jxcore-log: 
08-04 12:34:26.071  3738  3784 I jxcore-log: Number of ignored tests:  0
08-04 12:34:26.071  3738  3784 I jxcore-log: 
08-04 12:34:26.072  3738  3784 I jxcore-log: Total duration:  22827
08-04 12:34:26.072  3738  3784 I jxcore-log: 
,08-04 12:34:26.073  3738  3784 I jxcore-log: Unit Test app is loaded
08-04 12:34:26.073  3738  3784 I jxcore-log: 
,08-04 12:34:26.077  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.077  3738  3784 I jxcore-log: 
,08-04 12:34:26.080  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.080  3738  3784 I jxcore-log: 
,08-04 12:34:26.080  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.080  3738  3784 I jxcore-log: 
,08-04 12:34:26.081  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.081  3738  3784 I jxcore-log: 
,08-04 12:34:26.082  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.082  3738  3784 I jxcore-log: 
08-04 12:34:26.082  3738  3738 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-04 12:34:26.083  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.083  3738  3784 I jxcore-log: 
,08-04 12:34:26.084  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.084  3738  3784 I jxcore-log: 
,08-04 12:34:26.085  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.085  3738  3784 I jxcore-log: 
,08-04 12:34:26.086  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.086  3738  3784 I jxcore-log: 
,08-04 12:34:26.086  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.086  3738  3784 I jxcore-log: 
08-04 12:34:26.087  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.087  3738  3784 I jxcore-log: 
,08-04 12:34:26.087  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:34:26.087  3738  3784 I jxcore-log: 
,08-04 12:34:26.088  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.088  3738  3784 I jxcore-log: 
,08-04 12:34:26.089  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.089  3738  3784 I jxcore-log: 
08-04 12:34:26.089  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.089  3738  3784 I jxcore-log: 
,08-04 12:34:26.089  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:26.089  3738  3784 I jxcore-log: 
,08-04 12:34:26.090  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.090  3738  3784 I jxcore-log: 
08-04 12:34:26.090  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.090  3738  3784 I jxcore-log: 
,08-04 12:34:26.091  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.091  3738  3784 I jxcore-log: 
,08-04 12:34:26.091  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.091  3738  3784 I jxcore-log: 
08-04 12:34:26.092  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.092  3738  3784 I jxcore-log: 
,08-04 12:34:26.092  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.092  3738  3784 I jxcore-log: 
,08-04 12:34:26.093  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.093  3738  3784 I jxcore-log: 
08-04 12:34:26.093  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.093  3738  3784 I jxcore-log: 
,08-04 12:34:26.094  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.094  3738  3784 I jxcore-log: 
08-04 12:34:26.094  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:34:26.094  3738  3784 I jxcore-log: 
,08-04 12:34:26.094  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.094  3738  3784 I jxcore-log: 
,08-04 12:34:26.095  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.095  3738  3784 I jxcore-log: 
08-04 12:34:26.095  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.095  3738  3784 I jxcore-log: 
,08-04 12:34:26.096  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.096  3738  3784 I jxcore-log: 
08-04 12:34:26.096  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.096  3738  3784 I jxcore-log: 
,08-04 12:34:26.097  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.097  3738  3784 I jxcore-log: 
,08-04 12:34:26.097  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:34:26.097  3738  3784 I jxcore-log: 
,08-04 12:34:26.099  3738  3784 I jxcore-log: My device name is: motorola-Nexus 6
08-04 12:34:26.099  3738  3784 I jxcore-log: 
,08-04 12:34:26.103   871  1305 E native  : do suspend false
,08-04 12:34:26.113   871  2117 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 12:34:26.124   871  4133 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-04 12:34:26.125   871  2117 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-04 12:34:26.126   871  2117 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 12:34:26.138   871  4133 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-04 12:34:26.138   871  2117 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-04 12:34:26.140   371   869 D CommandListener: Setting iface cfg
,08-04 12:34:26.143   871  2117 D DhcpClient: Scheduling renewal in 86399s
,08-04 12:34:26.144   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 12:34:26.145   871  1305 E native  : do suspend true
,08-04 12:34:26.158   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 12:34:26.159   871  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 12:34:26.160   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 12:34:26.160   871  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-04 12:34:26.165   871  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 12:34:26.192   871  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 12:34:26.192   871  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-04 12:34:26.193   871  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-04 12:34:26.194   871  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-04 12:34:26.195   871  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-04 12:34:26.202   871  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 12:34:26.206   871  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-04 12:34:26.206   871  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-04 12:34:26.207   871  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-04 12:34:26.207   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:34:26.207   871  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-04 12:34:26.207   871  1307 D ConnectivityService:    accepting network in place of null
,08-04 12:34:26.209   871  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:34:26.217   871  4132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=428809, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 12:34:26.228   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:34:26.274   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:34:26.277   871  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-04 12:34:26.277   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:26.282   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:34:26.283   871  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:34:26.288  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:34:26.289  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:34:26.292   871  4131 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:34:26.299  1792  1792 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:34:26.307  1792  1792 D SystemUpdateService: onCreate
,08-04 12:34:26.311  1792  1792 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:34:26.328  1792  4144 I SystemUpdateService: active receiver: enabled
,08-04 12:34:26.330  1792  1792 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 12:34:26.332  1792  2358 I iu.UploadsManager: num queued entries: 0
,08-04 12:34:26.332  1792  2358 I iu.UploadsManager: num updated entries: 0
,08-04 12:34:26.333  1792  2358 I iu.SyncManager: NEXT; no task
,08-04 12:34:26.342  1792  1792 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:34:26.342  1792  1792 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-04 12:34:26.344  3886  3886 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:34:26.348  3886  3886 D SprintDMHelper: simOperator: 
08-04 12:34:26.348  3886  3886 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:34:26.364  1792  4146 I MDM     : [212] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 12:34:26.365  1792  4146 W BaseAppContext: Using Auth Proxy for data requests.
,08-04 12:34:26.373  1792  4146 V GoogleAuthProtoRequest: [212] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 12:34:26.378  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:34:26.379  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:34:26.383  1792  4144 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:34:26.392   871  4131 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 10:34:26 GMT], X-Android-Received-Millis=[1470306866391], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470306866351]}
,08-04 12:34:26.393   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 12:34:26.393   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-04 12:34:26.393   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 12:34:26.394   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 12:34:26.409  1792  4144 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-04 12:34:26.409  1792  4144 I SystemUpdateService: now status is 0 (complete)
08-04 12:34:26.409  1792  4144 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:34:26.409  1792  4144 I SystemUpdateService: file has been verified
08-04 12:34:26.409  1792  4144 I SystemUpdateService: OTA package size = 12249756
,08-04 12:34:26.418  1792  4144 I SystemUpdateService: showing system update notification
,08-04 12:34:26.427  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-04 12:34:26.427  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 12:34:26.427  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 12:34:26.427  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:34:26.433  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-04 12:34:26.445  1792  1792 D SystemUpdateService: onDestroy
,08-04 12:34:26.447  1792  4146 E MDM     : [212] SitrepService.a: Error sending sitrep.
,08-04 12:34:26.501  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:34:26.542  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:34:26.552  3844  4149 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 12:34:28.425  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 12:34:28.425  3738  3784 I jxcore-log: 
,08-04 12:34:29.043  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 12:34:29.043  3738  3784 I jxcore-log: 
,08-04 12:34:29.067  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 12:34:29.067  3738  3784 I jxcore-log: 
,08-04 12:34:30.412  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 12:34:30.412  3738  3784 I jxcore-log: 
,08-04 12:34:30.638  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-04 12:34:30.638  3738  3784 I jxcore-log: 
,08-04 12:34:30.643  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-04 12:34:30.643  3738  3784 I jxcore-log: 
,08-04 12:34:30.660  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-04 12:34:30.660  3738  3784 I jxcore-log: 
,08-04 12:34:30.664  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-04 12:34:30.664  3738  3784 I jxcore-log: 
,08-04 12:34:31.331  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-04 12:34:31.331  3738  3784 I jxcore-log: 
,08-04 12:34:31.345  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-04 12:34:31.345  3738  3784 I jxcore-log: 
,08-04 12:34:31.355  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-04 12:34:31.355  3738  3784 I jxcore-log: 
,08-04 12:34:31.363  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-04 12:34:31.363  3738  3784 I jxcore-log: 
,08-04 12:34:31.411  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-04 12:34:31.411  3738  3784 I jxcore-log: 
,08-04 12:34:31.467  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-04 12:34:31.467  3738  3784 I jxcore-log: 
,08-04 12:34:31.475  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-04 12:34:31.475  3738  3784 I jxcore-log: 
,08-04 12:34:31.640  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-04 12:34:31.640  3738  3784 I jxcore-log: 
,08-04 12:34:31.667  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-04 12:34:31.667  3738  3784 I jxcore-log: 
,08-04 12:34:31.673  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-04 12:34:31.673  3738  3784 I jxcore-log: 
,08-04 12:34:31.679  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-04 12:34:31.679  3738  3784 I jxcore-log: 
,08-04 12:34:31.698  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-04 12:34:31.698  3738  3784 I jxcore-log: 
,08-04 12:34:31.782  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-04 12:34:31.782  3738  3784 I jxcore-log: 
,08-04 12:34:31.794  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-04 12:34:31.794  3738  3784 I jxcore-log: 
,08-04 12:34:31.821  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-04 12:34:31.821  3738  3784 I jxcore-log: 
,08-04 12:34:31.834  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-04 12:34:31.834  3738  3784 I jxcore-log: 
,08-04 12:34:31.852  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-04 12:34:31.852  3738  3784 I jxcore-log: 
,08-04 12:34:31.889  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-04 12:34:31.889  3738  3784 I jxcore-log: 
,08-04 12:34:31.895  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-04 12:34:31.895  3738  3784 I jxcore-log: 
,08-04 12:34:32.117  3738  3784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-04 12:34:32.117  3738  3784 I jxcore-log: 
,08-04 12:34:32.128  3738  3784 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-04 12:34:32.129  3738  3784 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-04 12:34:32.129  3738  3784 I jxcore-log: 
,08-04 12:34:32.176  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:34:32.176  3738  3784 I jxcore-log: 
,08-04 12:34:32.177  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:34:32.177  3738  3784 I jxcore-log: 
08-04 12:34:32.177  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:34:32.177  3738  3784 I jxcore-log: 
,08-04 12:34:32.178  3738  3784 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:34:32.178  3738  3784 I jxcore-log: 
08-04 12:34:32.178  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:34:32.178  3738  3784 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-04 12:34:32.178  3738  3784 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:34:32.178  3738  3784 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-04 12:34:33.217  3738  3784 I jxcore-log: TAP version 13
08-04 12:34:33.217  3738  3784 I jxcore-log: 
,08-04 12:34:33.222  3738  3784 I jxcore-log: # setup
08-04 12:34:33.222  3738  3784 I jxcore-log: 
,08-04 12:34:33.904  3738  3784 I jxcore-log: # 1. calling createNativeListener directly rejects
08-04 12:34:33.904  3738  3784 I jxcore-log: 
,08-04 12:34:34.215   871  1307 D ConnectivityService: handlePromptUnvalidated 102
,08-04 12:34:34.585  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:34.585  3738  3784 I jxcore-log: 
,08-04 12:34:34.589  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 43014
08-04 12:34:34.589  3738  3784 I jxcore-log: 
,08-04 12:34:34.596  3738  3784 I jxcore-log: ok 1 Should throw
08-04 12:34:34.596  3738  3784 I jxcore-log: 
,08-04 12:34:34.598  3738  3784 I jxcore-log: # teardown
08-04 12:34:34.598  3738  3784 I jxcore-log: 
,08-04 12:34:35.629  3738  3784 I jxcore-log: # setup
08-04 12:34:35.629  3738  3784 I jxcore-log: 
,08-04 12:34:35.877  3738  3784 I jxcore-log: # 2. emits incomingConnectionState
08-04 12:34:35.877  3738  3784 I jxcore-log: 
,08-04 12:34:36.739  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server,
08-04 12:34:36.739  3738  3784 I jxcore-log: 
,08-04 12:34:36.743  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 45959
08-04 12:34:36.743  3738  3784 I jxcore-log: 
,08-04 12:34:36.754  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:36.754  3738  3784 I jxcore-log: 
,08-04 12:34:36.758  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:36.758  3738  3784 I jxcore-log: 
,08-04 12:34:36.768  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:36.768  3738  3784 I jxcore-log: 
,08-04 12:34:36.775  3738  3784 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-04 12:34:36.775  3738  3784 I jxcore-log: 
,08-04 12:34:36.796  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:36.796  3738  3784 I jxcore-log: 
,08-04 12:34:36.797  3738  3784 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-04 12:34:36.797  3738  3784 I jxcore-log: 
,08-04 12:34:36.803  3738  3784 I jxcore-log: # teardown
08-04 12:34:36.803  3738  3784 I jxcore-log: 
,08-04 12:34:37.242  3738  3784 I jxcore-log: # setup
08-04 12:34:37.242  3738  3784 I jxcore-log: 
,08-04 12:34:38.063  3738  3784 I jxcore-log: # 3. emits routerPortConnectionFailed
08-04 12:34:38.063  3738  3784 I jxcore-log: 
,08-04 12:34:38.477  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:38.477  3738  3784 I jxcore-log: 
08-04 12:34:38.479  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 47710
08-04 12:34:38.479  3738  3784 I jxcore-log: 
,08-04 12:34:38.487  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:38.487  3738  3784 I jxcore-log: 
,08-04 12:34:38.488  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:38.488  3738  3784 I jxcore-log: 
,08-04 12:34:38.490  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:38.490  3738  3784 I jxcore-log: 
,08-04 12:34:38.521  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:38.521  3738  3784 I jxcore-log: 
,08-04 12:34:38.524  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:38.524  3738  3784 I jxcore-log: 
,08-04 12:34:38.528  3738  3784 I jxcore-log: DEBUG createNativeListener: 
08-04 12:34:38.528  3738  3784 I jxcore-log: 
,08-04 12:34:38.529  3738  3784 I jxcore-log: ok 4 tried to connect to right port
08-04 12:34:38.529  3738  3784 I jxcore-log: 
,08-04 12:34:38.530  3738  3784 I jxcore-log: ok 5 failed due to refused connection
08-04 12:34:38.530  3738  3784 I jxcore-log: 
,08-04 12:34:38.531  3738  3784 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-04 12:34:38.531  3738  3784 I jxcore-log: 
,08-04 12:34:38.533  3738  3784 I jxcore-log: # teardown
08-04 12:34:38.533  3738  3784 I jxcore-log: 
,08-04 12:34:38.535  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:38.535  3738  3784 I jxcore-log: 
,08-04 12:34:39.405  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:39.405  3738  3784 I jxcore-log: 
,08-04 12:34:39.409  3738  3784 I jxcore-log: # setup
08-04 12:34:39.409  3738  3784 I jxcore-log: 
,08-04 12:34:39.410  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:39.410  3738  3784 I jxcore-log: 
,08-04 12:34:40.012  3738  3784 I jxcore-log: # 4. native server connections all up
08-04 12:34:40.012  3738  3784 I jxcore-log: 
,08-04 12:34:40.610  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:40.610  3738  3784 I jxcore-log: 
,08-04 12:34:40.620  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 41130
08-04 12:34:40.620  3738  3784 I jxcore-log: 
,08-04 12:34:40.627  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:40.627  3738  3784 I jxcore-log: 
,08-04 12:34:40.629  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:40.629  3738  3784 I jxcore-log: 
,08-04 12:34:40.630  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:40.630  3738  3784 I jxcore-log: 
,08-04 12:34:40.662  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:40.662  3738  3784 I jxcore-log: 
,08-04 12:34:40.665  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:40.665  3738  3784 I jxcore-log: 
,08-04 12:34:40.668  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:40.668  3738  3784 I jxcore-log: 
,08-04 12:34:40.671  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:40.671  3738  3784 I jxcore-log: 
,08-04 12:34:40.693  3738  3784 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-04 12:34:40.693  3738  3784 I jxcore-log: 
,08-04 12:34:40.694  3738  3784 I jxcore-log: ok 8 Send/recvd #1 should be same
08-04 12:34:40.694  3738  3784 I jxcore-log: 
,08-04 12:34:40.697  3738  3784 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-04 12:34:40.697  3738  3784 I jxcore-log: 
,08-04 12:34:40.697  3738  3784 I jxcore-log: ok 10 Send/recvd #2 should be same
08-04 12:34:40.697  3738  3784 I jxcore-log: 
,08-04 12:34:40.700  3738  3784 I jxcore-log: ok 11 Should be exactly 2 client sockets,
08-04 12:34:40.700  3738  3784 I jxcore-log: 
,08-04 12:34:40.707  3738  3784 I jxcore-log: # teardown
08-04 12:34:40.707  3738  3784 I jxcore-log: 
,08-04 12:34:41.340  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:41.340  3738  3784 I jxcore-log: 
,08-04 12:34:41.343  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:41.343  3738  3784 I jxcore-log: 
,08-04 12:34:41.345  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:41.345  3738  3784 I jxcore-log: 
,08-04 12:34:41.349  3738  3784 I jxcore-log: # setup
08-04 12:34:41.349  3738  3784 I jxcore-log: 
,08-04 12:34:41.350  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:41.350  3738  3784 I jxcore-log: 
,08-04 12:34:41.956  3738  3784 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-04 12:34:41.956  3738  3784 I jxcore-log: 
,08-04 12:34:42.758  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:42.758  3738  3784 I jxcore-log: 
,08-04 12:34:42.764  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 47364
08-04 12:34:42.764  3738  3784 I jxcore-log: 
,08-04 12:34:42.776  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:42.776  3738  3784 I jxcore-log: 
,08-04 12:34:42.778  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:42.778  3738  3784 I jxcore-log: 
,08-04 12:34:42.779  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:42.779  3738  3784 I jxcore-log: 
,08-04 12:34:42.795  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:42.795  3738  3784 I jxcore-log: 
,08-04 12:34:42.798  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:42.798  3738  3784 I jxcore-log: 
,08-04 12:34:42.812  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:42.812  3738  3784 I jxcore-log: 
,08-04 12:34:42.825  3738  3784 I jxcore-log: ok 12 socket shouldn't close until after stream
08-04 12:34:42.825  3738  3784 I jxcore-log: 
,08-04 12:34:42.826  3738  3784 I jxcore-log: ok 13 incoming remains open
08-04 12:34:42.826  3738  3784 I jxcore-log: 
,08-04 12:34:42.829  3738  3784 I jxcore-log: # teardown
08-04 12:34:42.829  3738  3784 I jxcore-log: 
,08-04 12:34:43.289  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:43.289  3738  3784 I jxcore-log: 
,08-04 12:34:43.299  3738  3784 I jxcore-log: # setup
08-04 12:34:43.299  3738  3784 I jxcore-log: 
,08-04 12:34:43.300  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:43.300  3738  3784 I jxcore-log: 
,08-04 12:34:44.117  3738  3784 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-04 12:34:44.117  3738  3784 I jxcore-log: 
,08-04 12:34:44.516  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:44.516  3738  3784 I jxcore-log: 
,08-04 12:34:44.522  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 46992
08-04 12:34:44.522  3738  3784 I jxcore-log: 
,08-04 12:34:44.540  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:44.540  3738  3784 I jxcore-log: 
,08-04 12:34:44.541  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:44.541  3738  3784 I jxcore-log: 
,08-04 12:34:44.543  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:44.543  3738  3784 I jxcore-log: 
,08-04 12:34:44.558  3738  3784 I jxcore-log: ok 14 we should not have gotten an error
08-04 12:34:44.558  3738  3784 I jxcore-log: 
,08-04 12:34:44.566  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:44.566  3738  3784 I jxcore-log: 
,08-04 12:34:44.572  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:44.572  3738  3784 I jxcore-log: 
,08-04 12:34:44.582  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:44.582  3738  3784 I jxcore-log: 
,08-04 12:34:44.584  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:44.584  3738  3784 I jxcore-log: 
,08-04 12:34:44.592  3738  3784 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-04 12:34:44.592  3738  3784 I jxcore-log: 
,08-04 12:34:44.593  3738  3784 I jxcore-log: ok 16 incoming is cleaned up
08-04 12:34:44.593  3738  3784 I jxcore-log: 
,08-04 12:34:44.596  3738  3784 I jxcore-log: # teardown
08-04 12:34:44.596  3738  3784 I jxcore-log: 
,08-04 12:34:45.640  3738  3784 I jxcore-log: # setup
08-04 12:34:45.640  3738  3784 I jxcore-log: 
,08-04 12:34:45.684  3738  3784 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-04 12:34:45.684  3738  3784 I jxcore-log: 
,08-04 12:34:45.700  1654  1724 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-04 12:34:45.701  1654  1724 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-04 12:34:45.734  1495  1495 I ConfigService: onCreate
,08-04 12:34:46.760  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:46.760  3738  3784 I jxcore-log: 
,08-04 12:34:46.768  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 43476
08-04 12:34:46.768  3738  3784 I jxcore-log: 
,08-04 12:34:46.780  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:46.780  3738  3784 I jxcore-log: 
,08-04 12:34:46.783  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:46.783  3738  3784 I jxcore-log: 
,08-04 12:34:46.786  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:46.786  3738  3784 I jxcore-log: 
,08-04 12:34:46.801  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:46.801  3738  3784 I jxcore-log: 
,08-04 12:34:46.803  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:46.803  3738  3784 I jxcore-log: 
,08-04 12:34:46.818  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:46.818  3738  3784 I jxcore-log: 
,08-04 12:34:46.834  3738  3784 I jxcore-log: ok 17 stream was closed
08-04 12:34:46.834  3738  3784 I jxcore-log: 
,08-04 12:34:46.835  3738  3784 I jxcore-log: ok 18 incoming should survive
08-04 12:34:46.835  3738  3784 I jxcore-log: 
08-04 12:34:46.836  3738  3784 I jxcore-log: ok 19 mux should have no streams
08-04 12:34:46.836  3738  3784 I jxcore-log: 
,08-04 12:34:46.841  3738  3784 I jxcore-log: # teardown
08-04 12:34:46.841  3738  3784 I jxcore-log: 
,08-04 12:34:47.023  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:47.023  3738  3784 I jxcore-log: 
,08-04 12:34:47.029  3738  3784 I jxcore-log: # setup
08-04 12:34:47.029  3738  3784 I jxcore-log: 
,08-04 12:34:47.030  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:47.030  3738  3784 I jxcore-log: 
,08-04 12:34:47.153  3738  3784 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-04 12:34:47.153  3738  3784 I jxcore-log: 
,08-04 12:34:47.227  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:47.227  3738  3784 I jxcore-log: 
,08-04 12:34:47.232  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 47548
08-04 12:34:47.232  3738  3784 I jxcore-log: 
,08-04 12:34:47.242  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.242  3738  3784 I jxcore-log: 
,08-04 12:34:47.244  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.244  3738  3784 I jxcore-log: 
,08-04 12:34:47.245  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.245  3738  3784 I jxcore-log: 
,08-04 12:34:47.255  3738  3784 I jxcore-log: ok 20 we should not have gotten an error
08-04 12:34:47.255  3738  3784 I jxcore-log: 
,08-04 12:34:47.270  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.270  3738  3784 I jxcore-log: 
,08-04 12:34:47.273  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.273  3738  3784 I jxcore-log: 
,08-04 12:34:47.283  3738  3784 I jxcore-log: ok 21 Buffers are identical
08-04 12:34:47.283  3738  3784 I jxcore-log: 
,08-04 12:34:47.285  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:47.285  3738  3784 I jxcore-log: 
,08-04 12:34:47.287  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:47.287  3738  3784 I jxcore-log: 
,08-04 12:34:47.290  3738  3784 I jxcore-log: ok 22 native server is nulled out
08-04 12:34:47.290  3738  3784 I jxcore-log: 
,08-04 12:34:47.290  3738  3784 I jxcore-log: ok 23 native server should be closed
08-04 12:34:47.290  3738  3784 I jxcore-log: 
,08-04 12:34:47.290  3738  3784 I jxcore-log: ok 24 incoming has been removed
08-04 12:34:47.290  3738  3784 I jxcore-log: 
,08-04 12:34:47.291  3738  3784 I jxcore-log: ok 25 Incoming should be done
08-04 12:34:47.291  3738  3784 I jxcore-log: 
,08-04 12:34:47.291  3738  3784 I jxcore-log: ok 26 The mux object should be closed
08-04 12:34:47.291  3738  3784 I jxcore-log: 
,08-04 12:34:47.291  3738  3784 I jxcore-log: ok 27 The mux stream should be closed
08-04 12:34:47.291  3738  3784 I jxcore-log: 
08-04 12:34:47.292  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:47.292  3738  3784 I jxcore-log: 
,08-04 12:34:47.304  3738  3784 I jxcore-log: # teardown
08-04 12:34:47.304  3738  3784 I jxcore-log: 
,08-04 12:34:47.423  3738  3784 I jxcore-log: # setup
08-04 12:34:47.423  3738  3784 I jxcore-log: 
,08-04 12:34:47.503  3738  3784 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-04 12:34:47.503  3738  3784 I jxcore-log: 
,08-04 12:34:47.601  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:47.601  3738  3784 I jxcore-log: 
,08-04 12:34:47.607  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 45975
08-04 12:34:47.607  3738  3784 I jxcore-log: 
,08-04 12:34:47.631  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.631  3738  3784 I jxcore-log: 
,08-04 12:34:47.632  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.632  3738  3784 I jxcore-log: 
,08-04 12:34:47.634  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.634  3738  3784 I jxcore-log: 
,08-04 12:34:47.637  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.637  3738  3784 I jxcore-log: 
,08-04 12:34:47.638  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.638  3738  3784 I jxcore-log: 
,08-04 12:34:47.639  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.639  3738  3784 I jxcore-log: 
,08-04 12:34:47.642  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.642  3738  3784 I jxcore-log: 
,08-04 12:34:47.643  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.643  3738  3784 I jxcore-log: 
,08-04 12:34:47.644  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.644  3738  3784 I jxcore-log: 
,08-04 12:34:47.652  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.652  3738  3784 I jxcore-log: 
,08-04 12:34:47.653  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.653  3738  3784 I jxcore-log: 
,08-04 12:34:47.655  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.655  3738  3784 I jxcore-log: 
,08-04 12:34:47.659  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.659  3738  3784 I jxcore-log: 
,08-04 12:34:47.659  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.659  3738  3784 I jxcore-log: 
,08-04 12:34:47.661  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.661  3738  3784 I jxcore-log: 
,08-04 12:34:47.663  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.663  3738  3784 I jxcore-log: 
,08-04 12:34:47.664  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.664  3738  3784 I jxcore-log: 
08-04 12:34:47.665  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.665  3738  3784 I jxcore-log: 
,08-04 12:34:47.674  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.674  3738  3784 I jxcore-log: 
,08-04 12:34:47.675  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.675  3738  3784 I jxcore-log: 
,08-04 12:34:47.677  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.677  3738  3784 I jxcore-log: 
,08-04 12:34:47.683  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.683  3738  3784 I jxcore-log: 
,08-04 12:34:47.683  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.683  3738  3784 I jxcore-log: 
,08-04 12:34:47.685  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.685  3738  3784 I jxcore-log: 
08-04 12:34:47.687  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.687  3738  3784 I jxcore-log: 
08-04 12:34:47.687  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.687  3738  3784 I jxcore-log: 
,08-04 12:34:47.688  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.688  3738  3784 I jxcore-log: 
,08-04 12:34:47.690  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:47.690  3738  3784 I jxcore-log: 
,08-04 12:34:47.690  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:47.690  3738  3784 I jxcore-log: 
,08-04 12:34:47.691  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:47.691  3738  3784 I jxcore-log: 
,08-04 12:34:47.778  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.778  3738  3784 I jxcore-log: 
,08-04 12:34:47.781  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.781  3738  3784 I jxcore-log: 
,08-04 12:34:47.783  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.783  3738  3784 I jxcore-log: 
,08-04 12:34:47.785  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.785  3738  3784 I jxcore-log: 
,08-04 12:34:47.786  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.786  3738  3784 I jxcore-log: 
,08-04 12:34:47.790  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.790  3738  3784 I jxcore-log: 
,08-04 12:34:47.797  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.797  3738  3784 I jxcore-log: 
,08-04 12:34:47.803  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.803  3738  3784 I jxcore-log: 
,08-04 12:34:47.811  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.811  3738  3784 I jxcore-log: 
,08-04 12:34:47.815  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.815  3738  3784 I jxcore-log: 
,08-04 12:34:47.817  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.817  3738  3784 I jxcore-log: 
,08-04 12:34:47.818  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.818  3738  3784 I jxcore-log: 
,08-04 12:34:47.819  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.819  3738  3784 I jxcore-log: 
,08-04 12:34:47.821  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.821  3738  3784 I jxcore-log: 
,08-04 12:34:47.822  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.822  3738  3784 I jxcore-log: 
,08-04 12:34:47.824  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.824  3738  3784 I jxcore-log: 
,08-04 12:34:47.826  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.826  3738  3784 I jxcore-log: 
,08-04 12:34:47.828  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.828  3738  3784 I jxcore-log: 
08-04 12:34:47.829  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.829  3738  3784 I jxcore-log: 
08-04 12:34:47.831  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.831  3738  3784 I jxcore-log: 
08-04 12:34:47.832  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.832  3738  3784 I jxcore-log: 
,08-04 12:34:47.835  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.835  3738  3784 I jxcore-log: 
08-04 12:34:47.836  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.836  3738  3784 I jxcore-log: 
,08-04 12:34:47.838  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.838  3738  3784 I jxcore-log: 
,08-04 12:34:47.840  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.840  3738  3784 I jxcore-log: 
,08-04 12:34:47.842  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.842  3738  3784 I jxcore-log: 
08-04 12:34:47.843  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.843  3738  3784 I jxcore-log: 
,08-04 12:34:47.845  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.845  3738  3784 I jxcore-log: 
,08-04 12:34:47.846  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.846  3738  3784 I jxcore-log: 
,08-04 12:34:47.847  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.847  3738  3784 I jxcore-log: 
,08-04 12:34:47.848  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.848  3738  3784 I jxcore-log: 
,08-04 12:34:47.850  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.850  3738  3784 I jxcore-log: 
,08-04 12:34:47.852  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.852  3738  3784 I jxcore-log: 
,08-04 12:34:47.854  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.854  3738  3784 I jxcore-log: 
,08-04 12:34:47.855  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.855  3738  3784 I jxcore-log: 
,08-04 12:34:47.857  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.857  3738  3784 I jxcore-log: 
08-04 12:34:47.858  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.858  3738  3784 I jxcore-log: 
,08-04 12:34:47.865  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.865  3738  3784 I jxcore-log: 
,08-04 12:34:47.868  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.868  3738  3784 I jxcore-log: 
,08-04 12:34:47.870  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.870  3738  3784 I jxcore-log: 
,08-04 12:34:47.872  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.872  3738  3784 I jxcore-log: 
,08-04 12:34:47.874  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.874  3738  3784 I jxcore-log: 
,08-04 12:34:47.875  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.875  3738  3784 I jxcore-log: 
,08-04 12:34:47.877  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.877  3738  3784 I jxcore-log: 
,08-04 12:34:47.878  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.878  3738  3784 I jxcore-log: 
,08-04 12:34:47.880  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.880  3738  3784 I jxcore-log: 
08-04 12:34:47.881  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.881  3738  3784 I jxcore-log: 
,08-04 12:34:47.882  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.882  3738  3784 I jxcore-log: 
,08-04 12:34:47.884  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.884  3738  3784 I jxcore-log: 
,08-04 12:34:47.886  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.886  3738  3784 I jxcore-log: 
08-04 12:34:47.887  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.887  3738  3784 I jxcore-log: 
,08-04 12:34:47.889  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.889  3738  3784 I jxcore-log: 
08-04 12:34:47.890  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.890  3738  3784 I jxcore-log: 
,08-04 12:34:47.891  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.891  3738  3784 I jxcore-log: 
,08-04 12:34:47.892  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.892  3738  3784 I jxcore-log: 
,08-04 12:34:47.894  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.894  3738  3784 I jxcore-log: 
,08-04 12:34:47.896  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.896  3738  3784 I jxcore-log: 
,08-04 12:34:47.898  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.898  3738  3784 I jxcore-log: 
08-04 12:34:47.899  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.899  3738  3784 I jxcore-log: 
,08-04 12:34:47.900  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.900  3738  3784 I jxcore-log: 
,08-04 12:34:47.901  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.901  3738  3784 I jxcore-log: 
,08-04 12:34:47.903  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.903  3738  3784 I jxcore-log: 
,08-04 12:34:47.904  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.904  3738  3784 I jxcore-log: 
,08-04 12:34:47.906  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.906  3738  3784 I jxcore-log: 
,08-04 12:34:47.908  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.908  3738  3784 I jxcore-log: 
,08-04 12:34:47.909  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.909  3738  3784 I jxcore-log: 
08-04 12:34:47.910  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.910  3738  3784 I jxcore-log: 
,08-04 12:34:47.912  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.912  3738  3784 I jxcore-log: 
08-04 12:34:47.913  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.913  3738  3784 I jxcore-log: 
,08-04 12:34:47.915  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.915  3738  3784 I jxcore-log: 
,08-04 12:34:47.916  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.916  3738  3784 I jxcore-log: 
,08-04 12:34:47.917  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.917  3738  3784 I jxcore-log: 
,08-04 12:34:47.919  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.919  3738  3784 I jxcore-log: 
,08-04 12:34:47.921  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.921  3738  3784 I jxcore-log: 
08-04 12:34:47.922  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.922  3738  3784 I jxcore-log: 
,08-04 12:34:47.924  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.924  3738  3784 I jxcore-log: 
,08-04 12:34:47.925  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.925  3738  3784 I jxcore-log: 
08-04 12:34:47.926  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.926  3738  3784 I jxcore-log: 
08-04 12:34:47.927  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:47.927  3738  3784 I jxcore-log: 
,08-04 12:34:47.929  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:47.929  3738  3784 I jxcore-log: 
,08-04 12:34:48.008  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.008  3738  3784 I jxcore-log: 
,08-04 12:34:48.010  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.010  3738  3784 I jxcore-log: 
,08-04 12:34:48.011  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.011  3738  3784 I jxcore-log: 
,08-04 12:34:48.012  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.012  3738  3784 I jxcore-log: 
08-04 12:34:48.014  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.014  3738  3784 I jxcore-log: 
,08-04 12:34:48.015  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.015  3738  3784 I jxcore-log: 
08-04 12:34:48.016  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.016  3738  3784 I jxcore-log: 
08-04 12:34:48.017  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.017  3738  3784 I jxcore-log: 
,08-04 12:34:48.018  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.018  3738  3784 I jxcore-log: 
,08-04 12:34:48.019  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.019  3738  3784 I jxcore-log: 
08-04 12:34:48.020  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.020  3738  3784 I jxcore-log: 
,08-04 12:34:48.023  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.023  3738  3784 I jxcore-log: 
,08-04 12:34:48.024  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.024  3738  3784 I jxcore-log: 
08-04 12:34:48.026  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.026  3738  3784 I jxcore-log: 
,08-04 12:34:48.027  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.027  3738  3784 I jxcore-log: 
,08-04 12:34:48.033  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.033  3738  3784 I jxcore-log: 
,08-04 12:34:48.035  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.035  3738  3784 I jxcore-log: 
,08-04 12:34:48.036  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.036  3738  3784 I jxcore-log: 
08-04 12:34:48.037  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.037  3738  3784 I jxcore-log: 
,08-04 12:34:48.038  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.038  3738  3784 I jxcore-log: 
,08-04 12:34:48.039  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.039  3738  3784 I jxcore-log: 
08-04 12:34:48.040  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.040  3738  3784 I jxcore-log: 
08-04 12:34:48.041  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.041  3738  3784 I jxcore-log: 
08-04 12:34:48.041  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.041  3738  3784 I jxcore-log: 
,08-04 12:34:48.043  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.043  3738  3784 I jxcore-log: 
08-04 12:34:48.044  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.044  3738  3784 I jxcore-log: 
,08-04 12:34:48.045  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.045  3738  3784 I jxcore-log: 
,08-04 12:34:48.046  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.046  3738  3784 I jxcore-log: 
,08-04 12:34:48.046  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.046  3738  3784 I jxcore-log: 
08-04 12:34:48.048  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.048  3738  3784 I jxcore-log: 
08-04 12:34:48.048  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.048  3738  3784 I jxcore-log: 
,08-04 12:34:48.049  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.049  3738  3784 I jxcore-log: 
,08-04 12:34:48.050  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.050  3738  3784 I jxcore-log: 
08-04 12:34:48.051  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.051  3738  3784 I jxcore-log: 
,08-04 12:34:48.052  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.052  3738  3784 I jxcore-log: 
08-04 12:34:48.053  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.053  3738  3784 I jxcore-log: 
,08-04 12:34:48.054  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.054  3738  3784 I jxcore-log: 
,08-04 12:34:48.054  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.054  3738  3784 I jxcore-log: 
,08-04 12:34:48.055  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.055  3738  3784 I jxcore-log: 
08-04 12:34:48.056  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.056  3738  3784 I jxcore-log: 
08-04 12:34:48.057  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.057  3738  3784 I jxcore-log: 
08-04 12:34:48.058  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.058  3738  3784 I jxcore-log: 
,08-04 12:34:48.059  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.059  3738  3784 I jxcore-log: 
08-04 12:34:48.060  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.060  3738  3784 I jxcore-log: 
08-04 12:34:48.060  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.060  3738  3784 I jxcore-log: 
,08-04 12:34:48.061  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.061  3738  3784 I jxcore-log: 
08-04 12:34:48.062  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.062  3738  3784 I jxcore-log: 
08-04 12:34:48.063  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.063  3738  3784 I jxcore-log: 
,08-04 12:34:48.064  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:48.064  3738  3784 I jxcore-log: 
,08-04 12:34:48.065  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:48.065  3738  3784 I jxcore-log: 
,08-04 12:34:48.068  3738  3784 I jxcore-log: ok 28 native server is nulled out
08-04 12:34:48.068  3738  3784 I jxcore-log: 
08-04 12:34:48.068  3738  3784 I jxcore-log: ok 29 native server should be closed
08-04 12:34:48.068  3738  3784 I jxcore-log: 
08-04 12:34:48.069  3738  3784 I jxcore-log: ok 30 incoming has been removed
08-04 12:34:48.069  3738  3784 I jxcore-log: 
,08-04 12:34:48.070  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.070  3738  3784 I jxcore-log: 
08-04 12:34:48.071  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.071  3738  3784 I jxcore-log: 
,08-04 12:34:48.071  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.071  3738  3784 I jxcore-log: 
08-04 12:34:48.072  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.072  3738  3784 I jxcore-log: 
08-04 12:34:48.072  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
,08-04 12:34:48.072  3738  3784 I jxcore-log: 
08-04 12:34:48.073  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.073  3738  3784 I jxcore-log: 
,08-04 12:34:48.073  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.073  3738  3784 I jxcore-log: 
08-04 12:34:48.073  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.073  3738  3784 I jxcore-log: 
,08-04 12:34:48.074  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.074  3738  3784 I jxcore-log: 
08-04 12:34:48.075  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:48.075  3738  3784 I jxcore-log: 
,08-04 12:34:48.205  3738  3784 I jxcore-log: # teardown
08-04 12:34:48.205  3738  3784 I jxcore-log: 
,08-04 12:34:48.608  3738  3784 I jxcore-log: # setup
08-04 12:34:48.608  3738  3784 I jxcore-log: 
,08-04 12:34:48.966  3738  3784 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-04 12:34:48.966  3738  3784 I jxcore-log: 
,08-04 12:34:49.868  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:49.868  3738  3784 I jxcore-log: 
,08-04 12:34:49.875  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 44957
08-04 12:34:49.875  3738  3784 I jxcore-log: 
,08-04 12:34:49.887  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:49.887  3738  3784 I jxcore-log: 
,08-04 12:34:49.888  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:49.888  3738  3784 I jxcore-log: 
,08-04 12:34:49.890  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:49.890  3738  3784 I jxcore-log: 
,08-04 12:34:49.901  3738  3784 I jxcore-log: ok 31 we should not have gotten an error
08-04 12:34:49.901  3738  3784 I jxcore-log: 
,08-04 12:34:49.908  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:49.908  3738  3784 I jxcore-log: 
,08-04 12:34:49.911  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:49.911  3738  3784 I jxcore-log: 
,08-04 12:34:49.919  3738  3784 I jxcore-log: ok 32 Buffers are identical
08-04 12:34:49.919  3738  3784 I jxcore-log: 
,08-04 12:34:49.920  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:49.920  3738  3784 I jxcore-log: 
,08-04 12:34:49.922  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:49.922  3738  3784 I jxcore-log: 
,08-04 12:34:49.934  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:49.934  3738  3784 I jxcore-log: 
,08-04 12:34:49.934  3738  3784 I jxcore-log: ok 33 server should be fine
08-04 12:34:49.934  3738  3784 I jxcore-log: 
,08-04 12:34:49.935  3738  3784 I jxcore-log: ok 34 server should be open
08-04 12:34:49.935  3738  3784 I jxcore-log: 
,08-04 12:34:49.935  3738  3784 I jxcore-log: ok 35 incoming has been removed
08-04 12:34:49.935  3738  3784 I jxcore-log: 
,08-04 12:34:49.936  3738  3784 I jxcore-log: ok 36 The mux object should be closed
08-04 12:34:49.936  3738  3784 I jxcore-log: 
08-04 12:34:49.936  3738  3784 I jxcore-log: ok 37 The mux stream should be closed
08-04 12:34:49.936  3738  3784 I jxcore-log: 
,08-04 12:34:49.941  3738  3784 I jxcore-log: # teardown
08-04 12:34:49.941  3738  3784 I jxcore-log: 
,08-04 12:34:50.326  3738  3784 I jxcore-log: # setup
08-04 12:34:50.326  3738  3784 I jxcore-log: 
,08-04 12:34:50.816  1495  1495 I ConfigService: onDestroy
,08-04 12:34:55.575  3738  3784 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-04 12:34:55.575  3738  3784 I jxcore-log: 
,08-04 12:34:55.779  3738  3784 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:34:55.779  3738  3784 I jxcore-log: 
,08-04 12:34:55.789  3738  3784 I jxcore-log: DEBUG createNativeListener: listening 42856
08-04 12:34:55.789  3738  3784 I jxcore-log: 
,08-04 12:34:55.798  3738  3784 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:34:55.798  3738  3784 I jxcore-log: 
,08-04 12:34:55.799  3738  3784 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:34:55.799  3738  3784 I jxcore-log: 
08-04 12:34:55.800  3738  3784 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:34:55.800  3738  3784 I jxcore-log: 
,08-04 12:34:55.806  3738  3784 I jxcore-log: ok 38 we should not have gotten an error
08-04 12:34:55.806  3738  3784 I jxcore-log: 
,08-04 12:34:55.813  3738  3784 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:34:55.813  3738  3784 I jxcore-log: 
,08-04 12:34:55.815  3738  3784 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:34:55.815  3738  3784 I jxcore-log: 
,08-04 12:34:55.822  3738  3784 I jxcore-log: ok 39 Buffers are identical
08-04 12:34:55.822  3738  3784 I jxcore-log: 
,08-04 12:34:55.826  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-04 12:34:55.826  3738  3784 I jxcore-log: 
,08-04 12:34:55.828  3738  3784 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:34:55.828  3738  3784 I jxcore-log: 
,08-04 12:34:55.830  3738  3784 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:34:55.830  3738  3784 I jxcore-log: 
,08-04 12:34:55.834  3738  3784 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:34:55.834  3738  3784 I jxcore-log: 
,08-04 12:34:55.835  3738  3784 I jxcore-log: ok 40 server should be fine
08-04 12:34:55.835  3738  3784 I jxcore-log: 
,08-04 12:34:55.835  3738  3784 I jxcore-log: ok 41 server should be open
08-04 12:34:55.835  3738  3784 I jxcore-log: 
,08-04 12:34:55.836  3738  3784 I jxcore-log: ok 42 incoming has been removed
08-04 12:34:55.836  3738  3784 I jxcore-log: 
,08-04 12:34:55.836  3738  3784 I jxcore-log: ok 43 The mux object should be closed
08-04 12:34:55.836  3738  3784 I jxcore-log: 
,08-04 12:34:55.837  3738  3784 I jxcore-log: ok 44 The mux stream should be closed
08-04 12:34:55.837  3738  3784 I jxcore-log: 
,08-04 12:34:55.842  3738  3784 I jxcore-log: # teardown
08-04 12:34:55.842  3738  3784 I jxcore-log: 
,08-04 12:34:59.313  1495  1980 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-04 12:35:07.970  3738  3784 I jxcore-log: # setup
08-04 12:35:07.970  3738  3784 I jxcore-log: 
,08-04 12:35:08.931  3738  3784 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-04 12:35:08.931  3738  3784 I jxcore-log: 
,08-04 12:35:12.413  3738  3784 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-04 12:35:12.413  3738  3784 I jxcore-log: 
,08-04 12:35:12.415  3738  3784 I jxcore-log: ok 45 Got right error
08-04 12:35:12.415  3738  3784 I jxcore-log: 
,08-04 12:35:12.420  3738  3784 I jxcore-log: # teardown
08-04 12:35:12.420  3738  3784 I jxcore-log: 
,08-04 12:35:13.099  3738  3784 I jxcore-log: # setup
08-04 12:35:13.099  3738  3784 I jxcore-log: 
,08-04 12:35:21.592  3738  3784 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-04 12:35:21.592  3738  3784 I jxcore-log: 
,08-04 12:35:22.602  3738  3784 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-04 12:35:22.602  3738  3784 I jxcore-log: 
,08-04 12:35:22.603  3738  3784 I jxcore-log: ok 46 Got socket hang up,
08-04 12:35:22.603  3738  3784 I jxcore-log: 
,08-04 12:35:22.607  3738  3784 I jxcore-log: # teardown
08-04 12:35:22.607  3738  3784 I jxcore-log: 
,08-04 12:35:33.266  3738  3784 I jxcore-log: # setup
08-04 12:35:33.266  3738  3784 I jxcore-log: 
,08-04 12:35:45.271  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:35:45.276  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:35:45.320  1495  2348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-04 12:35:45.320  1495  2348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-04 12:35:45.320  1495  2348 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 12:35:45.321  1495  2348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:35:45.344  2480  4170 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-04 12:35:45.344  2480  4170 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jdm.a(PG:82)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jcs.o(PG:406)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jcn.a(PG:1379)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jcs.i(PG:143)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at blb.a(PG:3937)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at czp.a(PG:18188)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at czp.a(PG:9081)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at czq.run(PG:1686)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-04 12:35:45.344  2480  4170 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jdj.a(PG:4091)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jdj.a(PG:1125)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jdm.a(PG:77)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	... 12 more
08-04 12:35:45.344  2480  4170 E HttpOperation: Caused by: faj: BadAuthentication
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at fal.a(PG:38)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	at jdj.a(PG:4089)
08-04 12:35:45.344  2480  4170 E HttpOperation: 	... 14 more
,08-04 12:35:45.421  1495  2348 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-04 12:35:45.421  1495  2348 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-04 12:35:45.421  1495  2348 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 12:35:45.421  1495  2348 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:35:45.444  2480  4170 E HttpOperation: [getmobileexperiments] Unexpected exception
08-04 12:35:45.444  2480  4170 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jdm.a(PG:82)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jcs.o(PG:406)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jcn.a(PG:1379)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jcs.i(PG:143)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at hec.a(PG:42)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at hee.a(PG:102)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at czr.a(PG:65)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at kka.a(PG:108)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at czp.a(PG:19176)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at czp.a(PG:9081)
,08-04 12:35:45.444  2480  4170 E HttpOperation: 	at czq.run(PG:1686)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-04 12:35:45.444  2480  4170 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jdj.a(PG:4091)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jdj.a(PG:1125)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jdm.a(PG:77)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	... 15 more
08-04 12:35:45.444  2480  4170 E HttpOperation: Caused by: faj: BadAuthentication
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at fal.a(PG:38)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	at jdj.a(PG:4089)
08-04 12:35:45.444  2480  4170 E HttpOperation: 	... 17 more
08-04 12:35:45.444  2480  4170 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-04 12:35:45.444  2480  4170 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jdm.a(PG:82)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jcs.o(PG:406)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jcn.a(PG:1379)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jcs.i(PG:143)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at hec.a(PG:42)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at hee.a(PG:102)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at czr.a(PG:65)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at kka.a(PG:108)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at czp.a(PG:19176)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at czp.a(PG:9081)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at czq.run(PG:1686)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jdj.a(PG:4091)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jdj.a(PG:1125)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jdm.a(PG:77)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	... 15 more
08-04 12:35:45.444  2480  4170 E ExperimentLoader: Caused by: faj: BadAuthentication
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at fal.a(PG:38)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	at jdj.a(PG:4089)
08-04 12:35:45.444  2480  4170 E ExperimentLoader: 	... 17 more
,08-04 12:35:45.575   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 507375, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-04 12:35:48.510  3738  3784 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-04 12:35:48.510  3738  3784 I jxcore-log: 
,08-04 12:35:55.276  3738  3784 E jxcore  : Error!: Missing PFX or certificate + private key.
08-04 12:35:55.276  3738  3784 E jxcore  : Stack: [{"_fileName":"tls.js","_functionName":"$0v","_lineNumber":"1065","_columnNumber":"1","_msg":"    at $0v@tls.js:1065:1"},{"_fileName":"https.js","_functionName":"$5","_lineNumber":"16","_columnNumber":"1","_msg":"    at $5@https.js:16:1"},{"_fileName":"https.js","_functionName":"exports.createServer","_lineNumber":"33","_columnNumber":"8","_msg":"    at exports.createServer@https.js:33:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js","_functionName":"","_lineNumber":"101","_columnNumber":"1","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js:101:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js","_functionName":"declareTest/</<","_lineNumber":"115","_columnNumber":"7","_msg":"    at declareTest/</<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:115:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"on","_lineNumber":"66","_columnNumber":"5","_msg":"    at on@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:66:5"}]
,08-04 12:35:55.293  3738  3784 I jxcore-log: [ { _fileName: 'tls.js',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _functionName: '$0v',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _lineNumber: '1065',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _columnNumber: '1',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _msg: '    at $0v@tls.js:1065:1' },
08-04 12:35:55.293  3738  3784 I jxcore-log:   { _fileName: 'https.js',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _functionName: '$5',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _lineNumber: '16',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _columnNumber: '1',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _msg: '    at $5@https.js:16:1' },
08-04 12:35:55.293  3738  3784 I jxcore-log:   { _fileName: 'https.js',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _functionName: 'exports.createServer',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _lineNumber: '33',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _columnNumber: '8',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _msg: '    at exports.createServer@https.js:33:8' },
08-04 12:35:55.293  3738  3784 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _functionName: '',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _lineNumber: '101',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _columnNumber: '1',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js:101:1' },
08-04 12:35:55.293  3738  3784 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _functionName: 'declareTest/</<',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _lineNumber: '115',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _columnNumber: '7',
08-04 12:35:55.293  3738  3784 I jxcore-log:     _msg: '    at declareTest/</<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:115:7' },
08-04 12:35:55.293  3738  3784 I jxcore-log:   { _fileName: '/da
08-04 12:35:55.293  3738  3784 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 12:35:55.293  3738  3784 I jxcore-log: 
,08-04 12:35:55.294  3738  3784 E jxcore-log: Error: 
08-04 12:35:55.294  3738  3784 E jxcore-log: Missing PFX or certificate + private key.
08-04 12:35:55.294  3738  3784 E jxcore-log:  (tls.js 1065:1)
08-04 12:35:55.294  3738  3784 E jxcore-log: 
,08-04 12:35:55.964  4173  4173 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 12:35:55.968  4173  4173 D AndroidRuntime: CheckJNI is OFF
,08-04 12:35:56.005  4173  4173 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 12:35:56.045  4173  4173 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 12:35:56.068  4173  4173 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 12:35:56.080   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-04 12:35:56.081   871   884 I ActivityManager: Killing 3738:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-04 12:35:56.199   871  1690 D GraphicsStats: Buffer count: 2
,08-04 12:35:56.200   871  1375 I WindowState: WIN DEATH: Window{10d8649 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 12:35:56.205   871  1306 D WifiService: Client connection lost with reason: 4
,08-04 12:35:56.214   871   895 W PackageSettings: Skipping PackageSetting{5f0a528 com.example.hello/10273} due to missing metadata,
,08-04 12:35:56.255   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-04 12:35:56.255   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-04 12:35:56.256   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-04 12:35:56.256   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-04 12:35:56.256   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102),
08-04 12:35:56.256   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.256   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:35:56.256   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 12:35:56.256   871   884 I ActivityManager:   Force finishing activity ActivityRecord{3109afa u0 com.test.thalitest/.MainActivity t2}
08-04 12:35:56.259   871   895 I art     : Starting a blocking GC Explicit
,08-04 12:35:56.269   871   882 W ActivityManager: Spurious death for ProcessRecord{134811b 0:com.test.thalitest/u0a0}, curProc for 3738: null
,08-04 12:35:56.322   871   895 I art     : Explicit concurrent mark sweep GC freed 53277(3MB) AllocSpace objects, 10(224KB) LOS objects, 33% free, 28MB/43MB, paused 873us total 63.045ms
,08-04 12:35:56.348   871   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 12:35:56.352  4173  4173 I art     : System.exit called, status: 0
08-04 12:35:56.352  4173  4173 I AndroidRuntime: VM exiting with result code 0.
,08-04 12:35:56.363   871   895 I ActivityManager: Start proc 4183:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-04 12:35:56.363   871   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-04 12:35:56.383   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-04 12:35:56.386  1654  1654 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-04 12:35:56.388  4076  4076 D BluetoothMapAppObserver: onReceive
08-04 12:35:56.388  4076  4076 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-04 12:35:56.388  1842  2018 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 12:35:56.398  3543  3543 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-04 12:35:56.399   871  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 12:35:56.414  1654  4195 I Keyboard.Facilitator.DecoderInitializer: run()
,08-04 12:35:56.416  1654  4195 I Decoder : createOrResetDecoder
,08-04 12:35:56.441   871   882 I ActivityManager: Start proc 4199:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-04 12:35:56.444  1750  1750 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-04 12:35:56.465   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 12:35:56.471  1495  1495 I ConfigService: onCreate
,08-04 12:35:56.483   871  1699 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3738 uid 10000
08-04 12:35:56.484  1654  1654 I Keyboard.Facilitator: onFinishInput()
,08-04 12:35:56.499  4199  4199 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-04 12:35:56.507  1495  4211 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 12:35:56.507  1495  4211 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 12:35:56.508  1495  4211 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-04 12:35:56.509  1495  4211 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-04 12:35:56.516  1767  1847 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-04 12:35:56.518   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-04 12:35:56.520   871   883 E PackageManager: Failed to write settings, restoring backup
08-04 12:35:56.520   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-04 12:35:56.520   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-04 12:35:56.520   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-04 12:35:56.520   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-04 12:35:56.520   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-04 12:35:56.520   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.520   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.520   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:35:56.524   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-04 12:35:56.524   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 12:35:56.524   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:35:56.524   871   884 E DropBoxManagerService: 	... 13 more
,08-04 12:35:56.528   871  1797 I ActivityManager: Start proc 4212:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-04 12:35:56.529  1767  1847 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 12:35:56.529  1767  1847 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1767
08-04 12:35:56.529  1767  1847 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.529  1767  1847 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:35:56.531   871  1375 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-04 12:35:56.532   871  4219 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:35:56.532   871  4219 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:35:56.532   871  4219 E DropBoxManagerService: 	... 5 more
,08-04 12:35:56.534  1767  1847 I Process : Sending signal. PID: 1767 SIG: 9
,08-04 12:35:56.539  1654  4195 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-04 12:35:56.579  1654  4195 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-04 12:35:56.581  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-04 12:35:56.582  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-04 12:35:56.584  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-04 12:35:56.584  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-04 12:35:56.584  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-04 12:35:56.584  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-04 12:35:56.587  1654  4195 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-04 12:35:56.587  1654  4195 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-04 12:35:56.587  1654  4195 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-04 12:35:56.588  1654  4195 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-04 12:35:56.588  1654  4195 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-04 12:35:56.588  1654  4195 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-04 12:35:56.592   871  1797 D GraphicsStats: Buffer count: 1
08-04 12:35:56.592   871  1374 I WindowState: WIN DEATH: Window{baf52ea u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-04 12:35:56.608   871   881 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1767) has died
,08-04 12:35:56.609   871   881 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-04 12:35:56.610   871   881 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 12:35:56.613  4199  4227 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: ,	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.613  4199  4227 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	,at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.613  4199  4227 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:35:56.623  4199  4199 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-04 12:35:56.630   871   884 I ActivityManager: Start proc 4230:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 12:35:56.647  4199  4241 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-04 12:35:56.647   871  1800 I ActivityManager: Start proc 4243:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-04 12:35:56.686  4243  4243 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-04 12:35:56.688  4230  4230 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:35:56.688  4230  4230 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:35:56.688  4230  4230 D AndroidRuntime: Shutting down VM
,08-04 12:35:56.696  4230  4230 E AndroidRuntime: FATAL EXCEPTION: main
08-04 12:35:56.696  4230  4230 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4230
08-04 12:35:56.696  4230  4230 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 12:35:56.696  4230  4230 E AndroidRuntime: 	... 10 more
,08-04 12:35:56.698   871  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 12:35:56.698  4230  4230 I Process : Sending signal. PID: 4230 SIG: 9
,08-04 12:35:56.700   871  4257 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:35:56.700   871  4257 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:35:56.700   871  4257 E DropBoxManagerService: 	... 5 more
,08-04 12:35:56.711  1792  4256 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-04 12:35:56.712  1792  4256 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-04 12:35:56.717  1792  4256 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-04 12:35:56.718  1792  4256 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-04 12:35:56.724   871   881 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4230) has died
,08-04 12:35:56.725   871   881 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 12:35:56.731  1495  1495 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-04 12:35:56.738  1495  1495 D AndroidRuntime: Shutting down VM
,08-04 12:35:56.739  1495  1495 E AndroidRuntime: FATAL EXCEPTION: main
08-04 12:35:56.739  1495  1495 E AndroidRuntime: Process: com.google.process.gapps, PID: 1495
08-04 12:35:56.739  1495  1495 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-04 12:35:56.739  1495  1495 E AndroidRuntime: 	... 8 more
,08-04 12:35:56.741   871   884 I ActivityManager: Start proc 4260:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 12:35:56.746   871  4266 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:35:56.746   871  4266 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:35:56.746   871  4266 E DropBoxManagerService: 	... 5 more
,08-04 12:35:56.748  1495  1495 I Process : Sending signal. PID: 1495 SIG: 9
,08-04 12:35:56.774   871  1690 I ActivityManager: Killing 1817:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-04 12:35:56.789   871  1306 D WifiService: Client connection lost with reason: 4
,08-04 12:35:56.801  4260  4260 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:35:56.801  4260  4260 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:35:56.801  4260  4260 D AndroidRuntime: Shutting down VM
,08-04 12:35:56.803  4199  4227 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-04 12:35:56.808  4199  4241 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	,at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.808  4199  4241 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-04 12:35:56.809  4199  4241 E AndroidRuntime: Process: android.process.acore, PID: 4199
08-04 12:35:56.809  4199  4241 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at com.a,ndroid.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:35:56.809  4199  4241 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:35:56.809  4199  4227 I Process : Sending signal. PID: 4199 SIG: 9
,08-04 12:35:56.822   871  1306 D WifiService: Client connection lost with reason: 4
,08-04 12:35:56.838   871  1800 I ActivityManager: Process android.process.acore (pid 4199) has died
,08-04 12:35:56.838   871  1800 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-04 12:35:56.839   871  1697 I ActivityManager: Process com.google.process.gapps (pid 1495) has died
08-04 12:35:56.840   871  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-04 12:35:56.840   871  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-04 12:35:56.840   871  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-04 12:35:56.843   871  4274 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:35:56.843   871  4274 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:35:56.843   871  4274 E DropBoxManagerService: 	... 5 more

```
