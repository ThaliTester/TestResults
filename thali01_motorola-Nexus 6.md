#### Test 83261120b3e784a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-31 12:08:40.121   873  1887 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-31 12:08:40.821  3857  3857 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 12:08:40.827  3857  3857 D AndroidRuntime: CheckJNI is OFF
08-31 12:08:40.869  3857  3857 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 12:08:40.919  3857  3857 I Radio-JNI: register_android_hardware_Radio DONE
08-31 12:08:40.941  3857  3857 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 12:08:40.946   873  1961 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 12:08:41.000   873  1961 I ActivityManager: Start proc 3867:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 12:08:41.006  3857  3857 D AndroidRuntime: Shutting down VM
08-31 12:08:41.113  3867  3867 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 12:08:41.145  3867  3867 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 12:08:41.152  3867  3867 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4012-4014)
08-31 12:08:41.152  3867  3867 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 12:08:41.164  3867  3867 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c0800b1}
08-31 12:08:41.164  3867  3867 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 12:08:41.164  3867  3867 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 12:08:41.172  3867  3867 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 12:08:41.174  3867  3867 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 12:08:41.185  3867  3867 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 12:08:41.196  3867  3867 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 12:08:41.196  3867  3867 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 12:08:41.196  3867  3867 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 12:08:41.196  3867  3867 I Adreno  : Build Date                       : 10/20/15
08-31 12:08:41.196  3867  3867 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 12:08:41.196  3867  3867 I Adreno  : Local Branch                     : M14
08-31 12:08:41.196  3867  3867 I Adreno  : Remote Branch                    : 
08-31 12:08:41.196  3867  3867 I Adreno  : Remote Branch                    : 
08-31 12:08:41.196  3867  3867 I Adreno  : Reconstruct Branch               : 
,08-31 12:08:41.247   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ebfb49e:true
,08-31 12:08:41.273  3867  3867 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 12:08:41.291  3867  3867 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 12:08:41.360  3867  3904 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 12:08:41.369  3867  3891 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 12:08:41.393  3867  3904 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 12:08:41.410  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 12:08:41.412  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-31 12:08:41.420  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 12:08:41.422  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 12:08:41.440  1493  2082 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 12:08:41.440  1493  2082 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 12:08:41.440  1493  2082 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 12:08:41.440  1493  2082 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 12:08:41.456   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +397ms (total +483ms)
,08-31 12:08:41.464  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 12:08:41.464  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 12:08:41.464  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-31 12:08:41.506  3867  3867 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3867
,08-31 12:08:41.574  3867  3867 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 12:08:41.733  3867  3906 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1683097296
,08-31 12:08:41.742  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 12:08:41.742  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 12:08:41.742  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 12:08:41.742  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 12:08:41.742  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 12:08:41.743  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@845b55c added. We now have 1 listener(s)
,08-31 12:08:41.749  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 12:08:41.752  3867  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 12:08:41.753  3867  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:08:41.754  3867  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 12:08:41.760  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f68f1eb added. We now have 1 listener(s)
08-31 12:08:41.760  3867  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:08:41.765   873  1302 D WifiService: New client listening to asynchronous messages
,08-31 12:08:41.768  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 12:08:41.768  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 12:08:41.769  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 12:08:41.769  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 12:08:41.770  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 12:08:41.782  3867  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 12:08:41.782  3867  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 12:08:41.789  3867  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:41.790  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:41.790  3867  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-31 12:08:41.790  3867  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:08:41.791  3867  3906 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 12:08:41.795  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:08:41.800  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:08:41.815  3867  3867 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 12:08:42.441  3867  3913 W jxcore-log: Initializing JXcore engine
,08-31 12:08:42.441  3867  3913 W jxcore-log: JXcore engine is ready
,08-31 12:08:42.474  3913  3913 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-31 12:08:42.474  3913  3913 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12088]" dev="sockfs" ino=12088 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 12:08:42.474  3913  3913 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 12:08:42.474  3913  3913 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[29117]" dev="sockfs" ino=29117 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 12:08:42.489  3867  3913 W jxcore-log: Starting JXcore engine
,08-31 12:08:42.571  3867  3913 W jxcore-log: Platform android
08-31 12:08:42.571  3867  3913 W jxcore-log: 
,08-31 12:08:42.571  3867  3913 W jxcore-log: Process ARCH arm
08-31 12:08:42.571  3867  3913 W jxcore-log: 
,08-31 12:08:42.759  3867  3913 I jxcore-log: JXcore Cordova bridge is ready!
08-31 12:08:42.759  3867  3913 I jxcore-log: 
,08-31 12:08:42.759  3867  3913 W jxcore-log: JXcore engine is started
,08-31 12:08:42.767  3867  3906 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 12:08:42.773  3867  3867 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 12:08:46.294   873  1887 D NetlinkSocketObserver: NeighborEvent{elapsedMs=189157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-31 12:08:52.300  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 12:08:52.300  3867  3913 I jxcore-log: 
,08-31 12:08:52.303  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 12:08:52.303  3867  3913 I jxcore-log: 
,08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:52.315  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 12:08:52.320  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 12:08:52.322  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 12:08:52.322  3867  3913 I jxcore-log: 
,08-31 12:08:52.324  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 12:08:52.324  3867  3913 I jxcore-log: 
,08-31 12:08:52.816  3867  3913 D executeNativeTests: Running unit tests
,08-31 12:08:52.874  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:08:52.874  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c added. We now have 2 listener(s)
,08-31 12:08:52.875  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 12:08:52.875  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:08:52.875  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 12:08:52.875  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 12:08:52.875  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 added. We now have 2 listener(s)
08-31 12:08:52.876  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:08:52.876  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 12:08:52.879  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:52.887  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 12:08:52.897  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.897  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 12:08:52.900  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 12:08:52.900  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 12:08:52.900  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 12:08:52.901  3867  3913 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 12:08:52.901  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 12:08:52.901  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 12:08:52.901  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 12:08:52.901  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 12:08:52.902  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 12:08:52.902  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:52.902  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 12:08:52.903  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 12:08:52.903  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.903  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:52.903  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 12:08:52.903  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c removed from the list
08-31 12:08:52.903  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.903  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 removed from the list
,08-31 12:08:52.907  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:52.909  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:52.909  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:52.909  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:08:52.909  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:08:52.909  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.910  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:52.911  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:52.911  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.911  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
,08-31 12:08:52.912  3867  3913 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 12:08:52.913  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:52.913  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:52.913  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:52.913  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 12:08:52.913  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.913  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.914  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:52.914  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.914  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:52.914  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:52.914  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.914  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.914  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:08:52.914  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.915  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:52.915  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:52.915  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.915  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
,08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 12:08:52.921  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 12:08:52.922  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 12:08:52.922  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:52.922  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:52.922  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:52.923  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:52.923  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.923  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.923  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:52.923  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.923  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:52.923  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:52.923  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.923  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.923  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.923  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.924  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:52.925  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:52.925  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.925  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:52.926  3867  391,3 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 12:08:52.927  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:52.931  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:52.932  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.933  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:08:52.934  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 12:08:52.934  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 12:08:52.934  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:52.935  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 12:08:52.935  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:52.935  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 12:08:52.936  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:52.939  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 12:08:52.939  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 12:08:52.944  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 12:08:52.945  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 12:08:52.945  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 12:08:52.947  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 12:08:52.949  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 12:08:52.949  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 12:08:52.950  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 12:08:52.951  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 12:08:52.952  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:08:52.958  2701  2834 D BtGatt.GattService: registerClient() - UUID=57e7ed40-b70a-4dd7-8467-a6c6eec0c810
08-31 12:08:52.959  2701  2723 D BtGatt.GattService: onClientRegistered() - UUID=57e7ed40-b70a-4dd7-8467-a6c6eec0c810, clientIf=5
08-31 12:08:52.959  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 12:08:52.960  2701  2713 D BtGatt.GattService: start scan with filters
08-31 12:08:52.964  2701  2729 D BtGatt.ScanManager: handling starting scan
08-31 12:08:52.964  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 12:08:52.964  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 12:08:52.964  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 12:08:52.964  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 12:08:52.965  2701  2729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:08:52.967  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:08:52.967  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 12:08:52.967  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:08:52.969  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 12:08:52.972  3867  3913 I io.jxcore.node.ConnectionHelper: start: OK
08-31 12:08:52.976  2701  2723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 12:08:52.976  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:52.976  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:52.976  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 12:08:52.976  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 12:08:52.976  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 12:08:52.976  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.976  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 12:08:52.977  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 12:08:52.977  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 12:08:52.977  2701  2729 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 12:08:52.977  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 12:08:52.977  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:08:52.977  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 12:08:52.977  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 12:08:52.978  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:08:52.978  2701  2714 D BtGatt.GattService: stopScan() - queue size =1
08-31 12:08:52.979  2701  2834 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 12:08:52.979  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 12:08:52.979  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 12:08:52.979  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 12:08:52.979  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 12:08:52.980  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 12:08:52.981  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:52.981  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 12:08:52.981  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 12:08:52.981  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 12:08:52.982  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:52.983  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:52.983  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:52.983  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:52.983  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:52.983  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:52.983  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:52.983  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:52.983  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:52.983  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:52.983  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:52.983  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:52.984  3867  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 12:08:52.985  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:52.990  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:52.991  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 12:08:52.991  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:52.991  2701  2729 D BtGatt.ScanManager: Starting BLE batch scan
08-31 12:08:52.991  2701  2729 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 12:08:52.993  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:52.993  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:08:52.994  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 12:08:52.994  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 12:08:52.994  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 12:08:52.994  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:52.994  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 12:08:52.996  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:52.998  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:52.999  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 12:08:53.000  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 12:08:53.003  2701  2723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 12:08:53.003  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.004  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 12:08:53.004  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 12:08:53.004  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 12:08:53.007  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 12:08:53.007  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 12:08:53.007  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 12:08:53.007  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:08:53.009  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 12:08:53.009  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.011  2701  2713 D BtGatt.GattService: registerClient() - UUID=a47415ad-67c0-43da-b306-0caedde87c9a
08-31 12:08:53.011  2701  2723 D BtGatt.GattService: onClientRegistered() - UUID=a47415ad-67c0-43da-b306-0caedde87c9a, clientIf=5
08-31 12:08:53.011  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 12:08:53.011  2701  2714 D BtGatt.GattService: start scan with filters
08-31 12:08:53.013  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 12:08:53.013  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 12:08:53.013  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 12:08:53.013  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 12:08:53.015  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:08:53.015  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:08:53.015  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 12:08:53.016  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 12:08:53.016  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.016  2701  2729 D BtGatt.ScanManager: stopping BLe Batch
08-31 12:08:53.016  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 12:08:53.018  3867  3913 I io.jxcore.node.ConnectionHelper: start: OK
08-31 12:08:53.020  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.020  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 12:08:53.020  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.020  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 12:08:53.020  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.020  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 12:08:53.020  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 12:08:53.020  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 12:08:53.020  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 12:08:53.020  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:08:53.020  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 12:08:53.020  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 12:08:53.021  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:08:53.021  2701  2834 D BtGatt.GattService: stopScan() - queue size =0
08-31 12:08:53.021  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 12:08:53.021  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.022  2701  2729 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 12:08:53.022  2701  2713 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 12:08:53.022  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 12:08:53.022  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 12:08:53.022  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 12:08:53.022  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 12:08:53.022  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 12:08:53.023  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:53.023  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 12:08:53.023  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 12:08:53.023  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 12:08:53.024  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:53.024  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:53.024  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:53.024  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:53.025  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.025  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.025  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:53.025  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.025  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.025  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.025  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.025  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.025  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.025  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.026  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.026  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.026  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.026  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.026  2701  2723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 12:08:53.027  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.027  3867  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 12:08:53.028  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:53.028  2701  2729 D BtGatt.ScanManager: handling starting scan
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:53.031  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:53.032  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:53.032  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:08:53.034  2701  2723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 12:08:53.034  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.034  2701  2729 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 12:08:53.034  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.036  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.036  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 12:08:53.036  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 12:08:53.036  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 12:08:53.036  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:53.036  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 12:08:53.038  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 12:08:53.038  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 12:08:53.039  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 12:08:53.039  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.039  2701  2729 D BtGatt.ScanManager: Starting BLE batch scan
08-31 12:08:53.039  2701  2729 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 12:08:53.040  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 12:08:53.041  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 12:08:53.041  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 12:08:53.044  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 12:08:53.044  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 12:08:53.044  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 12:08:53.044  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:08:53.045  2701  2713 D BtGatt.GattService: registerClient() - UUID=f845f518-8eda-4475-8f92-c2a576b4542e
08-31 12:08:53.046  2701  2723 D BtGatt.GattService: onClientRegistered() - UUID=f845f518-8eda-4475-8f92-c2a576b4542e, clientIf=5
08-31 12:08:53.046  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 12:08:53.046  2701  2714 D BtGatt.GattService: start scan with filters
08-31 12:08:53.048  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 12:08:53.048  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 12:08:53.048  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 12:08:53.048  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 12:08:53.049  2701  2723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 12:08:53.049  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.051  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:08:53.051  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:08:53.051  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 12:08:53.053  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 12:08:53.053  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 12:08:53.053  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.055  3867  3913 I io.jxcore.node.ConnectionHelper: start: OK
08-31 12:08:53.055  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.055  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 12:08:53.055  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.055  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 12:08:53.056  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.056  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 12:08:53.056  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 12:08:53.056  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 12:08:53.056  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 12:08:53.056  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:08:53.056  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 12:08:53.056  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 12:08:53.057  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:08:53.057  2701  2834 D BtGatt.GattService: stopScan() - queue size =0
08-31 12:08:53.058  2701  2713 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 12:08:53.058  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 12:08:53.058  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 12:08:53.058  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 12:08:53.058  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 12:08:53.058  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 12:08:53.059  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 12:08:53.059  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.059  2701  2729 D BtGatt.ScanManager: stopping BLe Batch
08-31 12:08:53.059  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:53.059  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 12:08:53.059  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 12:08:53.059  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 12:08:53.060  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:53.061  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:53.061  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:53.061  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:53.061  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.061  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 12:08:53.061  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.061  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.062  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.062  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.062  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:08:53.062  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.062  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.062  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.062  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.062  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.062  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.062  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.063  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.063  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.063  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.063  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.064  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 12:08:53.064  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.064  3867  3913 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 12:08:53.064  2701  2729 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 12:08:53.064  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.064  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.064  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.065  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.065  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.065  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.065  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.065  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.065  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.065  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.065  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.065  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.065  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.066  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.066  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.066  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.067  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.067  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.067  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 12:08:53.068  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.068  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.068  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.068  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.068  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.068  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.068  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.068  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.068  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.068  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.068  2701  2723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 12:08:53.068  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.068  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.068  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.068  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.069  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.069  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.069  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.069  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.069  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.070  2701  2729 D BtGatt.ScanManager: handling starting scan
08-31 12:08:53.070  3867  3913 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 12:08:53.070  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.070  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.070  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.071  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.071  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.071  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.071  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.071  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.071  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.071  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.071  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.071  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.071  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.071  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.072  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.072  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.072  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.072  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.073  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 12:08:53.073  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.073  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.073  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.073  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.073  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.073  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.073  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.073  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.073  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.074  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.074  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.074  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.074  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.074  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.074  2701  2723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 12:08:53.074  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.074  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.074  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.075  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.075  2701  2729 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 12:08:53.075  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.075  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 12:08:53.077  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 12:08:53.077  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 12:08:53.077  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 12:08:53.077  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 12:08:53.077  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 12:08:53.078  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.078  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.078  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.079  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.079  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.079  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.079  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.079  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.079  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.079  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.080  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 12:08:53.080  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.080  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.080  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.080  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.080  2701  2729 D BtGatt.ScanManager: Starting BLE batch scan
08-31 12:08:53.080  2701  2729 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 12:08:53.080  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.082  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.082  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.082  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.082  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.084  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 12:08:53.084  3867  3913 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 12:08:53.084  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 12:08:53.090  2701  2723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 12:08:53.090  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.090  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 12:08:53.091  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 12:08:53.091  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 12:08:53.091  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 12:08:53.091  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 12:08:53.091  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 12:08:53.091  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 12:08:53.091  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 12:08:53.092  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 12:08:53.093  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 12:08:53.093  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 12:08:53.093  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 12:08:53.093  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 12:08:53.093  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 12:08:53.093  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 12:08:53.094  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 12:08:53.095  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 12:08:53.095  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 12:08:53.095  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 12:08:53.095  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.095  3867  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 12:08:53.095  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 12:08:53.096  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 12:08:53.096  3867  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 12:08:53.096  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 12:08:53.096  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 12:08:53.096  3867  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 12:08:53.096  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 12:08:53.101  2701  2723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 12:08:53.101  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.101  2701  2729 D BtGatt.ScanManager: stopping BLe Batch
08-31 12:08:53.101  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 12:08:53.102  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 12:08:53.103  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 12:08:53.103  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 12:08:53.104  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 12:08:53.104  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 12:08:53.104  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 12:08:53.104  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 12:08:53.104  3867  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-31 12:08:53.106  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.106  3867  3915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 12:08:53.106  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.106  2701  2723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 12:08:53.106  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.106  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.106  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.106  2701  2729 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 12:08:53.106  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.106  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.107  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 12:08:53.108  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.108  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.108  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.108  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.108  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.108  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.109  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.109  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.111  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.111  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.111  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.111  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.111  3867  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-31 12:08:53.112  3867  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-31 12:08:53.112  3867  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-31 12:08:53.112  2701  2831 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-31 12:08:53.112  3867  3913 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 12:08:53.113  3867  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
08-31 12:08:53.113  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.113  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.113  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.114  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.114  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.114  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.114  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.114  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.114  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.114  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.114  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.114  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.114  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.114  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.116  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.116  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.116  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.116  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.116  2701  2723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 12:08:53.116  2701  2723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:08:53.116  3867  3913 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 12:08:53.117  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.117  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.117  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.117  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.117  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.117  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.117  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.117  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.117  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.117  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.117  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.117  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.117  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.117  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.119  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.119  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.119  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.119  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.119  3867  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 12:08:53.119  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 12:08:53.120  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 12:08:53.120  3867  3913 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 12:08:53.120  3867  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 12:08:53.120  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 12:08:53.120  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 12:08:53.120  3867  3913 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 12:08:53.120  3867  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 12:08:53.120  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 12:08:53.120  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 12:08:53.120  3867  3913 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 12:08:53.120  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.120  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.120  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.121  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.121  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.121  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.121  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.121  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.121  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.121  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.121  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.121  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.121  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.121  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.122  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.122  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.122  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.122  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.123  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.123  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.123  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.123  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.123  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.123  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.123  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.123  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.123  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.123  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.124  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.124  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.124  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.124  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.124  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.124  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.124  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.124  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.124  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.124  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.124  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.124  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.125  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.125  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.125  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.125  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.126  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.126  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.126  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.126  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.127  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 12:08:53.127  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:53.128  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 12:08:53.129  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 12:08:53.129  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 12:08:53.129  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 12:08:53.129  3867  3867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 12:08:53.129  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 12:08:53.129  3867  3913 I org.thaliproject.p2p.btconnectorlib.C,onnectionManager: dispose
08-31 12:08:53.130  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 12:08:53.130  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 12:08:53.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 12:08:53.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 12:08:53.130  3867  3867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 12:08:53.130  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.130  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.130  3867  3917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 12:08:53.130  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 12:08:53.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 12:08:53.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:08:53.130  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.131  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:53.131  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:53.131  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.131  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:08:53.131  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.131  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:08:53.132  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.132  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.132  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.132  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.132  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.132  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.132  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.132  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.132  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.132  3867  3917 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 12:08:53.132  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.132  3867  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 12:08:53.132  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.132  3867  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 12:08:53.132  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.132  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.133  3867  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 12:08:53.133  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.133  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.133  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.133  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.134  3867  3913 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 12:08:53.134  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 12:08:53.135  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 12:08:53.135  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 12:08:53.135  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.135  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.135  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.135  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.135  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.135  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.135  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
,08-31 12:08:53.135  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.135  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.135  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.135  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.136  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.136  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.136  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.137  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.137  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.137  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.137  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.140  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.140  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.140  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.140  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.140  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.140  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.140  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.140  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.140  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.140  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.140  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.140  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.140  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.141  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.141  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.141  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.141  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.141  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.142  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:08:53.142  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:08:53.142  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:08:53.142  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:08:53.142  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.142  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.143  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8267d2c not in the list
08-31 12:08:53.143  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.143  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.143  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:08:53.143  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.143  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.143  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:08:53.143  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:08:53.144  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:08:53.144  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:08:53.144  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:08:53.144  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8ee3f5 not in the list
08-31 12:08:53.145  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 12:08:53.145  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 12:08:53.145  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 12:08:53.145  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 12:08:53.145  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 12:08:53.145  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 12:08:53.147  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 12:08:53.147  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 12:08:53.147  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 12:08:53.148  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 12:08:53.148  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 12:08:53.148  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 12:08:53.148  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 12:08:53.148  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 12:08:53.148  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 12:08:53.148  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 12:08:53.149  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 12:08:53.149  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 12:08:53.149  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 12:08:53.149  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 12:08:53.150  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:08:53.150  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25e4bcf added. We now have 2 listener(s)
08-31 12:08:53.150  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:08:53.153  3867  3913 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 12:08:53.153   873  2161 D WifiService: setWifiEnabled: true pid=3867, uid=10000
08-31 12:08:53.153   873  2161 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 12:08:53.154  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:08:53.154  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e59895c added. We now have 3 listener(s)
08-31 12:08:53.154  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:08:53.159  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:08:53.159  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d21b465 added. We now have 4 listener(s)
08-31 12:08:53.159  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:08:53.161  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:08:53.161  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76ec53a added. We now have 5 listener(s)
08-31 12:08:53.161  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:08:53.163   873  1962 D WifiService: setWifiEnabled: false pid=3867, uid=10000
08-31 12:08:53.164   873  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 12:08:53.170  2701  2719 D BluetoothAdapterState: Current state: ON, message: 23
08-31 12:08:53.170  2701  2719 D BluetoothAdapterProperties: Setting state to 13
08-31 12:08:53.170  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 12:08:53.171  2701  2719 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 12:08:53.171  2701  2719 I BluetoothAdapterState: Entering PendingCommandState
08-31 12:08:53.172  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:08:53.172  2701  2723 D BluetoothAdapterProperties: Scan Mode:20
08-31 12:08:53.172  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 12:08:53.174  2701  2701 D HeadsetService: Received stop request...Stopping profile...
08-31 12:08:53.175  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 12:08:53.176  1346  1363 D BluetoothHeadset: Proxy object disconnected
,08-31 12:08:53.176  1346  1346 D HeadsetProfile: Bluetooth service disconnected
08-31 12:08:53.177   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 12:08:53.177   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 12:08:53.177   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 12:08:53.177  1943  1957 D BluetoothHeadset: Proxy object disconnected
08-31 12:08:53.178   873  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 12:08:53.178   873  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-31 12:08:53.178   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 12:08:53.178   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 12:08:53.178  2701  2701 D A2dpService: Received stop request...Stopping profile...
08-31 12:08:53.179  2701  2839 D A2dpStateMachine: Exit Disconnected: -1
08-31 12:08:53.180  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:53.180  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:53.181  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.181  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:53.181  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 12:08:53.181   873   873 D BluetoothA2dp: Proxy object disconnected
08-31 12:08:53.181  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-31 12:08:53.182  2701  2701 V BluetoothAdapterState: isTurningOff()=true
08-31 12:08:53.182  2701  2701 V BluetoothAdapterState: isTurningOn()=false
,08-31 12:08:53.182  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:08:53.182  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:08:53.183  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.185  2701  2701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 12:08:53.185  2701  2723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 12:08:53.185  2701  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:08:53.185  2701  2701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 12:08:53.185  2701  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 12:08:53.185  2701  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:08:53.185  2701  2723 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 12:08:53.185  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:08:53.187   873  1301 E native  : do suspend true
,08-31 12:08:53.187  2701  2701 D HidService: Received stop request...Stopping profile...
,08-31 12:08:53.187  2701  2701 D HidService: Stopping Bluetooth HidService
08-31 12:08:53.188  1346  1346 D BluetoothInputDevice: Proxy object disconnected
08-31 12:08:53.188  1346  1346 D HidProfile: Bluetooth service disconnected
08-31 12:08:53.189  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.189  2701  2701 D HealthService: Received stop request...Stopping profile...,
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:53.189  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:53.190  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.190  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:53.192  2701  2701 D PanService: Received stop request...Stopping profile...
08-31 12:08:53.192  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.192  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 12:08:53.193  1346  1346 D PanProfile: Bluetooth service disconnected
08-31 12:08:53.193  2701  2701 D BluetoothMapService: Received stop request...Stopping profile...
08-31 12:08:53.193  2701  2701 D BluetoothMapService: stop()
08-31 12:08:53.194  2701  2701 D BluetoothMapAppObserver: deinitObservers()
08-31 12:08:53.194  2701  2701 D BluetoothMapAppObserver: removeReceiver()
08-31 12:08:53.195  1346  1346 D BluetoothMap: Proxy object disconnected
08-31 12:08:53.195  1346  1346 D MapProfile: Bluetooth service disconnected
08-31 12:08:53.195  2701  2701 V BluetoothAdapterState: isTurningOff()=true
08-31 12:08:53.195  2701  2701 V BluetoothAdapterState: isTurningOn()=false
08-31 12:08:53.195  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:08:53.195  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:08:53.197  2701  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 12:08:53.197  2701  2723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 12:08:53.197  2701  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:08:53.197  2701  2815 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 12:08:53.197  2701  2815 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 12:08:53.197  2701  2701 V BluetoothAdapterState: isTurningOff()=true,
08-31 12:08:53.197  2701  2815 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 12:08:53.197  2701  2701 V BluetoothAdapterState: isTurningOn()=false
08-31 12:08:53.197  2701  2815 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 12:08:53.197  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:08:53.197  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:08:53.197  2701  2701 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-31 12:08:53.197  2701  2723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 12:08:53.197  2701  2701 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 12:08:53.198  2701  2701 V BluetoothAdapterState: isTurningOff()=true
,08-31 12:08:53.198  2701  2701 V BluetoothAdapterState: isTurningOn()=false
08-31 12:08:53.198  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 12:08:53.198  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:08:53.198  2701  2701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 12:08:53.198  2701  2723 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 12:08:53.198  2701  2701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 12:08:53.199   873  1889 D DhcpClient: Clearing IP address
,08-31 12:08:53.199   370   871 D CommandListener: Clearing all IP addresses on wlan0
08-31 12:08:53.199  2701  2701 V BluetoothAdapterState: isTurningOff()=true
08-31 12:08:53.199  2701  2701 V BluetoothAdapterState: isTurningOn()=false
08-31 12:08:53.199  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:08:53.199  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:08:53.200  2701  2701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-31 12:08:53.200  2701  2701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 12:08:53.201  2701  2701 D BluetoothMapService: MAP Service closeService in
,08-31 12:08:53.201  2701  2701 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 12:08:53.201  2701  2701 D ObexServerSockets0: shutdown(block = true)
08-31 12:08:53.201  2701  2870 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4,
08-31 12:08:53.202  2701  2701 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 12:08:53.202  2701  2831 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 12:08:53.202  2701  2871 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-31 12:08:53.202  2701  2701 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 12:08:53.202  2701  2701 V BluetoothAdapterState: isTurningOff()=true
08-31 12:08:53.202  2701  2701 V BluetoothAdapterState: isTurningOn()=false
,08-31 12:08:53.202  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:08:53.202  2701  2701 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:08:53.203  2701  2701 D BluetoothMapService: cleanup()
08-31 12:08:53.203  2701  2701 D BluetoothMapService: MAP Service closeService in
08-31 12:08:53.203   370   871 D CommandListener: Setting iface cfg
,08-31 12:08:53.209   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 12:08:53.209   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-31 12:08:53.213   401   401 E Parcel  : Reading a NULL string not supported here.
,08-31 12:08:53.214  1493  2497 V NativeCrypto: Read error: ssl=0x9adb3400: I/O error during system call, Connection timed out
,08-31 12:08:53.215  1493  2497 V NativeCrypto: SSL shutdown failed: ssl=0x9adb3400: I/O error during system call, Broken pipe
,08-31 12:08:53.217   873  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-31 12:08:53.218  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 12:08:53.218   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 12:08:53.218   873  1301 E native  : do suspend true
08-31 12:08:53.218  2701  2719 D BluetoothAdapterProperties: Setting state to 15
08-31 12:08:53.218  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 12:08:53.218  2701  2719 I BluetoothAdapterState: Entering BleOnState
,08-31 12:08:53.220   873  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 12:08:53.220   873  1891 D DhcpClient: Receive thread stopped
08-31 12:08:53.224  1346  1363 D BluetoothMap: onBluetoothStateChange: up=false
08-31 12:08:53.225  2701  2701 I BtOppRfcommListener: stopping Accept Thread
08-31 12:08:53.225  2701  3417 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 12:08:53.225  2701  3417 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 12:08:53.227  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:53.227  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:08:53.228  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.228  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 12:08:53.229  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:53.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:08:53.230  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.230  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:53.242   873   886 I ActivityManager: Start proc 3922:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-31 12:08:53.243  1346  3866 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 12:08:53.243  1346  2049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 12:08:53.244   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 12:08:53.244  1346  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:08:53.244  1346  1363 D BluetoothPan: onBluetoothStateChange on: false
08-31 12:08:53.245   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:08:53.245   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:08:53.245   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 12:08:53.245  1943  1959 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:08:53.245  1346  3866 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 12:08:53.246  2701  2719 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 12:08:53.247  2701  2719 D BluetoothAdapterProperties: Setting state to 16
08-31 12:08:53.247  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 12:08:53.247  2701  2719 D BluetoothAdapterProperties: onBleDisable
08-31 12:08:53.247  2701  2719 I BluetoothAdapterState: Entering PendingCommandState
08-31 12:08:53.247  2701  2720 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 12:08:53.248  2701  2723 D BluetoothAdapterProperties: Scan Mode:20
08-31 12:08:53.248  2701  2815 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 12:08:53.248  2701  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:08:53.251  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.251  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.253  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.254  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:08:53.260   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:08:53.278   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:08:53.279   370   871 D CommandListener: Clearing all IP addresses on wlan0
08-31 12:08:53.279   873  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 12:08:53.279   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:08:53.281   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-31 12:08:53.286   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 12:08:53.286  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:08:53.287  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:08:53.304  3922  3922 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-31 12:08:53.309   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 12:08:53.311   873  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 12:08:53.312  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:53.312  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:08:53.313  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:53.313  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:53.313  1900  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 12:08:53.314  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:53.314  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:08:53.315  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:53.315  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:53.320  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 12:08:53.325   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae6ad55:true
,08-31 12:08:53.325  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 12:08:53.339   873  1951 I ActivityManager: Start proc 3940:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 12:08:53.351   370   871 E Netd    : netlink response contains error (No such file or directory)
,08-31 12:08:53.365  3922  3922 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 12:08:53.367  3922  3922 D BluetoothMap: Create BluetoothMap proxy object
,08-31 12:08:53.375  3922  3922 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 12:08:53.376  3940  3940 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 12:08:53.385  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-31 12:08:53.395   873  1390 I ActivityManager: Killing 2268:com.google.android.talk/u0a61 (adj 15): empty #17
,08-31 12:08:53.451  2701  2723 I bt_hci  : shut_down
,08-31 12:08:53.452  2701  2730 D bt_hwcfg: hw_epilog_process
,08-31 12:08:53.453  2701  2730 I bt_vendor: low_power_mode_cb
,08-31 12:08:53.477  2701  2730 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 12:08:53.477  2701  2730 I bt_vendor: epilog_cb
,08-31 12:08:53.477  2701  2730 I bt_hci  : epilog_finished_callback
,08-31 12:08:53.484  2701  2723 I bt_hci_h4: hal_close
,08-31 12:08:53.485  2701  2723 I bt_userial_vendor: device fd = 51 close
,08-31 12:08:53.558  3940  3940 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.558  3940  3940 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.558  3940  3940 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.558  3940  3940 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.558  3940  3940 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.558  3940  3940 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.558  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.559  3940  3940 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.559  3940  3940 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:08:53.559  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:08:53.601   873  1951 I ActivityManager: Start proc 3970:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-31 12:08:53.602   873  1951 I ActivityManager: Killing 3550:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-31 12:08:53.633  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 12:08:53.721  2701  2720 D bt_stack_manager: event_shut_down_stack finished.
,08-31 12:08:53.721  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 12:08:53.728  2701  2719 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 12:08:53.729  2701  2701 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 12:08:53.729  2701  2701 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 12:08:53.729  2701  2701 D BtGatt.GattService: stop()
,08-31 12:08:53.729  2701  2701 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 12:08:53.732  2701  2701 V BluetoothAdapterState: isTurningOff()=false
,08-31 12:08:53.732  2701  2701 V BluetoothAdapterState: isTurningOn()=false
,08-31 12:08:53.732  2701  2701 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:08:53.732  2701  2701 V BluetoothAdapterState: isBleTurningOff()=true
,08-31 12:08:53.733  2701  2719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 12:08:53.733  2701  2719 D BluetoothAdapterProperties: Setting state to 10
,08-31 12:08:53.733  2701  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 12:08:53.734  2701  2719 I BluetoothAdapterState: Entering OffState
,08-31 12:08:53.736   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 12:08:53.752  2701  2701 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 12:08:53.752  2701  2701 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 12:08:53.752  2701  2701 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 12:08:53.753  2701  2720 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 12:08:53.763  2701  2720 D bt_stack_manager: event_clean_up_stack finished.
,08-31 12:08:53.771  3970  3970 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-31 12:08:53.772  2701  2701 I art     : System.exit called, status: 0
,08-31 12:08:53.772  2701  2701 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 12:08:53.816  3940  3966 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 12:08:53.826   873  1509 I ActivityManager: Process com.android.bluetooth (pid 2701) has died
,08-31 12:08:53.899   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f67091f:true
,08-31 12:08:54.021  3970  3990 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-31 12:08:54.021  3970  3990 I Babel_SMS: MmsConfig.loadMmsSettings
,08-31 12:08:54.022  3970  3990 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-31 12:08:54.022  3970  3990 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 12:08:54.061  3970  3990 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 12:08:54.061  3970  3990 I Babel_SMS: MmsConfig.loadFromResources
,08-31 12:08:54.062  3970  3990 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 12:08:54.063  3970  3990 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-31 12:08:54.124  3970  3970 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 12:08:54.126  3970  3970 I Babel_Crash: startup - clean
,08-31 12:08:54.146  3970  3970 I Babel_telephony: TeleModule.launchCompleted
,08-31 12:08:54.159   873  1962 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-31 12:08:54.171  3970  3970 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-31 12:08:54.178  3970  3970 W Babel   : BAM#gBA: invalid account id: -1
,08-31 12:08:54.178  3970  3970 W Babel   : BAM#gBA: invalid account id: -1
,08-31 12:08:54.178  3970  3970 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-31 12:08:54.181  3970  3995 I Babel   : deleted: false for 0
,08-31 12:08:54.190   873  2047 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-31 12:08:54.215  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 12:08:54.244   873  1380 I ActivityManager: Start proc 3998:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-31 12:08:54.245  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-31 12:08:54.277  3970  3970 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 12:08:54.357  3970  3970 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 12:08:54.369  3970  3970 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 12:08:54.378  3970  3970 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 12:08:54.382  3970  3970 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 12:08:54.397  3970  3970 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 12:08:54.410  3970  3970 I vclib   : onServiceConnected
,08-31 12:08:54.428  3998  3998 D AdapterServiceConfig: Adding HeadsetService
08-31 12:08:54.428  3998  3998 D AdapterServiceConfig: Adding A2dpService
08-31 12:08:54.428  3998  3998 D AdapterServiceConfig: Adding HidService
08-31 12:08:54.428  3998  3998 D AdapterServiceConfig: Adding HealthService
08-31 12:08:54.428  3998  3998 D AdapterServiceConfig: Adding PanService
08-31 12:08:54.428  3998  3998 D AdapterServiceConfig: Adding GattService
08-31 12:08:54.429  3998  3998 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 12:08:54.433   873  1962 I ActivityManager: Killing 3444:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 12:08:54.471  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 12:08:54.497  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 12:08:54.504  1694  1694 D SystemUpdateService: onCreate
,08-31 12:08:54.511  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 12:08:54.545  1694  4010 I SystemUpdateService: active receiver: enabled
,08-31 12:08:54.554  1694  4010 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 12:08:54.561  1694  4010 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 12:08:54.561  1694  4010 I SystemUpdateService: now status is 0 (complete),
08-31 12:08:54.561  1694  4010 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 12:08:54.561  1694  4010 I SystemUpdateService: file has been verified
08-31 12:08:54.561  1694  4010 I SystemUpdateService: OTA package size = 12249756
08-31 12:08:54.561  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-31 12:08:54.563  1694  4010 I SystemUpdateService: showing system update notification
,08-31 12:08:54.566  1694  2460 I iu.UploadsManager: num queued entries: 0
,08-31 12:08:54.581  1694  2460 I iu.UploadsManager: num updated entries: 0
08-31 12:08:54.582  1694  2460 I iu.SyncManager: NEXT; no task
,08-31 12:08:54.584  1694  1694 D SystemUpdateService: onDestroy
,08-31 12:08:54.596  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 12:08:54.601  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 12:08:54.615   873  1390 I ActivityManager: Start proc 4012:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 12:08:54.685  4012  4012 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 12:08:54.689  4012  4012 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:08:54.698  4012  4012 D SprintDMHelper: simOperator: 
08-31 12:08:54.698  4012  4012 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 12:08:54.715   873  1380 I ActivityManager: Start proc 4024:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 12:08:54.716   873  1380 I ActivityManager: Killing 3491:android.process.acore/u0a5 (adj 15): empty #17
,08-31 12:08:54.888   873  1390 I ActivityManager: Start proc 4039:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 12:08:54.891  3970  4038 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 12:08:54.898   873  2162 I ActivityManager: Killing 3623:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 12:08:54.972  4039  4039 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 12:08:55.034  4039  4039 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 12:08:55.034  4039  4039 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 12:08:55.034  4039  4039 I GAv4    :   adb logcat -s GAv4
,08-31 12:08:55.050  4039  4039 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 12:08:55.057  4039  4039 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 12:08:55.088  4039  4056 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 12:08:55.195  4039  4039 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 12:08:55.235  4039  4039 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 12:08:55.250  4039  4039 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 8104-8113)
,08-31 12:08:55.251  4039  4039 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 12:08:55.265  4039  4039 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11f3cd5}
,08-31 12:08:55.265  4039  4039 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 12:08:55.266  4039  4039 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 12:08:55.275  4039  4039 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 12:08:55.278  4039  4039 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 12:08:55.296  4039  4039 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 12:08:55.307  4039  4039 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 12:08:55.307  4039  4039 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 12:08:55.307  4039  4039 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 12:08:55.307  4039  4039 I Adreno  : Build Date                       : 10/20/15
08-31 12:08:55.307  4039  4039 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 12:08:55.307  4039  4039 I Adreno  : Local Branch                     : M14
08-31 12:08:55.307  4039  4039 I Adreno  : Remote Branch                    : 
08-31 12:08:55.307  4039  4039 I Adreno  : Remote Branch                    : 
08-31 12:08:55.307  4039  4039 I Adreno  : Reconstruct Branch               : 
,08-31 12:08:55.355  4039  4086 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 12:08:55.369  4039  4039 I NSApplication: Starting up...
,08-31 12:08:55.390   873  1390 I ActivityManager: Start proc 4091:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 12:08:55.392   873  1390 I ActivityManager: Killing 3638:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 12:08:55.475  4091  4091 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 12:08:55.651   873  2153 I ActivityManager: Killing 2146:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 12:08:56.184   873   883 D WifiService: setWifiEnabled: true pid=3867, uid=10000
,08-31 12:08:56.184   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 12:08:56.197   873  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-31 12:08:56.204  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:56.204  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:08:56.204  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:56.204  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:56.207  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:56.207  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:08:56.207  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:56.208  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:56.226   873  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-31 12:08:56.230   873  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-31 12:08:56.231   873  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 12:08:56.234   873  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 12:08:56.235   873  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 12:08:56.236   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 12:08:56.236   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 12:08:56.252   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 12:08:56.253   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 12:08:56.254   370   871 D CommandListener: Setting iface cfg
,08-31 12:08:56.255   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
08-31 12:08:56.255   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 12:08:56.267   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 12:08:56.267   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-31 12:08:56.268   873  1301 E native  : do suspend true
,08-31 12:08:56.298   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 12:08:57.668   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 12:08:57.711   873  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.12 rxSuccessRate=9.50 delta 1000 -> 994
,08-31 12:08:57.714   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-31 12:08:57.714   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:08:57.727   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 12:08:57.760   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 12:08:57.765  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 12:08:58.193  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 12:08:58.239  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 12:08:58.240  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 12:08:58.246   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 12:08:58.258   873  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 12:08:58.258   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:08:58.258   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 12:08:58.272   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:08:58.287   370   871 D CommandListener: Setting iface cfg
,08-31 12:08:58.290   873  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-31 12:08:58.306   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 12:08:58.334   873  4117 D DhcpClient: Receive thread started
,08-31 12:08:58.417   873  1301 E native  : do suspend false
,08-31 12:08:58.429   873  1889 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 12:08:58.450   873  4117 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172621, domain null
,08-31 12:08:58.451   873  1889 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172621 seconds
,08-31 12:08:58.455   873  1889 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 12:08:58.472   873  4117 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 12:08:58.473   873  1889 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 12:08:58.477   370   871 D CommandListener: Setting iface cfg
,08-31 12:08:58.482   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 12:08:58.483   873  1889 D DhcpClient: Scheduling renewal in 86399s
,08-31 12:08:58.486   873  1301 E native  : do suspend true
,08-31 12:08:58.501   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 12:08:58.501   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
08-31 12:08:58.502   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 12:08:58.503   873  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 12:08:58.504   873  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 12:08:58.546   873  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 12:08:58.546   873  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-31 12:08:58.547   873  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 12:08:58.548   873  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 12:08:58.549   873  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 12:08:58.554   873  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 12:08:58.558   873  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-31 12:08:58.558   873  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-31 12:08:58.559   873  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-31 12:08:58.559   873  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 12:08:58.559   873  1303 D ConnectivityService:    accepting network in place of null
08-31 12:08:58.559   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 12:08:58.559   873  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 12:08:58.571   873  4116 D NetlinkSocketObserver: NeighborEvent{elapsedMs=201434, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 12:08:58.595   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:08:58.633   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:08:58.639   873  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 12:08:58.639   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:08:58.648   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-31 12:08:58.649   873  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 12:08:58.652  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:58.652  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 12:08:58.652  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:58.652   873  4115 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.206,2a00:1450:400d:803::200e
08-31 12:08:58.652  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:58.659  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:08:58.659  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 12:08:58.659  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:58.659  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 12:08:58.669  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 12:08:58.672  1694  1694 D SystemUpdateService: onCreate
,08-31 12:08:58.676  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 12:08:58.679  1694  4129 I SystemUpdateService: active receiver: enabled
,08-31 12:08:58.682  1694  4129 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 12:08:58.687  1694  4129 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 12:08:58.687  1694  4129 I SystemUpdateService: now status is 0 (complete)
,08-31 12:08:58.689  1694  4129 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 12:08:58.690  1694  4129 I SystemUpdateService: file has been verified
08-31 12:08:58.690  1694  4129 I SystemUpdateService: OTA package size = 12249756
,08-31 12:08:58.693  1694  4129 I SystemUpdateService: showing system update notification
,08-31 12:08:58.700  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 12:08:58.702  1694  2460 I iu.UploadsManager: num queued entries: 0
08-31 12:08:58.702  1694  2460 I iu.UploadsManager: num updated entries: 0
08-31 12:08:58.703  1694  2460 I iu.SyncManager: NEXT; no task
08-31 12:08:58.706  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 12:08:58.707  1694  4134 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 12:08:58.707  1694  4134 W BaseAppContext: Using Auth Proxy for data requests.
08-31 12:08:58.707  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-31 12:08:58.708  1694  4134 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com,
,08-31 12:08:58.709  4012  4012 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:08:58.713  4012  4012 D SprintDMHelper: simOperator: 
,08-31 12:08:58.713  4012  4012 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 12:08:58.714  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 12:08:58.716  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 12:08:58.720  1694  1694 D SystemUpdateService: onDestroy
,08-31 12:08:58.735   873  4115 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 10:08:58 GMT], X-Android-Received-Millis=[1472638138734], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472638138698]}
08-31 12:08:58.735   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 12:08:58.735   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-31 12:08:58.735   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 12:08:58.737   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 12:08:58.743  1493  2400 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-31 12:08:58.743  1493  2400 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 12:08:58.743  1493  2400 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 12:08:58.743  1493  2400 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 12:08:58.755  1694  4134 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-31 12:08:58.770  3970  3970 I art     : Waiting for a blocking GC DisableMovingGc
,08-31 12:08:58.773  3970  3970 I art     : Starting a blocking GC DisableMovingGc
,08-31 12:08:58.891  3970  4137 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 12:08:58.907   873  2045 I ActivityManager: Killing 3663:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 12:08:59.194   873  2161 D WifiService: setWifiEnabled: false pid=3867, uid=10000
,08-31 12:08:59.194   873  2161 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 12:08:59.229  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 12:08:59.236   873  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 12:08:59.236   873  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 12:08:59.237   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 12:08:59.237   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:08:59.262   873  1301 E native  : do suspend true
,08-31 12:08:59.279   873  1889 D DhcpClient: Clearing IP address
,08-31 12:08:59.280   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 12:08:59.299   370   871 D CommandListener: Setting iface cfg
,08-31 12:08:59.307   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 12:08:59.308   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-31 12:08:59.311   401   401 E Parcel  : Reading a NULL string not supported here.
,08-31 12:08:59.318   873  1301 D WifiStateMachine: Start Disconnecting Watchdog 2,
,08-31 12:08:59.322   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 12:08:59.322   873  1301 E native  : do suspend true
08-31 12:08:59.322   873  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-31 12:08:59.329   873  4117 D DhcpClient: Receive thread stopped
,08-31 12:08:59.376   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:08:59.431   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:08:59.432   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 12:08:59.432   873  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 12:08:59.433   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:08:59.438   873   890 D Tethering: MasterInitialState.processMessage what=3,
08-31 12:08:59.449  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:59.449  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:08:59.450  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:59.450  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:59.453  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:59.453  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:08:59.454  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:59.454  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:59.463  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 12:08:59.468  1694  1694 D SystemUpdateService: onCreate
08-31 12:08:59.472  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 12:08:59.488  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 12:08:59.494  1694  2460 I iu.UploadsManager: num queued entries: 0
,08-31 12:08:59.494  1694  2460 I iu.UploadsManager: num updated entries: 0
08-31 12:08:59.495  1694  2460 I iu.SyncManager: NEXT; no task
,08-31 12:08:59.497  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 12:08:59.498  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 12:08:59.501  4012  4012 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:08:59.506  4012  4012 D SprintDMHelper: simOperator: 
,08-31 12:08:59.506  4012  4012 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 12:08:59.529  3970  4155 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 12:08:59.539  1694  4150 I SystemUpdateService: active receiver: enabled
,08-31 12:08:59.545   370   871 E Netd    : netlink response contains error (No such file or directory)
08-31 12:08:59.545  1694  4150 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-31 12:08:59.546   873  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 12:08:59.546  1694  4150 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-31 12:08:59.546  1694  4150 I SystemUpdateService: now status is 0 (complete)
,08-31 12:08:59.546  1694  4150 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 12:08:59.547   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-31 12:08:59.547  1694  4150 I SystemUpdateService: file has been verified
08-31 12:08:59.548  1694  4150 I SystemUpdateService: OTA package size = 12249756
,08-31 12:08:59.552  1694  4150 I SystemUpdateService: showing system update notification
,08-31 12:08:59.562   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 12:08:59.567  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:59.567  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:08:59.568  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:59.568   873  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 12:08:59.568  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:59.570  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:08:59.571  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:08:59.571  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 12:08:59.571  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:08:59.572  1900  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 12:08:59.576  1694  1694 D SystemUpdateService: onDestroy
,08-31 12:08:59.639   873  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 12:09:02.247   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dfcb342:true
,08-31 12:09:02.247  3998  3998 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 12:09:02.252  3998  3998 I bt_bluedroid: init
,08-31 12:09:02.253  3998  4158 I BluetoothAdapterState: Entering OffState
,08-31 12:09:02.260  3998  4159 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 12:09:02.261  3998  4159 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 12:09:02.261  3998  4159 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 12:09:02.261  3998  4159 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 12:09:02.264  3998  3998 I bt_bluedroid: get_profile_interface socket
,08-31 12:09:02.267  3998  4162 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 12:09:02.270  3998  3998 I bt_bluedroid: get_profile_interface sdp
,08-31 12:09:02.272  3998  4162 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 12:09:02.274  3998  4009 I bt_bluedroid: config_hci_snoop_log
,08-31 12:09:02.278   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 12:09:02.289  3998  4158 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 12:09:02.290  3998  4158 D BluetoothAdapterProperties: Setting state to 14
,08-31 12:09:02.290  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 12:09:02.292  3998  4158 D BluetoothBondStateMachine: make
,08-31 12:09:02.293  3998  4163 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 12:09:02.296  3998  4158 I BluetoothAdapterState: Entering PendingCommandState
,08-31 12:09:02.297  3998  3998 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 12:09:02.301  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:02.301  3998  3998 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 12:09:02.302  3998  3998 D BtGatt.GattService: Received start request. Starting profile...
,08-31 12:09:02.303  3998  3998 D BtGatt.GattService: start()
,08-31 12:09:02.303  3998  3998 I bt_bluedroid: get_profile_interface gatt
08-31 12:09:02.304  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:09:02.304  3998  3998 D BtGatt.AdvertiseManager: advertise manager created
,08-31 12:09:02.310  3998  3998 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:02.310  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:02.310  3998  3998 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 12:09:02.310  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:02.311  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 12:09:02.311  3998  4158 I bt_bluedroid: enable
,08-31 12:09:02.311  3998  4159 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 12:09:02.311  3998  4159 I bt_hci  : start_up
,08-31 12:09:02.318  3998  4159 I bt_vendor: alloc value 0xb39b9189
,08-31 12:09:02.318  3998  4159 I bt_vendor: init
08-31 12:09:02.318  3998  4159 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 12:09:02.318  3998  4159 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 12:09:02.425  3998  4159 D bt_hci  : start_up starting async portion
,08-31 12:09:02.425  3998  4166 I bt_hci  : event_finish_startup
08-31 12:09:02.426  3998  4166 I bt_hci_h4: hal_open
08-31 12:09:02.426  3998  4166 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 12:09:02.435  3998  4166 I bt_userial_vendor: device fd = 51 open
,08-31 12:09:02.467  3998  4166 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 12:09:02.499  3998  4166 D bt_hwcfg: Chipset BCM4354A2
,08-31 12:09:02.499  3998  4166 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 12:09:02.500  3998  4166 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 12:09:03.158  3998  4166 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 12:09:03.160  3998  4166 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 12:09:03.160  3998  4166 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 12:09:03.278  3998  4166 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 12:09:03.280  3998  4166 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 12:09:03.307  3998  4166 I bt_hwcfg: vendor lib fwcfg completed
,08-31 12:09:03.308  3998  4166 I bt_vendor: firmware callback
,08-31 12:09:03.308  3998  4166 I bt_hci  : firmware_config_callback
,08-31 12:09:03.321  3998  4168 I bt_btu  : btu_task pending for preload complete event
,08-31 12:09:03.321  3998  4168 I bt_btu_task: Bluetooth chip preload is complete
,08-31 12:09:03.322  3998  4168 I bt_btu  : btu_task received preload complete event
,08-31 12:09:03.333  3998  4168 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 12:09:03.333  3998  4168 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 12:09:03.334  3998  4168 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 12:09:03.334  3998  4168 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 12:09:03.334  3998  4168 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 12:09:03.335  3998  4168 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 12:09:03.336  3998  4168 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 12:09:03.336  3998  4168 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 12:09:03.336  3998  4168 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 12:09:03.337  3998  4168 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 12:09:03.337  3998  4168 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 12:09:03.338  3998  4168 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 12:09:03.339  3998  4168 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 12:09:03.341  3998  4168 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 12:09:03.341  3998  4168 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 12:09:03.476  3998  4168 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
08-31 12:09:03.476  3998  4168 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-31 12:09:03.501  3998  4162 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 12:09:03.503  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 12:09:03.504  3998  4162 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 12:09:03.511  3998  4162 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 12:09:03.515  3998  4162 D BluetoothAdapterProperties: Scan Mode:20
,08-31 12:09:03.518  3998  4162 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 12:09:03.520  3998  4162 D bt_hci  : do_postload posting postload work item
,08-31 12:09:03.520  3998  4166 I bt_hci  : event_postload
08-31 12:09:03.520  3998  4166 I bt_vendor: sco_config_cb
08-31 12:09:03.520  3998  4166 I bt_hci  : sco_config_callback postload finished.
08-31 12:09:03.521  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:03.525  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:03.526  3998  4166 I bt_vendor: low_power_mode_cb
,08-31 12:09:03.529  3998  4162 D bt_bte_conf: Device ID record 1 : primary
,08-31 12:09:03.529  3998  4162 D bt_bte_conf:   vendorId            = 000f
08-31 12:09:03.530  3998  4162 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 12:09:03.530  3998  4162 D bt_bte_conf:   product             = 1200
,08-31 12:09:03.530  3998  4162 D bt_bte_conf:   version             = 1436
08-31 12:09:03.530  3998  4162 D bt_bte_conf:   clientExecutableURL = 
08-31 12:09:03.530  3998  4162 D bt_bte_conf:   serviceDescription  = 
,08-31 12:09:03.530  3998  4162 D bt_bte_conf:   documentationURL    = 
,08-31 12:09:03.530  3998  4162 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 12:09:03.531  3998  4159 D bt_stack_manager: event_start_up_stack finished
08-31 12:09:03.532  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 12:09:03.532  3998  4158 D BluetoothAdapterProperties: Setting state to 15
08-31 12:09:03.532  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 12:09:03.533  3998  4158 I BluetoothAdapterState: Entering BleOnState
08-31 12:09:03.537  3998  4158 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 12:09:03.537  3998  4158 D BluetoothAdapterProperties: Setting state to 11
,08-31 12:09:03.537  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 12:09:03.545  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:03.546  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:09:03.547  3998  3998 D HeadsetService: Received start request. Starting profile...
,08-31 12:09:03.550  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:03.551  3998  3998 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 12:09:03.551  3998  3998 D HeadsetStateMachine: make
,08-31 12:09:03.559  3998  4158 I BluetoothAdapterState: Entering PendingCommandState
,08-31 12:09:03.561  3998  3998 D HeadsetStateMachine: max_hf_connections = 1
,08-31 12:09:03.561  3998  3998 I bt_bluedroid: get_profile_interface handsfree
,08-31 12:09:03.561  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 12:09:03.561  3998  4162 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 12:09:03.565  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:03.565  3998  3998 D A2dpService: Received start request. Starting profile...
,08-31 12:09:03.566  3998  3998 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 12:09:03.566  3998  3998 I bt_bluedroid: get_profile_interface avrcp
,08-31 12:09:03.573  3998  3998 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 12:09:03.573  3998  3998 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 12:09:03.573  3998  3998 D A2dpStateMachine: make
,08-31 12:09:03.574  3998  3998 I bt_bluedroid: get_profile_interface a2dp
08-31 12:09:03.575  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 12:09:03.576  3998  4178 D A2dpStateMachine: Enter Disconnected: -2
08-31 12:09:03.577  3998  3998 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 12:09:03.578  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:03.580  3998  3998 D HidService: Received start request. Starting profile...
,08-31 12:09:03.580  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 12:09:03.580  3998  3998 I bt_bluedroid: get_profile_interface hidhost
08-31 12:09:03.580  3998  3998 D HidService: setHidService(): set to: null
08-31 12:09:03.580  3998  4162 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-31 12:09:03.581  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 12:09:03.581  3998  3998 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 12:09:03.581  3922  3922 D BluetoothInputDevice: Proxy object connected
08-31 12:09:03.582  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:03.583  3922  3922 D HidProfile: Bluetooth service connected
08-31 12:09:03.583  3998  3998 D HealthService: Received start request. Starting profile...
08-31 12:09:03.586  3998  3998 I bt_bluedroid: get_profile_interface health
08-31 12:09:03.587  3998  3998 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 12:09:03.590  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:03.591  3998  3998 D PanService: Received start request. Starting profile...
,08-31 12:09:03.592  3998  3998 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 12:09:03.592  3998  3998 I bt_bluedroid: get_profile_interface pan
,08-31 12:09:03.593  3998  4162 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 12:09:03.592  3922  3922 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 12:09:03.596  3922  3922 D PanProfile: Bluetooth service connected
08-31 12:09:03.596  3998  3998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3,
,08-31 12:09:03.599  3998  3998 D BluetoothMapService: Received start request. Starting profile...
08-31 12:09:03.600  3998  3998 D BluetoothMapService: start()
08-31 12:09:03.600  3922  3922 D BluetoothMap: Proxy object connected
,08-31 12:09:03.602  3922  3922 D MapProfile: Bluetooth service connected
,08-31 12:09:03.602  3922  3922 D BluetoothMap: getConnectedDevices()
08-31 12:09:03.602  3998  3998 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 12:09:03.603  3998  3998 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 12:09:03.603  3998  3998 D BluetoothMapAppObserver: createReceiver()
,08-31 12:09:03.603  3922  3922 D BluetoothMap: Bluetooth is Not enabled
,08-31 12:09:03.604  3998  3998 D BluetoothMapAppObserver: initObservers()
,08-31 12:09:03.604  3998  3998 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 12:09:03.611  3998  3998 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:03.611  3998  3998 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:03.611  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 12:09:03.611  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:03.614  3998  3998 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:03.614  3998  3998 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:03.614  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 12:09:03.614  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:03.614  3998  4176 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 12:09:03.614  3998  3998 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:03.614  3998  3998 V BluetoothAdapterState: isTurningOn()=true
,08-31 12:09:03.615  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:03.615  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:09:03.615  3998  3998 V BluetoothAdapterState: isTurningOff()=false
,08-31 12:09:03.615  3998  3998 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:03.615  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:03.615  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isTurningOff()=false
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isTurningOn()=true
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isTurningOff()=false
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isTurningOn()=true
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 12:09:03.616  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:03.617  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 12:09:03.617  3998  4158 D BluetoothAdapterProperties: ScanMode =  20
08-31 12:09:03.617  3998  4158 D BluetoothAdapterProperties: State =  11
08-31 12:09:03.620  3998  4162 D BluetoothAdapterProperties: Scan Mode:21
08-31 12:09:03.621  3998  4162 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 12:09:03.621  3998  4158 D BluetoothAdapterProperties: Setting state to 12
,08-31 12:09:03.621  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 12:09:03.621  1346  3866 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:03.625  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:03.626  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:03.627  3998  4158 I BluetoothAdapterState: Entering OnState
08-31 12:09:03.627  1346  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:03.630  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:09:03.630  3922  3932 D BluetoothMap: onBluetoothStateChange: up=true
08-31 12:09:03.631  3922  3934 D BluetoothPan: onBluetoothStateChange on: true
,08-31 12:09:03.632  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 12:09:03.631  3922  3932 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 12:09:03.632  1346  2049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 12:09:03.634  3998  3998 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 12:09:03.634   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:03.635  3998  3998 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 12:09:03.635  1346  1346 D BluetoothMap: Proxy object connected
,08-31 12:09:03.635  1346  1346 D MapProfile: Bluetooth service connected
08-31 12:09:03.635  1346  1346 D BluetoothMap: getConnectedDevices()
08-31 12:09:03.635  3922  3932 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 12:09:03.637  3998  3998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 12:09:03.638  1346  3866 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 12:09:03.638  1346  1346 D BluetoothInputDevice: Proxy object connected
08-31 12:09:03.638  1346  1346 D HidProfile: Bluetooth service connected
08-31 12:09:03.638  1346  1363 D BluetoothPan: onBluetoothStateChange on: true
,08-31 12:09:03.639  3998  3998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 12:09:03.640  3998  3998 D ObexServerSockets: Succeed to create listening sockets 
,08-31 12:09:03.640  3998  3998 D ObexServerSockets0: startAccept()
08-31 12:09:03.640  3998  3998 D ObexServerSockets0: prepareForNewConnect()
,08-31 12:09:03.641   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 12:09:03.641   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 12:09:03.641   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 12:09:03.642  1943  1959 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:03.642  1346  3866 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 12:09:03.643  3998  3998 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 12:09:03.643  3998  3998 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 12:09:03.643  3998  4186 D ObexServerSockets0: Accepting socket connection...
08-31 12:09:03.644  3998  4187 D ObexServerSockets0: Accepting socket connection...
08-31 12:09:03.644   873   873 D BluetoothA2dp: Proxy object connected
08-31 12:09:03.648   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 12:09:03.648  3998  3998 D BluetoothMapService: onReceive
08-31 12:09:03.648  3998  3998 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 12:09:03.648  3998  3998 D BluetoothMapService: STATE_ON
,08-31 12:09:03.649  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:03.650  3922  3922 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 12:09:03.650  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:03.653  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 12:09:03.653  1346  1346 D PanProfile: Bluetooth service connected
,08-31 12:09:03.653  1346  1346 D BluetoothA2dp: Proxy object connected
08-31 12:09:03.655  3922  3922 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 12:09:03.660  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 12:09:03.662  3922  3922 D BluetoothA2dp: Proxy object connected
,08-31 12:09:03.666  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 12:09:03.673  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-31 12:09:03.674  3922  3922 D BluetoothPbap: Proxy object connected
,08-31 12:09:03.675  3922  3922 D PbapServerProfile: Bluetooth service connected
,08-31 12:09:03.676  3998  3998 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 12:09:03.676  3998  3998 D ObexServerSockets0: prepareForNewConnect()
,08-31 12:09:03.689  1346  1346 D BluetoothPbap: Proxy object connected
,08-31 12:09:03.689  1346  1346 D PbapServerProfile: Bluetooth service connected
,08-31 12:09:03.694  3998  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 12:09:03.716  3998  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 12:09:03.717  3998  4196 I BtOppRfcommListener: Accept thread started.
,08-31 12:09:03.737  1346  3866 D BluetoothHeadset: Proxy object connected
,08-31 12:09:03.738  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-31 12:09:03.738   873   873 D BluetoothHeadset: Proxy object connected
,08-31 12:09:03.738   873   873 D BluetoothHeadset: Proxy object connected
08-31 12:09:03.738   873   873 D BluetoothHeadset: Proxy object connected
08-31 12:09:03.738  1943  2108 D BluetoothHeadset: Proxy object connected
08-31 12:09:03.740  1346  1364 D BluetoothHeadset: Proxy object connected
08-31 12:09:03.740  1346  1346 D HeadsetProfile: Bluetooth service connected
08-31 12:09:03.741   873   890 D BluetoothHeadset: Proxy object connected
08-31 12:09:03.741   873   890 D BluetoothHeadset: Proxy object connected
,08-31 12:09:03.743  1943  1957 D BluetoothHeadset: Proxy object connected
,08-31 12:09:03.757  3922  4184 D BluetoothHeadset: Proxy object connected
,08-31 12:09:03.758  3922  3922 D HeadsetProfile: Bluetooth service connected
,08-31 12:09:05.210  3998  4158 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 12:09:05.211  3998  4158 D BluetoothAdapterProperties: Setting state to 13
,08-31 12:09:05.211  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 12:09:05.213  3998  4158 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 12:09:05.216  3998  4158 I BluetoothAdapterState: Entering PendingCommandState
,08-31 12:09:05.222  3998  3998 D BluetoothMapService: onReceive
08-31 12:09:05.222  3998  3998 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 12:09:05.223  3998  3998 D BluetoothMapService: STATE_TURNING_OFF
08-31 12:09:05.224  3998  3998 D BluetoothMapService: MAP Service closeService in
08-31 12:09:05.224  3998  3998 D BluetoothMapMasInstance0: MAP Service shutdown
,08-31 12:09:05.224  3998  3998 D ObexServerSockets0: shutdown(block = true),
,08-31 12:09:05.226  3998  4186 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 12:09:05.228  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:05.229  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:05.228  3998  3998 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 12:09:05.231  3998  3998 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 12:09:05.231  3998  4187 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 12:09:05.232  3998  4171 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 12:09:05.232  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:09:05.233  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 12:09:05.234  3998  4162 D BluetoothAdapterProperties: Scan Mode:20
08-31 12:09:05.235  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 12:09:05.234  3998  3998 I BtOppRfcommListener: stopping Accept Thread
08-31 12:09:05.237  3998  4196 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 12:09:05.240  3998  4196 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 12:09:05.240  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 12:09:05.242  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:05.242  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:09:05.244  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 12:09:05.244  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 12:09:05.246  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:05.247  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:05.249  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-31 12:09:05.250  3998  3998 D HeadsetService: Received stop request...Stopping profile...
08-31 12:09:05.252  1346  1363 D BluetoothHeadset: Proxy object disconnected
08-31 12:09:05.252  1346  1346 D HeadsetProfile: Bluetooth service disconnected
,08-31 12:09:05.253  3998  3998 D A2dpService: Received stop request...Stopping profile...
08-31 12:09:05.253  3998  4178 D A2dpStateMachine: Exit Disconnected: -1
08-31 12:09:05.254  3922  4184 D BluetoothHeadset: Proxy object disconnected
08-31 12:09:05.254   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 12:09:05.254  3922  3922 D HeadsetProfile: Bluetooth service disconnected,
08-31 12:09:05.254   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 12:09:05.254   873   873 D BluetoothHeadset: Proxy object disconnected
,08-31 12:09:05.255  3922  3922 D BluetoothA2dp: Proxy object disconnected
08-31 12:09:05.255  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-31 12:09:05.255  1943  1959 D BluetoothHeadset: Proxy object disconnected
,08-31 12:09:05.255   873   873 D BluetoothA2dp: Proxy object disconnected
08-31 12:09:05.256  3998  3998 D HidService: Received stop request...Stopping profile...
,08-31 12:09:05.256  3998  3998 D HidService: Stopping Bluetooth HidService
08-31 12:09:05.257  3922  3922 D BluetoothInputDevice: Proxy object disconnected
08-31 12:09:05.257  1346  1346 D BluetoothInputDevice: Proxy object disconnected
,08-31 12:09:05.257  1346  1346 D HidProfile: Bluetooth service disconnected
08-31 12:09:05.259  3998  3998 D HealthService: Received stop request...Stopping profile...
08-31 12:09:05.262  3922  3922 D HidProfile: Bluetooth service disconnected
,08-31 12:09:05.262  3998  3998 D PanService: Received stop request...Stopping profile...
08-31 12:09:05.262  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 12:09:05.263  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-31 12:09:05.263  1346  1346 D PanProfile: Bluetooth service disconnected
08-31 12:09:05.265  3998  3998 D BluetoothMapService: Received stop request...Stopping profile...
08-31 12:09:05.265  3998  3998 D BluetoothMapService: stop()
08-31 12:09:05.265  3922  3922 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 12:09:05.265  3922  3922 D PanProfile: Bluetooth service disconnected
08-31 12:09:05.265  3998  3998 D BluetoothMapAppObserver: deinitObservers()
,08-31 12:09:05.265  3998  3998 D BluetoothMapAppObserver: removeReceiver()
08-31 12:09:05.266  3922  3922 D BluetoothMap: Proxy object disconnected
08-31 12:09:05.267  3998  3998 V BluetoothAdapterState: isTurningOff()=true
08-31 12:09:05.267  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:05.266  3922  3922 D MapProfile: Bluetooth service disconnected,
08-31 12:09:05.267  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:05.267  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:09:05.267  1346  1346 D BluetoothMap: Proxy object disconnected
08-31 12:09:05.267  1346  1346 D MapProfile: Bluetooth service disconnected
08-31 12:09:05.268  3998  3998 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 12:09:05.268  3998  3998 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 12:09:05.268  3998  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:09:05.269  3998  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 12:09:05.269  3998  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:09:05.269  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 12:09:05.269  3998  4162 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 12:09:05.270  3998  3998 V BluetoothAdapterState: isTurningOff()=true
08-31 12:09:05.270  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:05.270  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:05.271  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:09:05.272  3998  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:09:05.272  3998  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:09:05.272  3998  4168 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 12:09:05.272  3998  4168 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 12:09:05.272  3998  4168 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 12:09:05.272  3998  4168 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 12:09:05.272  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 12:09:05.273  3998  3998 V BluetoothAdapterState: isTurningOff()=true
,08-31 12:09:05.273  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:05.273  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:05.273  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:09:05.273  3998  3998 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-31 12:09:05.274  3998  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 12:09:05.274  3998  3998 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 12:09:05.276  3922  3922 D BluetoothPbap: Proxy object disconnected
,08-31 12:09:05.276  1346  1346 D BluetoothPbap: Proxy object disconnected
,08-31 12:09:05.276  1346  1346 D PbapServerProfile: Bluetooth service disconnected
08-31 12:09:05.277  3998  3998 V BluetoothAdapterState: isTurningOff()=true
08-31 12:09:05.276  3922  3922 D PbapServerProfile: Bluetooth service disconnected
08-31 12:09:05.277  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:05.277  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:05.277  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:05.277  3998  3998 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 12:09:05.277  3998  4162 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 12:09:05.277  3998  3998 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 12:09:05.278  3998  3998 V BluetoothAdapterState: isTurningOff()=true
08-31 12:09:05.278  3998  3998 V BluetoothAdapterState: isTurningOn()=false
,08-31 12:09:05.278  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:05.278  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:05.278  3998  3998 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 12:09:05.279  3998  3998 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 12:09:05.280  3998  3998 D BluetoothMapService: MAP Service closeService in
08-31 12:09:05.280  3998  3998 V BluetoothAdapterState: isTurningOff()=true
08-31 12:09:05.280  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:05.280  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:05.280  3998  3998 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:05.280  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 12:09:05.280  3998  3998 D BluetoothMapService: cleanup()
,08-31 12:09:05.281  3998  3998 D BluetoothMapService: MAP Service closeService in
08-31 12:09:05.281  3998  4158 D BluetoothAdapterProperties: Setting state to 15
08-31 12:09:05.281  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 12:09:05.282  3998  4158 I BluetoothAdapterState: Entering BleOnState
08-31 12:09:05.282  1346  3866 D BluetoothMap: onBluetoothStateChange: up=false
08-31 12:09:05.284  1346  1363 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 12:09:05.285  3922  3934 D BluetoothMap: onBluetoothStateChange: up=false
08-31 12:09:05.286  3922  4184 D BluetoothPan: onBluetoothStateChange on: false
08-31 12:09:05.287  3922  3932 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 12:09:05.288  1346  2049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 12:09:05.288   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:09:05.288  3922  3934 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 12:09:05.289  3922  4184 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 12:09:05.290  1346  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:09:05.290  3922  3932 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 12:09:05.291  1346  3866 D BluetoothPan: onBluetoothStateChange on: false
,08-31 12:09:05.292   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 12:09:05.292   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 12:09:05.292   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 12:09:05.292  1943  2108 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 12:09:05.292  1346  1363 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 12:09:05.293  3998  4158 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 12:09:05.293  3998  4158 D BluetoothAdapterProperties: Setting state to 16
,08-31 12:09:05.293  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 12:09:05.294  3998  4158 D BluetoothAdapterProperties: onBleDisable
08-31 12:09:05.294  3998  4158 I BluetoothAdapterState: Entering PendingCommandState
08-31 12:09:05.294  3998  4159 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 12:09:05.295  3998  4168 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 12:09:05.295  3998  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 12:09:05.296  3998  4162 D BluetoothAdapterProperties: Scan Mode:20
,08-31 12:09:05.298  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:05.299  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:05.299  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 12:09:05.300  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:05.303  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:05.304  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 12:09:05.307  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-31 12:09:05.496  3998  4162 I bt_hci  : shut_down
,08-31 12:09:05.507  3998  4166 D bt_hwcfg: hw_epilog_process
,08-31 12:09:05.508  3998  4166 I bt_vendor: low_power_mode_cb
,08-31 12:09:05.526  3998  4166 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 12:09:05.526  3998  4166 I bt_vendor: epilog_cb
,08-31 12:09:05.526  3998  4166 I bt_hci  : epilog_finished_callback
,08-31 12:09:05.531  3998  4162 I bt_hci_h4: hal_close
,08-31 12:09:05.533  3998  4162 I bt_userial_vendor: device fd = 51 close
,08-31 12:09:05.647  3998  4159 D bt_stack_manager: event_shut_down_stack finished.
,08-31 12:09:05.648  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 12:09:05.653  3998  4158 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 12:09:05.654  3998  3998 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 12:09:05.655  3998  3998 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 12:09:05.656  3998  3998 D BtGatt.GattService: stop()
08-31 12:09:05.656  3998  3998 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 12:09:05.660  3998  3998 V BluetoothAdapterState: isTurningOff()=false
,08-31 12:09:05.661  3998  3998 V BluetoothAdapterState: isTurningOn()=false
08-31 12:09:05.661  3998  3998 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 12:09:05.661  3998  3998 V BluetoothAdapterState: isBleTurningOff()=true
08-31 12:09:05.663  3998  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 12:09:05.664  3998  4158 D BluetoothAdapterProperties: Setting state to 10
,08-31 12:09:05.664  3998  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 12:09:05.667  3998  4158 I BluetoothAdapterState: Entering OffState
08-31 12:09:05.668   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 12:09:05.688  3998  3998 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 12:09:05.688  3998  3998 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-31 12:09:05.688  3998  4159 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 12:09:05.692  3998  4159 D bt_stack_manager: event_clean_up_stack finished.
,08-31 12:09:05.692  3998  3998 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 12:09:05.695  3998  3998 I art     : System.exit called, status: 0
,08-31 12:09:05.695  3998  3998 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 12:09:05.755   873  1951 I ActivityManager: Process com.android.bluetooth (pid 3998) has died
,08-31 12:09:06.566   873  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-31 12:09:08.208  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 12:09:08.208  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:11.216  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 12:09:11.217  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a3df48 added. We now have 6 listener(s)
08-31 12:09:11.218  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:09:11.221  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 12:09:11.222  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7e31e1 added. We now have 7 listener(s)
08-31 12:09:11.222  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:09:11.223  3867  3913 I System.out: IsBluetoothEnabled
,08-31 12:09:11.234  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:11.277   873   890 I ActivityManager: Start proc 4206:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 12:09:11.387  4206  4206 D AdapterServiceConfig: Adding HeadsetService
,08-31 12:09:11.387  4206  4206 D AdapterServiceConfig: Adding A2dpService
,08-31 12:09:11.387  4206  4206 D AdapterServiceConfig: Adding HidService
08-31 12:09:11.388  4206  4206 D AdapterServiceConfig: Adding HealthService
08-31 12:09:11.388  4206  4206 D AdapterServiceConfig: Adding PanService
08-31 12:09:11.388  4206  4206 D AdapterServiceConfig: Adding GattService
08-31 12:09:11.388  4206  4206 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 12:09:11.402   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e688a77:true
,08-31 12:09:11.403  4206  4206 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 12:09:11.412  4206  4206 I bt_bluedroid: init
,08-31 12:09:11.413  4206  4218 I BluetoothAdapterState: Entering OffState
,08-31 12:09:11.417  4206  4219 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 12:09:11.417  4206  4219 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 12:09:11.417  4206  4219 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 12:09:11.417  4206  4219 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 12:09:11.418  4206  4206 I bt_bluedroid: get_profile_interface socket
,08-31 12:09:11.422  4206  4206 I bt_bluedroid: get_profile_interface sdp
,08-31 12:09:11.425  4206  4222 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 12:09:11.428  4206  4222 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 12:09:11.428  4206  4217 I bt_bluedroid: config_hci_snoop_log,
08-31 12:09:11.430   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 12:09:11.437  4206  4218 D BluetoothAdapterState: Current state: OFF, message: 0
08-31 12:09:11.437  4206  4218 D BluetoothAdapterProperties: Setting state to 14
08-31 12:09:11.438  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 12:09:11.440  4206  4218 D BluetoothBondStateMachine: make
,08-31 12:09:11.443  4206  4223 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 12:09:11.449  4206  4218 I BluetoothAdapterState: Entering PendingCommandState
,08-31 12:09:11.452  4206  4206 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 12:09:11.460  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:11.462  4206  4206 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 12:09:11.463  4206  4206 D BtGatt.GattService: Received start request. Starting profile...
,08-31 12:09:11.464  4206  4206 D BtGatt.GattService: start()
08-31 12:09:11.464  4206  4206 I bt_bluedroid: get_profile_interface gatt
,08-31 12:09:11.466  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:11.467  4206  4206 D BtGatt.AdvertiseManager: advertise manager created
,08-31 12:09:11.478  4206  4206 V BluetoothAdapterState: isTurningOff()=false
,08-31 12:09:11.478  4206  4206 V BluetoothAdapterState: isTurningOn()=false
,08-31 12:09:11.478  4206  4206 V BluetoothAdapterState: isBleTurningOn()=true
08-31 12:09:11.478  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 12:09:11.479  4206  4218 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 12:09:11.479  4206  4218 I bt_bluedroid: enable
08-31 12:09:11.480  4206  4219 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 12:09:11.480  4206  4219 I bt_hci  : start_up
,08-31 12:09:11.493  4206  4219 I bt_vendor: alloc value 0xb3a20189
,08-31 12:09:11.493  4206  4219 I bt_vendor: init
08-31 12:09:11.493  4206  4219 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 12:09:11.494  4206  4219 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 12:09:11.602  4206  4219 D bt_hci  : start_up starting async portion
,08-31 12:09:11.603  4206  4226 I bt_hci  : event_finish_startup
08-31 12:09:11.603  4206  4226 I bt_hci_h4: hal_open
08-31 12:09:11.603  4206  4226 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 12:09:11.616  4206  4226 I bt_userial_vendor: device fd = 51 open
,08-31 12:09:11.644  4206  4226 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 12:09:11.676  4206  4226 D bt_hwcfg: Chipset BCM4354A2
,08-31 12:09:11.676  4206  4226 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 12:09:11.677  4206  4226 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 12:09:12.330  4206  4226 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-31 12:09:12.332  4206  4226 D bt_hwcfg: Settlement delay -- 100 ms
08-31 12:09:12.332  4206  4226 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 12:09:12.449  4206  4226 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-31 12:09:12.450  4206  4226 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 12:09:12.480  4206  4226 I bt_hwcfg: vendor lib fwcfg completed
,08-31 12:09:12.480  4206  4226 I bt_vendor: firmware callback
,08-31 12:09:12.481  4206  4226 I bt_hci  : firmware_config_callback
,08-31 12:09:12.493  4206  4228 I bt_btu  : btu_task pending for preload complete event
,08-31 12:09:12.493  4206  4228 I bt_btu_task: Bluetooth chip preload is complete,
,08-31 12:09:12.493  4206  4228 I bt_btu  : btu_task received preload complete event
,08-31 12:09:12.505  4206  4228 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 12:09:12.506  4206  4228 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 12:09:12.506  4206  4228 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 12:09:12.506  4206  4228 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 12:09:12.507  4206  4228 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 12:09:12.507  4206  4228 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 12:09:12.507  4206  4228 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 12:09:12.508  4206  4228 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 12:09:12.508  4206  4228 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 12:09:12.508  4206  4228 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 12:09:12.509  4206  4228 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 12:09:12.509  4206  4228 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 12:09:12.509  4206  4228 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 12:09:12.510  4206  4228 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 12:09:12.510  4206  4228 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 12:09:12.640  4206  4228 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399dd9d
,08-31 12:09:12.640  4206  4228 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399dd9d 
,08-31 12:09:12.663  4206  4222 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-31 12:09:12.665  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 12:09:12.666  4206  4222 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 12:09:12.668  4206  4222 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 12:09:12.673  4206  4222 D BluetoothAdapterProperties: Scan Mode:20
,08-31 12:09:12.673  4206  4222 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 12:09:12.674  4206  4222 D bt_hci  : do_postload posting postload work item
,08-31 12:09:12.674  4206  4226 I bt_hci  : event_postload
08-31 12:09:12.674  4206  4226 I bt_vendor: sco_config_cb
08-31 12:09:12.674  4206  4226 I bt_hci  : sco_config_callback postload finished.
,08-31 12:09:12.678  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:12.681  4206  4222 D bt_bte_conf: Device ID record 1 : primary
,08-31 12:09:12.681  4206  4222 D bt_bte_conf:   vendorId            = 000f
,08-31 12:09:12.681  4206  4222 D bt_bte_conf:   vendorIdSource      = 0001
08-31 12:09:12.681  4206  4222 D bt_bte_conf:   product             = 1200
,08-31 12:09:12.681  4206  4222 D bt_bte_conf:   version             = 1436
,08-31 12:09:12.682  4206  4222 D bt_bte_conf:   clientExecutableURL = 
08-31 12:09:12.682  4206  4222 D bt_bte_conf:   serviceDescription  = 
,08-31 12:09:12.682  4206  4222 D bt_bte_conf:   documentationURL    = 
08-31 12:09:12.682  4206  4222 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 12:09:12.682  4206  4219 D bt_stack_manager: event_start_up_stack finished
08-31 12:09:12.683  4206  4218 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 12:09:12.683  4206  4218 D BluetoothAdapterProperties: Setting state to 15
08-31 12:09:12.683  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 12:09:12.684  4206  4218 I BluetoothAdapterState: Entering BleOnState
08-31 12:09:12.684  4206  4226 I bt_vendor: low_power_mode_cb
08-31 12:09:12.689  4206  4218 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 12:09:12.689  4206  4218 D BluetoothAdapterProperties: Setting state to 11
08-31 12:09:12.689  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 12:09:12.696  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:12.701  4206  4206 D HeadsetService: Received start request. Starting profile...
,08-31 12:09:12.707  4206  4206 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 12:09:12.707  4206  4206 D HeadsetStateMachine: make
,08-31 12:09:12.710  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:12.713  4206  4218 I BluetoothAdapterState: Entering PendingCommandState
,08-31 12:09:12.721  4206  4206 D HeadsetStateMachine: max_hf_connections = 1
,08-31 12:09:12.721  4206  4206 I bt_bluedroid: get_profile_interface handsfree
,08-31 12:09:12.721  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 12:09:12.721  4206  4222 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 12:09:12.725  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:09:12.726  4206  4206 D A2dpService: Received start request. Starting profile...,
08-31 12:09:12.727  4206  4206 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 12:09:12.727  4206  4206 I bt_bluedroid: get_profile_interface avrcp
,08-31 12:09:12.733  4206  4206 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 12:09:12.733  4206  4206 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 12:09:12.734  4206  4206 D A2dpStateMachine: make
08-31 12:09:12.735  4206  4206 I bt_bluedroid: get_profile_interface a2dp
,08-31 12:09:12.735  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 12:09:12.737  4206  4236 D A2dpStateMachine: Enter Disconnected: -2
,08-31 12:09:12.738  4206  4206 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 12:09:12.739  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:12.739  4206  4206 D HidService: Received start request. Starting profile...
,08-31 12:09:12.739  4206  4206 I bt_bluedroid: get_profile_interface hidhost
08-31 12:09:12.739  4206  4206 D HidService: setHidService(): set to: null
08-31 12:09:12.740  4206  4222 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397f3e5
,08-31 12:09:12.740  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 12:09:12.740  4206  4206 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 12:09:12.741  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:09:12.742  4206  4206 D HealthService: Received start request. Starting profile...
,08-31 12:09:12.743  4206  4206 I bt_bluedroid: get_profile_interface health
08-31 12:09:12.743  4206  4206 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 12:09:12.744  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:09:12.745  4206  4206 D PanService: Received start request. Starting profile...
08-31 12:09:12.745  4206  4206 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 12:09:12.745  4206  4206 I bt_bluedroid: get_profile_interface pan
08-31 12:09:12.746  4206  4222 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 12:09:12.748  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
08-31 12:09:12.754  4206  4206 D BluetoothMapService: Received start request. Starting profile...
08-31 12:09:12.754  4206  4206 D BluetoothMapService: start()
08-31 12:09:12.756  4206  4206 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 12:09:12.757  4206  4206 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 12:09:12.757  4206  4206 D BluetoothMapAppObserver: createReceiver()
08-31 12:09:12.758  4206  4206 D BluetoothMapAppObserver: initObservers()
08-31 12:09:12.758  4206  4206 D BluetoothMapAppObserver: getEnabledAccountItems()
08-31 12:09:12.770  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:12.771  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:12.771  4206  4234 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 12:09:12.771  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:12.771  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 12:09:12.771  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:12.774  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-31 12:09:12.775  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-31 12:09:12.775  4206  4218 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 12:09:12.775  4206  4218 D BluetoothAdapterProperties: ScanMode =  20
08-31 12:09:12.775  4206  4218 D BluetoothAdapterProperties: State =  11
08-31 12:09:12.778  4206  4222 D BluetoothAdapterProperties: Scan Mode:21
08-31 12:09:12.778  4206  4222 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 12:09:12.778  4206  4218 D BluetoothAdapterProperties: Setting state to 12
08-31 12:09:12.778  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 12:09:12.779  1346  3866 D BluetoothMap: onBluetoothStateChange: up=true
08-31 12:09:12.780  4206  4218 I BluetoothAdapterState: Entering OnState
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:12.782  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:09:12.784  1346  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 12:09:12.785  1346  1346 D BluetoothMap: Proxy object connected
08-31 12:09:12.785  1346  1346 D MapProfile: Bluetooth service connected
08-31 12:09:12.785  1346  1346 D BluetoothMap: getConnectedDevices()
08-31 12:09:12.787  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 12:09:12.787  4206  4206 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 12:09:12.787  4206  4206 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 12:09:12.787  3922  3934 D BluetoothMap: onBluetoothStateChange: up=true
08-31 12:09:12.788  4206  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 12:09:12.791  4206  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 12:09:12.792  3922  3932 D BluetoothPan: onBluetoothStateChange on: true
08-31 12:09:12.792  4206  4206 D ObexServerSockets: Succeed to create listening sockets 
08-31 12:09:12.792  4206  4206 D ObexServerSockets0: startAccept()
08-31 12:09:12.792  4206  4206 D ObexServerSockets0: prepareForNewConnect()
08-31 12:09:12.794  4206  4206 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 12:09:12.794  4206  4206 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 12:09:12.794  3922  4184 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 12:09:12.794  4206  4244 D ObexServerSockets0: Accepting socket connection...
08-31 12:09:12.795  4206  4245 D ObexServerSockets0: Accepting socket connection...
08-31 12:09:12.795  1346  1346 D BluetoothInputDevice: Proxy object connected
08-31 12:09:12.795  1346  1346 D HidProfile: Bluetooth service connected
08-31 12:09:12.797  3922  3922 D BluetoothMap: Proxy object connected
08-31 12:09:12.797  3922  3922 D MapProfile: Bluetooth service connected
08-31 12:09:12.797  3922  3922 D BluetoothMap: getConnectedDevices()
08-31 12:09:12.797  1346  3866 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 12:09:12.799   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 12:09:12.800  3922  3934 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 12:09:12.800  1346  1346 D BluetoothA2dp: Proxy object connected
08-31 12:09:12.801  3922  3932 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 12:09:12.802  1346  1364 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:12.803  3922  3934 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:12.803  1346  2049 D BluetoothPan: onBluetoothStateChange on: true
08-31 12:09:12.803  3922  3922 D BluetoothInputDevice: Proxy object connected
08-31 12:09:12.803  3922  3922 D HidProfile: Bluetooth service connected
08-31 12:09:12.804  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 12:09:12.804  1346  1346 D PanProfile: Bluetooth service connected
08-31 12:09:12.805   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:12.805   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:12.805   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 12:09:12.805  3922  3922 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 12:09:12.805  3922  3922 D PanProfile: Bluetooth service connected
08-31 12:09:12.805  3922  3922 D BluetoothA2dp: Proxy object connected
08-31 12:09:12.805   873   873 D BluetoothA2dp: Proxy object connected
,08-31 12:09:12.805  1943  1959 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 12:09:12.805  1346  1363 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 12:09:12.807   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 12:09:12.808  4206  4206 D BluetoothMapService: onReceive
08-31 12:09:12.808  4206  4206 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 12:09:12.809  4206  4206 D BluetoothMapService: STATE_ON
,08-31 12:09:12.809  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:12.812  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 12:09:12.818  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 12:09:12.822  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-31 12:09:12.823  3922  3922 D BluetoothPbap: Proxy object connected
,08-31 12:09:12.823  3922  3922 D PbapServerProfile: Bluetooth service connected
,08-31 12:09:12.832  1346  1346 D BluetoothPbap: Proxy object connected
,08-31 12:09:12.832  1346  1346 D PbapServerProfile: Bluetooth service connected
,08-31 12:09:12.833  4206  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 12:09:12.839  4206  4206 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 12:09:12.839  4206  4206 D ObexServerSockets0: prepareForNewConnect()
,08-31 12:09:12.842  4206  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 12:09:12.843  4206  4255 I BtOppRfcommListener: Accept thread started.
,08-31 12:09:12.901  1346  1363 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.902  1346  1346 D HeadsetProfile: Bluetooth service connected
08-31 12:09:12.902  3922  4184 D BluetoothHeadset: Proxy object connected
,08-31 12:09:12.903   873   873 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.903   873   873 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.903   873   873 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.903  1943  2108 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.904  1346  1364 D BluetoothHeadset: Proxy object connected
,08-31 12:09:12.904  1346  1346 D HeadsetProfile: Bluetooth service connected
08-31 12:09:12.905  3922  3932 D BluetoothHeadset: Proxy object connected
,08-31 12:09:12.905   873   890 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.905   873   890 D BluetoothHeadset: Proxy object connected
08-31 12:09:12.903  3922  3922 D HeadsetProfile: Bluetooth service connected
08-31 12:09:12.907  1943  1957 D BluetoothHeadset: Proxy object connected
,08-31 12:09:12.921  3922  3922 D HeadsetProfile: Bluetooth service connected
,08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:13.257  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:13.265  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:13.269  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 12:09:13.269  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f3fb06 added. We now have 8 listener(s)
,08-31 12:09:13.269  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:09:13.276   873  2045 D WifiService: setWifiEnabled: false pid=3867, uid=10000
,08-31 12:09:13.276   873  2045 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 12:09:13.288  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:13.289   873  2152 D WifiService: setWifiEnabled: true pid=3867, uid=10000
08-31 12:09:13.290   873  2152 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 12:09:13.305   873  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:13.326  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 12:09:13.331  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:13.358   873  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-31 12:09:13.360   873  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 12:09:13.361   873  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 12:09:13.362   873  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 12:09:13.362   873  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 12:09:13.362   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 12:09:13.362   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 12:09:13.377   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 12:09:13.379   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 12:09:13.379   370   871 D CommandListener: Setting iface cfg
08-31 12:09:13.381   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
08-31 12:09:13.381   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 12:09:13.437   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 12:09:13.437   873  1301 E native  : do suspend true
,08-31 12:09:13.438   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 12:09:13.480   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:14.313  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:14.321  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-31 12:09:14.332  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 12:09:14.335  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 12:09:14.341  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bfd40f Bundle[{}]
,08-31 12:09:14.344  3867  3913 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 12:09:14.344  3867  3913 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 12:09:14.345  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 12:09:14.346  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 12:09:14.346  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 12:09:14.347  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 12:09:14.351  3867  3913 I System.out: Running OutgoingSocketThread
,08-31 12:09:14.354  3867  4261 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-31 12:09:14.357  3867  4261 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39974
,08-31 12:09:14.357  3867  4261 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 12:09:14.863   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 12:09:15.004   873  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.25 rxSuccessRate=10.44 delta 1000 -> 994
,08-31 12:09:15.007   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-31 12:09:15.007   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:09:15.021   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 12:09:15.094   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 12:09:15.096  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 12:09:15.354  3867  3913 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
08-31 12:09:15.355  3867  3913 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-31 12:09:15.364  3867  3913 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-31 12:09:15.366  3867  3913 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 12:09:15.367  3867  3913 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-31 12:09:15.372  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.372  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201e5c7 added. We now have 2 listener(s)
,08-31 12:09:15.374  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.374  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.374  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.374  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.375  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbba7f4 added. We now have 9 listener(s)
08-31 12:09:15.375  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.375  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 12:09:15.379  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:15.385  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:15.388  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:15.389  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:09:15.389  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 12:09:15.389  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@944c192 added. We now have 3 listener(s)
,08-31 12:09:15.391  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.391  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.391  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.391  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 12:09:15.391  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d1763 added. We now have 10 listener(s)
,08-31 12:09:15.391  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:09:15.392  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:09:15.392  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 12:09:15.392  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 12:09:15.392  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:09:15.392  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:09:15.392  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 12:09:15.392  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 12:09:15.392  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201e5c7 removed from the list,
08-31 12:09:15.392  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 12:09:15.392  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbba7f4 removed from the list
,08-31 12:09:15.392  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:15.393  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:09:15.393  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.394  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 12:09:15.394  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:15.407  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 12:09:15.407  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.407  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 12:09:15.407  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbba7f4 not in the list
,08-31 12:09:15.407  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.407  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.409  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:15.411  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.411  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 12:09:15.411  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.411  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2d1763 removed from the list
08-31 12:09:15.411  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:09:15.411  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.411  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:15.411  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 12:09:15.411  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@944c192 removed from the list
08-31 12:09:15.412  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.412  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe54f60 added. We now have 2 listener(s)
,08-31 12:09:15.414  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.414  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.414  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.414  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.415  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7123c19 added. We now have 9 listener(s)
,08-31 12:09:15.415  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.415  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 12:09:15.419  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:15.425  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:15.428  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:15.428  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:09:15.428  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.428  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4fc6bf added. We now have 3 listener(s)
,08-31 12:09:15.430  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 12:09:15.430  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.430  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 12:09:15.431  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.431  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340018c added. We now have 10 listener(s)
08-31 12:09:15.431  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.431  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 12:09:15.431  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 12:09:15.431  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 12:09:15.431  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:09:15.431  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 12:09:15.431  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:15.434  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:15.435  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 12:09:15.435  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 12:09:15.439  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 12:09:15.440  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 12:09:15.440  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 12:09:15.444  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 12:09:15.444  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 12:09:15.444  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 12:09:15.445  3867  3913 D BluetoothAdapter: STATE_ON
,08-31 12:09:15.448  4206  4247 D BtGatt.GattService: registerClient() - UUID=1d37d9fd-919e-429c-a8d0-cd644808b1de
,08-31 12:09:15.449  4206  4222 D BtGatt.GattService: onClientRegistered() - UUID=1d37d9fd-919e-429c-a8d0-cd644808b1de, clientIf=5
,08-31 12:09:15.451  3867  4080 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 12:09:15.452  4206  4216 D BtGatt.GattService: start scan with filters
,08-31 12:09:15.457  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 12:09:15.457  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 12:09:15.457  4206  4225 D BtGatt.ScanManager: handling starting scan
08-31 12:09:15.457  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 12:09:15.457  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 12:09:15.460  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 12:09:15.461  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 12:09:15.461  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 12:09:15.461  4206  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93fefb3
,08-31 12:09:15.462  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 12:09:15.465  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 12:09:15.465  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 12:09:15.465  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 12:09:15.465  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:09:15.465  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 12:09:15.465  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 12:09:15.465  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 12:09:15.465  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 12:09:15.466  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:09:15.466  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 12:09:15.466  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 12:09:15.467  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:09:15.467  4206  4242 D BtGatt.GattService: stopScan() - queue size =1
,08-31 12:09:15.468  4206  4247 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 12:09:15.468  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 12:09:15.468  4206  4222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 12:09:15.469  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 12:09:15.469  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 12:09:15.469  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 12:09:15.469  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.469  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 12:09:15.470  4206  4225 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 12:09:15.471  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:09:15.471  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 12:09:15.471  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 12:09:15.472  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 12:09:15.472  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:09:15.473  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:09:15.474  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 12:09:15.474  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 12:09:15.479  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 12:09:15.479  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:09:15.479  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 12:09:15.481  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 12:09:15.481  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.481  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:09:15.482  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-31 12:09:15.482  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe54f60 removed from the list
08-31 12:09:15.482  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.482  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 12:09:15.482  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7123c19 removed from the list
08-31 12:09:15.482  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:09:15.482  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.484  4206  4225 D BtGatt.ScanManager: Starting BLE batch scan
08-31 12:09:15.484  4206  4225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 12:09:15.483  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:15.486  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.486  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.487  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:09:15.487  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.488  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 12:09:15.488  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7123c19 not in the list
08-31 12:09:15.488  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.488  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.489  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 12:09:15.489  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:09:15.489  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.489  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340018c removed from the list
08-31 12:09:15.489  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:09:15.489  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:09:15.489  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.489  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 12:09:15.490  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4fc6bf removed from the list
08-31 12:09:15.490  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 12:09:15.491  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb1aa78 added. We now have 2 listener(s)
,08-31 12:09:15.492  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.492  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 12:09:15.493  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.493  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.493  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1665551 added. We now have 9 listener(s)
08-31 12:09:15.493  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.494  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 12:09:15.497  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:15.501  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:15.503  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:15.503  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:09:15.504  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 12:09:15.504  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@569ceb7 added. We now have 3 listener(s)
,08-31 12:09:15.505  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 12:09:15.506  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.506  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.506  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 12:09:15.506  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392f624 added. We now have 10 listener(s)
08-31 12:09:15.506  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.506  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 12:09:15.507  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 12:09:15.507  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 12:09:15.507  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 12:09:15.507  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:09:15.508  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-31 12:09:15.509  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:15.512  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:15.513  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 12:09:15.513  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 12:09:15.514  4206  4222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 12:09:15.514  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.518  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 12:09:15.519  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 12:09:15.519  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 12:09:15.521  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 12:09:15.521  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.523  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 12:09:15.523  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 12:09:15.524  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 12:09:15.524  3867  3913 D BluetoothAdapter: STATE_ON
,08-31 12:09:15.528  4206  4246 D BtGatt.GattService: registerClient() - UUID=6b5fd31a-5c03-4a14-9ac5-1213308ceb8f
,08-31 12:09:15.528  4206  4222 D BtGatt.GattService: onClientRegistered() - UUID=6b5fd31a-5c03-4a14-9ac5-1213308ceb8f, clientIf=5
,08-31 12:09:15.528  3867  4080 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 12:09:15.529  4206  4247 D BtGatt.GattService: start scan with filters
,08-31 12:09:15.532  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 12:09:15.532  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 12:09:15.532  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 12:09:15.532  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 12:09:15.532  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 12:09:15.532  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.533  4206  4225 D BtGatt.ScanManager: stopping BLe Batch
,08-31 12:09:15.535  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:09:15.535  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 12:09:15.535  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 12:09:15.537  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 12:09:15.539  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 12:09:15.539  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.539  4206  4225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 12:09:15.540  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 12:09:15.540  3867  3913 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 12:09:15.541  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 12:09:15.541  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 12:09:15.541  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:09:15.541  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 12:09:15.541  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.541  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 12:09:15.541  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 12:09:15.541  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb1aa78 removed from the list
08-31 12:09:15.541  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 12:09:15.541  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1665551 removed from the list
08-31 12:09:15.541  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 12:09:15.541  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:09:15.542  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.542  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-31 12:09:15.542  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.542  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 12:09:15.543  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 12:09:15.543  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.543  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.543  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1665551 not in the list
,08-31 12:09:15.543  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 12:09:15.544  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 12:09:15.544  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:09:15.544  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 12:09:15.544  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 12:09:15.544  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:09:15.545  4206  4246 D BtGatt.GattService: stopScan() - queue size =0
08-31 12:09:15.545  4206  4222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 12:09:15.546  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.546  4206  4247 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 12:09:15.546  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 12:09:15.546  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 12:09:15.547  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 12:09:15.547  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 12:09:15.547  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 12:09:15.547  4206  4225 D BtGatt.ScanManager: handling starting scan
,08-31 12:09:15.548  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:09:15.548  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 12:09:15.548  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 12:09:15.548  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 12:09:15.549  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:15.550  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.550  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:09:15.550  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 12:09:15.550  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392f624 removed from the list,
,08-31 12:09:15.550  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-31 12:09:15.550  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-31 12:09:15.550  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:09:15.550  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 12:09:15.550  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:09:15.550  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 12:09:15.550  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@569ceb7 removed from the list
,08-31 12:09:15.550  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:09:15.551  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.551  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81b5090 added. We now have 2 listener(s)
,08-31 12:09:15.553  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.553  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 12:09:15.554  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.554  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.554  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58d5d89 added. We now have 9 listener(s)
08-31 12:09:15.554  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 12:09:15.554  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 12:09:15.555  4206  4222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 12:09:15.555  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.555  4206  4225 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 12:09:15.558  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:15.562  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:15.562  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 12:09:15.562  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.563  4206  4225 D BtGatt.ScanManager: Starting BLE batch scan,
08-31 12:09:15.563  4206  4225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 12:09:15.564  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 12:09:15.564  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-31 12:09:15.564  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.564  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cdddaf added. We now have 3 listener(s)
,08-31 12:09:15.565  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 12:09:15.567  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:15.568  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:15.574  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.574  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 12:09:15.574  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.574  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.574  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce5bc added. We now have 10 listener(s)
,08-31 12:09:15.574  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.574  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 12:09:15.575  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 12:09:15.575  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 12:09:15.575  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 12:09:15.575  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 12:09:15.575  4206  4222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 12:09:15.575  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.578  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 12:09:15.578  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 12:09:15.581  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-31 12:09:15.581  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.581  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 12:09:15.582  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 12:09:15.582  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 12:09:15.585  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 12:09:15.585  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 12:09:15.585  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-31 12:09:15.585  3867  3913 D BluetoothAdapter: STATE_ON
08-31 12:09:15.587  4206  4242 D BtGatt.GattService: registerClient() - UUID=25bef243-6c1e-4484-bc99-26b7386b9163
,08-31 12:09:15.587  4206  4222 D BtGatt.GattService: onClientRegistered() - UUID=25bef243-6c1e-4484-bc99-26b7386b9163, clientIf=5
08-31 12:09:15.587  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 12:09:15.588  4206  4247 D BtGatt.GattService: start scan with filters
,08-31 12:09:15.588  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 12:09:15.588  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.588  4206  4225 D BtGatt.ScanManager: stopping BLe Batch
,08-31 12:09:15.590  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 12:09:15.590  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 12:09:15.590  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-31 12:09:15.590  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 12:09:15.592  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 12:09:15.592  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 12:09:15.593  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 12:09:15.594  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-31 12:09:15.594  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.594  4206  4225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 12:09:15.594  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 12:09:15.599  4206  4222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
08-31 12:09:15.599  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.599  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:09:15.599  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 12:09:15.599  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 12:09:15.599  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:09:15.599  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:09:15.599  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 12:09:15.600  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 12:09:15.600  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81b5090 removed from the list
,08-31 12:09:15.600  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.600  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58d5d89 removed from the list
08-31 12:09:15.600  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 12:09:15.600  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:09:15.600  4206  4225 D BtGatt.ScanManager: handling starting scan
08-31 12:09:15.600  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.600  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
08-31 12:09:15.600  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.600  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 12:09:15.601  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 12:09:15.601  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 12:09:15.601  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.601  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58d5d89 not in the list,
08-31 12:09:15.601  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 12:09:15.601  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 12:09:15.602  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 12:09:15.602  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 12:09:15.602  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 12:09:15.602  3867  3913 D BluetoothAdapter: STATE_ON
,08-31 12:09:15.603  4206  4246 D BtGatt.GattService: stopScan() - queue size =1
08-31 12:09:15.603  4206  4247 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 12:09:15.604  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 12:09:15.604  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 12:09:15.604  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 12:09:15.604  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 12:09:15.604  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 12:09:15.605  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:09:15.605  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 12:09:15.605  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 12:09:15.605  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 12:09:15.605  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:15.606  4206  4222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 12:09:15.606  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-31 12:09:15.606  4206  4225 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 12:09:15.607  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 12:09:15.607  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 12:09:15.607  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 12:09:15.607  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.607  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 12:09:15.607  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.607  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce5bc removed from the list
08-31 12:09:15.607  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 12:09:15.607  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 12:09:15.607  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.607  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 12:09:15.608  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cdddaf removed from the list
,08-31 12:09:15.608  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.608  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a1a8 added. We now have 2 listener(s)
08-31 12:09:15.610  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-31 12:09:15.610  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.610  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 12:09:15.610  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.610  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1634c1 added. We now have 9 listener(s)
08-31 12:09:15.610  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.611  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 12:09:15.611  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 12:09:15.611  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.611  4206  4225 D BtGatt.ScanManager: Starting BLE batch scan
08-31 12:09:15.611  4206  4225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 12:09:15.615  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 12:09:15.618  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 12:09:15.618  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 12:09:15.621  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 12:09:15.621  4206  4222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 12:09:15.621  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.623   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 12:09:15.624  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 12:09:15.625  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 12:09:15.625  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 12:09:15.625  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5d3a7 added. We now have 3 listener(s)
,08-31 12:09:15.626  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 12:09:15.627  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 12:09:15.627  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 12:09:15.627  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 12:09:15.627  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 12:09:15.627  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b23054 added. We now have 10 listener(s)
,08-31 12:09:15.627  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 12:09:15.627  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 12:09:15.627  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 12:09:15.628  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 12:09:15.628  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.628  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 12:09:15.629  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 12:09:15.629  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:09:15.629  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.629  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 12:09:15.629  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 12:09:15.629  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a1a8 removed from the list
08-31 12:09:15.629  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 12:09:15.629  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1634c1 removed from the list
08-31 12:09:15.629  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-31 12:09:15.629  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.630  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.630  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 12:09:15.630   873  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 12:09:15.631   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 12:09:15.631   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:09:15.632  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 12:09:15.632  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.632  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.632  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1634c1 not in the list
,08-31 12:09:15.632  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 12:09:15.632  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.633  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 12:09:15.633  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 12:09:15.633  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 12:09:15.633  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b23054 removed from the list
08-31 12:09:15.633  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 12:09:15.633  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 12:09:15.633  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 12:09:15.634  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 12:09:15.634  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5d3a7 removed from the list
08-31 12:09:15.634  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 12:09:15.634  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 12:09:15.634  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.635  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 12:09:15.635  4206  4225 D BtGatt.ScanManager: stopping BLe Batch
,08-31 12:09:15.635  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 12:09:15.635  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 12:09:15.635  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 12:09:15.635  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 12:09:15.641  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 12:09:15.641  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 12:09:15.642  4206  4225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 12:09:15.644   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 12:09:15.649  3867  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
,08-31 12:09:15.649  3867  4264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
,08-31 12:09:15.650  4206  4222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 12:09:15.650  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 12:09:15.652   370   871 D CommandListener: Setting iface cfg
,08-31 12:09:15.652   873  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 12:09:15.653  3867  4264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 12:09:15.655  3867  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
,08-31 12:09:15.655  3867  4265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
,08-31 12:09:15.655  3867  4265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 12:09:15.657  3867  3913 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-31 12:09:15.657  3867  3913 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 12:09:15.657  3867  3913 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-31 12:09:15.657  3867  3913 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-31 12:09:15.657  3867  3913 D com.test.thalitest.ThaliTestRunner: Total duration: 22785 ms
,08-31 12:09:15.659  3867  3913 I jxcore-log: *Native tests were executed*
08-31 12:09:15.659  3867  3913 I jxcore-log: 
08-31 12:09:15.659  3867  3913 I jxcore-log: Total number of executed tests:  80
08-31 12:09:15.659  3867  3913 I jxcore-log: 
,08-31 12:09:15.659  3867  3913 I jxcore-log: Number of passed tests:  80
08-31 12:09:15.659  3867  3913 I jxcore-log: 
08-31 12:09:15.659  3867  3913 I jxcore-log: Number of failed tests:  0
08-31 12:09:15.659  3867  3913 I jxcore-log: 
,08-31 12:09:15.659  3867  3913 I jxcore-log: Number of ignored tests:  0
08-31 12:09:15.659  3867  3913 I jxcore-log: 
08-31 12:09:15.660  3867  3913 I jxcore-log: Total duration:  22785
08-31 12:09:15.660  3867  3913 I jxcore-log: 
,08-31 12:09:15.660  3867  3913 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 12:09:15.660  3867  3913 I jxcore-log: 
,08-31 12:09:15.661   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-31 12:09:15.663  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.663  3867  3913 I jxcore-log: 
08-31 12:09:15.666  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.666  3867  3913 I jxcore-log: 
08-31 12:09:15.667  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.667  3867  3913 I jxcore-log: 
08-31 12:09:15.668  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.668  3867  3913 I jxcore-log: 
08-31 12:09:15.668  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.668  3867  3913 I jxcore-log: 
08-31 12:09:15.670  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.670  3867  3913 I jxcore-log: 
08-31 12:09:15.672  3867  3867 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 12:09:15.672  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.672  3867  3913 I jxcore-log: 
08-31 12:09:15.674  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.674  3867  3913 I jxcore-log: 
08-31 12:09:15.675  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.675  3867  3913 I jxcore-log: 
08-31 12:09:15.675  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.675  3867  3913 I jxcore-log: 
08-31 12:09:15.676  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.676  3867  3913 I jxcore-log: 
08-31 12:09:15.677  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 12:09:15.677  3867  3913 I jxcore-log: 
08-31 12:09:15.678  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.678  3867  3913 I jxcore-log: 
08-31 12:09:15.679  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.679  3867  3913 I jxcore-log: 
08-31 12:09:15.679   873  4266 D DhcpClient: Receive thread started
08-31 12:09:15.679  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.679  3867  3913 I jxcore-log: 
08-31 12:09:15.680  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.680  3867  3913 I jxcore-log: 
08-31 12:09:15.681  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.681  3867  3913 I jxcore-log: 
08-31 12:09:15.681  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.681  3867  3913 I jxcore-log: 
08-31 12:09:15.682  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.682  3867  3913 I jxcore-log: 
08-31 12:09:15.683  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.683  3867  3913 I jxcore-log: 
,08-31 12:09:15.683  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.683  3867  3913 I jxcore-log: 
08-31 12:09:15.684  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.684  3867  3913 I jxcore-log: 
08-31 12:09:15.684  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.684  3867  3913 I jxcore-log: 
,08-31 12:09:15.685  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.685  3867  3913 I jxcore-log: 
,08-31 12:09:15.685  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.685  3867  3913 I jxcore-log: 
08-31 12:09:15.686  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 12:09:15.686  3867  3913 I jxcore-log: 
,08-31 12:09:15.687  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.687  3867  3913 I jxcore-log: 
,08-31 12:09:15.687  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.687  3867  3913 I jxcore-log: 
,08-31 12:09:15.688  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.688  3867  3913 I jxcore-log: 
08-31 12:09:15.688  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.688  3867  3913 I jxcore-log: 
,08-31 12:09:15.689  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.689  3867  3913 I jxcore-log: 
,08-31 12:09:15.690  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.690  3867  3913 I jxcore-log: 
,08-31 12:09:15.690  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 12:09:15.690  3867  3913 I jxcore-log: 
,08-31 12:09:15.763   873  1301 E native  : do suspend false
,08-31 12:09:15.778   873  1889 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 12:09:15.798   873  4266 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-31 12:09:15.799   873  1889 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-31 12:09:15.803   873  1889 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 12:09:15.818   873  4266 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 12:09:15.819   873  1889 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 12:09:15.824   370   871 D CommandListener: Setting iface cfg
,08-31 12:09:15.829   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 12:09:15.832   873  1301 E native  : do suspend true
,08-31 12:09:15.833   873  1889 D DhcpClient: Scheduling renewal in 86399s
,08-31 12:09:15.845   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 12:09:15.846   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 12:09:15.848   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 12:09:15.850   873  1303 D ConnectivityService: Adding iface wlan0 to network 102
08-31 12:09:15.856   873  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 12:09:15.884   873  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 12:09:15.884   873  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 12:09:15.886   873  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 12:09:15.887   873  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-31 12:09:15.888   873  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 12:09:15.895   873  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 12:09:15.899   873  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-31 12:09:15.899   873  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-31 12:09:15.899   873  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 12:09:15.899   873  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-31 12:09:15.899   873  1303 D ConnectivityService:    accepting network in place of null
08-31 12:09:15.900   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 12:09:15.900   873  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 12:09:15.921   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:09:15.930   873  4263 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218793, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 12:09:15.954   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 12:09:15.959   873  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-31 12:09:15.959   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:09:15.968   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-31 12:09:15.969   873  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 12:09:15.976  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 12:09:15.978  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 12:09:15.978  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 12:09:15.979  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 12:09:15.979  3867  3913 I jxcore-log: 
,08-31 12:09:15.980  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 12:09:15.980  3867  3913 I jxcore-log: 
08-31 12:09:15.992  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 12:09:16.000  1694  1694 D SystemUpdateService: onCreate
08-31 12:09:16.002  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 12:09:16.012   873  4262 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-31 12:09:16.028  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 12:09:16.039  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 12:09:16.040  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 12:09:16.042  4012  4012 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 12:09:16.036  1694  4277 I SystemUpdateService: active receiver: enabled
,08-31 12:09:16.048  4012  4012 D SprintDMHelper: simOperator: 
,08-31 12:09:16.048  4012  4012 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 12:09:16.051  1694  4279 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 12:09:16.051  1694  4279 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 12:09:16.051  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 12:09:16.053  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 12:09:16.053  3867  3913 I jxcore-log: 
,08-31 12:09:16.068  1694  4279 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 12:09:16.089   873  4262 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 10:09:16 GMT], X-Android-Received-Millis=[1472638156087], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472638156059]}
,08-31 12:09:16.091   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 12:09:16.092   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-31 12:09:16.093   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 12:09:16.094  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 12:09:16.096  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 12:09:16.100   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 12:09:16.108  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 12:09:16.109  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 12:09:16.109  3867  3913 I jxcore-log: 
,08-31 12:09:16.120  1694  2460 I iu.UploadsManager: num queued entries: 0
,08-31 12:09:16.122  1694  2460 I iu.UploadsManager: num updated entries: 0
08-31 12:09:16.123  1694  2460 I iu.SyncManager: NEXT; no task
,08-31 12:09:16.126  1694  4277 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 12:09:16.134  1694  4277 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 12:09:16.134  1694  4277 I SystemUpdateService: now status is 0 (complete)
08-31 12:09:16.134  1694  4277 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 12:09:16.136  1694  4277 I SystemUpdateService: file has been verified
,08-31 12:09:16.136  1694  4277 I SystemUpdateService: OTA package size = 12249756
,08-31 12:09:16.144  1694  4277 I SystemUpdateService: showing system update notification
,08-31 12:09:16.151  1493  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 12:09:16.151  1493  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 12:09:16.151  1493  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 12:09:16.151  1493  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 12:09:16.185  1694  4279 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-31 12:09:16.190  1694  1694 D SystemUpdateService: onDestroy
,08-31 12:09:16.221  3970  4282 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 12:09:16.434  4267  4267 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 12:09:16.440  4267  4267 D AndroidRuntime: CheckJNI is OFF
,08-31 12:09:16.482  4267  4267 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 12:09:16.531  4267  4267 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 12:09:16.554  4267  4267 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 12:09:16.569   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 12:09:16.571   873   886 I ActivityManager: Killing 3867:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 12:09:16.683   873   896 W PackageSettings: Skipping PackageSetting{57b0354 com.example.hello/10273} due to missing metadata
,08-31 12:09:16.691   873  1302 D WifiService: Client connection lost with reason: 4
,08-31 12:09:16.690   873  1380 I WindowState: WIN DEATH: Window{9c1026f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 12:09:16.690   873  2153 D GraphicsStats: Buffer count: 2
,08-31 12:09:16.733   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 12:09:16.734   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-31 12:09:16.734   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-31 12:09:16.734   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
,08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 12:09:16.734   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:16.734   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:16.734   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 12:09:16.734   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 12:09:16.735   873   886 I ActivityManager:   Force finishing activity ActivityRecord{a8726ab u0 com.test.thalitest/.MainActivity t2}
08-31 12:09:16.736   873   896 I art     : Starting a blocking GC Explicit
,08-31 12:09:16.742   873  1961 W ActivityManager: Spurious death for ProcessRecord{bf14559 0:com.test.thalitest/u0a0}, curProc for 3867: null
,08-31 12:09:16.794   873   896 I art     : Explicit concurrent mark sweep GC freed 53599(3MB) AllocSpace objects, 9(212KB) LOS objects, 33% free, 29MB/43MB, paused 886us total 57.867ms
,08-31 12:09:16.815   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 12:09:16.818  4267  4267 I art     : System.exit called, status: 0
08-31 12:09:16.818  4267  4267 I AndroidRuntime: VM exiting with result code 0.
,08-31 12:09:16.823   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 12:09:16.831   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 12:09:16.840   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 12:09:16.840  4206  4206 D BluetoothMapAppObserver: onReceive
08-31 12:09:16.840  4206  4206 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-31 12:09:16.842  1900  2289 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 12:09:16.864  3609  3609 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 12:09:16.884  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 12:09:16.893  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 12:09:16.906   873   883 I ActivityManager: Start proc 4303:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 12:09:16.923  1871  4302 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 12:09:16.937  1871  4302 I Decoder : createOrResetDecoder
,08-31 12:09:16.941  4303  4303 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 12:09:16.945   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 12:09:16.954  1493  1493 I ConfigService: onCreate
,08-31 12:09:16.963  1963  2050 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 12:09:16.963   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-31 12:09:16.966   873   885 E PackageManager: Failed to write settings, restoring backup
08-31 12:09:16.966   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 12:09:16.966   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 12:09:16.966   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 12:09:16.966   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 12:09:16.966   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 12:09:16.966   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:16.966   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:16.966   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 12:09:16.971   873  2162 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3867 uid 10000
08-31 12:09:16.974  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-31 12:09:16.975   873   883 I ActivityManager: Start proc 4316:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-31 12:09:16.976  1963  2050 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 12:09:16.976  1963  2050 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1963
08-31 12:09:16.976  1963  2050 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:16.976  1963  2050 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 12:09:16.978   873  1962 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 12:09:16.982  1493  4315 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-31 12:09:16.982  1493  4315 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-31 12:09:16.982  1493  4315 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-31 12:09:16.983  1963  2050 I Process : Sending signal. PID: 1963 SIG: 9
08-31 12:09:16.984   873  4322 E DropBoxManagerService: Can't write: system_app_crash
08-31 12:09:16.984   873  4322 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 12:09:16.984   873  4322 E DropBoxManagerService: 	... 5 more
08-31 12:09:16.984   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-31 12:09:16.984   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 12:09:16.984   ,873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 12:09:16.984   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 12:09:16.984   873   886 E DropBoxManagerService: 	... 13 more
08-31 12:09:16.989  1493  4315 W SQLiteOpenHelper: Opened config.db in read-only mode
08-31 12:09:17.009  1871  4302 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 12:09:17.105  4303  4303 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 12:09:17.118  1871  4302 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 12:09:17.120  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-31 12:09:17.120  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 12:09:17.122   873   884 D GraphicsStats: Buffer count: 1
,08-31 12:09:17.123   873  1951 I WindowState: WIN DEATH: Window{28800ef u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 12:09:17.132  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-31 12:09:17.132  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-31 12:09:17.134  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 12:09:17.134  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-31 12:09:17.135  1871  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 12:09:17.135  1871  4302 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-31 12:09:17.135  1871  4302 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 12:09:17.136  1871  4302 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-31 12:09:17.143   873  1380 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1963) has died
,08-31 12:09:17.143   873  1380 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-31 12:09:17.144   873  1380 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 12:09:17.136  1871  4302 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-31 12:09:17.152  1871  4302 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 12:09:17.156  4303  4323 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.156  4303  4323 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.156  4303  4323 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 12:09:17.164   873   886 I ActivityManager: Start proc 4335:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 12:09:17.179  4303  4345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 12:09:17.184   873  1961 I ActivityManager: Start proc 4348:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 12:09:17.219  4335  4335 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:09:17.219  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 12:09:17.219  4335  4335 D AndroidRuntime: Shutting down VM
,08-31 12:09:17.227  4335  4335 E AndroidRuntime: FATAL EXCEPTION: main
08-31 12:09:17.227  4335  4335 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4335
08-31 12:09:17.227  4335  4335 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 12:09:17.227  4335  4335 E AndroidRuntime: 	... 10 more
08-31 12:09:17.230   873  1380 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 12:09:17.230  4335  4335 I Process : Sending signal. PID: 4335 SIG: 9
08-31 12:09:17.231   873  4362 E DropBoxManagerService: Can't write: system_app_crash
08-31 12:09:17.231   873  4362 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 12:09:17.231   873  4362 E DropBoxManagerService: 	... 5 more
08-31 12:09:17.239  1694  4346 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 12:09:17.240  1694  4346 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-31 12:09:17.244  1694  4346 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 12:09:17.244  1694  4346 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-31 12:09:17.254  4348  4348 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 12:09:17.274  1493  1493 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 12:09:17.276  1493  1493 D AndroidRuntime: Shutting down VM
,08-31 12:09:17.277  1493  1493 E AndroidRuntime: FATAL EXCEPTION: main
08-31 12:09:17.277  1493  1493 E AndroidRuntime: Process: com.google.process.gapps, PID: 1493
08-31 12:09:17.277  1493  1493 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 12:09:17.277  1493  1493 E AndroidRuntime: 	... 8 more
,08-31 12:09:17.280   873  1380 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4335) has died
08-31 12:09:17.281   873  1380 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-31 12:09:17.283   873  4365 E DropBoxManagerService: Can't write: system_app_crash
08-31 12:09:17.283   873  4365 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 12:09:17.283   873  4365 E DropBoxManagerService: 	... 5 more
,08-31 12:09:17.306  4303  4323 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-31 12:09:17.311  4303  4345 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.311  4303  4345 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 12:09:17.311  4303  4345 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 12:09:17.311  4303  4345 E AndroidRuntime: Process: android.process.acore, PID: 4303
08-31 12:09:17.311  4303  4345 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 12:09:17.311  4303  4345 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 12:09:17.314  4303  4323 I Process : Sending signal. PID: 4303 SIG: 9
,08-31 12:09:17.316   873   886 I ActivityManager: Start proc 4368:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 12:09:17.321  1493  1493 I Process : Sending signal. PID: 1493 SIG: 9

```
