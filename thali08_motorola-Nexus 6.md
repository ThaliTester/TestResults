#### Test 797510150318bb5_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-04 12:50:15.163   876  2116 D NetlinkSocketObserver: NeighborEvent{elapsedMs=378772, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-04 12:50:15.881  3845  3845 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 12:50:15.886  3845  3845 D AndroidRuntime: CheckJNI is OFF
08-04 12:50:15.921  3845  3845 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 12:50:15.964  3845  3845 I Radio-JNI: register_android_hardware_Radio DONE
08-04 12:50:15.984  3845  3845 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 12:50:15.989   876   886 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 12:50:16.036   876   886 I ActivityManager: Start proc 3854:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-04 12:50:16.039  3845  3845 D AndroidRuntime: Shutting down VM
08-04 12:50:16.205  3854  3854 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-04 12:50:16.233  3854  3854 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-04 12:50:16.241  3854  3854 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9849-9852)
08-04 12:50:16.241  3854  3854 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 12:50:16.274  3854  3854 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d855ad0}
,08-04 12:50:16.274  3854  3854 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:50:16.275  3854  3854 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 12:50:16.284  3854  3854 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 12:50:16.286  3854  3854 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 12:50:16.311  3854  3854 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 12:50:16.327  3854  3854 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 12:50:16.327  3854  3854 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 12:50:16.327  3854  3854 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 12:50:16.327  3854  3854 I Adreno  : Build Date                       : 10/20/15
08-04 12:50:16.327  3854  3854 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 12:50:16.327  3854  3854 I Adreno  : Local Branch                     : M14
08-04 12:50:16.327  3854  3854 I Adreno  : Remote Branch                    : 
08-04 12:50:16.327  3854  3854 I Adreno  : Remote Branch                    : 
08-04 12:50:16.327  3854  3854 I Adreno  : Reconstruct Branch               : 
,08-04 12:50:16.407   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a6d8c8c:true
,08-04 12:50:16.503  3854  3854 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 12:50:16.524  3854  3854 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-04 12:50:16.634  3854  3891 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 12:50:16.644   876   889 W ActivityManager: Activity pause timeout for ActivityRecord{31a90e1 u0 com.test.thalitest/.MainActivity t2}
,08-04 12:50:16.653  3854  3878 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-04 12:50:16.726  3854  3891 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 12:50:16.782   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +638ms (total +765ms)
,08-04 12:50:16.793  1657  1657 I Keyboard.Facilitator: onFinishInput()
,08-04 12:50:16.886  3854  3854 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3854
,08-04 12:50:16.972  3854  3854 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 12:50:17.279  3854  3893 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1678313168
,08-04 12:50:17.306  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 12:50:17.306  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 12:50:17.306  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 12:50:17.306  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 12:50:17.306  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 12:50:17.306  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d526a7 added. We now have 1 listener(s)
,08-04 12:50:17.314  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-04 12:50:17.315  3854  3893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:50:17.315  3854  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:50:17.316  3854  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 12:50:17.321  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a61ff2 added. We now have 1 listener(s)
,08-04 12:50:17.321  3854  3893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:17.325   876  1313 D WifiService: New client listening to asynchronous messages
,08-04 12:50:17.326  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:17.326  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-04 12:50:17.326  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 12:50:17.326  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-04 12:50:17.326  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-04 12:50:17.330  3854  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:17.330  3854  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-04 12:50:17.341  3854  3893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:17.341  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:50:17.341  3854  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 12:50:17.341  3854  3893 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:17.343  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-04 12:50:17.344  3854  3893 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 12:50:17.346  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:17.375  3854  3854 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 12:50:18.464  3854  3901 W jxcore-log: Initializing JXcore engine
,08-04 12:50:18.465  3854  3901 W jxcore-log: JXcore engine is ready
,08-04 12:50:18.502  3901  3901 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-04 12:50:18.502  3901  3901 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12671]" dev="sockfs" ino=12671 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
,08-04 12:50:18.502  3901  3901 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-04 12:50:18.502  3901  3901 W Thread-338: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24399]" dev="sockfs" ino=24399 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-04 12:50:18.516  3854  3901 W jxcore-log: Starting JXcore engine
,08-04 12:50:18.597  3854  3901 W jxcore-log: Platform android
08-04 12:50:18.597  3854  3901 W jxcore-log: 
08-04 12:50:18.597  3854  3901 W jxcore-log: Process ARCH arm
08-04 12:50:18.597  3854  3901 W jxcore-log: 
,08-04 12:50:18.810  3854  3901 I jxcore-log: JXcore Cordova bridge is ready!
08-04 12:50:18.810  3854  3901 I jxcore-log: 
,08-04 12:50:18.811  3854  3901 W jxcore-log: JXcore engine is started
,08-04 12:50:18.818  3854  3893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 12:50:18.824  3854  3854 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 12:50:30.467   876  2116 D NetlinkSocketObserver: NeighborEvent{elapsedMs=394077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-04 12:50:34.180  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 12:50:34.180  3854  3901 I jxcore-log: 
,08-04 12:50:34.182  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 12:50:34.182  3854  3901 I jxcore-log: 
,08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:34.192  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:50:34.195  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:50:34.197  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 12:50:34.197  3854  3901 I jxcore-log: 
,08-04 12:50:34.199  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 12:50:34.199  3854  3901 I jxcore-log: 
,08-04 12:50:34.534  3854  3901 D ExecuteNativeTests: Running unit tests
,08-04 12:50:34.591  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:34.592  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 added. We now have 2 listener(s)
,08-04 12:50:34.593  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:50:34.593  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:50:34.593  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:34.593  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:34.593  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 added. We now have 2 listener(s)
08-04 12:50:34.593  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:34.594  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:34.606  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:34.617  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:50:34.622  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:50:34.623  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:34.626  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 12:50:34.628  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:34.628  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 12:50:34.629  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 12:50:34.631  3854  3901 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-04 12:50:34.631  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 12:50:34.631  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:50:34.631  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:50:34.631  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:50:34.631  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-04 12:50:34.632  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.632  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.632  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.632  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-04 12:50:34.632  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:34.632  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:50:34.632  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 removed from the list
08-04 12:50:34.633  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.633  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 removed from the list
,08-04 12:50:34.634  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:34.635  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:50:34.635  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.635  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.635  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.636  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.636  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.636  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.636  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.638  3854  3901 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 12:50:34.638  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.639  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.639  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.639  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.639  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.639  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.639  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.639  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.639  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.639  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.639  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.639  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.639  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.639  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.641  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.641  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.641  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.641  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.Co,nnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 12:50:34.646  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 12:50:34.647  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 12:50:34.647  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.647  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.647  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.648  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.648  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.648  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.648  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.648  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.648  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.648  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.648  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.648  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.648  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.648  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.649  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.649  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.649  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.649  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.650  3854  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:50:34.651  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:34.654  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:50:34.656  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.656  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:50:34.658  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:34.658  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:50:34.658  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:50:34.658  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:50:34.659  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:34.659  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:50:34.659  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:34.664  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:50:34.664  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:50:34.669  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:50:34.672  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:50:34.672  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 12:50:34.675  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-04 12:50:34.678  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-04 12:50:34.678  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:50:34.679  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:50:34.680  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:50:34.681  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:34.685  2640  2852 D BtGatt.GattService: registerClient() - UUID=49925484-7b5a-4cec-be6d-5535028ea674
08-04 12:50:34.686  2640  2692 D BtGatt.GattService: onClientRegistered() - UUID=49925484-7b5a-4cec-be6d-5535028ea674, clientIf=5
08-04 12:50:34.687  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:50:34.688  2640  2840 D BtGatt.GattService: start scan with filters
08-04 12:50:34.690  2640  2696 D BtGatt.ScanManager: handling starting scan
08-04 12:50:34.691  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:50:34.691  2640  2696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
08-04 12:50:34.692  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:50:34.692  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:50:34.693  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 12:50:34.699  2640  2692 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:50:34.699  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.700  2640  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:50:34.700  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:50:34.702  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:50:34.704  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:50:34.705  2640  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:50:34.705  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.705  2640  2696 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:50:34.705  2640  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:50:34.710  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 12:50:34.714  2640  2692 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:50:34.714  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.719  2640  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:50:34.719  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.720  3854  3901 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:50:34.724  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.725  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 12:50:34.725  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:34.725  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:50:34.725  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.725  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:50:34.725  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:50:34.725  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:34.725  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:50:34.725  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:50:34.726  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:50:34.726  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:50:34.727  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:34.728  2640  2653 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:50:34.728  2640  2654 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:50:34.729  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:50:34.729  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:50:34.729  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 12:50:34.729  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:50:34.729  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:50:34.730  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:50:34.731  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:50:34.731  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:50:34.731  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:50:34.732  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:50:34.733  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:34.733  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:50:34.733  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:34.733  2640  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:50:34.734  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.734  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.734  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.734  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:34.734  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.734  2640  2696 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:50:34.734  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.734  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.734  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.734  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.735  3854  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 12:50:34.736  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:34.740  2640  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:34.740  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:50:34.740  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.740  2640  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:50:34.742  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.742  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:34.744  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:34.744  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:50:34.744  2640  2692 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:50:34.744  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:50:34.744  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.745  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:50:34.746  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:34.746  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:50:34.746  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:34.748  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:50:34.749  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:50:34.753  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:50:34.753  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:50:34.753  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:50:34.757  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:50:34.758  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:50:34.758  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 12:50:34.758  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:34.761  2640  2840 D BtGatt.GattService: registerClient() - UUID=059bea4c-da5a-46bb-8869-31087131ee14
08-04 12:50:34.761  2640  2692 D BtGatt.GattService: onClientRegistered() - UUID=059bea4c-da5a-46bb-8869-31087131ee14, clientIf=5
,08-04 12:50:34.762  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:50:34.762  2640  2851 D BtGatt.GattService: start scan with filters
,08-04 12:50:34.766  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:50:34.766  2640  2696 D BtGatt.ScanManager: handling starting scan
08-04 12:50:34.766  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 12:50:34.766  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:50:34.766  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:50:34.769  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:50:34.770  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:50:34.770  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 12:50:34.772  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 12:50:34.772  2640  2692 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:50:34.772  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.773  2640  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:50:34.775  3854  3901 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:50:34.777  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.777  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:50:34.777  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.777  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:50:34.777  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.777  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:50:34.777  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:50:34.778  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:34.778  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:50:34.778  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:50:34.778  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:50:34.778  2640  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 12:50:34.778  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:50:34.778  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.778  2640  2696 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:50:34.778  2640  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:50:34.779  3854  3901 D BluetoothAdapter: STATE_ON
08-04 12:50:34.779  2640  2852 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:50:34.780  2640  2654 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:50:34.781  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:50:34.781  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:50:34.781  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 12:50:34.781  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:50:34.781  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:50:34.783  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:34.783  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:50:34.783  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:50:34.783  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:50:34.784  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:50:34.785  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:34.786  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:34.786  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:34.786  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.786  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.786  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:34.786  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.786  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.786  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.786  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.786  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.787  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.787  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.788  2640  2692 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 12:50:34.788  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.788  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.789  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.789  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.789  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.789  3854  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:50:34.791  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:34.793  2640  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 12:50:34.793  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:34.796  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:50:34.799  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:34.799  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:34.800  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:50:34.800  2640  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:50:34.801  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:50:34.801  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.801  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:50:34.801  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:34.801  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:50:34.801  2640  2696 D BtGatt.ScanManager: stopping BLe Batch
,08-04 12:50:34.802  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:34.805  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:34.806  2640  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:50:34.806  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.806  2640  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:50:34.806  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:50:34.806  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:50:34.812  2640  2692 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:50:34.812  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:34.814  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:50:34.815  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:50:34.815  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:50:34.821  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:50:34.821  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:50:34.821  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:50:34.822  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:34.825  2640  2653 D BtGatt.GattService: registerClient() - UUID=71ce1ac2-698b-4bd9-8de2-535312b68524
,08-04 12:50:34.826  2640  2692 D BtGatt.GattService: onClientRegistered() - UUID=71ce1ac2-698b-4bd9-8de2-535312b68524, clientIf=5
08-04 12:50:34.826  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:50:34.826  2640  2654 D BtGatt.GattService: start scan with filters
,08-04 12:50:34.830  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-04 12:50:34.830  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:50:34.831  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:50:34.831  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 12:50:34.831  2640  2696 D BtGatt.ScanManager: handling starting scan
,08-04 12:50:34.836  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:50:34.836  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:50:34.837  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:50:34.837  2640  2692 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:50:34.837  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.838  2640  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:50:34.840  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:50:34.844  3854  3901 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:50:34.845  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:50:34.845  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 12:50:34.845  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.845  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:50:34.845  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.845  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:50:34.845  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:50:34.845  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:34.846  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-04 12:50:34.846  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:50:34.846  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:50:34.846  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:50:34.848  3854  3901 D BluetoothAdapter: STATE_ON
08-04 12:50:34.848  2640  2653 D BtGatt.GattService: stopScan() - queue size =1
,08-04 12:50:34.849  2640  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 12:50:34.850  2640  2654 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:50:34.850  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.850  2640  2696 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 12:50:34.850  2640  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:50:34.851  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 12:50:34.851  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:50:34.851  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:50:34.851  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:50:34.851  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:50:34.853  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:34.853  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:50:34.854  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 12:50:34.854  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:50:34.855  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:34.856  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:50:34.856  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:34.857  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:50:34.857  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.857  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:50:34.857  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:34.857  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-04 12:50:34.858  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:34.858  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.858  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:34.858  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.858  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.858  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.858  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.859  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.860  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.860  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.861  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:50:34.861  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:50:34.861  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.861  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.862  3854  3901 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-04 12:50:34.863  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.863  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:34.863  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.864  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.864  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.864  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.864  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list,
08-04 12:50:34.864  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.864  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.864  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.864  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.864  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.865  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.865  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.872  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.872  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:50:34.872  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.872  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.873  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-04 12:50:34.874  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:50:34.874  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:34.874  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.874  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:34.874  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.874  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.875  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.875  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:50:34.875  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.875  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.875  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.875  2640  2692 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:50:34.875  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.875  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.875  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.875  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.877  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.878  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.878  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.878  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.879  3854  3901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-04 12:50:34.879  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.879  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:34.879  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.880  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.880  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.880  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.880  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
,08-04 12:50:34.880  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.880  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.880  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:50:34.880  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.880  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.881  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.881  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.882  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:50:34.883  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.883  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.883  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.884  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-04 12:50:34.884  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:50:34.884  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.884  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-04 12:50:34.884  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:34.884  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.885  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.885  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
,08-04 12:50:34.885  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.885  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list,
,08-04 12:50:34.885  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.885  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.885  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.885  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:34.885  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:34.885  2640  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:50:34.886  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:34.886  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.886  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:50:34.887  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.887  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
,08-04 12:50:34.887  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 12:50:34.889  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 12:50:34.890  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:50:34.890  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 12:50:34.890  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 12:50:34.890  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 12:50:34.890  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.890  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-04 12:50:34.891  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:50:34.891  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.891  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.891  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.891  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.891  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.891  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.891  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.891  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.892  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.892  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.892  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.894  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.894  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.894  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.894  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.896  2640  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:50:34.896  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.897  2640  2696 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:50:34.898  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:50:34.898  3854  3901 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 12:50:34.898  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 12:50:34.905  2640  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:50:34.905  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.905  2640  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:50:34.913  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:50:34.912  2640  2692 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:50:34.913  2640  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:34.914  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 12:50:34.914  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 12:50:34.914  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 12:50:34.914  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 12:50:34.914  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 12:50:34.915  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 12:50:34.916  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 12:50:34.917  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 12:50:34.917  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 12:50:34.917  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-04 12:50:34.917  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 12:50:34.917  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 12:50:34.917  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 12:50:34.917  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 12:50:34.918  3854  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:50:34.918  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 12:50:34.918  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:50:34.918  3854  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:50:34.919  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 12:50:34.919  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:50:34.919  3854  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:50:34.919  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 12:50:34.923  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 12:50:34.923  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 12:50:34.923  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 12:50:34.924  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 12:50:34.924  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 12:50:34.924  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 12:50:34.924  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:50:34.924  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 12:50:34.925  3854  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 402)
08-04 12:50:34.925  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.925  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.925  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.925  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.925  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.926  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.926  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 12:50:34.926  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.926  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.926  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.926  3854  3903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:50:34.926  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.927  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.927  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.927  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.927  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.927  3854  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 402
08-04 12:50:34.928  3854  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 402)
08-04 12:50:34.928  3854  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 402)
08-04 12:50:34.928  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.928  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.928  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.928  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.930  3854  3901 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 12:50:34.930  3854  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 402)
08-04 12:50:34.930  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.930  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.930  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.930  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.930  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.930  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.930  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.930  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.930  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.930  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.930  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.930  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.930  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.931  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.931  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.931  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.931  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.931  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.932  3854  3901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 12:50:34.932  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.932  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.932  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.932  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.932  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.932  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.932  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.932  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.932  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.933  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.933  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.933  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.933  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.933  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.934  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.934  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.934  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.934  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.934  3854  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 12:50:34.934  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 12:50:34.934  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:50:34.935  3854  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 12:50:34.935  3854  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 12:50:34.935  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 12:50:34.935  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:50:34.935  3854  3901 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 12:50:34.935  3854  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 12:50:34.935  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 12:50:34.935  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:50:34.935  3854  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 12:50:34.935  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.935  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.935  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.936  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.936  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.936  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.936  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.936  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.936  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.936  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.936  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.936  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.936  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.936  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.937  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.937  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.938  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.938  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.938  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.938  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.938  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.938  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.938  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.938  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.938  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.939  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.939  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.939  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.939  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.939  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.939  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.939  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.939  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.939  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.939  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.939  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.940  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.940  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.940  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.940  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.940  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.940  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.940  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.940  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.940  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.940  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.940  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.941  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.941  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.941  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.941  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.942  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 12:50:34.943  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:34.944  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 12:50:34.945  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 12:50:34.945  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 12:50:34.945  3854  3854 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 12:50:34.945  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 12:50:34.945  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:50:34.946  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.946  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 12:50:34.946  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 12:50:34.946  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 12:50:34.946  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.946  3854  3905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:50:34.946  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 12:50:34.946  3854  3854 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 12:50:34.946  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.946  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:50:34.946  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:34.946  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:50:34.947  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:50:34.947  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.947  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.948  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:34.948  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:34.948  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:34.948  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:34.948  3854  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-04 12:50:34.948  3854  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 12:50:34.948  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.948  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.948  3854  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 12:50:34.948  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.948  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.949  3854  3854 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 12:50:34.949  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.949  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.949  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.949  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.949  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.949  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.949  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.949  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.949  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.949  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.950  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.950  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.951  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.951  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.951  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.952  3854  3901 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 12:50:34.952  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 12:50:34.952  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:50:34.952  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:50:34.952  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.953  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.953  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.953  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.953  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.953  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.953  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.953  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.953  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.953  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.953  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.953  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.953  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.953  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.954  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.954  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.955  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.955  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.959  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.959  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.959  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.959  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.959  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.959  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.959  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.959  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.959  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.959  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.960  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.960  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.960  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.960  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.961  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.961  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.961  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.961  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.961  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:34.966  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:34.966  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:34.966  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:34.966  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.966  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.966  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91d6167 not in the list
08-04 12:50:34.967  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.967  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.967  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:34.967  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.967  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.967  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:34.967  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:34.968  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:34.968  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:34.968  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:34.968  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da0b14 not in the list
08-04 12:50:34.970  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 12:50:34.970  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:50:34.970  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 12:50:34.970  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:50:34.970  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 12:50:34.970  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:50:34.973  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 12:50:34.973  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 12:50:34.974  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 12:50:34.974  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 12:50:34.974  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 12:50:34.974  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 12:50:34.974  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 12:50:34.974  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 12:50:34.975  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 12:50:34.975  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 12:50:34.976  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 12:50:34.976  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 12:50:34.976  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 12:50:34.976  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 12:50:34.977  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:34.977  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f09fd6 added. We now have 2 listener(s)
08-04 12:50:34.977  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:34.980  3854  3901 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 12:50:34.980   876  1715 D WifiService: setWifiEnabled: true pid=3854, uid=10000
08-04 12:50:34.980   876  1715 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 12:50:34.981  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:34.981  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cab7257 added. We now have 3 listener(s)
08-04 12:50:34.982  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:35.000  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:35.000  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8206144 added. We now have 4 listener(s)
08-04 12:50:35.000  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:35.002  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:50:35.002  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@204522d added. We now have 5 listener(s)
08-04 12:50:35.002  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:35.011   876  2929 D WifiService: setWifiEnabled: false pid=3854, uid=10000
,08-04 12:50:35.011   876  2929 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:50:35.016  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:35.025  2640  2688 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 12:50:35.026  2640  2688 D BluetoothAdapterProperties: Setting state to 13
,08-04 12:50:35.026  2640  2688 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 12:50:35.027  2640  2688 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 12:50:35.027  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 12:50:35.027  2640  2688 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:50:35.027  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 12:50:35.028  2640  2692 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:50:35.028  2640  2688 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 12:50:35.030   876  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-04 12:50:35.030   876  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-04 12:50:35.030   876  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:50:35.030   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:50:35.030  2640  2640 D HeadsetService: Received stop request...Stopping profile...
08-04 12:50:35.032   876   876 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:35.032  1356  1367 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:35.032  1356  1356 D HeadsetProfile: Bluetooth service disconnected
08-04 12:50:35.033   876   876 D BluetoothHeadset: Proxy object disconnected
,08-04 12:50:35.033  1727  1741 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:35.033   876   876 D BluetoothHeadset: Proxy object disconnected
,08-04 12:50:35.033  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:35.033  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.034  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:50:35.034  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:35.034  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:50:35.034  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:35.034  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:35.034  2640  2640 D A2dpService: Received stop request...Stopping profile...
08-04 12:50:35.035  2640  2843 D A2dpStateMachine: Exit Disconnected: -1
08-04 12:50:35.036   876   876 D BluetoothA2dp: Proxy object disconnected
08-04 12:50:35.036  1356  1356 D BluetoothA2dp: Proxy object disconnected
08-04 12:50:35.037  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:50:35.041  2640  2640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-04 12:50:35.041  2640  2692 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 12:50:35.041  2640  2816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:50:35.041  2640  2816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:35.041  2640  2816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:50:35.041  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:35.041  2640  2640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:35.041  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:50:35.042  2640  2640 D HidService: Received stop request...Stopping profile...
08-04 12:50:35.042  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.042  2640  2640 D HidService: Stopping Bluetooth HidService
08-04 12:50:35.042  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:35.042  2640  2692 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-04 12:50:35.043  2640  2837 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-04 12:50:35.043   876  1312 E native  : do suspend true
08-04 12:50:35.046  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.049  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:35.049  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:50:35.050  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:35.050  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:35.051   876   889 I ActivityManager: Start proc 3908:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-04 12:50:35.052  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.053   876  2117 D DhcpClient: Clearing IP address
,08-04 12:50:35.053   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-04 12:50:35.055   372   874 D CommandListener: Setting iface cfg
08-04 12:50:35.055  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.057  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.058   876  2118 D DhcpClient: Receive thread stopped
08-04 12:50:35.058  2640  2640 D HealthService: Received stop request...Stopping profile...
08-04 12:50:35.061  2640  2640 D PanService: Received stop request...Stopping profile...
08-04 12:50:35.063   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 12:50:35.063   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-04 12:50:35.065   876  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-04 12:50:35.065  1356  1356 D BluetoothInputDevice: Proxy object disconnected
08-04 12:50:35.065  1356  1356 D HidProfile: Bluetooth service disconnected
08-04 12:50:35.065  1356  1356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 12:50:35.065  1356  1356 D PanProfile: Bluetooth service disconnected
,08-04 12:50:35.066   416   416 E Parcel  : Reading a NULL string not supported here.
,08-04 12:50:35.066   876  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:50:35.066   876  1312 E native  : do suspend true
08-04 12:50:35.066  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:35.066  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.067  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:35.067  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:35.068  2640  2816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:50:35.068  2640  2816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:35.068  2640  2816 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:50:35.068  2640  2816 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:50:35.068  2640  2816 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:50:35.068  2640  2816 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-04 12:50:35.068  2640  2692 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-04 12:50:35.069  2640  2640 D BluetoothMapService: Received stop request...Stopping profile...
08-04 12:50:35.069  2640  2640 D BluetoothMapService: stop()
08-04 12:50:35.070  2640  2640 D BluetoothMapAppObserver: deinitObservers()
08-04 12:50:35.070  2640  2640 D BluetoothMapAppObserver: removeReceiver()
08-04 12:50:35.071  1356  1356 D BluetoothMap: Proxy object disconnected
08-04 12:50:35.071  1356  1356 D MapProfile: Bluetooth service disconnected
08-04 12:50:35.073   876  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-04 12:50:35.073  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:35.073  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.073  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:50:35.073  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:35.074  2640  2640 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-04 12:50:35.074  2640  2692 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:50:35.074  2640  2640 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-04 12:50:35.075  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:35.075  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.075  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:35.075  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:35.075  2640  2640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 12:50:35.076  2640  2692 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 12:50:35.076  2640  2640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 12:50:35.076  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:35.076  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.076  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:50:35.076  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:35.077  2640  2640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 12:50:35.078  2640  2640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 12:50:35.079  2640  2640 D BluetoothMapService: MAP Service closeService in
,08-04 12:50:35.079  2640  2640 D BluetoothMapMasInstance0: MAP Service shutdown
,08-04 12:50:35.079  2640  2640 D ObexServerSockets0: shutdown(block = true)
,08-04 12:50:35.079  2640  2853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-04 12:50:35.080  2640  2640 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:50:35.080  2640  2837 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 12:50:35.080  2640  2640 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:50:35.080  2640  2854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 12:50:35.083  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:35.084  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.084  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:35.084  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:35.084  2640  2688 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 12:50:35.084  2640  2688 D BluetoothAdapterProperties: Setting state to 15
08-04 12:50:35.084  2640  2640 D BluetoothMapService: cleanup()
08-04 12:50:35.084  2640  2640 D BluetoothMapService: MAP Service closeService in
08-04 12:50:35.084  2640  2688 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 12:50:35.084  2640  2688 I BluetoothAdapterState: Entering BleOnState
08-04 12:50:35.085  2640  2640 I BtOppRfcommListener: stopping Accept Thread
08-04 12:50:35.085  1727  1742 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:35.085  2640  3387 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 12:50:35.085  1356  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:50:35.085  2640  3387 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 12:50:35.085  1356  1834 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:50:35.086  1356  1376 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:50:35.086   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:35.087  1356  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:35.087   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:50:35.087   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:35.087  1356  1834 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:50:35.088   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 12:50:35.088  1356  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:50:35.088  2640  2688 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-04 12:50:35.089  2640  2688 D BluetoothAdapterProperties: Setting state to 16
08-04 12:50:35.089  2640  2688 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-04 12:50:35.089  2640  2688 D BluetoothAdapterProperties: onBleDisable
08-04 12:50:35.089  2640  2688 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:50:35.090  2640  2689 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 12:50:35.090  2640  2816 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 12:50:35.090  2640  2816 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:35.095  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:35.095  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:35.096  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.096  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:35.096  2640  2692 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:50:35.098  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:35.098  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:35.099  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.099  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:35.100  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.103  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.078  1511  2255 V NativeCrypto: Read error: ssl=0xacbd8e00: I/O error during system call, Connection timed out
08-04 12:50:35.114  1511  2255 V NativeCrypto: SSL shutdown failed: ssl=0xacbd8e00: I/O error during system call, Broken pipe
08-04 12:50:35.115   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:35.136   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:35.137   876  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 12:50:35.137   876  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-04 12:50:35.139   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-04 12:50:35.140   876   893 D Tethering: MasterInitialState.processMessage what=3
08-04 12:50:35.143  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.144  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:35.146  3379  3379 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@120379a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-04 12:50:35.152  3908  3908 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-04 12:50:35.160  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:50:35.165  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:35.168   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7bc86a1:true
,08-04 12:50:35.177   876  1740 I ActivityManager: Start proc 3928:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-04 12:50:35.181   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-04 12:50:35.182   876  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-04 12:50:35.183   876  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:50:35.190  3908  3908 D LocalBluetoothProfileManager: Adding local MAP profile
,08-04 12:50:35.192  3908  3908 D BluetoothMap: Create BluetoothMap proxy object
,08-04 12:50:35.201  3908  3908 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-04 12:50:35.201   876  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:50:35.204  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:35.204  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:35.204  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.204  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:35.205   876  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 12:50:35.206  1836  2059 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 12:50:35.206  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:35.206  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:35.207  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:35.207  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:35.215  3928  3928 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-04 12:50:35.218  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:50:35.224   876   887 I ActivityManager: Killing 3379:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-04 12:50:35.297  2640  2692 I bt_hci  : shut_down
,08-04 12:50:35.304  2640  2698 I bt_vendor: low_power_mode_cb
,08-04 12:50:35.307  2640  2698 D bt_hwcfg: hw_epilog_process
,08-04 12:50:35.332  2640  2698 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 12:50:35.332  2640  2698 I bt_vendor: epilog_cb
,08-04 12:50:35.332  2640  2698 I bt_hci  : epilog_finished_callback
,08-04 12:50:35.339  2640  2692 I bt_hci_h4: hal_close
,08-04 12:50:35.339  2640  2692 I bt_userial_vendor: device fd = 51 close
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.k.d(PG:583)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.379  3928  3928 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.379  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.380  3928  3928 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:50:35.380  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:50:35.384  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:50:35.395  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:35.440   876  2929 I ActivityManager: Start proc 3960:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-04 12:50:35.442  3908  3908 D DockEventReceiver: finishStartingService: stopping service
08-04 12:50:35.449  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:50:35.457   876  1749 I ActivityManager: Killing 3427:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-04 12:50:35.550  2640  2689 D bt_stack_manager: event_shut_down_stack finished.
,08-04 12:50:35.551  2640  2688 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 12:50:35.558  2640  2688 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-04 12:50:35.559  2640  2640 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:50:35.560  2640  2640 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 12:50:35.560  2640  2640 D BtGatt.GattService: stop()
08-04 12:50:35.560  2640  2640 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 12:50:35.562  2640  2640 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:35.562  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:35.562  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:35.562  2640  2640 V BluetoothAdapterState: isBleTurningOff()=true
08-04 12:50:35.563  2640  2688 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-04 12:50:35.563  2640  2688 D BluetoothAdapterProperties: Setting state to 10
08-04 12:50:35.563  2640  2688 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-04 12:50:35.564   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-04 12:50:35.565  2640  2688 I BluetoothAdapterState: Entering OffState
,08-04 12:50:35.582  2640  2640 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-04 12:50:35.582  2640  2640 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-04 12:50:35.582  2640  2640 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 12:50:35.583  2640  2689 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-04 12:50:35.587  2640  2689 D bt_stack_manager: event_clean_up_stack finished.
,08-04 12:50:35.593  2640  2640 I art     : System.exit called, status: 0
,08-04 12:50:35.593  2640  2640 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 12:50:35.604  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-04 12:50:35.642   876  1384 I ActivityManager: Process com.android.bluetooth (pid 2640) has died
,08-04 12:50:35.707  3928  3945 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-04 12:50:35.843  3960  3980 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-04 12:50:35.843  3960  3980 I Babel_SMS: MmsConfig.loadMmsSettings
,08-04 12:50:35.844  3960  3980 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-04 12:50:35.852  3960  3980 I Babel_SMS: MmsConfig.loadFromDatabase
,08-04 12:50:35.864   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ba7667:true
,08-04 12:50:35.930  3960  3980 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-04 12:50:35.930  3960  3980 I Babel_SMS: MmsConfig.loadFromResources
,08-04 12:50:35.931  3960  3980 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-04 12:50:35.933  3960  3980 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-04 12:50:35.983  3960  3960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:50:35.987  3960  3960 I Babel_Crash: startup - clean
,08-04 12:50:36.024  3960  3960 I Babel_telephony: TeleModule.launchCompleted
,08-04 12:50:36.037   876  1738 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 12:50:36.047  3960  3960 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-04 12:50:36.054  3960  3960 W Babel   : BAM#gBA: invalid account id: -1
08-04 12:50:36.055  3960  3960 W Babel   : BAM#gBA: invalid account id: -1
08-04 12:50:36.055  3960  3960 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-04 12:50:36.063   876  2929 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 12:50:36.066  3960  3985 I Babel   : deleted: false for 0
,08-04 12:50:36.095  1939  1939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:50:36.108  1939  1939 D SystemUpdateService: onCreate
,08-04 12:50:36.136  1939  1939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:50:36.140  1939  3987 I SystemUpdateService: active receiver: enabled
,08-04 12:50:36.144  1939  3987 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:50:36.150  1939  3987 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 12:50:36.150  1939  3987 I SystemUpdateService: now status is 0 (complete)
08-04 12:50:36.150  1939  3987 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:50:36.150  1939  3987 I SystemUpdateService: file has been verified
08-04 12:50:36.150  1939  3987 I SystemUpdateService: OTA package size = 12249756
,08-04 12:50:36.161  1939  3987 I SystemUpdateService: showing system update notification
,08-04 12:50:36.166  1939  1939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 12:50:36.170  1939  2404 I iu.UploadsManager: num queued entries: 0
,08-04 12:50:36.171  1939  2404 I iu.UploadsManager: num updated entries: 0
08-04 12:50:36.172  1939  2404 I iu.SyncManager: NEXT; no task
,08-04 12:50:36.177  1939  1939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:50:36.178  1939  1939 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:50:36.181  3960  3960 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:50:36.192   876  1749 I ActivityManager: Start proc 3989:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-04 12:50:36.208  1939  1939 D SystemUpdateService: onDestroy
,08-04 12:50:36.238  3989  3989 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-04 12:50:36.242  3989  3989 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:36.247  3960  3960 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 12:50:36.253  3989  3989 D SprintDMHelper: simOperator: 
,08-04 12:50:36.253  3989  3989 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:50:36.258  3960  3960 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:50:36.260  3960  3960 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:50:36.263  3960  3960 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:50:36.268  3960  3960 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:50:36.269   876  2930 I ActivityManager: Start proc 4001:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-04 12:50:36.273   876  1525 I ActivityManager: Killing 1757:android.process.acore/u0a5 (adj 15): empty #17
,08-04 12:50:36.327  3960  3960 I vclib   : onServiceConnected
,08-04 12:50:36.444   876  1725 I ActivityManager: Start proc 4016:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-04 12:50:36.447  3960  4015 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-04 12:50:36.450   876  2930 I ActivityManager: Killing 3679:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-04 12:50:36.527  4016  4016 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-04 12:50:36.582  4016  4016 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-04 12:50:36.582  4016  4016 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-04 12:50:36.582  4016  4016 I GAv4    :   adb logcat -s GAv4
,08-04 12:50:36.600  4016  4016 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:50:36.607  4016  4016 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:50:36.629  4016  4033 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:50:36.730  4016  4016 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-04 12:50:36.771  4016  4016 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 12:50:36.779  4016  4016 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 387-390)
,08-04 12:50:36.780  4016  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 12:50:36.789  4016  4016 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c306d84}
,08-04 12:50:36.790  4016  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:50:36.790  4016  4016 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 12:50:36.796  4016  4016 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 12:50:36.798  4016  4016 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 12:50:36.815  4016  4016 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 12:50:36.825  4016  4016 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 12:50:36.825  4016  4016 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 12:50:36.825  4016  4016 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 12:50:36.825  4016  4016 I Adreno  : Build Date                       : 10/20/15
08-04 12:50:36.825  4016  4016 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 12:50:36.825  4016  4016 I Adreno  : Local Branch                     : M14
08-04 12:50:36.825  4016  4016 I Adreno  : Remote Branch                    : 
08-04 12:50:36.825  4016  4016 I Adreno  : Remote Branch                    : 
08-04 12:50:36.825  4016  4016 I Adreno  : Reconstruct Branch               : 
,08-04 12:50:36.880  4016  4016 I NSApplication: Starting up...
,08-04 12:50:36.886  4016  4063 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 12:50:36.899   876   886 I ActivityManager: Start proc 4068:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-04 12:50:36.900   876   886 I ActivityManager: Killing 3694:com.android.musicfx/u0a18 (adj 15): empty #17
,08-04 12:50:37.000  4068  4068 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-04 12:50:37.208   876   887 I ActivityManager: Killing 3448:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-04 12:50:38.040   876  1715 D WifiService: setWifiEnabled: true pid=3854, uid=10000
08-04 12:50:38.041   876  1715 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:50:38.057   876  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-04 12:50:38.061  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:38.061  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:38.061  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:38.061  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:38.062  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:38.062  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:38.062  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:38.062  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:38.089   876  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-04 12:50:38.089   876  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 12:50:38.090   876  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-04 12:50:38.093   876  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 12:50:38.094   876  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 12:50:38.094   876  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-04 12:50:38.094   876  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 12:50:38.094   876  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 12:50:38.113   876  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-04 12:50:38.114   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 12:50:38.116   372   874 D CommandListener: Setting iface cfg
,08-04 12:50:38.125   876  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-04 12:50:38.126   876  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 12:50:38.128   876  1312 E native  : do suspend true
,08-04 12:50:38.143   876  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:50:38.144   876  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 12:50:38.150   876  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 12:50:39.514   876  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:50:39.591   876  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.19 rxSuccessRate=11.69 delta 1000 -> 994
,08-04 12:50:39.593   876  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-04 12:50:39.593   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:50:39.610   876  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 12:50:39.666   876  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 12:50:39.668  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 12:50:40.095  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 12:50:40.134  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 12:50:40.135  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 12:50:40.140   876  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:50:40.151   876  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:50:40.151   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:50:40.151   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-04 12:50:40.167   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:50:40.183   372   874 D CommandListener: Setting iface cfg
,08-04 12:50:40.184   876  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,08-04 12:50:40.191   876  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 12:50:40.227   876  4092 D DhcpClient: Receive thread started
,08-04 12:50:40.307   876  1312 E native  : do suspend false
,08-04 12:50:40.316   876  2117 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 12:50:40.328   876  4092 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172420, domain null
,08-04 12:50:40.328   876  2117 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172420 seconds
,08-04 12:50:40.331   876  2117 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 12:50:40.344   876  4092 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-04 12:50:40.345   876  2117 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 12:50:40.349   372   874 D CommandListener: Setting iface cfg
,08-04 12:50:40.353   876  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 12:50:40.355   876  1312 E native  : do suspend true
,08-04 12:50:40.357   876  2117 D DhcpClient: Scheduling renewal in 86399s
,08-04 12:50:40.365   876  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 12:50:40.365   876  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 12:50:40.367   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 12:50:40.368   876  1314 D ConnectivityService: Adding iface wlan0 to network 101
08-04 12:50:40.370   876  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 12:50:40.440   876  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 12:50:40.440   876  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-04 12:50:40.444   876  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-04 12:50:40.448   876  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-04 12:50:40.451   876  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-04 12:50:40.463   876  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 12:50:40.469   876  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-04 12:50:40.469   876  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-04 12:50:40.470   876  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-04 12:50:40.470   876  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:50:40.471   876  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-04 12:50:40.471   876  1314 D ConnectivityService:    accepting network in place of null
08-04 12:50:40.472   876  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:50:40.482   876  4091 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404092, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 12:50:40.519   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:40.549   876  4090 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:50:40.554   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:40.564   876  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 12:50:40.564   876  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:40.572   876  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-04 12:50:40.599  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:40.599  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:50:40.599  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:40.599  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:40.602  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:40.602  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:50:40.602  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:40.602  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:50:40.603   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:50:40.618  1939  1939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:50:40.621  1939  1939 D SystemUpdateService: onCreate
,08-04 12:50:40.625  1939  1939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-04 12:50:40.627  1939  4102 I SystemUpdateService: active receiver: enabled
,08-04 12:50:40.631  1939  4102 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:50:40.635  1939  4102 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-04 12:50:40.636  1939  4102 I SystemUpdateService: now status is 0 (complete)
08-04 12:50:40.636  1939  4102 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:50:40.636  1939  4102 I SystemUpdateService: file has been verified
08-04 12:50:40.636  1939  4102 I SystemUpdateService: OTA package size = 12249756
,08-04 12:50:40.640  1939  4102 I SystemUpdateService: showing system update notification
,08-04 12:50:40.645  1939  1939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 12:50:40.648  1939  2404 I iu.UploadsManager: num queued entries: 0
,08-04 12:50:40.649  1939  2404 I iu.UploadsManager: num updated entries: 0
,08-04 12:50:40.650  1939  1939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-04 12:50:40.651   876  4090 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 10:50:40 GMT], X-Android-Received-Millis=[1470307840651], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470307840610]}
08-04 12:50:40.651  1939  4105 I MDM     : [222] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-04 12:50:40.652  1939  4105 W BaseAppContext: Using Auth Proxy for data requests.
08-04 12:50:40.652  1939  1939 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-04 12:50:40.653   876  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-04 12:50:40.653   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-04 12:50:40.653  1939  4105 V GoogleAuthProtoRequest: [222] a.<init>: mAccountName set to: thalitester@gmail.com
08-04 12:50:40.653   876  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 12:50:40.654   876  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 12:50:40.655  3989  3989 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:40.657  1939  2404 I iu.SyncManager: NEXT; no task
,08-04 12:50:40.660  3989  3989 D SprintDMHelper: simOperator: 
08-04 12:50:40.660  3989  3989 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-04 12:50:40.660  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:50:40.661  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:50:40.666  1939  1939 D SystemUpdateService: onDestroy
,08-04 12:50:40.692  1511  3790 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-04 12:50:40.692  1511  3790 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 12:50:40.692  1511  3790 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-04 12:50:40.692  1511  3790 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:50:40.707  1939  4105 E MDM     : [222] SitrepService.a: Error sending sitrep.
,08-04 12:50:40.710  3960  3960 I art     : Waiting for a blocking GC DisableMovingGc
,08-04 12:50:40.713  3960  3960 I art     : Starting a blocking GC DisableMovingGc
,08-04 12:50:40.851  3960  4110 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 12:50:40.858   876   887 I ActivityManager: Killing 3639:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-04 12:50:41.046   876  1749 D WifiService: setWifiEnabled: false pid=3854, uid=10000
,08-04 12:50:41.046   876  1749 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:50:41.083  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 12:50:41.087   876  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-04 12:50:41.087   876  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-04 12:50:41.088   876  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:50:41.088   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:50:41.097   876  1312 E native  : do suspend true
,08-04 12:50:41.107   876  2117 D DhcpClient: Clearing IP address
,08-04 12:50:41.108   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-04 12:50:41.111   372   874 D CommandListener: Setting iface cfg
,08-04 12:50:41.115   876  4092 D DhcpClient: Receive thread stopped
08-04 12:50:41.116  1511  4114 V NativeCrypto: Read error: ssl=0x99cb5400: I/O error during system call, Connection timed out
08-04 12:50:41.119  1939  1939 I GCM     : Message from null null
08-04 12:50:41.119  1939  1939 E GCM     : Dropping message from null
08-04 12:50:41.119   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-04 12:50:41.119   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-04 12:50:41.123   876  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-04 12:50:41.124   876  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:50:41.124   876  1312 E native  : do suspend true
08-04 12:50:41.124   416   416 E Parcel  : Reading a NULL string not supported here.
08-04 12:50:41.128   876  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-04 12:50:41.128  1511  4114 V NativeCrypto: SSL shutdown failed: ssl=0x99cb5400: I/O error during system call, Broken pipe
,08-04 12:50:41.166   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:41.213   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:41.214   876  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 12:50:41.214   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-04 12:50:41.214   876  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:41.216   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:50:41.219  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:41.219  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:41.220  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:41.220  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:41.221  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:41.221  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:41.221  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:41.221  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:41.228  1939  1939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:50:41.233  1939  1939 D SystemUpdateService: onCreate
08-04 12:50:41.236  1939  1939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:50:41.246  1939  1939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 12:50:41.247  1939  2404 I iu.UploadsManager: num queued entries: 0
08-04 12:50:41.248  1939  2404 I iu.UploadsManager: num updated entries: 0
08-04 12:50:41.248  1939  2404 I iu.SyncManager: NEXT; no task
,08-04 12:50:41.253  1939  4125 I SystemUpdateService: active receiver: enabled
,08-04 12:50:41.255  1939  1939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:50:41.256  1939  1939 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:50:41.258  3989  3989 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:41.280  1939  4125 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:50:41.288  1939  4125 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 12:50:41.288  1939  4125 I SystemUpdateService: now status is 0 (complete)
,08-04 12:50:41.288  1939  4125 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:50:41.290  1939  4125 I SystemUpdateService: file has been verified
08-04 12:50:41.290  1939  4125 I SystemUpdateService: OTA package size = 12249756
08-04 12:50:41.291  3989  3989 D SprintDMHelper: simOperator: 
08-04 12:50:41.291  3989  3989 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-04 12:50:41.291   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-04 12:50:41.293   876  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-04 12:50:41.294   876  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:50:41.310   876  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-04 12:50:41.313  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:41.313  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:41.313  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:41.313  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:41.314  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:41.314  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:41.314  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:41.315  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:41.317   876  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 12:50:41.317  1836  2059 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:50:41.344  3960  4130 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-04 12:50:41.347  1939  4125 I SystemUpdateService: showing system update notification
,08-04 12:50:41.354  1939  1939 D SystemUpdateService: onDestroy
,08-04 12:50:41.562   876  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 12:50:44.102   876   893 I ActivityManager: Start proc 4133:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 12:50:44.248  4133  4133 D AdapterServiceConfig: Adding HeadsetService
,08-04 12:50:44.248  4133  4133 D AdapterServiceConfig: Adding A2dpService
08-04 12:50:44.249  4133  4133 D AdapterServiceConfig: Adding HidService
08-04 12:50:44.249  4133  4133 D AdapterServiceConfig: Adding HealthService
08-04 12:50:44.249  4133  4133 D AdapterServiceConfig: Adding PanService
,08-04 12:50:44.249  4133  4133 D AdapterServiceConfig: Adding GattService
08-04 12:50:44.249  4133  4133 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 12:50:44.265   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d4a81e:true
,08-04 12:50:44.266  4133  4133 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 12:50:44.274  4133  4145 I BluetoothAdapterState: Entering OffState
,08-04 12:50:44.274  4133  4133 I bt_bluedroid: init
,08-04 12:50:44.279  4133  4146 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 12:50:44.279  4133  4146 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 12:50:44.280  4133  4146 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 12:50:44.280  4133  4146 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 12:50:44.282  4133  4133 I bt_bluedroid: get_profile_interface socket
,08-04 12:50:44.285  4133  4149 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:50:44.286  4133  4133 I bt_bluedroid: get_profile_interface sdp
,08-04 12:50:44.288  4133  4149 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:50:44.292  4133  4144 I bt_bluedroid: config_hci_snoop_log
,08-04 12:50:44.295   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 12:50:44.303  4133  4145 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 12:50:44.304  4133  4145 D BluetoothAdapterProperties: Setting state to 14
,08-04 12:50:44.304  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 12:50:44.306  4133  4145 D BluetoothBondStateMachine: make
,08-04 12:50:44.310  4133  4150 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 12:50:44.314  4133  4145 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:50:44.317  4133  4133 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 12:50:44.326  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:44.327  4133  4133 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:50:44.328  4133  4133 D BtGatt.GattService: Received start request. Starting profile...
08-04 12:50:44.329  4133  4133 D BtGatt.GattService: start()
08-04 12:50:44.329  4133  4133 I bt_bluedroid: get_profile_interface gatt
,08-04 12:50:44.331  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:44.332  4133  4133 D BtGatt.AdvertiseManager: advertise manager created
,08-04 12:50:44.348  4133  4133 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:44.348  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:44.348  4133  4133 V BluetoothAdapterState: isBleTurningOn()=true
08-04 12:50:44.349  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:44.349  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-04 12:50:44.350  4133  4145 I bt_bluedroid: enable
08-04 12:50:44.350  4133  4146 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-04 12:50:44.351  4133  4146 I bt_hci  : start_up
,08-04 12:50:44.359  4133  4146 I bt_vendor: alloc value 0xb3a31189
,08-04 12:50:44.359  4133  4146 I bt_vendor: init
08-04 12:50:44.359  4133  4146 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 12:50:44.359  4133  4146 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 12:50:44.466  4133  4146 D bt_hci  : start_up starting async portion
,08-04 12:50:44.467  4133  4153 I bt_hci  : event_finish_startup
08-04 12:50:44.467  4133  4153 I bt_hci_h4: hal_open
08-04 12:50:44.468  4133  4153 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 12:50:44.475  4133  4153 I bt_userial_vendor: device fd = 51 open
,08-04 12:50:44.510  4133  4153 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:50:44.542  4133  4153 D bt_hwcfg: Chipset BCM4354A2
08-04 12:50:44.542  4133  4153 D bt_hwcfg: Target name = [BCM4354A2]
,08-04 12:50:44.543  4133  4153 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 12:50:45.199  4133  4153 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 12:50:45.200  4133  4153 D bt_hwcfg: Settlement delay -- 100 ms
08-04 12:50:45.200  4133  4153 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 12:50:45.317  4133  4153 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:50:45.319  4133  4153 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 12:50:45.348  4133  4153 I bt_hwcfg: vendor lib fwcfg completed
,08-04 12:50:45.348  4133  4153 I bt_vendor: firmware callback
08-04 12:50:45.348  4133  4153 I bt_hci  : firmware_config_callback
,08-04 12:50:45.361  4133  4155 I bt_btu  : btu_task pending for preload complete event
,08-04 12:50:45.361  4133  4155 I bt_btu_task: Bluetooth chip preload is complete
08-04 12:50:45.361  4133  4155 I bt_btu  : btu_task received preload complete event
,08-04 12:50:45.373  4133  4155 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 12:50:45.373  4133  4155 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 12:50:45.373  4133  4155 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 12:50:45.373  4133  4155 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-04 12:50:45.374  4133  4155 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 12:50:45.374  4133  4155 I         : BTE_InitTraceLevels -- TRC_A2D
,08-04 12:50:45.375  4133  4155 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 12:50:45.375  4133  4155 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 12:50:45.376  4133  4155 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 12:50:45.376  4133  4155 I         : BTE_InitTraceLevels -- TRC_PAN
,08-04 12:50:45.377  4133  4155 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 12:50:45.377  4133  4155 I         : BTE_InitTraceLevels -- TRC_GATT
,08-04 12:50:45.377  4133  4155 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 12:50:45.377  4133  4155 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-04 12:50:45.378  4133  4155 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 12:50:45.512  4133  4155 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39aed9d
,08-04 12:50:45.513  4133  4155 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39aed9d 
,08-04 12:50:45.539  4133  4149 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 12:50:45.540  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:50:45.541  4133  4149 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:50:45.546  4133  4149 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:50:45.551  4133  4149 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:50:45.552  4133  4149 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 12:50:45.553  4133  4149 D bt_hci  : do_postload posting postload work item
08-04 12:50:45.553  4133  4153 I bt_hci  : event_postload
08-04 12:50:45.553  4133  4153 I bt_vendor: sco_config_cb
,08-04 12:50:45.553  4133  4153 I bt_hci  : sco_config_callback postload finished.
08-04 12:50:45.554  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:45.559  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:45.559  4133  4149 D bt_bte_conf: Device ID record 1 : primary
08-04 12:50:45.559  4133  4149 D bt_bte_conf:   vendorId            = 000f
08-04 12:50:45.559  4133  4149 D bt_bte_conf:   vendorIdSource      = 0001
08-04 12:50:45.560  4133  4149 D bt_bte_conf:   product             = 1200
08-04 12:50:45.560  4133  4149 D bt_bte_conf:   version             = 1436
08-04 12:50:45.560  4133  4149 D bt_bte_conf:   clientExecutableURL = 
,08-04 12:50:45.560  4133  4149 D bt_bte_conf:   serviceDescription  = 
08-04 12:50:45.561  4133  4149 D bt_bte_conf:   documentationURL    = 
08-04 12:50:45.561  4133  4149 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 12:50:45.562  4133  4146 D bt_stack_manager: event_start_up_stack finished
08-04 12:50:45.564  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 12:50:45.565  4133  4145 D BluetoothAdapterProperties: Setting state to 15
08-04 12:50:45.565  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-04 12:50:45.566  4133  4145 I BluetoothAdapterState: Entering BleOnState
,08-04 12:50:45.570  4133  4153 I bt_vendor: low_power_mode_cb
,08-04 12:50:45.573  4133  4145 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-04 12:50:45.573  4133  4145 D BluetoothAdapterProperties: Setting state to 11
08-04 12:50:45.573  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 12:50:45.578  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:45.579  4133  4133 D HeadsetService: Received start request. Starting profile...
08-04 12:50:45.582  4133  4133 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 12:50:45.582  4133  4133 D HeadsetStateMachine: make
,08-04 12:50:45.591  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:45.593  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:45.597  4133  4133 D HeadsetStateMachine: max_hf_connections = 1
,08-04 12:50:45.597  4133  4133 I bt_bluedroid: get_profile_interface handsfree
08-04 12:50:45.598  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 12:50:45.598  4133  4149 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 12:50:45.601  4133  4145 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:50:45.603  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:45.604  4133  4133 D A2dpService: Received start request. Starting profile...
08-04 12:50:45.604  4133  4133 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 12:50:45.605  4133  4133 I bt_bluedroid: get_profile_interface avrcp
,08-04 12:50:45.611  4133  4133 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 12:50:45.612  4133  4133 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 12:50:45.612  4133  4133 D A2dpStateMachine: make
08-04 12:50:45.613  4133  4133 I bt_bluedroid: get_profile_interface a2dp
,08-04 12:50:45.613  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 12:50:45.615  4133  4165 D A2dpStateMachine: Enter Disconnected: -2
,08-04 12:50:45.616  4133  4133 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 12:50:45.617  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:45.618  4133  4133 D HidService: Received start request. Starting profile...
,08-04 12:50:45.619  4133  4133 I bt_bluedroid: get_profile_interface hidhost
08-04 12:50:45.619  4133  4149 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39903e5
08-04 12:50:45.619  4133  4133 D HidService: setHidService(): set to: null
08-04 12:50:45.619  3908  3908 D BluetoothInputDevice: Proxy object connected
08-04 12:50:45.619  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 12:50:45.619  4133  4133 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 12:50:45.620  3908  3908 D HidProfile: Bluetooth service connected
08-04 12:50:45.620  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:45.621  4133  4133 D HealthService: Received start request. Starting profile...
08-04 12:50:45.623  4133  4133 I bt_bluedroid: get_profile_interface health
,08-04 12:50:45.626  4133  4133 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 12:50:45.627  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:45.627  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:45.628  4133  4133 D PanService: Received start request. Starting profile...
08-04 12:50:45.628  4133  4133 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 12:50:45.628  4133  4133 I bt_bluedroid: get_profile_interface pan
08-04 12:50:45.629  4133  4149 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 12:50:45.631  4133  4133 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:45.631  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:50:45.632  3908  3908 D PanProfile: Bluetooth service connected
08-04 12:50:45.632  3908  3908 D BluetoothMap: Proxy object connected
08-04 12:50:45.632  4133  4133 D BluetoothMapService: Received start request. Starting profile...
08-04 12:50:45.632  4133  4133 D BluetoothMapService: start()
,08-04 12:50:45.633  3908  3908 D MapProfile: Bluetooth service connected
08-04 12:50:45.633  3908  3908 D BluetoothMap: getConnectedDevices()
,08-04 12:50:45.634  3908  3908 D BluetoothMap: Bluetooth is Not enabled
08-04 12:50:45.635  4133  4133 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 12:50:45.636  4133  4133 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-04 12:50:45.636  4133  4133 D BluetoothMapAppObserver: createReceiver()
,08-04 12:50:45.637  4133  4133 D BluetoothMapAppObserver: initObservers()
,08-04 12:50:45.637  4133  4133 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 12:50:45.643  4133  4133 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:45.643  4133  4133 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:45.643  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:45.643  4133  4161 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 12:50:45.643  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:45.645  4133  4133 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:45.646  4133  4133 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:45.646  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:45.646  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:45.648  4133  4133 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:45.648  4133  4133 V BluetoothAdapterState: isTurningOn()=true
,08-04 12:50:45.648  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:45.648  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:45.649  4133  4133 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:45.649  4133  4133 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:45.649  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:45.649  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:45.649  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 12:50:45.649  4133  4145 D BluetoothAdapterProperties: ScanMode =  20
,08-04 12:50:45.650  4133  4145 D BluetoothAdapterProperties: State =  11
08-04 12:50:45.650  4133  4145 D BluetoothAdapterProperties: Setting state to 12
08-04 12:50:45.650  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 12:50:45.651  1727  1742 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:45.652  4133  4145 I BluetoothAdapterState: Entering OnState
,08-04 12:50:45.652  1356  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:50:45.653  4133  4149 D BluetoothAdapterProperties: Scan Mode:21
,08-04 12:50:45.653  4133  4149 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 12:50:45.654  1356  1376 D BluetoothMap: onBluetoothStateChange: up=true
08-04 12:50:45.655  1356  1356 D BluetoothA2dp: Proxy object connected
08-04 12:50:45.657  3908  3919 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 12:50:45.657  1356  1356 D BluetoothMap: Proxy object connected
,08-04 12:50:45.657  1356  1356 D MapProfile: Bluetooth service connected
08-04 12:50:45.657  1356  1376 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:50:45.657  1356  1356 D BluetoothMap: getConnectedDevices()
,08-04 12:50:45.657  3854  3854 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:45.657  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:45.659  3908  3920 D BluetoothMap: onBluetoothStateChange: up=true
08-04 12:50:45.660   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:45.660  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:45.660  1356  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:50:45.661  3908  3919 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 12:50:45.661  1356  1356 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:50:45.661  1356  1356 D PanProfile: Bluetooth service connected
08-04 12:50:45.662   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:50:45.663   876   876 D BluetoothA2dp: Proxy object connected
08-04 12:50:45.663  3908  3920 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:50:45.663   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:45.664  1356  1834 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:45.664  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:45.665   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:50:45.666  1356  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 12:50:45.667  4133  4133 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:50:45.668  1356  1356 D BluetoothInputDevice: Proxy object connected
,08-04 12:50:45.669  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:45.668  1356  1356 D HidProfile: Bluetooth service connected
,08-04 12:50:45.670  4133  4133 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-04 12:50:45.671   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 12:50:45.674  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:45.675  4133  4133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:50:45.675  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:45.677  3908  3908 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 12:50:45.677  4133  4133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:50:45.679  4133  4133 D ObexServerSockets: Succeed to create listening sockets 
,08-04 12:50:45.679  4133  4133 D ObexServerSockets0: startAccept()
08-04 12:50:45.679  4133  4133 D ObexServerSockets0: prepareForNewConnect()
08-04 12:50:45.680  3908  3908 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-04 12:50:45.681  4133  4133 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 12:50:45.681  4133  4133 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-04 12:50:45.682  4133  4133 D BluetoothMapService: onReceive
08-04 12:50:45.683  4133  4133 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 12:50:45.683  4133  4133 D BluetoothMapService: STATE_ON
,08-04 12:50:45.685  4133  4171 D ObexServerSockets0: Accepting socket connection...
08-04 12:50:45.685  4133  4170 D ObexServerSockets0: Accepting socket connection...
,08-04 12:50:45.690  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:50:45.693  3908  3908 D BluetoothA2dp: Proxy object connected
,08-04 12:50:45.696  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:45.700  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:50:45.703  1356  1356 D BluetoothPbap: Proxy object connected
,08-04 12:50:45.703  1356  1356 D PbapServerProfile: Bluetooth service connected
08-04 12:50:45.704  3908  3908 D BluetoothPbap: Proxy object connected
08-04 12:50:45.704  3908  3908 D PbapServerProfile: Bluetooth service connected
,08-04 12:50:45.708  4133  4133 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 12:50:45.708  4133  4133 D ObexServerSockets0: prepareForNewConnect()
08-04 12:50:45.710  4133  4175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:50:45.727  4133  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:50:45.729  4133  4179 I BtOppRfcommListener: Accept thread started.
,08-04 12:50:45.754   876   876 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.755  1356  1834 D BluetoothHeadset: Proxy object connected
08-04 12:50:45.755   876   876 D BluetoothHeadset: Proxy object connected
08-04 12:50:45.755  1356  1356 D HeadsetProfile: Bluetooth service connected
,08-04 12:50:45.755  1727  1741 D BluetoothHeadset: Proxy object connected
08-04 12:50:45.756   876   876 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.760   876   893 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.761  1356  1367 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.762  1356  1356 D HeadsetProfile: Bluetooth service connected
,08-04 12:50:45.764   876   893 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.765   876   893 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.786  3908  3919 D BluetoothHeadset: Proxy object connected
,08-04 12:50:45.787  3908  3908 D HeadsetProfile: Bluetooth service connected
,08-04 12:50:45.890  1511  2229 I art     : Waiting for a blocking GC DisableMovingGc
,08-04 12:50:45.896  1511  2229 I art     : WaitForGcToComplete blocked for 5.900ms for cause DisableMovingGc
,08-04 12:50:45.896  1511  2229 I art     : Starting a blocking GC DisableMovingGc
,08-04 12:50:47.064  4133  4145 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 12:50:47.064  4133  4145 D BluetoothAdapterProperties: Setting state to 13
,08-04 12:50:47.065  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-04 12:50:47.069  4133  4145 D BluetoothAdapterProperties: onBluetoothDisable()
,08-04 12:50:47.075  4133  4145 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:50:47.075  4133  4133 D BluetoothMapService: onReceive
,08-04 12:50:47.076  4133  4133 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 12:50:47.076  4133  4133 D BluetoothMapService: STATE_TURNING_OFF
08-04 12:50:47.077  4133  4133 D BluetoothMapService: MAP Service closeService in
08-04 12:50:47.077  4133  4133 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 12:50:47.077  4133  4133 D ObexServerSockets0: shutdown(block = true)
08-04 12:50:47.078  4133  4170 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-04 12:50:47.083  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:47.083  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:47.085  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:47.086  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:47.087  4133  4133 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:50:47.087  4133  4157 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 12:50:47.088  4133  4171 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 12:50:47.088  4133  4133 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:50:47.089  4133  4133 I BtOppRfcommListener: stopping Accept Thread
08-04 12:50:47.090  4133  4179 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 12:50:47.091  4133  4179 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 12:50:47.092  4133  4149 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:50:47.093  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 12:50:47.093  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:47.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:50:47.095  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Check,ing support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:50:47.095  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:47.095  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:50:47.098  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:47.100  4133  4133 D HeadsetService: Received stop request...Stopping profile...
08-04 12:50:47.101  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:47.103  4133  4133 D A2dpService: Received stop request...Stopping profile...
08-04 12:50:47.103   876   876 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:47.103  4133  4165 D A2dpStateMachine: Exit Disconnected: -1
08-04 12:50:47.103  1356  1376 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:47.103   876   876 D BluetoothHeadset: Proxy object disconnected
,08-04 12:50:47.104  1727  1879 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:47.104  1356  1356 D HeadsetProfile: Bluetooth service disconnected
08-04 12:50:47.104   876   876 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:47.104  3908  3920 D BluetoothHeadset: Proxy object disconnected
08-04 12:50:47.105  4133  4133 V BluetoothAdapterState: isTurningOff()=true
,08-04 12:50:47.105  1356  1356 D BluetoothA2dp: Proxy object disconnected
08-04 12:50:47.105   876   876 D BluetoothA2dp: Proxy object disconnected
08-04 12:50:47.105  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.105  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:47.105  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:47.108  4133  4133 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-04 12:50:47.108  4133  4133 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 12:50:47.108  4133  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:47.108  4133  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:47.109  4133  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:47.109  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 12:50:47.109  4133  4149 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-04 12:50:47.109  4133  4133 D HidService: Received stop request...Stopping profile...
,08-04 12:50:47.109  4133  4133 D HidService: Stopping Bluetooth HidService
08-04 12:50:47.110  1356  1356 D BluetoothInputDevice: Proxy object disconnected
08-04 12:50:47.110  1356  1356 D HidProfile: Bluetooth service disconnected
08-04 12:50:47.111  3908  3908 D DockEventReceiver: finishStartingService: stopping service
08-04 12:50:47.111  4133  4133 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:47.111  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.111  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:50:47.111  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:47.111  4133  4133 D HealthService: Received stop request...Stopping profile...
08-04 12:50:47.111  3908  3908 D BluetoothA2dp: Proxy object disconnected
,08-04 12:50:47.112  3908  3908 D HeadsetProfile: Bluetooth service disconnected
08-04 12:50:47.112  3908  3908 D BluetoothInputDevice: Proxy object disconnected
,08-04 12:50:47.112  3908  3908 D HidProfile: Bluetooth service disconnected
08-04 12:50:47.115  4133  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:50:47.115  4133  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:50:47.115  4133  4155 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-04 12:50:47.115  4133  4155 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:50:47.115  4133  4155 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:50:47.115  4133  4155 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-04 12:50:47.115  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-04 12:50:47.116  4133  4133 D PanService: Received stop request...Stopping profile...
08-04 12:50:47.117  3908  3908 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 12:50:47.117  3908  3908 D PanProfile: Bluetooth service disconnected
08-04 12:50:47.118  1356  1356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 12:50:47.118  1356  1356 D PanProfile: Bluetooth service disconnected
08-04 12:50:47.118  4133  4133 D BluetoothMapService: Received stop request...Stopping profile...
,08-04 12:50:47.118  4133  4133 D BluetoothMapService: stop()
,08-04 12:50:47.119  4133  4133 D BluetoothMapAppObserver: deinitObservers()
,08-04 12:50:47.119  4133  4133 D BluetoothMapAppObserver: removeReceiver()
,08-04 12:50:47.120  1356  1356 D BluetoothMap: Proxy object disconnected
08-04 12:50:47.120  1356  1356 D MapProfile: Bluetooth service disconnected
08-04 12:50:47.121  3908  3908 D BluetoothMap: Proxy object disconnected
08-04 12:50:47.121  3908  3908 D MapProfile: Bluetooth service disconnected
08-04 12:50:47.122  4133  4133 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:47.122  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.122  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:47.122  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:47.123  4133  4133 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 12:50:47.123  4133  4133 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 12:50:47.123  4133  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-04 12:50:47.123  4133  4133 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:47.123  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.123  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:47.123  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:47.124  4133  4133 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 12:50:47.124  4133  4149 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 12:50:47.124  4133  4133 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 12:50:47.124  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 12:50:47.124  4133  4133 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:47.124  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.124  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:47.124  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:47.125  4133  4133 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 12:50:47.125  4133  4133 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 12:50:47.127  4133  4133 D BluetoothMapService: MAP Service closeService in
08-04 12:50:47.127  4133  4133 V BluetoothAdapterState: isTurningOff()=true
08-04 12:50:47.127  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.127  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:47.127  4133  4133 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:47.127  4133  4133 D BluetoothMapService: cleanup()
08-04 12:50:47.128  4133  4133 D BluetoothMapService: MAP Service closeService in
08-04 12:50:47.128  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 12:50:47.128  4133  4145 D BluetoothAdapterProperties: Setting state to 15
08-04 12:50:47.128  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-04 12:50:47.129  4133  4145 I BluetoothAdapterState: Entering BleOnState
08-04 12:50:47.129  1356  1356 D BluetoothPbap: Proxy object disconnected
08-04 12:50:47.129  1356  1356 D PbapServerProfile: Bluetooth service disconnected
08-04 12:50:47.130  1727  1742 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:47.130  3908  3908 D BluetoothPbap: Proxy object disconnected
08-04 12:50:47.130  1356  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 12:50:47.130  3908  3908 D PbapServerProfile: Bluetooth service disconnected
08-04 12:50:47.133  3908  3920 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:50:47.134  3908  3919 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:47.135  1356  1376 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:50:47.135  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:50:47.136  1356  1834 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:50:47.137  3908  3919 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:50:47.137   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:47.137  1356  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 12:50:47.138  3908  3920 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:50:47.138   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:50:47.138  3908  3919 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:50:47.139   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:47.139  1356  1376 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:50:47.139   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:50:47.140  1356  1834 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:50:47.141  4133  4145 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-04 12:50:47.141  4133  4145 D BluetoothAdapterProperties: Setting state to 16
,08-04 12:50:47.141  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-04 12:50:47.143  4133  4145 D BluetoothAdapterProperties: onBleDisable
,08-04 12:50:47.143  4133  4146 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 12:50:47.143  4133  4145 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:50:47.145  4133  4149 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:50:47.145  4133  4155 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 12:50:47.146  4133  4155 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-04 12:50:47.146  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:47.147  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:47.148  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:50:47.148  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:47.150  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:47.153  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:47.157  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:50:47.346  4133  4149 I bt_hci  : shut_down
08-04 12:50:47.347  4133  4153 D bt_hwcfg: hw_epilog_process
,08-04 12:50:47.347  4133  4153 I bt_vendor: low_power_mode_cb
,08-04 12:50:47.378  4133  4153 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-04 12:50:47.378  4133  4153 I bt_vendor: epilog_cb
08-04 12:50:47.378  4133  4153 I bt_hci  : epilog_finished_callback
,08-04 12:50:47.388  4133  4149 I bt_hci_h4: hal_close
,08-04 12:50:47.389  4133  4149 I bt_userial_vendor: device fd = 51 close
,08-04 12:50:47.513  4133  4146 D bt_stack_manager: event_shut_down_stack finished.
,08-04 12:50:47.514  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 12:50:47.520  4133  4145 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-04 12:50:47.521  4133  4133 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:50:47.522  4133  4133 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 12:50:47.523  4133  4133 D BtGatt.GattService: stop()
08-04 12:50:47.523  4133  4133 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 12:50:47.527  4133  4133 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:47.528  4133  4133 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:47.528  4133  4133 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:50:47.528  4133  4133 V BluetoothAdapterState: isBleTurningOff()=true
08-04 12:50:47.529  4133  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-04 12:50:47.530  4133  4145 D BluetoothAdapterProperties: Setting state to 10
08-04 12:50:47.530  4133  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-04 12:50:47.531  4133  4145 I BluetoothAdapterState: Entering OffState
08-04 12:50:47.533   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-04 12:50:47.562  4133  4133 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-04 12:50:47.562  4133  4133 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-04 12:50:47.563  4133  4146 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 12:50:47.572  4133  4146 D bt_stack_manager: event_clean_up_stack finished.
,08-04 12:50:47.573  4133  4133 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 12:50:47.579  4133  4133 I art     : System.exit called, status: 0
,08-04 12:50:47.579  4133  4133 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 12:50:47.620   876   886 I ActivityManager: Process com.android.bluetooth (pid 4133) has died
,08-04 12:50:48.477   876  1314 D ConnectivityService: handlePromptUnvalidated 101
,08-04 12:50:50.061  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:50:50.061  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:53.069  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:50:53.070  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8adcf3 added. We now have 6 listener(s)
08-04 12:50:53.070  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:53.074  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:50:53.075  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@644db0 added. We now have 7 listener(s)
,08-04 12:50:53.075  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:53.077  3854  3901 I System.out: IsBluetoothEnabled
,08-04 12:50:53.088  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:53.126   876   893 I ActivityManager: Start proc 4189:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 12:50:53.298  4189  4189 D AdapterServiceConfig: Adding HeadsetService
08-04 12:50:53.298  4189  4189 D AdapterServiceConfig: Adding A2dpService
,08-04 12:50:53.298  4189  4189 D AdapterServiceConfig: Adding HidService
08-04 12:50:53.299  4189  4189 D AdapterServiceConfig: Adding HealthService
08-04 12:50:53.299  4189  4189 D AdapterServiceConfig: Adding PanService
08-04 12:50:53.299  4189  4189 D AdapterServiceConfig: Adding GattService
08-04 12:50:53.299  4189  4189 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 12:50:53.314  4189  4189 D BluetoothAdapterState: make() - Creating AdapterState
08-04 12:50:53.314   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e521d63:true
,08-04 12:50:53.319  4189  4189 I bt_bluedroid: init
,08-04 12:50:53.321  4189  4201 I BluetoothAdapterState: Entering OffState
,08-04 12:50:53.323  4189  4202 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 12:50:53.323  4189  4202 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 12:50:53.323  4189  4202 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 12:50:53.323  4189  4202 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 12:50:53.324  4189  4189 I bt_bluedroid: get_profile_interface socket
08-04 12:50:53.326  4189  4189 I bt_bluedroid: get_profile_interface sdp
,08-04 12:50:53.330  4189  4205 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:50:53.330  4189  4200 I bt_bluedroid: config_hci_snoop_log
,08-04 12:50:53.336   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-04 12:50:53.337  4189  4205 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:50:53.344  4189  4201 D BluetoothAdapterState: Current state: OFF, message: 0
08-04 12:50:53.345  4189  4201 D BluetoothAdapterProperties: Setting state to 14
,08-04 12:50:53.345  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 12:50:53.350  4189  4201 D BluetoothBondStateMachine: make
,08-04 12:50:53.354  4189  4206 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 12:50:53.363  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:50:53.367  4189  4189 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 12:50:53.377  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:53.378  4189  4189 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:50:53.381  4189  4189 D BtGatt.GattService: Received start request. Starting profile...
,08-04 12:50:53.382  4189  4189 D BtGatt.GattService: start()
08-04 12:50:53.382  4189  4189 I bt_bluedroid: get_profile_interface gatt
,08-04 12:50:53.385  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:53.385  4189  4189 D BtGatt.AdvertiseManager: advertise manager created
,08-04 12:50:53.399  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:53.399  4189  4189 V BluetoothAdapterState: isTurningOn()=false
08-04 12:50:53.399  4189  4189 V BluetoothAdapterState: isBleTurningOn()=true
,08-04 12:50:53.399  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:53.400  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-04 12:50:53.401  4189  4201 I bt_bluedroid: enable
08-04 12:50:53.401  4189  4202 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-04 12:50:53.402  4189  4202 I bt_hci  : start_up
,08-04 12:50:53.418  4189  4202 I bt_vendor: alloc value 0xb3a31189
,08-04 12:50:53.419  4189  4202 I bt_vendor: init
08-04 12:50:53.419  4189  4202 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 12:50:53.419  4189  4202 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 12:50:53.529  4189  4202 D bt_hci  : start_up starting async portion
,08-04 12:50:53.530  4189  4209 I bt_hci  : event_finish_startup
08-04 12:50:53.530  4189  4209 I bt_hci_h4: hal_open
08-04 12:50:53.530  4189  4209 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 12:50:53.544  4189  4209 I bt_userial_vendor: device fd = 51 open
,08-04 12:50:53.572  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:50:53.603  4189  4209 D bt_hwcfg: Chipset BCM4354A2
,08-04 12:50:53.603  4189  4209 D bt_hwcfg: Target name = [BCM4354A2]
,08-04 12:50:53.604  4189  4209 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 12:50:54.491  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 12:50:54.493  4189  4209 D bt_hwcfg: Settlement delay -- 100 ms
08-04 12:50:54.493  4189  4209 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 12:50:54.611  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:50:54.612  4189  4209 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 12:50:54.641  4189  4209 I bt_hwcfg: vendor lib fwcfg completed
08-04 12:50:54.641  4189  4209 I bt_vendor: firmware callback
08-04 12:50:54.641  4189  4209 I bt_hci  : firmware_config_callback
,08-04 12:50:54.653  4189  4211 I bt_btu  : btu_task pending for preload complete event
,08-04 12:50:54.653  4189  4211 I bt_btu_task: Bluetooth chip preload is complete
08-04 12:50:54.654  4189  4211 I bt_btu  : btu_task received preload complete event
,08-04 12:50:54.666  4189  4211 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 12:50:54.666  4189  4211 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-04 12:50:54.666  4189  4211 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 12:50:54.667  4189  4211 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 12:50:54.667  4189  4211 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 12:50:54.667  4189  4211 I         : BTE_InitTraceLevels -- TRC_A2D
,08-04 12:50:54.667  4189  4211 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 12:50:54.668  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 12:50:54.668  4189  4211 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 12:50:54.668  4189  4211 I         : BTE_InitTraceLevels -- TRC_PAN
,08-04 12:50:54.668  4189  4211 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 12:50:54.669  4189  4211 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 12:50:54.669  4189  4211 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 12:50:54.669  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-04 12:50:54.669  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 12:50:54.819  4189  4211 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39aed9d
,08-04 12:50:54.820  4189  4211 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39aed9d 
,08-04 12:50:54.835  4189  4205 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 12:50:54.839  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:50:54.840  4189  4205 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:50:54.842  4189  4205 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:50:54.844  4189  4205 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:50:54.845  4189  4205 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 12:50:54.845  4189  4205 D bt_hci  : do_postload posting postload work item
08-04 12:50:54.845  4189  4209 I bt_hci  : event_postload
08-04 12:50:54.845  4189  4209 I bt_vendor: sco_config_cb
,08-04 12:50:54.845  4189  4209 I bt_hci  : sco_config_callback postload finished.
,08-04 12:50:54.849  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:54.850  4189  4205 D bt_bte_conf: Device ID record 1 : primary
,08-04 12:50:54.850  4189  4205 D bt_bte_conf:   vendorId            = 000f
,08-04 12:50:54.850  4189  4205 D bt_bte_conf:   vendorIdSource      = 0001
,08-04 12:50:54.851  4189  4205 D bt_bte_conf:   product             = 1200
,08-04 12:50:54.851  4189  4205 D bt_bte_conf:   version             = 1436
,08-04 12:50:54.851  4189  4205 D bt_bte_conf:   clientExecutableURL = 
08-04 12:50:54.851  4189  4205 D bt_bte_conf:   serviceDescription  = 
,08-04 12:50:54.851  4189  4205 D bt_bte_conf:   documentationURL    = 
,08-04 12:50:54.852  4189  4205 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 12:50:54.852  4189  4202 D bt_stack_manager: event_start_up_stack finished
,08-04 12:50:54.853  4189  4209 I bt_vendor: low_power_mode_cb
,08-04 12:50:54.854  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-04 12:50:54.855  4189  4201 D BluetoothAdapterProperties: Setting state to 15
08-04 12:50:54.855  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-04 12:50:54.856  4189  4201 I BluetoothAdapterState: Entering BleOnState
08-04 12:50:54.863  4189  4201 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-04 12:50:54.863  4189  4201 D BluetoothAdapterProperties: Setting state to 11
08-04 12:50:54.863  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-04 12:50:54.876  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:54.882  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:54.883  4189  4189 D HeadsetService: Received start request. Starting profile...
,08-04 12:50:54.889  4189  4189 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 12:50:54.889  4189  4189 D HeadsetStateMachine: make
,08-04 12:50:54.895  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:50:54.902  4189  4189 D HeadsetStateMachine: max_hf_connections = 1
,08-04 12:50:54.902  4189  4189 I bt_bluedroid: get_profile_interface handsfree
08-04 12:50:54.903  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 12:50:54.903  4189  4205 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 12:50:54.907  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:54.908  4189  4189 D A2dpService: Received start request. Starting profile...
08-04 12:50:54.908  4189  4189 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 12:50:54.909  4189  4189 I bt_bluedroid: get_profile_interface avrcp
,08-04 12:50:54.914  4189  4189 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 12:50:54.914  4189  4189 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 12:50:54.914  4189  4189 D A2dpStateMachine: make
,08-04 12:50:54.915  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:54.918  4189  4189 I bt_bluedroid: get_profile_interface a2dp
,08-04 12:50:54.920  4189  4220 D A2dpStateMachine: Enter Disconnected: -2
,08-04 12:50:54.920  4189  4189 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 12:50:54.921  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:54.922  4189  4189 D HidService: Received start request. Starting profile...
08-04 12:50:54.922  4189  4189 I bt_bluedroid: get_profile_interface hidhost
08-04 12:50:54.922  4189  4189 D HidService: setHidService(): set to: null
08-04 12:50:54.919  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-04 12:50:54.923  4189  4189 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 12:50:54.923  4189  4205 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39903e5
08-04 12:50:54.924  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 12:50:54.924  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
08-04 12:50:54.925  4189  4189 D HealthService: Received start request. Starting profile...
,08-04 12:50:54.927  4189  4189 I bt_bluedroid: get_profile_interface health
,08-04 12:50:54.927  4189  4189 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 12:50:54.928  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:54.929  4189  4189 D PanService: Received start request. Starting profile...
08-04 12:50:54.929  4189  4189 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-04 12:50:54.929  4189  4189 I bt_bluedroid: get_profile_interface pan
08-04 12:50:54.930  4189  4205 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 12:50:54.932  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
08-04 12:50:54.933  4189  4189 D BluetoothMapService: Received start request. Starting profile...
08-04 12:50:54.933  4189  4189 D BluetoothMapService: start()
,08-04 12:50:54.935  4189  4189 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 12:50:54.936  4189  4189 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-04 12:50:54.936  4189  4189 D BluetoothMapAppObserver: createReceiver()
,08-04 12:50:54.937  4189  4189 D BluetoothMapAppObserver: initObservers()
08-04 12:50:54.937  4189  4189 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 12:50:54.946  4189  4218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 12:50:54.946  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:54.947  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:54.947  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:54.947  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:54.951  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:54.952  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:54.953  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-04 12:50:54.953  4189  4189 V BluetoothAdapterState: isTurningOn()=true
,08-04 12:50:54.953  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:50:54.953  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:50:54.953  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-04 12:50:54.953  4189  4201 D BluetoothAdapterProperties: ScanMode =  20
08-04 12:50:54.953  4189  4201 D BluetoothAdapterProperties: State =  11
08-04 12:50:54.954  4189  4201 D BluetoothAdapterProperties: Setting state to 12
08-04 12:50:54.954  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 12:50:54.955  1727  1741 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:54.957  4189  4205 D BluetoothAdapterProperties: Scan Mode:21
08-04 12:50:54.957  4189  4205 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:50:54.957  1356  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 12:50:54.958  4189  4201 I BluetoothAdapterState: Entering OnState
,08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:54.961  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:54.962  3908  3920 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:50:54.963  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:54.964  1356  1356 D BluetoothA2dp: Proxy object connected
,08-04 12:50:54.965  4189  4189 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:50:54.966  3908  3919 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:54.966  4189  4189 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-04 12:50:54.967  3908  3908 D BluetoothA2dp: Proxy object connected
08-04 12:50:54.968  1356  1376 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 12:50:54.969  4189  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:50:54.970  3908  3919 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 12:50:54.973  1356  1367 D BluetoothPan: onBluetoothStateChange on: true
,08-04 12:50:54.974  4189  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:50:54.975  4189  4189 D ObexServerSockets: Succeed to create listening sockets 
,08-04 12:50:54.975  4189  4189 D ObexServerSockets0: startAccept()
08-04 12:50:54.975  4189  4189 D ObexServerSockets0: prepareForNewConnect()
08-04 12:50:54.976  3908  4225 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 12:50:54.978  4189  4189 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-04 12:50:54.978  4189  4189 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-04 12:50:54.979  1356  1356 D BluetoothMap: Proxy object connected
08-04 12:50:54.979  1356  1356 D MapProfile: Bluetooth service connected
08-04 12:50:54.979  1356  1356 D BluetoothMap: getConnectedDevices()
,08-04 12:50:54.981  4189  4226 D ObexServerSockets0: Accepting socket connection...
08-04 12:50:54.982  4189  4227 D ObexServerSockets0: Accepting socket connection...
,08-04 12:50:54.982  3908  3908 D BluetoothMap: Proxy object connected
,08-04 12:50:54.982  3908  3908 D MapProfile: Bluetooth service connected
,08-04 12:50:54.982  3908  3908 D BluetoothMap: getConnectedDevices()
,08-04 12:50:54.983   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:54.984  1356  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:54.984  1356  1356 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:50:54.984  1356  1356 D PanProfile: Bluetooth service connected
08-04 12:50:54.984  3908  3920 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 12:50:54.986  3908  3908 D BluetoothInputDevice: Proxy object connected
,08-04 12:50:54.986  3908  3908 D HidProfile: Bluetooth service connected
,08-04 12:50:54.987   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:50:54.988  3908  3919 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:50:54.988   876   876 D BluetoothA2dp: Proxy object connected
08-04 12:50:54.991   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:54.991  1356  1367 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 12:50:54.992  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:50:54.992  3908  3908 D PanProfile: Bluetooth service connected
,08-04 12:50:54.993   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:50:54.994  1356  1834 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 12:50:54.996  1356  1356 D BluetoothInputDevice: Proxy object connected
,08-04 12:50:54.996  1356  1356 D HidProfile: Bluetooth service connected
,08-04 12:50:54.997   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
08-04 12:50:54.999  4189  4189 D BluetoothMapService: onReceive
08-04 12:50:54.999  4189  4189 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:50:55.000  4189  4189 D BluetoothMapService: STATE_ON
08-04 12:50:55.000  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:55.008  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:50:55.016  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:50:55.017  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:50:55.024  3908  3908 D BluetoothPbap: Proxy object connected
,08-04 12:50:55.024  3908  3908 D PbapServerProfile: Bluetooth service connected
08-04 12:50:55.024  4189  4189 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 12:50:55.024  4189  4189 D ObexServerSockets0: prepareForNewConnect()
08-04 12:50:55.026  1356  1356 D BluetoothPbap: Proxy object connected
08-04 12:50:55.026  1356  1356 D PbapServerProfile: Bluetooth service connected
,08-04 12:50:55.035  4189  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:50:55.059   876   876 D BluetoothHeadset: Proxy object connected
,08-04 12:50:55.059  4189  4237 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:50:55.060  1356  1376 D BluetoothHeadset: Proxy object connected
08-04 12:50:55.060  1356  1356 D HeadsetProfile: Bluetooth service connected
08-04 12:50:55.061   876   876 D BluetoothHeadset: Proxy object connected
,08-04 12:50:55.062  1727  1879 D BluetoothHeadset: Proxy object connected
08-04 12:50:55.062  4189  4237 I BtOppRfcommListener: Accept thread started.
08-04 12:50:55.063   876   876 D BluetoothHeadset: Proxy object connected
,08-04 12:50:55.064  3908  4225 D BluetoothHeadset: Proxy object connected
08-04 12:50:55.065  3908  3908 D HeadsetProfile: Bluetooth service connected
,08-04 12:50:55.067  3908  3919 D BluetoothHeadset: Proxy object connected
08-04 12:50:55.068  3908  3908 D HeadsetProfile: Bluetooth service connected
,08-04 12:50:55.084   876   893 D BluetoothHeadset: Proxy object connected
,08-04 12:50:55.085  1356  1834 D BluetoothHeadset: Proxy object connected
08-04 12:50:55.086  1356  1356 D HeadsetProfile: Bluetooth service connected
,08-04 12:50:55.092   876   893 D BluetoothHeadset: Proxy object connected
,08-04 12:50:55.094   876   893 D BluetoothHeadset: Proxy object connected
,08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:55.111  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:55.114  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:55.115  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:50:55.115  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80e429 added. We now have 8 listener(s)
08-04 12:50:55.115  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:55.119   876  1384 D WifiService: setWifiEnabled: false pid=3854, uid=10000
,08-04 12:50:55.120   876  1384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:50:55.125  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:55.126   876   886 D WifiService: setWifiEnabled: true pid=3854, uid=10000
,08-04 12:50:55.126   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:50:55.134   876  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:55.145  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:55.151  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:55.158   876  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-04 12:50:55.159   876  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 12:50:55.159   876  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-04 12:50:55.160   876  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 12:50:55.161   876  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-04 12:50:55.161   876  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 12:50:55.161   876  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 12:50:55.161   876  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 12:50:55.173   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 12:50:55.173   876  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:50:55.174   372   874 D CommandListener: Setting iface cfg
,08-04 12:50:55.175   876  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-04 12:50:55.175   876  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 12:50:55.228   876  1312 E native  : do suspend true
,08-04 12:50:55.231   876  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 12:50:55.232   876  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 12:50:55.299   876  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:56.142  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:56.149  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:56.162  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 12:50:56.165  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 12:50:56.172  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@35070a6 Bundle[{}]
,08-04 12:50:56.175  3854  3901 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 12:50:56.176  3854  3901 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 12:50:56.180  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-04 12:50:56.181  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-04 12:50:56.181  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 12:50:56.183  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-04 12:50:56.188  3854  3901 I System.out: Running OutgoingSocketThread
,08-04 12:50:56.191  3854  4243 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,08-04 12:50:56.193  3854  4243 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47532
,08-04 12:50:56.193  3854  4243 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 12:50:56.680   876  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:50:56.827   876  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.88 rxSuccessRate=13.12 delta 1000 -> 994
08-04 12:50:56.829   876  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 12:50:56.829   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:50:56.854   876  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 12:50:56.927   876  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 12:50:56.930  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 12:50:57.191  3854  3901 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,08-04 12:50:57.191  3854  3901 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,08-04 12:50:57.203  3854  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-04 12:50:57.207  3854  3901 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 12:50:57.207  3854  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,08-04 12:50:57.210  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:50:57.210  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1bd3ae added. We now have 2 listener(s)
,08-04 12:50:57.212  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:50:57.213  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:50:57.213  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.213  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.213  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec554f added. We now have 9 listener(s)
08-04 12:50:57.213  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:57.214  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:57.219  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:57.225  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:57.228  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:57.229  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:50:57.229  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.229  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71a99e5 added. We now have 3 listener(s)
,08-04 12:50:57.231  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:50:57.231  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:50:57.231  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.232  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.232  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d557cba added. We now have 10 listener(s)
08-04 12:50:57.232  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.232  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:57.232  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:57.232  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:57.232  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:57.233  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:57.233  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.233  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.233  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:50:57.233  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1bd3ae removed from the list
08-04 12:50:57.233  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.233  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec554f removed from the list
08-04 12:50:57.235  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:57.235  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:57.235  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.236  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.236  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:57.237  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:50:57.237  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.238  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.238  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ec554f not in the list
08-04 12:50:57.238  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.238  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:57.239  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.239  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:50:57.239  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.239  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d557cba removed from the list
08-04 12:50:57.239  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:57.240  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.240  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.240  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:50:57.240  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71a99e5 removed from the list
08-04 12:50:57.241  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.241  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b42f76b added. We now have 2 listener(s)
08-04 12:50:57.243  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:50:57.243  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:50:57.244  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.244  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.244  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa822c8 added. We now have 9 listener(s)
08-04 12:50:57.244  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.245  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:57.248  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:57.254  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:57.256  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:57.257  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:57.257  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.258  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4eaa86 added. We now have 3 listener(s)
,08-04 12:50:57.261  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:57.263  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:50:57.264  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:50:57.264  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:57.264  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:50:57.265  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.265  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5179f47 added. We now have 10 listener(s)
,08-04 12:50:57.265  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.266  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:50:57.266  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:50:57.266  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 12:50:57.267  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:57.267  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:50:57.273  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 12:50:57.274  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:50:57.282  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:50:57.284  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:50:57.284  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:50:57.290  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:50:57.291  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:50:57.291  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 12:50:57.292  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:57.299  4189  4200 D BtGatt.GattService: registerClient() - UUID=88543575-d34c-4d31-807c-fc0ca229e609
,08-04 12:50:57.301  4189  4205 D BtGatt.GattService: onClientRegistered() - UUID=88543575-d34c-4d31-807c-fc0ca229e609, clientIf=5
,08-04 12:50:57.303  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 12:50:57.305  4189  4199 D BtGatt.GattService: start scan with filters
,08-04 12:50:57.311  4189  4208 D BtGatt.ScanManager: handling starting scan
,08-04 12:50:57.313  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:50:57.313  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 12:50:57.314  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:50:57.314  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:50:57.314  4189  4208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57120da
,08-04 12:50:57.322  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:50:57.322  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:50:57.322  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:50:57.323  4189  4205 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:50:57.323  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.324  4189  4208 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:50:57.328  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:50:57.336  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:50:57.336  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:57.336  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:50:57.337  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.337  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:50:57.337  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:50:57.337  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:57.338  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:50:57.338  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-04 12:50:57.338  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:50:57.339  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 12:50:57.342  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 12:50:57.343  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.342  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:57.344  4189  4208 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:50:57.344  4189  4208 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 12:50:57.345  4189  4200 D BtGatt.GattService: stopScan() - queue size =1
,08-04 12:50:57.349  4189  4199 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:50:57.350  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:50:57.350  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:50:57.350  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:50:57.351  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-04 12:50:57.351  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:50:57.353  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:57.353  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:50:57.354  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:50:57.354  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 12:50:57.357  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.359  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-04 12:50:57.361  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:57.361  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:57.361  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:50:57.370  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:50:57.371  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:57.371  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:57.372  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:57.373  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.374  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.375  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:50:57.375  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b42f76b removed from the list
,08-04 12:50:57.375  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.376  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa822c8 removed from the list
,08-04 12:50:57.376  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:57.376  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-04 12:50:57.380  4189  4205 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 12:50:57.380  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.380  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.380  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:57.382  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:50:57.382  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:50:57.382  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:50:57.383  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa822c8 not in the list
,08-04 12:50:57.383  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.383  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:50:57.384  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:50:57.384  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:50:57.384  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.384  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5179f47 removed from the list
,08-04 12:50:57.385  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:57.385  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.385  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.385  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:50:57.385  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4eaa86 removed from the list
08-04 12:50:57.386  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:50:57.386  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4e8e3 added. We now have 2 listener(s)
08-04 12:50:57.387  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:50:57.387  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.388  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,08-04 12:50:57.388  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:50:57.388  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.388  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:50:57.388  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be82e0 added. We now have 9 listener(s)
08-04 12:50:57.388  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:57.389  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:57.392  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:57.402  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:50:57.403  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.403  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 12:50:57.403  4189  4208 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:50:57.403  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-04 12:50:57.405   876  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:57.406  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:57.410  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:57.410  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:57.413  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:57.414  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:50:57.414  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.414  4189  4208 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:50:57.414  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:50:57.414  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77a845e added. We now have 3 listener(s)
08-04 12:50:57.415   876  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 12:50:57.416   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:50:57.416   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 12:50:57.416  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:50:57.416  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:50:57.416  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.416  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.416  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@233303f added. We now have 10 listener(s)
08-04 12:50:57.416  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:50:57.417  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:50:57.417  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:50:57.417  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-04 12:50:57.417  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:50:57.417  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:57.417  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:50:57.418  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:57.421  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:50:57.421  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:50:57.421  4189  4205 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:50:57.421  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.425  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:50:57.425  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:50:57.425  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 12:50:57.428  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:50:57.428  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-04 12:50:57.429  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:50:57.429   876  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:50:57.429  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:57.434  4189  4229 D BtGatt.GattService: registerClient() - UUID=7f8f3d64-27a5-4135-9ed4-0228abb97e37
,08-04 12:50:57.435  4189  4205 D BtGatt.GattService: onClientRegistered() - UUID=7f8f3d64-27a5-4135-9ed4-0228abb97e37, clientIf=5
08-04 12:50:57.435  3854  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
08-04 12:50:57.435  4189  4200 D BtGatt.GattService: start scan with filters
,08-04 12:50:57.438  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:50:57.438  4189  4208 D BtGatt.ScanManager: handling starting scan
,08-04 12:50:57.438  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:50:57.438  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:50:57.438  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:50:57.440   372   874 D CommandListener: Setting iface cfg
08-04 12:50:57.440   876  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,08-04 12:50:57.448  4189  4205 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:50:57.448  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.448  4189  4208 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:50:57.451   876  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-04 12:50:57.452  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:50:57.452  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:50:57.452  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:50:57.453  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:50:57.453  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.453  4189  4208 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:50:57.453  4189  4208 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-04 12:50:57.456  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:50:57.463  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:50:57.463  3854  3901 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-04 12:50:57.464  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:50:57.464  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:57.464  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:50:57.465  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:57.465  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.465  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:50:57.466  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:50:57.466  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4e8e3 removed from the list
08-04 12:50:57.466  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.466  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be82e0 removed from the list
08-04 12:50:57.466  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:57.467  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.467  4189  4205 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 12:50:57.467  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.467  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.467  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 12:50:57.467  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.467  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.468  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:57.468  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:50:57.468  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.468  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be82e0 not in the list
08-04 12:50:57.468  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:57.468  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:50:57.468  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-04 12:50:57.469  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 12:50:57.469  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:50:57.469  3854  3901 D BluetoothAdapter: STATE_ON
08-04 12:50:57.470  4189  4200 D BtGatt.GattService: stopScan() - queue size =1
,08-04 12:50:57.470  4189  4228 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:50:57.471  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:50:57.471  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:50:57.471  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:50:57.471  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:50:57.471  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:50:57.472  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:57.472  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:50:57.473  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 12:50:57.473  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:50:57.474  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.474   876  4246 D DhcpClient: Receive thread started
08-04 12:50:57.474  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:50:57.474  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.475  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.475  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:57.475  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.475  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:57.475  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@233303f removed from the list
08-04 12:50:57.475  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:50:57.475  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:57.475  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.475  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:57.475  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.475  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:50:57.475  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77a845e removed from the list
08-04 12:50:57.476  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.476  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@434915b added. We now have 2 listener(s)
,08-04 12:50:57.478  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:50:57.478  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:50:57.478  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.478  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.478  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60dcdf8 added. We now have 9 listener(s)
,08-04 12:50:57.478  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.479  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:57.480  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:50:57.482  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:50:57.482  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.483  4189  4208 D BtGatt.ScanManager: stopping BLe Batch
,08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:57.484  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:57.486  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:50:57.486  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:50:57.486  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.486  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45cc136 added. We now have 3 listener(s)
08-04 12:50:57.488  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:57.488  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:50:57.489  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.489  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:57.489  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:50:57.489  4189  4208 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:50:57.489  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:50:57.490  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.490  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.490  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@420e837 added. We now have 10 listener(s)
08-04 12:50:57.490  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.490  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:50:57.490  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:50:57.490  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:50:57.490  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:57.490  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:50:57.493  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 12:50:57.493  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:50:57.495  4189  4205 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:50:57.495  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.497  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:50:57.498  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:50:57.498  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:50:57.500  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:50:57.501  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:50:57.501  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:50:57.501  3854  3901 D BluetoothAdapter: STATE_ON
,08-04 12:50:57.503  4189  4200 D BtGatt.GattService: registerClient() - UUID=1bd7f1cf-070b-48e2-a7fe-fed4563c5962
,08-04 12:50:57.503  4189  4205 D BtGatt.GattService: onClientRegistered() - UUID=1bd7f1cf-070b-48e2-a7fe-fed4563c5962, clientIf=5
08-04 12:50:57.504  3854  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:50:57.504  4189  4229 D BtGatt.GattService: start scan with filters
,08-04 12:50:57.506  4189  4208 D BtGatt.ScanManager: handling starting scan
,08-04 12:50:57.506  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:50:57.506  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:50:57.506  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:50:57.506  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:50:57.510  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:50:57.510  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:50:57.510  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:50:57.512  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:50:57.513  4189  4205 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:50:57.513  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.513  4189  4208 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:50:57.517  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:50:57.517  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:50:57.517  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:50:57.518  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:57.518  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.518  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:50:57.518  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:50:57.518  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@434915b removed from the list
08-04 12:50:57.518  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.518  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60dcdf8 removed from the list
,08-04 12:50:57.518  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:57.518  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.520  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.520  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 12:50:57.520  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:50:57.520  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.520  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.520  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.520  4189  4208 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:50:57.520  4189  4208 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 12:50:57.521  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:57.521  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.521  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.521  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60dcdf8 not in the list
08-04 12:50:57.521  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:50:57.521  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:50:57.521  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:50:57.521  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:50:57.522  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:50:57.522  3854  3901 D BluetoothAdapter: STATE_ON
08-04 12:50:57.523  4189  4229 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:50:57.523  4189  4228 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:50:57.523  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:50:57.523  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:50:57.523  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:50:57.524  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:50:57.524  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:50:57.524  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:57.525  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:50:57.525  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 12:50:57.525  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:50:57.525  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.526  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.526  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:57.526  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.526  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:57.526  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@420e837 removed from the list
08-04 12:50:57.526  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:50:57.526  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:57.526  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.526  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:50:57.526  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.526  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:50:57.526  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45cc136 removed from the list
,08-04 12:50:57.527  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.527  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@311d0d3 added. We now have 2 listener(s)
08-04 12:50:57.529  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:50:57.529  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:50:57.530  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.530  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:50:57.530  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2686410 added. We now have 9 listener(s)
08-04 12:50:57.530  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.530  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:50:57.532  4189  4205 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-04 12:50:57.532  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.532  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:50:57.536  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:50:57.537  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-04 12:50:57.537  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.538  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:50:57.538  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:50:57.538  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:50:57.538  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efec10e added. We now have 3 listener(s)
08-04 12:50:57.539  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:50:57.540  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:50:57.540  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:50:57.540  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:50:57.540  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:50:57.540  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea72f added. We now have 10 listener(s)
08-04 12:50:57.540  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:50:57.540  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:50:57.541  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:57.541  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:50:57.541  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:50:57.541  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.541  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:50:57.541  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:50:57.542  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:50:57.542  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@311d0d3 removed from the list
08-04 12:50:57.542  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.542  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2686410 removed from the list
,08-04 12:50:57.542  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:50:57.542  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.543  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.543  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.543  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:50:57.543  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:50:57.543  4189  4208 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:50:57.544  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:57.544  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.544  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:50:57.544  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2686410 not in the list
08-04 12:50:57.544  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:50:57.544  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.545  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:50:57.545  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:50:57.545  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:50:57.545  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea72f removed from the list
08-04 12:50:57.545  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:50:57.545  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:50:57.545  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:50:57.545  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:50:57.545  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efec10e removed from the list
,08-04 12:50:57.546  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 12:50:57.546  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 12:50:57.546  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 12:50:57.546  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:50:57.546  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-04 12:50:57.547  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:50:57.548  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 12:50:57.548  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.549  4189  4208 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:50:57.553  3854  4247 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
,08-04 12:50:57.553  3854  4247 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
08-04 12:50:57.553  3854  4247 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 12:50:57.553  4189  4205 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:50:57.553  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:50:57.554  3854  4248 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
08-04 12:50:57.554  3854  4248 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
08-04 12:50:57.555  3854  4248 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-04 12:50:57.555   876  1312 E native  : do suspend false
,08-04 12:50:57.556  3854  3901 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-04 12:50:57.556  3854  3901 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-04 12:50:57.556  3854  3901 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 12:50:57.556  3854  3901 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 12:50:57.556  3854  3901 D com.test.thalitest.ThaliTestRunner: Total duration: 22967 ms
,08-04 12:50:57.558  3854  3901 I jxcore-log: Total number of executed tests:  80
08-04 12:50:57.558  3854  3901 I jxcore-log: 
,08-04 12:50:57.558  3854  3901 I jxcore-log: Number of passed tests:  80
08-04 12:50:57.558  3854  3901 I jxcore-log: 
08-04 12:50:57.558  3854  3901 I jxcore-log: Number of failed tests:  0
08-04 12:50:57.558  3854  3901 I jxcore-log: 
08-04 12:50:57.558  3854  3901 I jxcore-log: Number of ignored tests:  0
08-04 12:50:57.558  3854  3901 I jxcore-log: 
08-04 12:50:57.558  3854  3901 I jxcore-log: Total duration:  22967
08-04 12:50:57.558  3854  3901 I jxcore-log: 
,08-04 12:50:57.560  3854  3901 I jxcore-log: Unit Test app is loaded
08-04 12:50:57.560  3854  3901 I jxcore-log: 
,08-04 12:50:57.565  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.565  3854  3901 I jxcore-log: 
,08-04 12:50:57.566   876  2117 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 12:50:57.569  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.569  3854  3901 I jxcore-log: 
,08-04 12:50:57.569  3854  3854 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-04 12:50:57.570  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.570  3854  3901 I jxcore-log: 
,08-04 12:50:57.571  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.571  3854  3901 I jxcore-log: 
,08-04 12:50:57.571  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.571  3854  3901 I jxcore-log: 
,08-04 12:50:57.573  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.573  3854  3901 I jxcore-log: 
,08-04 12:50:57.575  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.575  3854  3901 I jxcore-log: 
,08-04 12:50:57.576  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.576  3854  3901 I jxcore-log: 
,08-04 12:50:57.577  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.577  3854  3901 I jxcore-log: 
08-04 12:50:57.577   876  4246 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-04 12:50:57.577   876  2117 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-04 12:50:57.578   876  2117 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 12:50:57.579  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.579  3854  3901 I jxcore-log: 
,08-04 12:50:57.580  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.580  3854  3901 I jxcore-log: 
,08-04 12:50:57.580  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.580  3854  3901 I jxcore-log: 
,08-04 12:50:57.581  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:50:57.581  3854  3901 I jxcore-log: 
,08-04 12:50:57.582  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.582  3854  3901 I jxcore-log: 
,08-04 12:50:57.583  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.583  3854  3901 I jxcore-log: 
,08-04 12:50:57.583  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.583  3854  3901 I jxcore-log: 
,08-04 12:50:57.584  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:50:57.584  3854  3901 I jxcore-log: 
,08-04 12:50:57.585  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.585  3854  3901 I jxcore-log: 
,08-04 12:50:57.585  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.585  3854  3901 I jxcore-log: 
,08-04 12:50:57.586  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.586  3854  3901 I jxcore-log: 
,08-04 12:50:57.587  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.587  3854  3901 I jxcore-log: 
,08-04 12:50:57.587  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.587  3854  3901 I jxcore-log: 
,08-04 12:50:57.588  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.588  3854  3901 I jxcore-log: 
,08-04 12:50:57.588  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.588  3854  3901 I jxcore-log: 
,08-04 12:50:57.589   876  4246 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-04 12:50:57.589  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.589  3854  3901 I jxcore-log: 
08-04 12:50:57.589   876  2117 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 12:50:57.590   372   874 D CommandListener: Setting iface cfg
,08-04 12:50:57.592  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.592  3854  3901 I jxcore-log: 
08-04 12:50:57.592  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:50:57.592  3854  3901 I jxcore-log: 
,08-04 12:50:57.593  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.593  3854  3901 I jxcore-log: 
08-04 12:50:57.593   876  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 12:50:57.595   876  1312 E native  : do suspend true
,08-04 12:50:57.595   876  2117 D DhcpClient: Scheduling renewal in 86399s
08-04 12:50:57.595  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.595  3854  3901 I jxcore-log: 
,08-04 12:50:57.596  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.596  3854  3901 I jxcore-log: 
,08-04 12:50:57.597  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.597  3854  3901 I jxcore-log: 
,08-04 12:50:57.597  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.597  3854  3901 I jxcore-log: 
08-04 12:50:57.598  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.598  3854  3901 I jxcore-log: 
,08-04 12:50:57.598  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:50:57.598  3854  3901 I jxcore-log: 
,08-04 12:50:57.601  3854  3901 I jxcore-log: My device name is: motorola-Nexus 6
08-04 12:50:57.601  3854  3901 I jxcore-log: 
,08-04 12:50:57.605   876  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 12:50:57.606   876  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 12:50:57.606   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 12:50:57.608   876  1314 D ConnectivityService: Adding iface wlan0 to network 102
,08-04 12:50:57.610   876  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 12:50:57.658   876  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 12:50:57.658   876  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-04 12:50:57.659   876  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-04 12:50:57.660   876  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-04 12:50:57.661   876  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-04 12:50:57.667   876  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 12:50:57.673   876  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-04 12:50:57.673   876  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-04 12:50:57.673   876  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-04 12:50:57.673   876  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-04 12:50:57.673   876  1314 D ConnectivityService:    accepting network in place of null
08-04 12:50:57.673   876  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:50:57.674   876  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:50:57.680   876  4245 D NetlinkSocketObserver: NeighborEvent{elapsedMs=421290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 12:50:57.704   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:57.733   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:50:57.738   876  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-04 12:50:57.738   876  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:57.744   876  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-04 12:50:57.744   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:50:57.750   876  4244 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:50:57.768  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:50:57.771  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:50:57.774  1939  1939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:50:57.782  1939  1939 D SystemUpdateService: onCreate
,08-04 12:50:57.786  1939  1939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:50:57.807  1939  1939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 12:50:57.811  1939  2404 I iu.UploadsManager: num queued entries: 0
08-04 12:50:57.811  1939  2404 I iu.UploadsManager: num updated entries: 0
08-04 12:50:57.811  1939  2404 I iu.SyncManager: NEXT; no task
,08-04 12:50:57.822  1939  1939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:50:57.823  1939  1939 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:50:57.825  3989  3989 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:50:57.830  1939  4259 I MDM     : [227] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-04 12:50:57.830  1939  4259 W BaseAppContext: Using Auth Proxy for data requests.
,08-04 12:50:57.830  3989  3989 D SprintDMHelper: simOperator: 
08-04 12:50:57.830  3989  3989 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:50:57.843  1939  4259 V GoogleAuthProtoRequest: [227] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 12:50:57.845  1939  4257 I SystemUpdateService: active receiver: enabled
,08-04 12:50:57.848   876  4244 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 10:50:57 GMT], X-Android-Received-Millis=[1470307857848], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470307857808]}
,08-04 12:50:57.849   876  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 12:50:57.849   876  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-04 12:50:57.849   876  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 12:50:57.850   876  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 12:50:57.862  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:50:57.871  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-04 12:50:57.873  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:50:57.885  1939  4257 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:50:57.899  1939  4257 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-04 12:50:57.899  1939  4257 I SystemUpdateService: now status is 0 (complete)
08-04 12:50:57.899  1939  4257 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-04 12:50:57.899  1939  4257 I SystemUpdateService: file has been verified
08-04 12:50:57.900  1939  4257 I SystemUpdateService: OTA package size = 12249756
,08-04 12:50:57.907  1939  4257 I SystemUpdateService: showing system update notification
,08-04 12:50:57.920  1511  3790 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-04 12:50:57.920  1511  3790 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 12:50:57.920  1511  3790 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 12:50:57.921  1511  3790 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:50:57.928  1939  1939 D SystemUpdateService: onDestroy
,08-04 12:50:57.942  1939  4259 E MDM     : [227] SitrepService.a: Error sending sitrep.
,08-04 12:50:57.976  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:50:58.027  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:50:58.053  3960  4262 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 12:50:58.227  1511  4267 I GCM     : Ack for not saved message 64
,08-04 12:50:59.978  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 12:50:59.978  3854  3901 I jxcore-log: 
,08-04 12:51:00.590  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 12:51:00.590  3854  3901 I jxcore-log: 
,08-04 12:51:00.615  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 12:51:00.615  3854  3901 I jxcore-log: 
,08-04 12:51:01.960  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 12:51:01.960  3854  3901 I jxcore-log: 
,08-04 12:51:02.187  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-04 12:51:02.187  3854  3901 I jxcore-log: 
,08-04 12:51:02.192  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-04 12:51:02.192  3854  3901 I jxcore-log: 
,08-04 12:51:02.209  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-04 12:51:02.209  3854  3901 I jxcore-log: 
,08-04 12:51:02.214  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-04 12:51:02.214  3854  3901 I jxcore-log: 
,08-04 12:51:02.888  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-04 12:51:02.888  3854  3901 I jxcore-log: 
,08-04 12:51:02.901  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-04 12:51:02.901  3854  3901 I jxcore-log: 
,08-04 12:51:02.912  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-04 12:51:02.912  3854  3901 I jxcore-log: 
,08-04 12:51:02.919  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-04 12:51:02.919  3854  3901 I jxcore-log: 
,08-04 12:51:02.969  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-04 12:51:02.969  3854  3901 I jxcore-log: 
,08-04 12:51:03.026  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-04 12:51:03.026  3854  3901 I jxcore-log: 
,08-04 12:51:03.034  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-04 12:51:03.034  3854  3901 I jxcore-log: 
,08-04 12:51:03.199  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-04 12:51:03.199  3854  3901 I jxcore-log: 
,08-04 12:51:03.226  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-04 12:51:03.226  3854  3901 I jxcore-log: 
,08-04 12:51:03.232  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-04 12:51:03.232  3854  3901 I jxcore-log: 
,08-04 12:51:03.238  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-04 12:51:03.238  3854  3901 I jxcore-log: 
,08-04 12:51:03.256  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-04 12:51:03.256  3854  3901 I jxcore-log: 
,08-04 12:51:03.340  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-04 12:51:03.340  3854  3901 I jxcore-log: 
,08-04 12:51:03.352  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-04 12:51:03.352  3854  3901 I jxcore-log: 
,08-04 12:51:03.380  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-04 12:51:03.380  3854  3901 I jxcore-log: 
,08-04 12:51:03.392  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-04 12:51:03.392  3854  3901 I jxcore-log: 
,08-04 12:51:03.413  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-04 12:51:03.413  3854  3901 I jxcore-log: 
,08-04 12:51:03.450  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-04 12:51:03.450  3854  3901 I jxcore-log: 
,08-04 12:51:03.455  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-04 12:51:03.455  3854  3901 I jxcore-log: 
,08-04 12:51:03.679  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-04 12:51:03.679  3854  3901 I jxcore-log: 
,08-04 12:51:03.690  3854  3901 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-04 12:51:03.691  3854  3901 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-04 12:51:03.691  3854  3901 I jxcore-log: 
,08-04 12:51:03.739  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:51:03.739  3854  3901 I jxcore-log: 
,08-04 12:51:03.740  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:51:03.740  3854  3901 I jxcore-log: 
08-04 12:51:03.741  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:51:03.741  3854  3901 I jxcore-log: 
,08-04 12:51:03.741  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:51:03.741  3854  3901 I jxcore-log: 
08-04 12:51:03.741  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:51:03.741  3854  3901 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-04 12:51:03.742  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:51:03.742  3854  3901 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-04 12:51:04.712  3854  3901 I jxcore-log: TAP version 13
08-04 12:51:04.712  3854  3901 I jxcore-log: 
,08-04 12:51:04.717  3854  3901 I jxcore-log: # setup
08-04 12:51:04.717  3854  3901 I jxcore-log: 
,08-04 12:51:05.573  3854  3901 I jxcore-log: # 1. calling createNativeListener directly rejects
08-04 12:51:05.573  3854  3901 I jxcore-log: 
,08-04 12:51:05.681   876  1314 D ConnectivityService: handlePromptUnvalidated 102
,08-04 12:51:05.796  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:05.796  3854  3901 I jxcore-log: 
,08-04 12:51:05.804  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 45818
08-04 12:51:05.804  3854  3901 I jxcore-log: 
,08-04 12:51:05.811  3854  3901 I jxcore-log: ok 1 Should throw
08-04 12:51:05.811  3854  3901 I jxcore-log: 
,08-04 12:51:05.813  3854  3901 I jxcore-log: # teardown
08-04 12:51:05.813  3854  3901 I jxcore-log: 
,08-04 12:51:06.915  3854  3901 I jxcore-log: # setup
08-04 12:51:06.915  3854  3901 I jxcore-log: 
,08-04 12:51:08.433  3854  3901 I jxcore-log: # 2. emits incomingConnectionState
08-04 12:51:08.433  3854  3901 I jxcore-log: 
,08-04 12:51:08.476  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:08.476  3854  3901 I jxcore-log: 
,08-04 12:51:08.479  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 47853
08-04 12:51:08.479  3854  3901 I jxcore-log: 
,08-04 12:51:08.501  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:08.501  3854  3901 I jxcore-log: 
,08-04 12:51:08.509  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:08.509  3854  3901 I jxcore-log: 
,08-04 12:51:08.521  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:08.521  3854  3901 I jxcore-log: 
,08-04 12:51:08.528  3854  3901 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-04 12:51:08.528  3854  3901 I jxcore-log: 
,08-04 12:51:08.553  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:08.553  3854  3901 I jxcore-log: 
,08-04 12:51:08.555  3854  3901 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-04 12:51:08.555  3854  3901 I jxcore-log: 
,08-04 12:51:08.560  3854  3901 I jxcore-log: # teardown
08-04 12:51:08.560  3854  3901 I jxcore-log: 
,08-04 12:51:10.376  3854  3901 I jxcore-log: # setup
08-04 12:51:10.376  3854  3901 I jxcore-log: 
,08-04 12:51:10.999  3854  3901 I jxcore-log: # 3. emits routerPortConnectionFailed
08-04 12:51:10.999  3854  3901 I jxcore-log: 
,08-04 12:51:11.614  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:11.614  3854  3901 I jxcore-log: 
,08-04 12:51:11.616  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 45304
08-04 12:51:11.616  3854  3901 I jxcore-log: 
,08-04 12:51:11.624  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:11.624  3854  3901 I jxcore-log: 
,08-04 12:51:11.625  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:11.625  3854  3901 I jxcore-log: 
08-04 12:51:11.627  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:11.627  3854  3901 I jxcore-log: 
,08-04 12:51:11.658  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:11.658  3854  3901 I jxcore-log: 
,08-04 12:51:11.661  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:11.661  3854  3901 I jxcore-log: 
,08-04 12:51:11.666  3854  3901 I jxcore-log: DEBUG createNativeListener: 
08-04 12:51:11.666  3854  3901 I jxcore-log: 
,08-04 12:51:11.667  3854  3901 I jxcore-log: ok 4 tried to connect to right port
08-04 12:51:11.667  3854  3901 I jxcore-log: 
08-04 12:51:11.668  3854  3901 I jxcore-log: ok 5 failed due to refused connection
08-04 12:51:11.668  3854  3901 I jxcore-log: 
,08-04 12:51:11.668  3854  3901 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-04 12:51:11.668  3854  3901 I jxcore-log: 
08-04 12:51:11.671  3854  3901 I jxcore-log: # teardown
08-04 12:51:11.671  3854  3901 I jxcore-log: 
,08-04 12:51:11.673  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:11.673  3854  3901 I jxcore-log: 
,08-04 12:51:12.329  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:12.329  3854  3901 I jxcore-log: 
,08-04 12:51:12.337  3854  3901 I jxcore-log: # setup
08-04 12:51:12.337  3854  3901 I jxcore-log: 
,08-04 12:51:12.338  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:12.338  3854  3901 I jxcore-log: 
,08-04 12:51:12.937  3854  3901 I jxcore-log: # 4. native server connections all up
08-04 12:51:12.937  3854  3901 I jxcore-log: 
,08-04 12:51:13.104  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:13.104  3854  3901 I jxcore-log: 
,08-04 12:51:13.115  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 45822
08-04 12:51:13.115  3854  3901 I jxcore-log: 
,08-04 12:51:13.128  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:13.128  3854  3901 I jxcore-log: 
,08-04 12:51:13.129  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:13.129  3854  3901 I jxcore-log: 
,08-04 12:51:13.131  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:13.131  3854  3901 I jxcore-log: 
,08-04 12:51:13.163  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:13.163  3854  3901 I jxcore-log: 
,08-04 12:51:13.166  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:13.166  3854  3901 I jxcore-log: 
,08-04 12:51:13.170  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:13.170  3854  3901 I jxcore-log: 
,08-04 12:51:13.173  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:13.173  3854  3901 I jxcore-log: 
,08-04 12:51:13.197  3854  3901 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-04 12:51:13.197  3854  3901 I jxcore-log: 
,08-04 12:51:13.198  3854  3901 I jxcore-log: ok 8 Send/recvd #1 should be same
08-04 12:51:13.198  3854  3901 I jxcore-log: 
,08-04 12:51:13.200  3854  3901 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-04 12:51:13.200  3854  3901 I jxcore-log: 
08-04 12:51:13.201  3854  3901 I jxcore-log: ok 10 Send/recvd #2 should be same
08-04 12:51:13.201  3854  3901 I jxcore-log: 
,08-04 12:51:13.204  3854  3901 I jxcore-log: ok 11 Should be exactly 2 client sockets
08-04 12:51:13.204  3854  3901 I jxcore-log: 
,08-04 12:51:13.211  3854  3901 I jxcore-log: # teardown
08-04 12:51:13.211  3854  3901 I jxcore-log: 
,08-04 12:51:14.166  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:14.166  3854  3901 I jxcore-log: 
,08-04 12:51:14.172  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:14.172  3854  3901 I jxcore-log: 
,08-04 12:51:14.175  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:14.175  3854  3901 I jxcore-log: 
,08-04 12:51:14.178  3854  3901 I jxcore-log: # setup
08-04 12:51:14.178  3854  3901 I jxcore-log: 
,08-04 12:51:14.180  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:14.180  3854  3901 I jxcore-log: 
,08-04 12:51:14.571  3854  3901 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-04 12:51:14.571  3854  3901 I jxcore-log: 
,08-04 12:51:15.587  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:15.587  3854  3901 I jxcore-log: 
,08-04 12:51:15.593  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 48447
08-04 12:51:15.593  3854  3901 I jxcore-log: 
,08-04 12:51:15.599  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:15.599  3854  3901 I jxcore-log: 
,08-04 12:51:15.601  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:15.601  3854  3901 I jxcore-log: 
,08-04 12:51:15.602  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:15.602  3854  3901 I jxcore-log: 
,08-04 12:51:15.618  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:15.618  3854  3901 I jxcore-log: 
,08-04 12:51:15.621  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:15.621  3854  3901 I jxcore-log: 
,08-04 12:51:15.634  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:15.634  3854  3901 I jxcore-log: 
,08-04 12:51:15.647  3854  3901 I jxcore-log: ok 12 socket shouldn't close until after stream
08-04 12:51:15.647  3854  3901 I jxcore-log: 
,08-04 12:51:15.647  3854  3901 I jxcore-log: ok 13 incoming remains open
08-04 12:51:15.647  3854  3901 I jxcore-log: 
,08-04 12:51:15.650  3854  3901 I jxcore-log: # teardown
08-04 12:51:15.650  3854  3901 I jxcore-log: 
,08-04 12:51:15.684  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:15.684  3854  3901 I jxcore-log: 
,08-04 12:51:15.688  3854  3901 I jxcore-log: # setup
08-04 12:51:15.688  3854  3901 I jxcore-log: 
,08-04 12:51:15.690  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:15.690  3854  3901 I jxcore-log: 
,08-04 12:51:15.852  3854  3901 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-04 12:51:15.852  3854  3901 I jxcore-log: 
,08-04 12:51:15.925  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:15.925  3854  3901 I jxcore-log: 
,08-04 12:51:15.936  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 45349
08-04 12:51:15.936  3854  3901 I jxcore-log: 
,08-04 12:51:15.943  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:15.943  3854  3901 I jxcore-log: 
,08-04 12:51:15.945  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:15.945  3854  3901 I jxcore-log: 
,08-04 12:51:15.946  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:15.946  3854  3901 I jxcore-log: 
,08-04 12:51:15.962  3854  3901 I jxcore-log: ok 14 we should not have gotten an error
08-04 12:51:15.962  3854  3901 I jxcore-log: 
,08-04 12:51:15.971  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:15.971  3854  3901 I jxcore-log: 
,08-04 12:51:15.975  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:15.975  3854  3901 I jxcore-log: 
,08-04 12:51:15.984  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:15.984  3854  3901 I jxcore-log: 
,08-04 12:51:15.987  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:15.987  3854  3901 I jxcore-log: 
,08-04 12:51:15.994  3854  3901 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-04 12:51:15.994  3854  3901 I jxcore-log: 
,08-04 12:51:15.995  3854  3901 I jxcore-log: ok 16 incoming is cleaned up
08-04 12:51:15.995  3854  3901 I jxcore-log: 
,08-04 12:51:15.997  3854  3901 I jxcore-log: # teardown
08-04 12:51:15.997  3854  3901 I jxcore-log: 
,08-04 12:51:16.094  3854  3901 I jxcore-log: # setup
08-04 12:51:16.094  3854  3901 I jxcore-log: 
,08-04 12:51:16.171  3854  3901 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-04 12:51:16.171  3854  3901 I jxcore-log: 
,08-04 12:51:16.235  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:16.235  3854  3901 I jxcore-log: 
,08-04 12:51:16.241  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 41022
08-04 12:51:16.241  3854  3901 I jxcore-log: 
,08-04 12:51:16.252  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.252  3854  3901 I jxcore-log: 
,08-04 12:51:16.253  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.253  3854  3901 I jxcore-log: 
,08-04 12:51:16.256  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.256  3854  3901 I jxcore-log: 
,08-04 12:51:16.271  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:16.271  3854  3901 I jxcore-log: 
,08-04 12:51:16.274  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:16.274  3854  3901 I jxcore-log: 
,08-04 12:51:16.289  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:16.289  3854  3901 I jxcore-log: 
,08-04 12:51:16.304  3854  3901 I jxcore-log: ok 17 stream was closed
08-04 12:51:16.304  3854  3901 I jxcore-log: 
,08-04 12:51:16.305  3854  3901 I jxcore-log: ok 18 incoming should survive
08-04 12:51:16.305  3854  3901 I jxcore-log: 
08-04 12:51:16.305  3854  3901 I jxcore-log: ok 19 mux should have no streams
08-04 12:51:16.305  3854  3901 I jxcore-log: 
,08-04 12:51:16.310  3854  3901 I jxcore-log: # teardown
08-04 12:51:16.310  3854  3901 I jxcore-log: 
,08-04 12:51:16.441  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:16.441  3854  3901 I jxcore-log: 
,08-04 12:51:16.454  3854  3901 I jxcore-log: # setup
08-04 12:51:16.454  3854  3901 I jxcore-log: 
,08-04 12:51:16.455  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:16.455  3854  3901 I jxcore-log: 
,08-04 12:51:16.526  3854  3901 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-04 12:51:16.526  3854  3901 I jxcore-log: 
,08-04 12:51:16.616  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:16.616  3854  3901 I jxcore-log: 
,08-04 12:51:16.624  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 43089
08-04 12:51:16.624  3854  3901 I jxcore-log: 
,08-04 12:51:16.635  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.635  3854  3901 I jxcore-log: 
,08-04 12:51:16.637  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.637  3854  3901 I jxcore-log: 
,08-04 12:51:16.638  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.638  3854  3901 I jxcore-log: 
,08-04 12:51:16.648  3854  3901 I jxcore-log: ok 20 we should not have gotten an error
08-04 12:51:16.648  3854  3901 I jxcore-log: 
,08-04 12:51:16.663  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:16.663  3854  3901 I jxcore-log: 
,08-04 12:51:16.666  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:16.666  3854  3901 I jxcore-log: 
,08-04 12:51:16.676  3854  3901 I jxcore-log: ok 21 Buffers are identical
08-04 12:51:16.676  3854  3901 I jxcore-log: 
,08-04 12:51:16.678  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:16.678  3854  3901 I jxcore-log: 
,08-04 12:51:16.681  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:16.681  3854  3901 I jxcore-log: 
,08-04 12:51:16.684  3854  3901 I jxcore-log: ok 22 native server is nulled out
08-04 12:51:16.684  3854  3901 I jxcore-log: 
,08-04 12:51:16.684  3854  3901 I jxcore-log: ok 23 native server should be closed
08-04 12:51:16.684  3854  3901 I jxcore-log: 
08-04 12:51:16.685  3854  3901 I jxcore-log: ok 24 incoming has been removed
08-04 12:51:16.685  3854  3901 I jxcore-log: 
08-04 12:51:16.685  3854  3901 I jxcore-log: ok 25 Incoming should be done
08-04 12:51:16.685  3854  3901 I jxcore-log: 
,08-04 12:51:16.686  3854  3901 I jxcore-log: ok 26 The mux object should be closed
08-04 12:51:16.686  3854  3901 I jxcore-log: 
08-04 12:51:16.686  3854  3901 I jxcore-log: ok 27 The mux stream should be closed
08-04 12:51:16.686  3854  3901 I jxcore-log: 
08-04 12:51:16.687  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:16.687  3854  3901 I jxcore-log: 
,08-04 12:51:16.700  3854  3901 I jxcore-log: # teardown
08-04 12:51:16.700  3854  3901 I jxcore-log: 
,08-04 12:51:16.771  3854  3901 I jxcore-log: # setup
08-04 12:51:16.771  3854  3901 I jxcore-log: 
,08-04 12:51:16.811  3854  3901 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-04 12:51:16.811  3854  3901 I jxcore-log: 
,08-04 12:51:16.834  1657  1702 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-04 12:51:16.834  1657  1702 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-04 12:51:16.868  1511  1511 I ConfigService: onCreate
,08-04 12:51:16.871  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:16.871  3854  3901 I jxcore-log: 
,08-04 12:51:16.874  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 47149
08-04 12:51:16.874  3854  3901 I jxcore-log: 
,08-04 12:51:16.900  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.900  3854  3901 I jxcore-log: 
,08-04 12:51:16.901  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.901  3854  3901 I jxcore-log: 
,08-04 12:51:16.902  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.902  3854  3901 I jxcore-log: 
,08-04 12:51:16.905  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.905  3854  3901 I jxcore-log: 
,08-04 12:51:16.906  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.906  3854  3901 I jxcore-log: 
,08-04 12:51:16.908  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.908  3854  3901 I jxcore-log: 
,08-04 12:51:16.911  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.911  3854  3901 I jxcore-log: 
,08-04 12:51:16.911  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.911  3854  3901 I jxcore-log: 
,08-04 12:51:16.915  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.915  3854  3901 I jxcore-log: 
,08-04 12:51:16.919  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.919  3854  3901 I jxcore-log: 
,08-04 12:51:16.919  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.919  3854  3901 I jxcore-log: 
,08-04 12:51:16.920  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.920  3854  3901 I jxcore-log: 
,08-04 12:51:16.923  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.923  3854  3901 I jxcore-log: 
,08-04 12:51:16.924  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.924  3854  3901 I jxcore-log: 
,08-04 12:51:16.925  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.925  3854  3901 I jxcore-log: 
,08-04 12:51:16.927  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.927  3854  3901 I jxcore-log: 
08-04 12:51:16.927  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.927  3854  3901 I jxcore-log: 
,08-04 12:51:16.928  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.928  3854  3901 I jxcore-log: 
,08-04 12:51:16.934  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.934  3854  3901 I jxcore-log: 
,08-04 12:51:16.935  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.935  3854  3901 I jxcore-log: 
,08-04 12:51:16.936  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.936  3854  3901 I jxcore-log: 
,08-04 12:51:16.940  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.940  3854  3901 I jxcore-log: 
,08-04 12:51:16.940  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.940  3854  3901 I jxcore-log: 
08-04 12:51:16.941  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.941  3854  3901 I jxcore-log: 
,08-04 12:51:16.942  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.942  3854  3901 I jxcore-log: 
,08-04 12:51:16.943  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.943  3854  3901 I jxcore-log: 
08-04 12:51:16.944  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.944  3854  3901 I jxcore-log: 
,08-04 12:51:16.945  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:16.945  3854  3901 I jxcore-log: 
,08-04 12:51:16.945  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:16.945  3854  3901 I jxcore-log: 
,08-04 12:51:16.946  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:16.946  3854  3901 I jxcore-log: 
,08-04 12:51:17.036  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.036  3854  3901 I jxcore-log: 
,08-04 12:51:17.038  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.038  3854  3901 I jxcore-log: 
,08-04 12:51:17.040  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.040  3854  3901 I jxcore-log: 
,08-04 12:51:17.041  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.041  3854  3901 I jxcore-log: 
,08-04 12:51:17.043  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.043  3854  3901 I jxcore-log: 
,08-04 12:51:17.044  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.044  3854  3901 I jxcore-log: 
,08-04 12:51:17.046  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.046  3854  3901 I jxcore-log: 
,08-04 12:51:17.047  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.047  3854  3901 I jxcore-log: 
,08-04 12:51:17.050  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.050  3854  3901 I jxcore-log: 
,08-04 12:51:17.051  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.051  3854  3901 I jxcore-log: 
,08-04 12:51:17.053  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.053  3854  3901 I jxcore-log: 
,08-04 12:51:17.054  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.054  3854  3901 I jxcore-log: 
,08-04 12:51:17.055  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.055  3854  3901 I jxcore-log: 
,08-04 12:51:17.057  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.057  3854  3901 I jxcore-log: 
,08-04 12:51:17.058  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.058  3854  3901 I jxcore-log: 
,08-04 12:51:17.060  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.060  3854  3901 I jxcore-log: 
,08-04 12:51:17.062  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.062  3854  3901 I jxcore-log: 
,08-04 12:51:17.063  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.063  3854  3901 I jxcore-log: 
,08-04 12:51:17.065  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.065  3854  3901 I jxcore-log: 
,08-04 12:51:17.066  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.066  3854  3901 I jxcore-log: 
,08-04 12:51:17.069  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.069  3854  3901 I jxcore-log: 
,08-04 12:51:17.071  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.071  3854  3901 I jxcore-log: 
,08-04 12:51:17.072  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.072  3854  3901 I jxcore-log: 
,08-04 12:51:17.074  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.074  3854  3901 I jxcore-log: 
,08-04 12:51:17.076  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.076  3854  3901 I jxcore-log: 
,08-04 12:51:17.078  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.078  3854  3901 I jxcore-log: 
,08-04 12:51:17.079  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.079  3854  3901 I jxcore-log: 
,08-04 12:51:17.080  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.080  3854  3901 I jxcore-log: 
,08-04 12:51:17.082  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.082  3854  3901 I jxcore-log: 
,08-04 12:51:17.083  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.083  3854  3901 I jxcore-log: 
,08-04 12:51:17.084  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.084  3854  3901 I jxcore-log: 
,08-04 12:51:17.086  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.086  3854  3901 I jxcore-log: 
,08-04 12:51:17.088  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.088  3854  3901 I jxcore-log: 
,08-04 12:51:17.089  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.089  3854  3901 I jxcore-log: 
,08-04 12:51:17.091  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.091  3854  3901 I jxcore-log: 
08-04 12:51:17.092  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.092  3854  3901 I jxcore-log: 
,08-04 12:51:17.093  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.093  3854  3901 I jxcore-log: 
,08-04 12:51:17.101  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.101  3854  3901 I jxcore-log: 
,08-04 12:51:17.103  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.103  3854  3901 I jxcore-log: 
,08-04 12:51:17.105  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.105  3854  3901 I jxcore-log: 
,08-04 12:51:17.107  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.107  3854  3901 I jxcore-log: 
,08-04 12:51:17.109  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.109  3854  3901 I jxcore-log: 
,08-04 12:51:17.110  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.110  3854  3901 I jxcore-log: 
,08-04 12:51:17.111  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.111  3854  3901 I jxcore-log: 
08-04 12:51:17.112  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.112  3854  3901 I jxcore-log: 
,08-04 12:51:17.114  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.114  3854  3901 I jxcore-log: 
,08-04 12:51:17.115  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.115  3854  3901 I jxcore-log: 
,08-04 12:51:17.116  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.116  3854  3901 I jxcore-log: 
,08-04 12:51:17.118  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.118  3854  3901 I jxcore-log: 
,08-04 12:51:17.119  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.119  3854  3901 I jxcore-log: 
,08-04 12:51:17.120  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.120  3854  3901 I jxcore-log: 
,08-04 12:51:17.122  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.122  3854  3901 I jxcore-log: 
,08-04 12:51:17.123  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.123  3854  3901 I jxcore-log: 
,08-04 12:51:17.124  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.124  3854  3901 I jxcore-log: 
08-04 12:51:17.125  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.125  3854  3901 I jxcore-log: 
,08-04 12:51:17.126  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.126  3854  3901 I jxcore-log: 
,08-04 12:51:17.128  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.128  3854  3901 I jxcore-log: 
,08-04 12:51:17.130  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.130  3854  3901 I jxcore-log: 
,08-04 12:51:17.131  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.131  3854  3901 I jxcore-log: 
,08-04 12:51:17.132  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.132  3854  3901 I jxcore-log: 
08-04 12:51:17.133  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.133  3854  3901 I jxcore-log: 
,08-04 12:51:17.135  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.135  3854  3901 I jxcore-log: 
,08-04 12:51:17.136  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.136  3854  3901 I jxcore-log: 
,08-04 12:51:17.137  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.137  3854  3901 I jxcore-log: 
,08-04 12:51:17.139  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.139  3854  3901 I jxcore-log: 
,08-04 12:51:17.140  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.140  3854  3901 I jxcore-log: 
,08-04 12:51:17.141  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.141  3854  3901 I jxcore-log: 
,08-04 12:51:17.143  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.143  3854  3901 I jxcore-log: 
,08-04 12:51:17.144  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.144  3854  3901 I jxcore-log: 
,08-04 12:51:17.145  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.145  3854  3901 I jxcore-log: 
,08-04 12:51:17.146  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.146  3854  3901 I jxcore-log: 
,08-04 12:51:17.148  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.148  3854  3901 I jxcore-log: 
,08-04 12:51:17.149  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.149  3854  3901 I jxcore-log: 
,08-04 12:51:17.151  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.151  3854  3901 I jxcore-log: 
08-04 12:51:17.152  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.152  3854  3901 I jxcore-log: 
,08-04 12:51:17.153  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.153  3854  3901 I jxcore-log: 
,08-04 12:51:17.154  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.154  3854  3901 I jxcore-log: 
,08-04 12:51:17.156  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.156  3854  3901 I jxcore-log: 
,08-04 12:51:17.157  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:17.157  3854  3901 I jxcore-log: 
,08-04 12:51:17.158  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:17.158  3854  3901 I jxcore-log: 
,08-04 12:51:17.237  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.237  3854  3901 I jxcore-log: 
,08-04 12:51:17.239  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.239  3854  3901 I jxcore-log: 
,08-04 12:51:17.240  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.240  3854  3901 I jxcore-log: 
,08-04 12:51:17.241  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.241  3854  3901 I jxcore-log: 
08-04 12:51:17.243  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.243  3854  3901 I jxcore-log: 
,08-04 12:51:17.244  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.244  3854  3901 I jxcore-log: 
,08-04 12:51:17.245  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.245  3854  3901 I jxcore-log: 
,08-04 12:51:17.246  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.246  3854  3901 I jxcore-log: 
08-04 12:51:17.247  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.247  3854  3901 I jxcore-log: 
,08-04 12:51:17.248  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.248  3854  3901 I jxcore-log: 
,08-04 12:51:17.249  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.249  3854  3901 I jxcore-log: 
,08-04 12:51:17.252  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.252  3854  3901 I jxcore-log: 
,08-04 12:51:17.253  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.253  3854  3901 I jxcore-log: 
,08-04 12:51:17.254  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.254  3854  3901 I jxcore-log: 
,08-04 12:51:17.256  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.256  3854  3901 I jxcore-log: 
,08-04 12:51:17.261  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.261  3854  3901 I jxcore-log: 
,08-04 12:51:17.264  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.264  3854  3901 I jxcore-log: 
,08-04 12:51:17.265  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.265  3854  3901 I jxcore-log: 
08-04 12:51:17.266  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.266  3854  3901 I jxcore-log: 
,08-04 12:51:17.267  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.267  3854  3901 I jxcore-log: 
,08-04 12:51:17.268  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.268  3854  3901 I jxcore-log: 
08-04 12:51:17.269  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.269  3854  3901 I jxcore-log: 
,08-04 12:51:17.269  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.269  3854  3901 I jxcore-log: 
,08-04 12:51:17.270  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.270  3854  3901 I jxcore-log: 
08-04 12:51:17.271  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.271  3854  3901 I jxcore-log: 
,08-04 12:51:17.272  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.272  3854  3901 I jxcore-log: 
08-04 12:51:17.273  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.273  3854  3901 I jxcore-log: 
,08-04 12:51:17.274  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.274  3854  3901 I jxcore-log: 
08-04 12:51:17.275  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.275  3854  3901 I jxcore-log: 
,08-04 12:51:17.276  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.276  3854  3901 I jxcore-log: 
08-04 12:51:17.277  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.277  3854  3901 I jxcore-log: 
,08-04 12:51:17.278  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.278  3854  3901 I jxcore-log: 
08-04 12:51:17.279  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.279  3854  3901 I jxcore-log: 
08-04 12:51:17.279  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.279  3854  3901 I jxcore-log: 
,08-04 12:51:17.280  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.280  3854  3901 I jxcore-log: 
,08-04 12:51:17.281  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.281  3854  3901 I jxcore-log: 
08-04 12:51:17.282  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.282  3854  3901 I jxcore-log: 
,08-04 12:51:17.283  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.283  3854  3901 I jxcore-log: 
08-04 12:51:17.284  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.284  3854  3901 I jxcore-log: 
,08-04 12:51:17.285  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.285  3854  3901 I jxcore-log: 
08-04 12:51:17.285  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.285  3854  3901 I jxcore-log: 
,08-04 12:51:17.286  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.286  3854  3901 I jxcore-log: 
08-04 12:51:17.287  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.287  3854  3901 I jxcore-log: 
,08-04 12:51:17.288  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.288  3854  3901 I jxcore-log: 
08-04 12:51:17.289  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.289  3854  3901 I jxcore-log: 
,08-04 12:51:17.290  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.290  3854  3901 I jxcore-log: 
08-04 12:51:17.290  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.290  3854  3901 I jxcore-log: 
,08-04 12:51:17.291  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.291  3854  3901 I jxcore-log: 
08-04 12:51:17.292  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:17.292  3854  3901 I jxcore-log: 
,08-04 12:51:17.293  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:17.293  3854  3901 I jxcore-log: 
,08-04 12:51:17.296  3854  3901 I jxcore-log: ok 28 native server is nulled out
08-04 12:51:17.296  3854  3901 I jxcore-log: 
,08-04 12:51:17.297  3854  3901 I jxcore-log: ok 29 native server should be closed
08-04 12:51:17.297  3854  3901 I jxcore-log: 
08-04 12:51:17.297  3854  3901 I jxcore-log: ok 30 incoming has been removed
08-04 12:51:17.297  3854  3901 I jxcore-log: 
,08-04 12:51:17.298  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.298  3854  3901 I jxcore-log: 
08-04 12:51:17.299  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.299  3854  3901 I jxcore-log: 
,08-04 12:51:17.300  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.300  3854  3901 I jxcore-log: 
08-04 12:51:17.300  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.300  3854  3901 I jxcore-log: 
,08-04 12:51:17.301  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.301  3854  3901 I jxcore-log: 
08-04 12:51:17.301  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.301  3854  3901 I jxcore-log: 
,08-04 12:51:17.301  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.301  3854  3901 I jxcore-log: 
08-04 12:51:17.302  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.302  3854  3901 I jxcore-log: 
08-04 12:51:17.302  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.302  3854  3901 I jxcore-log: 
,08-04 12:51:17.302  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:17.302  3854  3901 I jxcore-log: 
,08-04 12:51:17.410  3854  3901 I jxcore-log: # teardown
08-04 12:51:17.410  3854  3901 I jxcore-log: 
,08-04 12:51:17.600  3854  3901 I jxcore-log: # setup
08-04 12:51:17.600  3854  3901 I jxcore-log: 
,08-04 12:51:18.255  3854  3901 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-04 12:51:18.255  3854  3901 I jxcore-log: 
,08-04 12:51:18.969  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:18.969  3854  3901 I jxcore-log: 
,08-04 12:51:18.976  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 47528
08-04 12:51:18.976  3854  3901 I jxcore-log: 
,08-04 12:51:18.982  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:18.982  3854  3901 I jxcore-log: 
,08-04 12:51:18.983  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:18.983  3854  3901 I jxcore-log: 
,08-04 12:51:18.984  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:18.984  3854  3901 I jxcore-log: 
,08-04 12:51:18.995  3854  3901 I jxcore-log: ok 31 we should not have gotten an error
08-04 12:51:18.995  3854  3901 I jxcore-log: 
,08-04 12:51:19.003  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:19.003  3854  3901 I jxcore-log: 
,08-04 12:51:19.005  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:19.005  3854  3901 I jxcore-log: 
,08-04 12:51:19.013  3854  3901 I jxcore-log: ok 32 Buffers are identical
08-04 12:51:19.013  3854  3901 I jxcore-log: 
,08-04 12:51:19.014  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:19.014  3854  3901 I jxcore-log: 
,08-04 12:51:19.016  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:19.016  3854  3901 I jxcore-log: 
,08-04 12:51:19.027  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:19.027  3854  3901 I jxcore-log: 
,08-04 12:51:19.028  3854  3901 I jxcore-log: ok 33 server should be fine
08-04 12:51:19.028  3854  3901 I jxcore-log: 
08-04 12:51:19.029  3854  3901 I jxcore-log: ok 34 server should be open
08-04 12:51:19.029  3854  3901 I jxcore-log: 
,08-04 12:51:19.029  3854  3901 I jxcore-log: ok 35 incoming has been removed
08-04 12:51:19.029  3854  3901 I jxcore-log: 
08-04 12:51:19.030  3854  3901 I jxcore-log: ok 36 The mux object should be closed
08-04 12:51:19.030  3854  3901 I jxcore-log: 
,08-04 12:51:19.030  3854  3901 I jxcore-log: ok 37 The mux stream should be closed
08-04 12:51:19.030  3854  3901 I jxcore-log: 
,08-04 12:51:19.035  3854  3901 I jxcore-log: # teardown
08-04 12:51:19.035  3854  3901 I jxcore-log: 
,08-04 12:51:20.099  3854  3901 I jxcore-log: # setup
08-04 12:51:20.099  3854  3901 I jxcore-log: 
,08-04 12:51:20.340  3854  3901 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-04 12:51:20.340  3854  3901 I jxcore-log: 
,08-04 12:51:21.326  3854  3901 I jxcore-log: DEBUG createNativeListener: creating native server
08-04 12:51:21.326  3854  3901 I jxcore-log: 
,08-04 12:51:21.333  3854  3901 I jxcore-log: DEBUG createNativeListener: listening 38985
08-04 12:51:21.333  3854  3901 I jxcore-log: 
,08-04 12:51:21.339  3854  3901 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-04 12:51:21.339  3854  3901 I jxcore-log: 
,08-04 12:51:21.340  3854  3901 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-04 12:51:21.340  3854  3901 I jxcore-log: 
,08-04 12:51:21.342  3854  3901 I jxcore-log: DEBUG createNativeListener: new mux
08-04 12:51:21.342  3854  3901 I jxcore-log: 
,08-04 12:51:21.348  3854  3901 I jxcore-log: ok 38 we should not have gotten an error
08-04 12:51:21.348  3854  3901 I jxcore-log: 
,08-04 12:51:21.355  3854  3901 I jxcore-log: DEBUG createNativeListener: new stream: 
08-04 12:51:21.355  3854  3901 I jxcore-log: 
,08-04 12:51:21.358  3854  3901 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-04 12:51:21.358  3854  3901 I jxcore-log: 
,08-04 12:51:21.365  3854  3901 I jxcore-log: ok 39 Buffers are identical
08-04 12:51:21.365  3854  3901 I jxcore-log: 
,08-04 12:51:21.369  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-04 12:51:21.369  3854  3901 I jxcore-log: 
,08-04 12:51:21.371  3854  3901 I jxcore-log: DEBUG createNativeListener: stream close:
08-04 12:51:21.371  3854  3901 I jxcore-log: 
,08-04 12:51:21.372  3854  3901 I jxcore-log: DEBUG createNativeListener: mux close
08-04 12:51:21.372  3854  3901 I jxcore-log: 
,08-04 12:51:21.377  3854  3901 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-04 12:51:21.377  3854  3901 I jxcore-log: 
,08-04 12:51:21.378  3854  3901 I jxcore-log: ok 40 server should be fine
08-04 12:51:21.378  3854  3901 I jxcore-log: 
,08-04 12:51:21.378  3854  3901 I jxcore-log: ok 41 server should be open
08-04 12:51:21.378  3854  3901 I jxcore-log: 
,08-04 12:51:21.379  3854  3901 I jxcore-log: ok 42 incoming has been removed
08-04 12:51:21.379  3854  3901 I jxcore-log: 
,08-04 12:51:21.379  3854  3901 I jxcore-log: ok 43 The mux object should be closed
08-04 12:51:21.379  3854  3901 I jxcore-log: 
,08-04 12:51:21.380  3854  3901 I jxcore-log: ok 44 The mux stream should be closed
08-04 12:51:21.380  3854  3901 I jxcore-log: 
08-04 12:51:21.386  3854  3901 I jxcore-log: # teardown
08-04 12:51:21.386  3854  3901 I jxcore-log: 
,08-04 12:51:21.850  3854  3901 I jxcore-log: # setup
08-04 12:51:21.850  3854  3901 I jxcore-log: 
,08-04 12:51:21.945  1511  1511 I ConfigService: onDestroy
,08-04 12:51:22.243  3854  3901 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-04 12:51:22.243  3854  3901 I jxcore-log: 
,08-04 12:51:23.794  3854  3901 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-04 12:51:23.794  3854  3901 I jxcore-log: 
,08-04 12:51:23.795  3854  3901 I jxcore-log: ok 45 Got right error
08-04 12:51:23.795  3854  3901 I jxcore-log: 
,08-04 12:51:23.801  3854  3901 I jxcore-log: # teardown
08-04 12:51:23.801  3854  3901 I jxcore-log: 
,08-04 12:51:24.606  3854  3901 I jxcore-log: # setup
08-04 12:51:24.606  3854  3901 I jxcore-log: 
,08-04 12:51:25.010  3854  3901 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-04 12:51:25.010  3854  3901 I jxcore-log: 
,08-04 12:51:26.503  3854  3901 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-04 12:51:26.503  3854  3901 I jxcore-log: 
,08-04 12:51:26.504  3854  3901 I jxcore-log: ok 46 Got socket hang up
08-04 12:51:26.504  3854  3901 I jxcore-log: 
,08-04 12:51:26.508  3854  3901 I jxcore-log: # teardown
08-04 12:51:26.508  3854  3901 I jxcore-log: 
,08-04 12:51:26.550  3854  3901 I jxcore-log: # setup
08-04 12:51:26.550  3854  3901 I jxcore-log: 
,08-04 12:51:26.961  3854  3901 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-04 12:51:26.961  3854  3901 I jxcore-log: 
,08-04 12:51:27.010  3854  3901 E jxcore  : Error!: Missing PFX or certificate + private key.
08-04 12:51:27.010  3854  3901 E jxcore  : Stack: [{"_fileName":"tls.js","_functionName":"$0v","_lineNumber":"1065","_columnNumber":"1","_msg":"    at $0v@tls.js:1065:1"},{"_fileName":"https.js","_functionName":"$5","_lineNumber":"16","_columnNumber":"1","_msg":"    at $5@https.js:16:1"},{"_fileName":"https.js","_functionName":"exports.createServer","_lineNumber":"33","_columnNumber":"8","_msg":"    at exports.createServer@https.js:33:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js","_functionName":"","_lineNumber":"101","_columnNumber":"1","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js:101:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js","_functionName":"declareTest/</<","_lineNumber":"115","_columnNumber":"7","_msg":"    at declareTest/</<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:115:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"on","_lineNumber":"66","_columnNumber":"5","_msg":"    at on@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:66:5"}]
,08-04 12:51:27.028  3854  3901 I jxcore-log: [ { _fileName: 'tls.js',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _functionName: '$0v',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _lineNumber: '1065',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _columnNumber: '1',
,08-04 12:51:27.028  3854  3901 I jxcore-log:     _msg: '    at $0v@tls.js:1065:1' },
08-04 12:51:27.028  3854  3901 I jxcore-log:   { _fileName: 'https.js',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _functionName: '$5',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _lineNumber: '16',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _columnNumber: '1',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _msg: '    at $5@https.js:16:1' },
08-04 12:51:27.028  3854  3901 I jxcore-log:   { _fileName: 'https.js',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _functionName: 'exports.createServer',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _lineNumber: '33',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _columnNumber: '8',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _msg: '    at exports.createServer@https.js:33:8' },
08-04 12:51:27.028  3854  3901 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _functionName: '',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _lineNumber: '101',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _columnNumber: '1',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js:101:1' },
08-04 12:51:27.028  3854  3901 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _functionName: 'declareTest/</<',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _lineNumber: '115',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _columnNumber: '7',
08-04 12:51:27.028  3854  3901 I jxcore-log:     _msg: '    at declareTest/</<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:115:7' },
08-04 12:51:27.028  3854  3901 I jxcore-log:   { _fileName: '/da
08-04 12:51:27.029  3854  3901 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 12:51:27.029  3854  3901 I jxcore-log: 
,08-04 12:51:27.030  3854  3901 E jxcore-log: Error: 
08-04 12:51:27.030  3854  3901 E jxcore-log: Missing PFX or certificate + private key.
08-04 12:51:27.030  3854  3901 E jxcore-log:  (tls.js 1065:1)
08-04 12:51:27.030  3854  3901 E jxcore-log: 
,08-04 12:51:27.683  4281  4281 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 12:51:27.688  4281  4281 D AndroidRuntime: CheckJNI is OFF
,08-04 12:51:27.731  4281  4281 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 12:51:27.779  4281  4281 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 12:51:27.804  4281  4281 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 12:51:27.817   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-04 12:51:27.818   876   889 I ActivityManager: Killing 3854:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-04 12:51:27.914   876  2928 I WindowState: WIN DEATH: Window{fb330bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 12:51:27.915   876  1313 D WifiService: Client connection lost with reason: 4
,08-04 12:51:27.915   876  1753 D GraphicsStats: Buffer count: 2
,08-04 12:51:27.956   876   899 W PackageSettings: Skipping PackageSetting{e16407f com.example.hello/10273} due to missing metadata
,08-04 12:51:27.982   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-04 12:51:27.982   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-04 12:51:27.983   876   889 E ActivityManager: Failure starting process com.test.thalitest
08-04 12:51:27.983   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-04 12:51:27.983   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:51:27.983   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:27.983   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:51:27.983   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-04 12:51:27.984   876   889 I ActivityManager:   Force finishing activity ActivityRecord{31a90e1 u0 com.test.thalitest/.MainActivity t2}
,08-04 12:51:27.991   876   899 I art     : Starting a blocking GC Explicit
,08-04 12:51:28.003   876   886 W ActivityManager: Spurious death for ProcessRecord{ec7fb6b 0:com.test.thalitest/u0a0}, curProc for 3854: null
,08-04 12:51:28.060   876   899 I art     : Explicit concurrent mark sweep GC freed 31104(1945KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.127ms total 68.585ms
,08-04 12:51:28.098   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 12:51:28.104  4281  4281 I art     : System.exit called, status: 0
08-04 12:51:28.104  4281  4281 I AndroidRuntime: VM exiting with result code 0.
,08-04 12:51:28.156   876   899 I ActivityManager: Start proc 4291:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-04 12:51:28.162   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-04 12:51:28.182   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-04 12:51:28.188  4189  4189 D BluetoothMapAppObserver: onReceive
,08-04 12:51:28.188  4189  4189 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-04 12:51:28.189   876  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 12:51:28.192  1836  2023 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 12:51:28.191  3664  3664 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-04 12:51:28.217  1657  1657 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-04 12:51:28.225   876  2928 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3854 uid 10000
08-04 12:51:28.232  1727  1727 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-04 12:51:28.240   876  1310 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-04 12:51:28.249   876  1738 I ActivityManager: Start proc 4306:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver,
,08-04 12:51:28.283   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 12:51:28.285   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-04 12:51:28.286   876   888 E PackageManager: Failed to write settings, restoring backup
08-04 12:51:28.286   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-04 12:51:28.286   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-04 12:51:28.286   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-04 12:51:28.286   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-04 12:51:28.286   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-04 12:51:28.286   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:51:28.286   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:28.286   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:51:28.291   876   889 E DropBoxManagerService: Can't write: system_server_wtf
08-04 12:51:28.291   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 12:51:28.291   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:51:28.291   876   889 E DropBoxManagerService: 	... 13 more
,08-04 12:51:28.300  1657  1657 I Keyboard.Facilitator: onFinishInput()
,08-04 12:51:28.313   876  1725 I ActivityManager: Killing 3718:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-04 12:51:28.334  1657  4311 I Keyboard.Facilitator.DecoderInitializer: run()
,08-04 12:51:28.336  1657  4311 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-04 12:51:28.336  1657  4311 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-04 12:51:28.336  1657  4311 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-04 12:51:28.336  1657  4311 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-04 12:51:28.336  1657  4311 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-04 12:51:28.336  1657  4311 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-04 12:51:28.338  1657  4311 I Decoder : createOrResetDecoder
,08-04 12:51:28.348  4306  4306 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-04 12:51:28.387  4306  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:28.387  4306  4320 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:28.387  4306  4320 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:51:28.412  4306  4320 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,--------- beginning of crash
08-04 12:51:28.417  4306  4320 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-04 12:51:28.417  4306  4320 E AndroidRuntime: Process: android.process.acore, PID: 4306
08-04 12:51:28.417  4306  4320 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:28.417  4306  4320 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:51:28.457  4306  4306 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-04 12:51:28.451  1511  1511 I ConfigService: onCreate
,08-04 12:51:28.460   876  4322 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:51:28.460   876  4322 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:51:28.460   876  4322 E DropBoxManagerService: 	... 5 more
,08-04 12:51:28.468  1511  4323 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 12:51:28.468  1511  4323 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 12:51:28.469  1511  4323 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-04 12:51:28.470  1511  4323 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-04 12:51:28.476   876   889 I ActivityManager: Start proc 4324:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-04 12:51:28.477   876  1749 I ActivityManager: Killing 1803:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-04 12:51:28.479  1743  1830 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-04 12:51:28.532   876  1313 D WifiService: Client connection lost with reason: 4
,08-04 12:51:28.538  4306  4320 I Process : Sending signal. PID: 4306 SIG: 9
,08-04 12:51:28.549  1657  4311 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-04 12:51:28.566   876  2928 I ActivityManager: Start proc 4336:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-04 12:51:28.567  1743  1830 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 12:51:28.567  1743  1830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1743
08-04 12:51:28.567  1743  1830 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:51:28.567  1743  1830 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:51:28.568   876  1715 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 12:51:28.570   876  4341 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:51:28.570   876  4341 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:51:28.570   876  4341 E DropBoxManagerService: 	... 5 more
,08-04 12:51:28.573  1743  1830 I Process : Sending signal. PID: 1743 SIG: 9
,08-04 12:51:28.583  4324  4324 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm

```
