#### Test 82914073d0f9b46_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-06 19:17:11.276  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:17:11.288  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:17:11.291  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:17:11.337  1528  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-06 19:17:11.337  1528  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 19:17:11.338  1528  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:17:11.338  1528  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-06 19:17:11.386  3502  3502 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-06 19:17:11.387  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 19:17:11.388  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
09-06 19:17:11.912  3818  3818 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-06 19:17:11.917  3818  3818 D AndroidRuntime: CheckJNI is OFF
09-06 19:17:11.960  3818  3818 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-06 19:17:12.010  3818  3818 I Radio-JNI: register_android_hardware_Radio DONE
09-06 19:17:12.031  3818  3818 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:17:12.036   872  1986 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:17:12.117   872  1986 I ActivityManager: Start proc 3827:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-06 19:17:12.122  3818  3818 D AndroidRuntime: Shutting down VM
09-06 19:17:12.249  3827  3827 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-06 19:17:12.277  3827  3827 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-06 19:17:12.284  3827  3827 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3080-3082)
09-06 19:17:12.284  3827  3827 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:17:12.299  3827  3827 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc28561}
09-06 19:17:12.300  3827  3827 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:17:12.300  3827  3827 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:17:12.306  3827  3827 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 19:17:12.308  3827  3827 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:17:12.329  3827  3827 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-06 19:17:12.340  3827  3827 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:17:12.340  3827  3827 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:17:12.340  3827  3827 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:17:12.340  3827  3827 I Adreno  : Build Date                       : 10/20/15
09-06 19:17:12.340  3827  3827 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:17:12.340  3827  3827 I Adreno  : Local Branch                     : M14
09-06 19:17:12.340  3827  3827 I Adreno  : Remote Branch                    : 
09-06 19:17:12.340  3827  3827 I Adreno  : Remote Branch                    : 
09-06 19:17:12.340  3827  3827 I Adreno  : Reconstruct Branch               : 
,09-06 19:17:12.402   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@da36da6:true
,09-06 19:17:12.440  3827  3827 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 19:17:12.451  3827  3827 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-06 19:17:12.498  3827  3864 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 19:17:12.512  3827  3851 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-06 19:17:12.581  3827  3864 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 19:17:12.608  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-06 19:17:12.675   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +495ms (total +588ms)
,09-06 19:17:12.708  3827  3827 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3827
,09-06 19:17:12.837  3827  3827 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:17:12.966  3827  3865 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1657013968
,09-06 19:17:12.975  3827  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:17:12.975  3827  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:17:12.975  3827  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:17:12.975  3827  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:17:12.975  3827  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:17:12.975  3827  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3653cc added. We now have 1 listener(s)
,09-06 19:17:12.980  3827  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-06 19:17:12.984  3827  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:17:12.987  3827  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:17:12.987  3827  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-06 19:17:13.003  3827  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d93371b added. We now have 1 listener(s)
,09-06 19:17:13.004  3827  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:13.011   872  1307 D WifiService: New client listening to asynchronous messages
,09-06 19:17:13.012  3827  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:17:13.013  3827  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 19:17:13.015  3827  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-06 19:17:13.017  3827  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-06 19:17:13.018  3827  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:17:13.027  3827  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:13.028  3827  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-06 19:17:13.034  3827  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:13.035  3827  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:13.035  3827  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-06 19:17:13.036  3827  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:13.037  3827  3865 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:17:13.038  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:13.039  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:13.060  3827  3827 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:17:13.853  3827  3874 W jxcore-log: Initializing JXcore engine
,09-06 19:17:13.853  3827  3874 W jxcore-log: JXcore engine is ready
,09-06 19:17:13.892  3874  3874 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8979 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-06 19:17:13.892  3874  3874 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13393]" dev="sockfs" ino=13393 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-06 19:17:13.892  3874  3874 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 19:17:13.892  3874  3874 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25031]" dev="sockfs" ino=25031 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-06 19:17:13.908  3827  3874 W jxcore-log: Starting JXcore engine
,09-06 19:17:13.988  3827  3874 W jxcore-log: Platform android
09-06 19:17:13.988  3827  3874 W jxcore-log: 
,09-06 19:17:13.988  3827  3874 W jxcore-log: Process ARCH arm
09-06 19:17:13.988  3827  3874 W jxcore-log: 
,09-06 19:17:14.183  3827  3874 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:17:14.183  3827  3874 I jxcore-log: 
,09-06 19:17:14.183  3827  3874 W jxcore-log: JXcore engine is started
,09-06 19:17:14.194  3827  3865 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:17:14.199  3827  3827 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:17:15.065   872  1848 D NetlinkSocketObserver: NeighborEvent{elapsedMs=185863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE},
,09-06 19:17:22.785   872  1848 D NetlinkSocketObserver: NeighborEvent{elapsedMs=193583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-06 19:17:23.633  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:17:23.633  3827  3874 I jxcore-log: 
,09-06 19:17:23.635  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:17:23.635  3827  3874 I jxcore-log: 
,09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:23.645  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:17:23.653  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:17:23.655  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:17:23.655  3827  3874 I jxcore-log: 
,09-06 19:17:23.657  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:17:23.657  3827  3874 I jxcore-log: 
,09-06 19:17:24.149  3827  3874 D executeNativeTests: Running unit tests
,09-06 19:17:24.206  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:24.207  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c added. We now have 2 listener(s)
,09-06 19:17:24.208  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:17:24.208  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:24.208  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:17:24.208  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:24.208  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 added. We now have 2 listener(s)
,09-06 19:17:24.208  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:24.209  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:17:24.210  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.220  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:17:24.224  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.224  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:17:24.225  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:24.227  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:24.232  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:17:24.232  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:17:24.232  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:17:24.237  3827  3874 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:17:24.239  3827  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-06 19:17:24.239  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 19:17:24.240  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:17:24.240  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:17:24.242  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:24.244  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:24.244  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-06 19:17:24.248  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.248  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.248  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:24.248  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:24.248  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c removed from the list
09-06 19:17:24.248  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.248  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 removed from the list
09-06 19:17:24.249  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.249  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.249  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.249  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.252  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.252  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.252  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.252  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.255  3827  3874 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-06 19:17:24.256  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:24.256  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:24.256  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.256  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.256  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.257  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.257  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.257  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.257  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.257  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.257  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.257  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.257  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.257  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.259  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.259  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.259  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.259  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:17:24.265  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-06 19:17:24.266  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:17:24.267  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:17:24.267  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.267  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.267  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.267  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.268  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.268  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.268  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.268  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.268  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.268  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.268  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.268  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.268  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.268  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.269  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.269  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.269  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.269  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.270  3827  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:17:24.272  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.277  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:24.280  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.280  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:24.280  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:24.280  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:17:24.280  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:17:24.281  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.281  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:17:24.282  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.284  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.284  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:17:24.284  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:17:24.290  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:17:24.292  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:17:24.292  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:17:24.295  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:17:24.298  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 19:17:24.299  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:17:24.299  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:17:24.300  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:17:24.301  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:24.306  2681  2694 D BtGatt.GattService: registerClient() - UUID=a106947b-fee1-4d00-8277-36f5c1509cad
09-06 19:17:24.307  2681  2706 D BtGatt.GattService: onClientRegistered() - UUID=a106947b-fee1-4d00-8277-36f5c1509cad, clientIf=5
09-06 19:17:24.308  3827  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:17:24.309  2681  2811 D BtGatt.GattService: start scan with filters
09-06 19:17:24.313  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:17:24.313  2681  2709 D BtGatt.ScanManager: handling starting scan
09-06 19:17:24.314  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:17:24.314  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:17:24.314  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:17:24.316  2681  2709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:24.318  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:24.319  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:17:24.319  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:24.321  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:17:24.324  2681  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:17:24.324  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.325  2681  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:17:24.327  3827  3874 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:17:24.331  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.332  3827  3874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:17:24.332  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.332  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:17:24.332  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.332  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:17:24.332  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:17:24.332  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:17:24.333  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:17:24.333  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:24.333  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:17:24.334  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:17:24.334  2681  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:17:24.334  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.334  2681  2709 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:17:24.334  2681  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:17:24.335  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:24.336  2681  2693 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:17:24.337  2681  2811 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:17:24.337  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:17:24.337  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:17:24.338  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:17:24.338  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:17:24.338  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:17:24.339  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.339  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:17:24.339  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:17:24.340  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:17:24.340  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:24.341  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.341  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.341  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.341  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.341  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:24.341  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.341  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.341  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.341  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.341  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.341  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.342  3827  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:17:24.343  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.348  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:24.350  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.351  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:24.351  2681  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:17:24.351  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:24.351  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:24.351  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:17:24.351  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:17:24.351  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.351  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:17:24.354  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:17:24.355  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:17:24.355  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.356  2681  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:17:24.357  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.357  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:17:24.358  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.358  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:17:24.358  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:17:24.361  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:17:24.361  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:17:24.361  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:17:24.362  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:24.364  2681  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:17:24.364  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.365  2681  2709 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:17:24.365  2681  2693 D BtGatt.GattService: registerClient() - UUID=cd3d80a8-e878-4a01-a266-bc44a1aab85a
09-06 19:17:24.365  2681  2706 D BtGatt.GattService: onClientRegistered() - UUID=cd3d80a8-e878-4a01-a266-bc44a1aab85a, clientIf=5
09-06 19:17:24.366  3827  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:17:24.366  2681  2811 D BtGatt.GattService: start scan with filters
09-06 19:17:24.369  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:17:24.369  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:17:24.369  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:17:24.369  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:17:24.372  2681  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:17:24.372  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:24.372  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.372  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:24.372  2681  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:17:24.372  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:17:24.374  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:17:24.377  3827  3874 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:17:24.377  2681  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:17:24.377  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.379  2681  2709 D BtGatt.ScanManager: handling starting scan
09-06 19:17:24.379  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.379  3827  3874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:17:24.380  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.380  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:17:24.380  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.380  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:17:24.380  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:17:24.380  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:17:24.380  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:17:24.380  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:24.380  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:17:24.381  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:17:24.381  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:24.382  2681  2694 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:17:24.382  2681  2693 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:17:24.383  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:17:24.383  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:17:24.383  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:17:24.383  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:17:24.383  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:17:24.384  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.384  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:17:24.384  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:17:24.384  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:17:24.384  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:24.385  2681  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:17:24.385  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.386  2681  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:17:24.386  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.386  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.386  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:24.386  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.386  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.386  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.386  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.386  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.386  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.386  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.386  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.387  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.387  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.388  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.388  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.388  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.388  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.389  3827  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:17:24.390  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.392  2681  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:17:24.392  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.392  2681  2709 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:17:24.392  2681  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.394  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:24.396  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.396  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:24.396  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:24.396  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:17:24.397  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:17:24.397  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.397  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:17:24.399  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.400  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:17:24.401  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:17:24.401  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.403  2681  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:17:24.403  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.405  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:17:24.406  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:17:24.406  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:17:24.409  2681  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:17:24.409  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.410  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:17:24.410  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:17:24.410  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:17:24.411  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:24.414  2681  2811 D BtGatt.GattService: registerClient() - UUID=3cffc1cd-6bb1-400e-82ed-ef11c7cdd0e7
09-06 19:17:24.414  2681  2706 D BtGatt.GattService: onClientRegistered() - UUID=3cffc1cd-6bb1-400e-82ed-ef11c7cdd0e7, clientIf=5
09-06 19:17:24.415  3827  3838 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:17:24.415  2681  2693 D BtGatt.GattService: start scan with filters
09-06 19:17:24.417  2681  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:17:24.417  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.418  2681  2709 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:17:24.422  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:17:24.422  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:17:24.422  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:17:24.422  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:17:24.424  2681  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:17:24.424  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.425  2681  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:17:24.426  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:24.426  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:17:24.426  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:24.427  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:17:24.431  2681  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:17:24.431  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.432  3827  3874 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:17:24.432  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.432  3827  3874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:17:24.432  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.432  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:17:24.432  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.432  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:17:24.432  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:17:24.432  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:17:24.432  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:17:24.432  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:24.433  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:17:24.433  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:17:24.433  3827  3874 D BluetoothAdapter: STATE_ON
,09-06 19:17:24.433  2681  2709 D BtGatt.ScanManager: handling starting scan
09-06 19:17:24.434  2681  2811 D BtGatt.GattService: stopScan() - queue size =0
09-06 19:17:24.435  2681  2693 D BtGatt.GattService: unregisterClient() - clientIf=5,
09-06 19:17:24.435  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:17:24.435  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:17:24.435  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:17:24.435  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:17:24.436  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:17:24.437  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.437  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:17:24.437  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:17:24.437  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:17:24.437  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:17:24.439  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.439  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.439  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.439  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:17:24.439  3827  3874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:17:24.439  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:24.439  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.439  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.440  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.440  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:24.440  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.440  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 19:17:24.440  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.440  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:17:24.440  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.441  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.441  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:17:24.441  2681  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:17:24.442  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.442  2681  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:17:24.443  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:24.443  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:24.443  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:24.443  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.444  3827  3874 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-06 19:17:24.445  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.445  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:24.445  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:17:24.445  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.445  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.445  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.446  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.446  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.446  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.446  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.446  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.446  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.446  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.446  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.449  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.449  2681  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:17:24.449  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.449  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:24.450  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.450  2681  2709 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:17:24.450  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.450  2681  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:17:24.451  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:17:24.451  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.452  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.452  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.452  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:24.452  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.452  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.452  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.452  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.453  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.453  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.453  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.453  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.453  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.453  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.455  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.455  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.455  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.455  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.456  3827  3874 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 19:17:24.456  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.456  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.456  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.457  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.457  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.457  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.457  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.457  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.457  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.457  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.458  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.458  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.458  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.458  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.459  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:24.459  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.459  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.460  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.460  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:17:24.460  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.461  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.461  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:17:24.461  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.461  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.461  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.461  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.461  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:24.462  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.462  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.462  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.462  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.462  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.462  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.463  2681  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:17:24.463  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:24.465  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:24.465  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.465  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.466  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.467  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
,09-06 19:17:24.467  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:17:24.468  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:17:24.468  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:17:24.468  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:17:24.468  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:17:24.469  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.469  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.469  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.469  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.469  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.469  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.470  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
,09-06 19:17:24.470  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.470  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.470  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.470  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.470  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.470  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.470  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.472  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.472  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.472  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:24.472  2681  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:17:24.472  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.472  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:24.473  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:17:24.474  3827  3874 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-06 19:17:24.474  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:17:24.481  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:17:24.481  3827  3874 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-06 19:17:24.482  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:17:24.483  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:17:24.484  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-06 19:17:24.484  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:17:24.484  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:17:24.485  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:17:24.485  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:17:24.485  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:17:24.485  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:17:24.485  2681  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:17:24.485  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:17:24.485  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:24.485  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:17:24.486  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:17:24.486  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:17:24.486  2681  2709 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:17:24.486  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:17:24.486  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:17:24.486  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:17:24.486  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:17:24.487  3827  3874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-06 19:17:24.487  3827  3874 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:17:24.487  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:17:24.487  3827  3874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:17:24.487  3827  3874 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:17:24.487  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:17:24.487  3827  3874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:17:24.488  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-06 19:17:24.492  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-06 19:17:24.493  2681  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:17:24.493  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:17:24.493  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:24.493  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-06 19:17:24.493  2681  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:17:24.494  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-06 19:17:24.494  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:17:24.494  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:17:24.494  3827  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:17:24.494  3827  3874 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:17:24.495  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.495  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.495  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:17:24.495  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.495  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.495  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.495  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:17:24.496  3827  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
,09-06 19:17:24.497  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.497  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:24.497  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.497  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.497  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.497  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.497  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.497  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.499  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.499  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.499  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.499  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.500  3827  3874 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:17:24.501  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.501  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:24.501  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.501  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:24.501  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.501  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.501  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-06 19:17:24.501  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
,09-06 19:17:24.501  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.501  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.501  3827  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
09-06 19:17:24.501  2681  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:17:24.502  2681  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:24.501  3827  3876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:17:24.501  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.502  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.502  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.502  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.502  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.502  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.503  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.503  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.503  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:24.503  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.505  3827  3874 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:17:24.505  3827  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
,09-06 19:17:24.505  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.505  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:24.505  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.505  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.505  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.505  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.506  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
,09-06 19:17:24.506  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.506  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.506  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.506  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.506  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.506  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.506  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.507  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.507  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:24.507  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.507  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.508  3827  3874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-06 19:17:24.508  3827  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:17:24.508  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:17:24.508  3827  3874 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:17:24.509  3827  3874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:17:24.509  3827  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-06 19:17:24.509  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:17:24.509  3827  3874 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:17:24.509  3827  3874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-06 19:17:24.509  3827  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:17:24.509  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:17:24.509  3827  3874 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:17:24.509  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.509  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.509  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.510  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.510  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.510  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.510  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
,09-06 19:17:24.510  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.510  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.510  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.510  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.510  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.510  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.510  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.512  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.512  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.512  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.512  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.512  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:24.512  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.512  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.512  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.513  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.513  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.513  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.513  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.513  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.513  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.513  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.513  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:24.513  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.513  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.513  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.513  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.513  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.513  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.514  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:24.514  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.514  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.514  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.514  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.514  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.514  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.514  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.514  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.514  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.514  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.516  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.516  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:24.516  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.516  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.518  3827  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:17:24.518  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:24.519  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:17:24.519  3827  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:17:24.519  3827  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-06 19:17:24.520  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:17:24.520  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:17:24.520  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:17:24.520  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.520  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:17:24.520  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:17:24.521  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:17:24.521  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.521  3827  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:17:24.521  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-06 19:17:24.521  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.521  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.521  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:17:24.521  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:17:24.521  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:24.521  3827  3878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:17:24.522  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.522  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:17:24.523  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.523  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.523  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:24.523  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:24.523  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.524  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:24.524  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.524  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.524  3827  3878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 19:17:24.524  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.524  3827  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:17:24.524  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.524  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.524  3827  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:17:24.524  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.524  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.524  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:17:24.524  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.525  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.525  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.525  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.525  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.525  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.526  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:24.526  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.526  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.526  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.527  3827  3874 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:17:24.528  3827  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:17:24.528  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:17:24.529  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:17:24.529  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:24.529  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.529  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.530  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.530  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.530  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.530  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.530  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.531  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.531  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.531  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:24.531  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.531  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.531  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.532  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.532  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:24.533  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.533  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.536  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:24.536  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-06 19:17:24.536  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.537  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.537  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.537  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.537  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.537  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.537  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
09-06 19:17:24.537  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.537  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.537  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.537  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.537  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.539  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:24.539  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.539  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.539  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.540  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:24.540  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:24.540  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:24.540  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:24.541  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.541  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.541  3827  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9f9c not in the list
09-06 19:17:24.541  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.541  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.541  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:24.541  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.542  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:24.542  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:24.542  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:24.543  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:24.543  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:24.543  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:24.543  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4fada5 not in the list
,09-06 19:17:24.545  3827  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:17:24.545  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:17:24.545  3827  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:17:24.545  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:17:24.545  3827  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-06 19:17:24.546  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-06 19:17:24.548  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:17:24.548  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-06 19:17:24.549  3827  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:17:24.550  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:17:24.550  3827  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:17:24.550  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-06 19:17:24.550  3827  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:17:24.550  3827  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-06 19:17:24.551  3827  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:17:24.551  3827  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:17:24.552  3827  3874 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-06 19:17:24.552  3827  3874 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:17:24.552  3827  3874 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:17:24.552  3827  3874 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-06 19:17:24.554  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:24.554  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9aa9dff added. We now have 2 listener(s)
09-06 19:17:24.554  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:24.557  3827  3874 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 19:17:24.557   872  1986 D WifiService: setWifiEnabled: true pid=3827, uid=10000
09-06 19:17:24.557   872  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:17:24.558  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:17:24.559  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c0327cc added. We now have 3 listener(s)
09-06 19:17:24.559  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:24.568  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:24.568  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7404a15 added. We now have 4 listener(s)
09-06 19:17:24.568  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:24.571  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:24.571  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e30212a added. We now have 5 listener(s)
,09-06 19:17:24.571  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:24.575   872  2004 D WifiService: setWifiEnabled: false pid=3827, uid=10000
,09-06 19:17:24.575   872  2004 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:17:24.583  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:24.589  2681  2702 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 19:17:24.589  2681  2702 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:17:24.590  2681  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:17:24.590  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.590  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:24.591  2681  2702 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 19:17:24.592  2681  2702 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:17:24.592  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.592  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.593  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:24.593  2681  2706 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:17:24.594  2681  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 19:17:24.603  2681  2681 D BluetoothMapService: onReceive
09-06 19:17:24.603  2681  2681 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:17:24.603  2681  2681 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:17:24.603  2681  2681 D BluetoothMapService: MAP Service closeService in
09-06 19:17:24.603  2681  2681 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 19:17:24.604  2681  2681 D ObexServerSockets0: shutdown(block = true)
09-06 19:17:24.604  2681  2681 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 19:17:24.604  2681  2681 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:17:24.605  2681  2840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 19:17:24.606  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:17:24.606  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:17:24.606  2681  2841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.606  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:24.606  2681  2807 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-06 19:17:24.607  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.607  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.609  2681  2681 I BtOppRfcommListener: stopping Accept Thread
09-06 19:17:24.609  2681  3423 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:17:24.610   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:17:24.610   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 19:17:24.610   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:17:24.611  2681  3423 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:17:24.611   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:17:24.612  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.616   872  1306 E native  : do suspend true
09-06 19:17:24.617  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:24.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:17:24.618  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.619  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:24.621  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:24.624  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:24.626  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:24.628   872  1852 D DhcpClient: Clearing IP address
,09-06 19:17:24.629   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:17:24.632   872   885 I ActivityManager: Start proc 3883:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-06 19:17:24.632   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:24.634  2681  2681 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:17:24.636  1969  1983 D BluetoothHeadset: Proxy object disconnected
,09-06 19:17:24.637  1352  1375 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:24.637   872   872 D BluetoothHeadset: Proxy object disconnected
,09-06 19:17:24.637   872   872 D BluetoothHeadset: Proxy object disconnected
,09-06 19:17:24.637   872   872 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:24.638  2681  2681 D A2dpService: Received stop request...Stopping profile...
09-06 19:17:24.638  1352  1352 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:17:24.639  2681  2819 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:17:24.640  1528  2434 V NativeCrypto: Read error: ssl=0x9aa7ec00: I/O error during system call, Connection timed out
09-06 19:17:24.641   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 19:17:24.641   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-06 19:17:24.643   394   394 E Parcel  : Reading a NULL string not supported here.,
09-06 19:17:24.644   872   872 D BluetoothA2dp: Proxy object disconnected
09-06 19:17:24.644  2681  2681 D HidService: Received stop request...Stopping profile...
,09-06 19:17:24.645  2681  2681 D HidService: Stopping Bluetooth HidService
09-06 19:17:24.648  2681  2681 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:17:24.648  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:24.648  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false,
09-06 19:17:24.648   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-06 19:17:24.648  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:24.649  2681  2681 D HealthService: Received stop request...Stopping profile...
09-06 19:17:24.649   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,09-06 19:17:24.649   872  1306 E native  : do suspend true
,09-06 19:17:24.650  1352  1352 D BluetoothA2dp: Proxy object disconnected
09-06 19:17:24.650  1352  1352 D BluetoothInputDevice: Proxy object disconnected
09-06 19:17:24.651  1352  1352 D HidProfile: Bluetooth service disconnected
09-06 19:17:24.651   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-06 19:17:24.656  2681  2681 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:17:24.657  2681  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-06 19:17:24.657  2681  2805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:17:24.657  2681  2805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:17:24.657  2681  2805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:17:24.657  2681  2706 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-06 19:17:24.658  2681  2681 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:17:24.658  1528  2434 V NativeCrypto: SSL shutdown failed: ssl=0x9aa7ec00: I/O error during system call, Broken pipe
,09-06 19:17:24.660  2681  2681 D PanService: Received stop request...Stopping profile...
09-06 19:17:24.661  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:17:24.661  1352  1352 D PanProfile: Bluetooth service disconnected
09-06 19:17:24.661  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-06 19:17:24.661  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:24.661  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:24.662  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:24.663  2681  2805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:24.664  2681  2805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:24.664  2681  2805 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:17:24.664  2681  2805 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:17:24.664  2681  2805 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:17:24.664  2681  2805 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:17:24.664  2681  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 19:17:24.665  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-06 19:17:24.665  2681  2681 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:17:24.665  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:24.665  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:24.665  2681  2681 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:17:24.665  2681  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:17:24.665  2681  2681 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:17:24.666  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-06 19:17:24.666  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:24.666  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:24.666  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:24.667  2681  2681 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:17:24.667  2681  2681 D BluetoothMapService: stop()
09-06 19:17:24.668   872  1863 D DhcpClient: Receive thread stopped
09-06 19:17:24.669  2681  2681 D BluetoothMapAppObserver: deinitObservers()
09-06 19:17:24.669  2681  2681 D BluetoothMapAppObserver: removeReceiver()
09-06 19:17:24.674  2681  2681 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:17:24.674  2681  2706 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:17:24.675  2681  2681 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:17:24.675  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-06 19:17:24.675  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:24.675  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:24.675  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:24.675  2681  2681 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:17:24.675  2681  2681 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:17:24.676  2681  2681 D BluetoothMapService: MAP Service closeService in
09-06 19:17:24.676  2681  2681 V BluetoothAdapterState: isTurningOff()=true
09-06 19:17:24.676  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:24.676  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:24.676  2681  2681 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:24.676  2681  2681 D BluetoothMapService: cleanup()
09-06 19:17:24.676  2681  2681 D BluetoothMapService: MAP Service closeService in
09-06 19:17:24.677  2681  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:17:24.677  2681  2702 D BluetoothAdapterProperties: Setting state to 15
09-06 19:17:24.677  2681  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:17:24.678   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:17:24.678  1352  1375 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:17:24.679   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:17:24.679  1352  1916 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:17:24.680  1969  2130 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:17:24.680  1352  1363 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:17:24.681  1352  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:17:24.681  1352  1916 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:17:24.682   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:17:24.682  1352  1363 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:17:24.682   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:17:24.685   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 19:17:24.677  2681  2702 I BluetoothAdapterState: Entering BleOnState
09-06 19:17:24.686  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.686  2681  2702 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 19:17:24.688  2681  2702 D BluetoothAdapterProperties: Setting state to 16
,09-06 19:17:24.688  2681  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:24.686  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:24.688  2681  2702 D BluetoothAdapterProperties: onBleDisable
,09-06 19:17:24.688  2681  2702 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:17:24.688  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.689  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:24.689  2681  2706 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:17:24.691  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:24.691  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:24.691  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.691  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:24.692  2681  2703 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:17:24.693  2681  2805 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:17:24.693  2681  2805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:24.693  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.694  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.706   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 19:17:24.706   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:17:24.707   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:17:24.707   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:17:24.707   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-06 19:17:24.709  3883  3883 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-06 19:17:24.709   872   889 D Tethering: MasterInitialState.processMessage what=3
09-06 19:17:24.712  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:24.713  3369  3369 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@720615 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-06 19:17:24.713  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:24.725   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:17:24.727  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:24.728  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:24.728   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:17:24.728  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.728  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:24.729  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:24.729  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:24.730  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:24.730  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:24.730  2046  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:17:24.733  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:17:24.737   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1386b53:true
09-06 19:17:24.738  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:17:24.751   872   882 I ActivityManager: Start proc 3902:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-06 19:17:24.759  3883  3883 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 19:17:24.762  3883  3883 D BluetoothMap: Create BluetoothMap proxy object
09-06 19:17:24.763   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:17:24.764   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-06 19:17:24.767  3883  3883 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-06 19:17:24.778  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:17:24.784  3902  3902 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-06 19:17:24.786   872  1918 I ActivityManager: Killing 3369:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-06 19:17:24.896  2681  2706 I bt_hci  : shut_down
,09-06 19:17:24.916  2681  2710 I bt_vendor: low_power_mode_cb
,09-06 19:17:24.923  2681  2710 D bt_hwcfg: hw_epilog_process
,09-06 19:17:24.930  2681  2710 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:17:24.930  2681  2710 I bt_vendor: epilog_cb
09-06 19:17:24.930  2681  2710 I bt_hci  : epilog_finished_callback
,09-06 19:17:24.933  2681  2706 I bt_hci_h4: hal_close
09-06 19:17:24.933  2681  2706 I bt_userial_vendor: device fd = 51 close
,09-06 19:17:24.978  3902  3902 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.978  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.k.d(PG:583)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:24.979  3902  3902 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:24.979  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:25.002  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:17:25.018  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:17:25.024  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:17:25.039  3883  3883 D DockEventReceiver: finishStartingService: stopping service
09-06 19:17:25.045  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:17:25.058  1725  1725 D SystemUpdateService: onCreate
,09-06 19:17:25.062  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:17:25.071  2681  2703 D bt_stack_manager: event_shut_down_stack finished.
,09-06 19:17:25.072  2681  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:17:25.078  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:17:25.078  2681  2702 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-06 19:17:25.078  2681  2681 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:17:25.079  2681  2681 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 19:17:25.080  2681  2681 D BtGatt.GattService: stop()
09-06 19:17:25.080  2681  2681 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:17:25.082  1725  2390 I iu.UploadsManager: num queued entries: 0
09-06 19:17:25.082  1725  2390 I iu.UploadsManager: num updated entries: 0
,09-06 19:17:25.083  1725  2390 I iu.SyncManager: NEXT; no task
09-06 19:17:25.083  2681  2681 V BluetoothAdapterState: isTurningOff()=false
09-06 19:17:25.083  2681  2681 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:25.084  2681  2681 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:17:25.084  2681  2681 V BluetoothAdapterState: isBleTurningOff()=true
09-06 19:17:25.085  2681  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 19:17:25.085  2681  2702 D BluetoothAdapterProperties: Setting state to 10
09-06 19:17:25.085  2681  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 19:17:25.086  1725  3933 I SystemUpdateService: active receiver: enabled
09-06 19:17:25.086  2681  2702 I BluetoothAdapterState: Entering OffState
09-06 19:17:25.088   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 19:17:25.090  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:17:25.092  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:17:25.095  1725  3933 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:17:25.109  1725  3933 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 19:17:25.109  1725  3933 I SystemUpdateService: now status is 0 (complete)
,09-06 19:17:25.111  1725  3933 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:17:25.113  1725  3933 I SystemUpdateService: file has been verified
,09-06 19:17:25.113  1725  3933 I SystemUpdateService: OTA package size = 12249756
09-06 19:17:25.114   872  1992 I ActivityManager: Start proc 3936:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-06 19:17:25.125  1725  3933 I SystemUpdateService: showing system update notification
,09-06 19:17:25.131  2681  2681 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 19:17:25.131  2681  2681 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-06 19:17:25.131  2681  2681 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:17:25.132  2681  2703 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-06 19:17:25.133  2681  2703 D bt_stack_manager: event_clean_up_stack finished.
,09-06 19:17:25.136  2681  2681 I art     : System.exit called, status: 0
,09-06 19:17:25.136  2681  2681 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:17:25.178   872  1961 I ActivityManager: Process com.android.bluetooth (pid 2681) has died
,09-06 19:17:25.181  3936  3936 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-06 19:17:25.183  3936  3936 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:25.194  3936  3936 D SprintDMHelper: simOperator: 
,09-06 19:17:25.194  3936  3936 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:17:25.213   872  1986 I ActivityManager: Start proc 3949:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher,
,09-06 19:17:25.214   872  1986 I ActivityManager: Killing 3556:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-06 19:17:25.256  1725  1725 D SystemUpdateService: onDestroy
,09-06 19:17:25.259   872   882 I ActivityManager: Killing 3433:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-06 19:17:25.292  3902  3927 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:17:25.311   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0a76a2:true
,09-06 19:17:25.416   872  1986 I ActivityManager: Start proc 3968:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-06 19:17:25.475  3968  3968 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-06 19:17:25.522  3968  3968 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:17:25.522  3968  3968 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:17:25.522  3968  3968 I GAv4    :   adb logcat -s GAv4
,09-06 19:17:25.536  3968  3968 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:17:25.542  3968  3968 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:17:25.568  3968  3985 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:17:25.678  3968  3968 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-06 19:17:25.718  3968  3968 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-06 19:17:25.726  3968  3968 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6522-6525)
09-06 19:17:25.726  3968  3968 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:17:25.734  3968  3968 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5a19e85}
09-06 19:17:25.735  3968  3968 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:17:25.735  3968  3968 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:17:25.741  3968  3968 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 19:17:25.742  3968  3968 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:17:25.764  3968  3968 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 19:17:25.778  3968  3968 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:17:25.778  3968  3968 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:17:25.778  3968  3968 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:17:25.778  3968  3968 I Adreno  : Build Date                       : 10/20/15
09-06 19:17:25.778  3968  3968 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:17:25.778  3968  3968 I Adreno  : Local Branch                     : M14
09-06 19:17:25.778  3968  3968 I Adreno  : Remote Branch                    : 
09-06 19:17:25.778  3968  3968 I Adreno  : Remote Branch                    : 
09-06 19:17:25.778  3968  3968 I Adreno  : Reconstruct Branch               : 
,09-06 19:17:25.844  3968  3968 I NSApplication: Starting up...
,09-06 19:17:25.856  3968  4014 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:17:25.881   872  1995 I ActivityManager: Start proc 4019:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-06 19:17:25.883   872  1995 I ActivityManager: Killing 3483:android.process.acore/u0a5 (adj 15): empty #17
,09-06 19:17:25.963  4019  4019 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-06 19:17:26.166   872  1918 I ActivityManager: Killing 3674:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-06 19:17:26.263   872  1918 I ActivityManager: Start proc 4033:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-06 19:17:26.389  4033  4033 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-06 19:17:26.436  4033  4033 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-06 19:17:26.455   872  2004 I ActivityManager: Killing 3689:com.android.musicfx/u0a18 (adj 15): empty #17
,09-06 19:17:27.596   872  1967 D WifiService: setWifiEnabled: true pid=3827, uid=10000
,09-06 19:17:27.596   872  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:17:27.610   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:17:27.617  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:27.617  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:27.617  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:17:27.617  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:27.618  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:27.619  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:27.619  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:17:27.619  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:27.638   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:17:27.639   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 19:17:27.641   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-06 19:17:27.642   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:17:27.642   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-06 19:17:27.642   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 19:17:27.642   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:17:27.660   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:17:27.661   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:17:27.661   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:27.662   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-06 19:17:27.662   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:17:27.674   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:17:27.675   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:17:27.680   872  1306 E native  : do suspend true
,09-06 19:17:27.705   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:17:28.984   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:17:29.072   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.69 rxSuccessRate=10.81 delta 1000 -> 994
,09-06 19:17:29.073   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:17:29.073   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:17:29.094   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:17:29.138   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:17:29.142  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:17:29.571  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:17:29.608  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:17:29.608  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:17:29.617   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:17:29.629   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:17:29.629   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:17:29.630   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 19:17:29.654   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:17:29.669   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:29.670   872  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:17:29.682   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:17:29.723   872  4068 D DhcpClient: Receive thread started
,09-06 19:17:29.805   872  1306 E native  : do suspend false
,09-06 19:17:29.816   872  1852 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:17:29.847   872  4068 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172622, domain null
09-06 19:17:29.848   872  1852 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172622 seconds
,09-06 19:17:29.851   872  1852 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:17:29.864   872  4068 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:17:29.865   872  1852 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:17:29.872   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:29.876   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:17:29.880   872  1852 D DhcpClient: Scheduling renewal in 86399s
,09-06 19:17:29.880   872  1306 E native  : do suspend true
,09-06 19:17:29.894   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:17:29.894   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-06 19:17:29.895   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:17:29.902   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:17:29.902   872  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-06 19:17:29.970   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:17:29.971   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-06 19:17:29.974   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-06 19:17:29.976   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-06 19:17:29.979   872  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-06 19:17:29.995   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:17:30.007   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-06 19:17:30.008   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-06 19:17:30.008   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-06 19:17:30.008   872  1308 D ConnectivityService:    accepting network in place of null,
,09-06 19:17:30.009   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 19:17:30.010   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
09-06 19:17:30.011   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:17:30.069   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:17:30.104   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:17:30.115   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:17:30.116   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:30.128   872   889 D Tethering: MasterInitialState.processMessage what=3
09-06 19:17:30.135   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-06 19:17:30.138  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:30.138  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:30.138  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.138  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:30.144  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:30.144  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:30.145  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.145  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:30.152  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:17:30.156  1725  1725 D SystemUpdateService: onCreate
,09-06 19:17:30.159  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:17:30.162  1725  4078 I SystemUpdateService: active receiver: enabled
,09-06 19:17:30.165  1725  4078 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:17:30.167  1725  4078 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-06 19:17:30.168  1725  4078 I SystemUpdateService: now status is 0 (complete)
09-06 19:17:30.168  1725  4078 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:17:30.168  1725  4078 I SystemUpdateService: file has been verified
09-06 19:17:30.168  1725  4078 I SystemUpdateService: OTA package size = 12249756
,09-06 19:17:30.174  1725  4078 I SystemUpdateService: showing system update notification
,09-06 19:17:30.180  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:17:30.182  1725  2390 I iu.UploadsManager: num queued entries: 0
,09-06 19:17:30.182  1725  2390 I iu.UploadsManager: num updated entries: 0
09-06 19:17:30.183  1725  2390 I iu.SyncManager: NEXT; no task
,09-06 19:17:30.190  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:17:30.191  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-06 19:17:30.192  1725  1725 D SystemUpdateService: onDestroy
09-06 19:17:30.192  1725  4083 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-06 19:17:30.192  1725  4083 W BaseAppContext: Using Auth Proxy for data requests.
,09-06 19:17:30.193  1725  4083 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:17:30.198  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:17:30.200  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:17:30.215  3936  3936 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:30.218  3936  3936 D SprintDMHelper: simOperator: 
,09-06 19:17:30.218  3936  3936 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:17:30.224  1528  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-06 19:17:30.225  1528  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 19:17:30.225  1528  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:17:30.225  1528  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:17:30.246  1725  4083 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-06 19:17:30.604   872   883 D WifiService: setWifiEnabled: false pid=3827, uid=10000
09-06 19:17:30.604   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:17:30.636  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 19:17:30.647   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:17:30.647   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 19:17:30.648   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:17:30.649   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:17:30.669   872  1306 E native  : do suspend true
,09-06 19:17:30.687   872  1852 D DhcpClient: Clearing IP address
09-06 19:17:30.688   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:17:30.697   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:30.703   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-06 19:17:30.703   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 19:17:30.703   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-06 19:17:30.704   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:17:30.704   872  1306 E native  : do suspend true
09-06 19:17:30.709   394   394 E Parcel  : Reading a NULL string not supported here.
09-06 19:17:30.716   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-06 19:17:30.738   872  4068 D DhcpClient: Receive thread stopped
,09-06 19:17:30.756   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:17:30.812   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:17:30.814   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:17:30.814   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:17:30.814   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:30.816   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:17:30.823  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:30.823  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:30.823  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.823  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:30.826   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-06 19:17:30.828  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:30.828  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:30.828  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.828  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:30.851  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-06 19:17:30.856   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 19:17:30.856  1725  1725 D SystemUpdateService: onCreate
,09-06 19:17:30.860  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:30.860  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:30.860  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.860  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:30.862  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:30.862  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:30.862  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:30.862  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:30.867   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:17:30.868  2046  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:17:30.885  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:17:30.901  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:17:30.904  1725  2390 I iu.UploadsManager: num queued entries: 0
,09-06 19:17:30.904  1725  2390 I iu.UploadsManager: num updated entries: 0
,09-06 19:17:30.916  1725  4098 I SystemUpdateService: active receiver: enabled
,09-06 19:17:30.917  1725  2390 I iu.SyncManager: NEXT; no task
,09-06 19:17:30.919  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:17:30.921  1725  4098 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:17:30.923   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:17:30.926  1725  4098 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 19:17:30.927  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:17:30.928  3936  3936 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:30.927  1725  4098 I SystemUpdateService: now status is 0 (complete)
,09-06 19:17:30.930  1725  4098 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:17:30.930  1725  4098 I SystemUpdateService: file has been verified
09-06 19:17:30.930  1725  4098 I SystemUpdateService: OTA package size = 12249756
09-06 19:17:30.935  3936  3936 D SprintDMHelper: simOperator: 
,09-06 19:17:30.935  3936  3936 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:17:30.948  1725  4098 I SystemUpdateService: showing system update notification
,09-06 19:17:30.961  1725  1725 D SystemUpdateService: onDestroy
,09-06 19:17:31.012  4019  4019 I art     : Waiting for a blocking GC DisableMovingGc
,09-06 19:17:31.012  4019  4019 I art     : Starting a blocking GC DisableMovingGc
,09-06 19:17:31.110   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 19:17:33.658   872   889 I ActivityManager: Start proc 4104:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 19:17:33.812  4104  4104 D AdapterServiceConfig: Adding HeadsetService
09-06 19:17:33.812  4104  4104 D AdapterServiceConfig: Adding A2dpService
,09-06 19:17:33.813  4104  4104 D AdapterServiceConfig: Adding HidService
09-06 19:17:33.814  4104  4104 D AdapterServiceConfig: Adding HealthService
09-06 19:17:33.814  4104  4104 D AdapterServiceConfig: Adding PanService
09-06 19:17:33.815  4104  4104 D AdapterServiceConfig: Adding GattService
09-06 19:17:33.816  4104  4104 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:17:33.835  4104  4104 D BluetoothAdapterState: make() - Creating AdapterState
09-06 19:17:33.835   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@568b3a4:true
,09-06 19:17:33.839  4104  4104 I bt_bluedroid: init
,09-06 19:17:33.839  4104  4116 I BluetoothAdapterState: Entering OffState
,09-06 19:17:33.847  4104  4117 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:17:33.848  4104  4117 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:17:33.848  4104  4117 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:17:33.850  4104  4117 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:17:33.852  4104  4104 I bt_bluedroid: get_profile_interface socket
,09-06 19:17:33.854  4104  4104 I bt_bluedroid: get_profile_interface sdp
,09-06 19:17:33.858  4104  4120 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-06 19:17:33.858  4104  4115 I bt_bluedroid: config_hci_snoop_log
,09-06 19:17:33.859   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:17:33.861  4104  4120 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:17:33.865  4104  4116 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:17:33.866  4104  4116 D BluetoothAdapterProperties: Setting state to 14
09-06 19:17:33.866  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:17:33.869  4104  4116 D BluetoothBondStateMachine: make
,09-06 19:17:33.873  4104  4121 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:17:33.880  4104  4116 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:17:33.880  4104  4104 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:17:33.883  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:33.884  4104  4104 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:17:33.884  4104  4104 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:17:33.884  4104  4104 D BtGatt.GattService: start()
09-06 19:17:33.884  4104  4104 I bt_bluedroid: get_profile_interface gatt
,09-06 19:17:33.885  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:33.886  4104  4104 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:17:33.890  4104  4104 V BluetoothAdapterState: isTurningOff()=false
09-06 19:17:33.891  4104  4104 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:17:33.891  4104  4104 V BluetoothAdapterState: isBleTurningOn()=true
09-06 19:17:33.891  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:33.892  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 19:17:33.892  4104  4116 I bt_bluedroid: enable
09-06 19:17:33.893  4104  4117 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-06 19:17:33.893  4104  4117 I bt_hci  : start_up
,09-06 19:17:33.901  4104  4117 I bt_vendor: alloc value 0xb3a70189
09-06 19:17:33.901  4104  4117 I bt_vendor: init
,09-06 19:17:33.901  4104  4117 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:17:33.901  4104  4117 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:17:34.013  4104  4117 D bt_hci  : start_up starting async portion
,09-06 19:17:34.013  4104  4124 I bt_hci  : event_finish_startup
09-06 19:17:34.014  4104  4124 I bt_hci_h4: hal_open
09-06 19:17:34.014  4104  4124 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:17:34.025  4104  4124 I bt_userial_vendor: device fd = 51 open
,09-06 19:17:34.052  4104  4124 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:17:34.084  4104  4124 D bt_hwcfg: Chipset BCM4354A2
09-06 19:17:34.084  4104  4124 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 19:17:34.085  4104  4124 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:17:34.738  4104  4124 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:17:34.739  4104  4124 D bt_hwcfg: Settlement delay -- 100 ms
09-06 19:17:34.739  4104  4124 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:17:34.856  4104  4124 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:17:34.857  4104  4124 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:17:34.886  4104  4124 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:17:34.887  4104  4124 I bt_vendor: firmware callback
,09-06 19:17:34.887  4104  4124 I bt_hci  : firmware_config_callback
,09-06 19:17:34.899  4104  4126 I bt_btu  : btu_task pending for preload complete event
,09-06 19:17:34.899  4104  4126 I bt_btu_task: Bluetooth chip preload is complete
,09-06 19:17:34.900  4104  4126 I bt_btu  : btu_task received preload complete event
,09-06 19:17:34.912  4104  4126 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:17:34.912  4104  4126 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:17:34.913  4104  4126 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:17:34.913  4104  4126 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:17:34.913  4104  4126 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:17:34.913  4104  4126 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 19:17:34.914  4104  4126 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:17:34.915  4104  4126 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 19:17:34.915  4104  4126 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:17:34.915  4104  4126 I         : BTE_InitTraceLevels -- TRC_PAN
,09-06 19:17:34.916  4104  4126 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:17:34.916  4104  4126 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:17:34.917  4104  4126 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:17:34.918  4104  4126 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-06 19:17:34.919  4104  4126 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:17:35.026   872  4066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-06 19:17:35.028   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 19:17:35.048  4104  4126 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,09-06 19:17:35.048  4104  4126 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,09-06 19:17:35.074  4104  4120 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-06 19:17:35.075  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:17:35.076  4104  4120 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:17:35.079  4104  4120 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:17:35.083  4104  4120 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:17:35.085  4104  4120 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:17:35.089  4104  4120 D bt_hci  : do_postload posting postload work item
,09-06 19:17:35.089  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:35.089  4104  4124 I bt_hci  : event_postload
09-06 19:17:35.090  4104  4124 I bt_vendor: sco_config_cb
09-06 19:17:35.090  4104  4124 I bt_hci  : sco_config_callback postload finished.
,09-06 19:17:35.093  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:35.096  4104  4120 D bt_bte_conf: Device ID record 1 : primary
09-06 19:17:35.096  4104  4120 D bt_bte_conf:   vendorId            = 000f
09-06 19:17:35.097  4104  4120 D bt_bte_conf:   vendorIdSource      = 0001
09-06 19:17:35.097  4104  4120 D bt_bte_conf:   product             = 1200
09-06 19:17:35.097  4104  4120 D bt_bte_conf:   version             = 1436
09-06 19:17:35.097  4104  4120 D bt_bte_conf:   clientExecutableURL = 
09-06 19:17:35.099  4104  4124 I bt_vendor: low_power_mode_cb
09-06 19:17:35.098  4104  4120 D bt_bte_conf:   serviceDescription  = 
09-06 19:17:35.099  4104  4120 D bt_bte_conf:   documentationURL    = 
,09-06 19:17:35.100  4104  4120 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:17:35.102  4104  4117 D bt_stack_manager: event_start_up_stack finished
,09-06 19:17:35.102  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 19:17:35.102  4104  4116 D BluetoothAdapterProperties: Setting state to 15
09-06 19:17:35.103  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-06 19:17:35.103  4104  4116 I BluetoothAdapterState: Entering BleOnState
,09-06 19:17:35.107  4104  4116 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-06 19:17:35.107  4104  4116 D BluetoothAdapterProperties: Setting state to 11
09-06 19:17:35.107  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:17:35.114  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:35.115  4104  4104 D HeadsetService: Received start request. Starting profile...
09-06 19:17:35.117  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:35.118  4104  4104 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:17:35.118  4104  4104 D HeadsetStateMachine: make
,09-06 19:17:35.121  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:35.129  4104  4104 D HeadsetStateMachine: max_hf_connections = 1
,09-06 19:17:35.129  4104  4104 I bt_bluedroid: get_profile_interface handsfree
09-06 19:17:35.129  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 19:17:35.129  4104  4120 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:17:35.134  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:35.135  4104  4104 D A2dpService: Received start request. Starting profile...
09-06 19:17:35.136  4104  4104 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:17:35.136  4104  4104 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:17:35.137  4104  4116 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:17:35.145  4104  4104 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:17:35.145  4104  4104 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:17:35.145  4104  4104 D A2dpStateMachine: make
,09-06 19:17:35.147  4104  4104 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:17:35.148  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:17:35.152  4104  4135 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:17:35.155  4104  4104 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:17:35.156  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:35.157  4104  4104 D HidService: Received start request. Starting profile...
,09-06 19:17:35.157  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:17:35.158  4104  4104 I bt_bluedroid: get_profile_interface hidhost
,09-06 19:17:35.158  4104  4104 D HidService: setHidService(): set to: null
,09-06 19:17:35.158  4104  4120 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
09-06 19:17:35.158  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-06 19:17:35.159  4104  4104 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:17:35.160  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:35.160  3883  3883 D BluetoothInputDevice: Proxy object connected
09-06 19:17:35.160  4104  4104 D HealthService: Received start request. Starting profile...
,09-06 19:17:35.161  3883  3883 D HidProfile: Bluetooth service connected
09-06 19:17:35.162  4104  4104 I bt_bluedroid: get_profile_interface health
09-06 19:17:35.164  4104  4104 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:17:35.165  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:35.166  3883  3883 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:17:35.166  3883  3883 D PanProfile: Bluetooth service connected
,09-06 19:17:35.167  4104  4104 D PanService: Received start request. Starting profile...
09-06 19:17:35.167  4104  4104 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:17:35.167  4104  4104 I bt_bluedroid: get_profile_interface pan
,09-06 19:17:35.169  4104  4120 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:17:35.172  4104  4104 V BluetoothAdapterState: isTurningOff()=false
09-06 19:17:35.173  4104  4132 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:17:35.173  4104  4104 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:35.173  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:35.173  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:35.181  4104  4104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:35.183  3883  3883 D BluetoothMap: Proxy object connected
09-06 19:17:35.184  3883  3883 D MapProfile: Bluetooth service connected
09-06 19:17:35.184  4104  4104 D BluetoothMapService: Received start request. Starting profile...
,09-06 19:17:35.184  3883  3883 D BluetoothMap: getConnectedDevices()
09-06 19:17:35.184  4104  4104 D BluetoothMapService: start()
,09-06 19:17:35.186  3883  3883 D BluetoothMap: Bluetooth is Not enabled
,09-06 19:17:35.187  4104  4104 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:17:35.188  4104  4104 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 19:17:35.188  4104  4104 D BluetoothMapAppObserver: createReceiver()
,09-06 19:17:35.189  4104  4104 D BluetoothMapAppObserver: initObservers()
09-06 19:17:35.189  4104  4104 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:17:35.195  4104  4104 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:35.195  4104  4104 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:35.195  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:35.195  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:35.195  4104  4104 V BluetoothAdapterState: isTurningOff()=false
09-06 19:17:35.196  4104  4104 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:35.196  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:17:35.196  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:35.198  4104  4104 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:35.198  4104  4104 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:35.198  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:35.199  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:35.199  4104  4104 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:35.199  4104  4104 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:17:35.200  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:17:35.200  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:35.200  4104  4104 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:35.200  4104  4104 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:17:35.200  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:17:35.200  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:35.201  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-06 19:17:35.201  4104  4116 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:17:35.201  4104  4116 D BluetoothAdapterProperties: State =  11
,09-06 19:17:35.203  4104  4120 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:17:35.203  4104  4120 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:17:35.203  4104  4116 D BluetoothAdapterProperties: Setting state to 12
09-06 19:17:35.203  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:17:35.204   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:17:35.204  4104  4116 I BluetoothAdapterState: Entering OnState
,09-06 19:17:35.205  1352  1375 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:17:35.207  3827  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:35.207  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:35.208  1352  1352 D BluetoothMap: Proxy object connected
,09-06 19:17:35.208  1352  1352 D MapProfile: Bluetooth service connected
09-06 19:17:35.208  1352  1352 D BluetoothMap: getConnectedDevices()
09-06 19:17:35.209   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:17:35.210  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:35.211   872   872 D BluetoothA2dp: Proxy object connected
09-06 19:17:35.211  3883  3893 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:17:35.212  3883  3895 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:17:35.215  1352  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:35.216  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:35.219  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:35.219  4104  4104 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:17:35.220  4104  4104 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 19:17:35.220  1352  1352 D BluetoothInputDevice: Proxy object connected
09-06 19:17:35.220  1969  2130 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:17:35.220  1352  1352 D HidProfile: Bluetooth service connected
09-06 19:17:35.221  3883  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:17:35.222  1352  1375 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:17:35.222  4104  4104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:35.223  1352  1363 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:17:35.225  1352  1352 D BluetoothA2dp: Proxy object connected
09-06 19:17:35.225  1352  1375 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:17:35.225  4104  4104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:35.227   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:17:35.227  1352  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:17:35.227  4104  4104 D ObexServerSockets: Succeed to create listening sockets ,
09-06 19:17:35.227  4104  4104 D ObexServerSockets0: startAccept()
09-06 19:17:35.227  4104  4104 D ObexServerSockets0: prepareForNewConnect()
09-06 19:17:35.227   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:17:35.228  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:17:35.228  1352  1352 D PanProfile: Bluetooth service connected
09-06 19:17:35.228  3883  3895 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:17:35.229   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:17:35.231  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:35.231  4104  4104 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:17:35.231  4104  4104 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 19:17:35.232  4104  4104 D BluetoothMapService: onReceive
09-06 19:17:35.232  4104  4104 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:17:35.232  4104  4104 D BluetoothMapService: STATE_ON
09-06 19:17:35.232  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:35.234  4104  4141 D ObexServerSockets0: Accepting socket connection...
,09-06 19:17:35.235  4104  4142 D ObexServerSockets0: Accepting socket connection...
,09-06 19:17:35.235  3883  3883 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:17:35.240  2277  4085 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-06 19:17:35.240  2277  4085 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:17:35.241  3883  3883 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-06 19:17:35.243  2277  4085 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-06 19:17:35.250  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:17:35.252  3883  3883 D BluetoothA2dp: Proxy object connected
,09-06 19:17:35.253  4104  4104 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:17:35.253  4104  4104 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:17:35.257  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:17:35.263  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:17:35.266   872  1384 I ActivityManager: Killing 2186:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-06 19:17:35.304  3883  3883 D BluetoothPbap: Proxy object connected
,09-06 19:17:35.304  1352  1352 D BluetoothPbap: Proxy object connected
09-06 19:17:35.305  1352  1352 D PbapServerProfile: Bluetooth service connected
09-06 19:17:35.305  3883  3883 D PbapServerProfile: Bluetooth service connected
,09-06 19:17:35.335  4104  4146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:35.351  3883  3893 D BluetoothHeadset: Proxy object connected
09-06 19:17:35.352  3883  3883 D HeadsetProfile: Bluetooth service connected
09-06 19:17:35.352  1969  1984 D BluetoothHeadset: Proxy object connected
09-06 19:17:35.353  1352  1363 D BluetoothHeadset: Proxy object connected
09-06 19:17:35.353   872   872 D BluetoothHeadset: Proxy object connected
09-06 19:17:35.353   872   872 D BluetoothHeadset: Proxy object connected
09-06 19:17:35.353  1352  1352 D HeadsetProfile: Bluetooth service connected
09-06 19:17:35.353   872   872 D BluetoothHeadset: Proxy object connected
,09-06 19:17:35.363  4104  4150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:35.369  4104  4150 I BtOppRfcommListener: Accept thread started.
,09-06 19:17:36.619  4104  4116 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 19:17:36.620  4104  4116 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:17:36.620  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-06 19:17:36.622  4104  4116 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 19:17:36.624  4104  4116 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:17:36.628  4104  4120 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:17:36.628  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-06 19:17:36.638  4104  4104 D BluetoothMapService: onReceive
,09-06 19:17:36.638  4104  4104 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:17:36.638  4104  4104 D BluetoothMapService: STATE_TURNING_OFF
,09-06 19:17:36.639  4104  4104 D BluetoothMapService: MAP Service closeService in
,09-06 19:17:36.639  4104  4104 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 19:17:36.639  4104  4104 D ObexServerSockets0: shutdown(block = true)
,09-06 19:17:36.646  4104  4141 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 19:17:36.647  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:36.647  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:36.651  4104  4104 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 19:17:36.652  4104  4142 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:17:36.653  4104  4104 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:17:36.653  4104  4104 I BtOppRfcommListener: stopping Accept Thread,
09-06 19:17:36.653  4104  4128 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 19:17:36.654  4104  4150 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
09-06 19:17:36.654  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:17:36.654  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:36.654  4104  4150 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:17:36.656  4104  4104 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:17:36.657  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:36.657  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:36.658  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:17:36.658  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:36.659  3883  3895 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:36.660  1969  1983 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:36.660  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:17:36.660  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 19:17:36.661  1352  1916 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:36.661   872   872 D BluetoothHeadset: Proxy object disconnected
,09-06 19:17:36.661   872   872 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:36.661   872   872 D BluetoothHeadset: Proxy object disconnected
09-06 19:17:36.662  4104  4104 D A2dpService: Received stop request...Stopping profile...,
09-06 19:17:36.663  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:36.663  4104  4135 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:17:36.665   872   872 D BluetoothA2dp: Proxy object disconnected
,09-06 19:17:36.666  3883  3883 D HeadsetProfile: Bluetooth service disconnected
09-06 19:17:36.668  4104  4104 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:17:36.668  4104  4104 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:17:36.669  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:36.669  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:36.672  3883  3883 D DockEventReceiver: finishStartingService: stopping service
09-06 19:17:36.673  3883  3883 D BluetoothA2dp: Proxy object disconnected
09-06 19:17:36.673  4104  4104 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:17:36.674  4104  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:36.674  4104  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:36.674  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 19:17:36.675  4104  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:36.675  4104  4104 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:17:36.675  4104  4120 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-06 19:17:36.675  4104  4104 D HidService: Received stop request...Stopping profile...
09-06 19:17:36.676  4104  4104 D HidService: Stopping Bluetooth HidService
09-06 19:17:36.683  1352  1352 D HeadsetProfile: Bluetooth service disconnected
09-06 19:17:36.683  1352  1352 D BluetoothA2dp: Proxy object disconnected
09-06 19:17:36.684  1352  1352 D BluetoothInputDevice: Proxy object disconnected
09-06 19:17:36.684  1352  1352 D HidProfile: Bluetooth service disconnected
09-06 19:17:36.685  3883  3883 D BluetoothInputDevice: Proxy object disconnected
09-06 19:17:36.685  3883  3883 D HidProfile: Bluetooth service disconnected
,09-06 19:17:36.686  4104  4104 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:17:36.687  4104  4104 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:36.687  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:36.687  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:36.688  4104  4104 D HealthService: Received stop request...Stopping profile...
,09-06 19:17:36.692  4104  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:17:36.692  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 19:17:36.692  4104  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-06 19:17:36.693  4104  4126 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:17:36.693  4104  4126 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
09-06 19:17:36.693  4104  4126 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:17:36.693  4104  4126 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-06 19:17:36.695  4104  4104 D PanService: Received stop request...Stopping profile...
09-06 19:17:36.696  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:17:36.696  1352  1352 D PanProfile: Bluetooth service disconnected
,09-06 19:17:36.696  4104  4104 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:17:36.697  4104  4104 D BluetoothMapService: stop()
,09-06 19:17:36.697  4104  4104 D BluetoothMapAppObserver: deinitObservers()
,09-06 19:17:36.698  4104  4104 D BluetoothMapAppObserver: removeReceiver()
,09-06 19:17:36.700  1352  1352 D BluetoothMap: Proxy object disconnected
,09-06 19:17:36.700  1352  1352 D MapProfile: Bluetooth service disconnected
,09-06 19:17:36.702  4104  4104 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:17:36.702  4104  4104 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:36.702  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:17:36.702  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:36.702  4104  4104 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 19:17:36.702  4104  4104 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-06 19:17:36.702  4104  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:17:36.704  4104  4104 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:17:36.704  4104  4104 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:36.704  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:36.704  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:36.705  4104  4104 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-06 19:17:36.705  4104  4120 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:17:36.705  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:17:36.705  4104  4104 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:17:36.705  4104  4104 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:17:36.706  4104  4104 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:36.706  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:36.706  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:36.706  4104  4104 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:17:36.706  4104  4104 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:17:36.707  4104  4104 D BluetoothMapService: MAP Service closeService in
09-06 19:17:36.708  4104  4104 V BluetoothAdapterState: isTurningOff()=true,
09-06 19:17:36.708  3883  3883 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:17:36.708  4104  4104 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:17:36.708  3883  3883 D PanProfile: Bluetooth service disconnected
09-06 19:17:36.708  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:17:36.708  4104  4104 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:36.708  3883  3883 D BluetoothMap: Proxy object disconnected
,09-06 19:17:36.708  3883  3883 D MapProfile: Bluetooth service disconnected
,09-06 19:17:36.708  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:17:36.709  4104  4116 D BluetoothAdapterProperties: Setting state to 15
09-06 19:17:36.709  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:17:36.709   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:17:36.710  4104  4116 I BluetoothAdapterState: Entering BleOnState
,09-06 19:17:36.710  3883  3893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:17:36.710  4104  4104 D BluetoothMapService: cleanup()
,09-06 19:17:36.710  4104  4104 D BluetoothMapService: MAP Service closeService in
09-06 19:17:36.711  1352  1916 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:17:36.712   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:17:36.713  3883  3893 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:17:36.713  1352  1352 D BluetoothPbap: Proxy object disconnected
,09-06 19:17:36.713  1352  1352 D PbapServerProfile: Bluetooth service disconnected
09-06 19:17:36.714  3883  4154 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:17:36.713  3883  3883 D BluetoothPbap: Proxy object disconnected
,09-06 19:17:36.714  3883  3883 D PbapServerProfile: Bluetooth service disconnected,
,09-06 19:17:36.717  1352  1916 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:17:36.718  1969  2130 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:17:36.718  3883  3895 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:17:36.720  1352  1375 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:17:36.721  3883  3893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:17:36.721  1352  1363 D BluetoothA2dp: onBluetoothStateChange: up=false,
09-06 19:17:36.722  1352  1916 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:17:36.723   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-06 19:17:36.723  1352  1375 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-06 19:17:36.724   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:17:36.724  3883  4154 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:17:36.725  4104  4116 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-06 19:17:36.725  4104  4116 D BluetoothAdapterProperties: Setting state to 16
09-06 19:17:36.725  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:17:36.726  4104  4116 D BluetoothAdapterProperties: onBleDisable
09-06 19:17:36.726  4104  4116 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:17:36.726  4104  4117 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:17:36.728  4104  4126 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 19:17:36.728  4104  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:17:36.733  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 19:17:36.734  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:36.735  4104  4120 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:17:36.737  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:17:36.737  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:36.739  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:36.742  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:17:36.743  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:17:36.929  4104  4120 I bt_hci  : shut_down
,09-06 19:17:36.929  4104  4124 D bt_hwcfg: hw_epilog_process
,09-06 19:17:36.945  4104  4124 I bt_vendor: low_power_mode_cb
,09-06 19:17:36.967  4104  4124 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:17:36.968  4104  4124 I bt_vendor: epilog_cb
,09-06 19:17:36.968  4104  4124 I bt_hci  : epilog_finished_callback,
,09-06 19:17:36.977  4104  4120 I bt_hci_h4: hal_close
,09-06 19:17:36.979  4104  4120 I bt_userial_vendor: device fd = 51 close
,09-06 19:17:37.106  4104  4117 D bt_stack_manager: event_shut_down_stack finished.
,09-06 19:17:37.107  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:17:37.113  4104  4104 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:17:37.112  4104  4116 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-06 19:17:37.114  4104  4104 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:17:37.115  4104  4104 D BtGatt.GattService: stop()
,09-06 19:17:37.115  4104  4104 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:17:37.119  4104  4104 V BluetoothAdapterState: isTurningOff()=false
09-06 19:17:37.120  4104  4104 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:37.120  4104  4104 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:37.120  4104  4104 V BluetoothAdapterState: isBleTurningOff()=true
09-06 19:17:37.121  4104  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 19:17:37.122  4104  4116 D BluetoothAdapterProperties: Setting state to 10
09-06 19:17:37.122  4104  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 19:17:37.124  4104  4116 I BluetoothAdapterState: Entering OffState
,09-06 19:17:37.125   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:17:37.151  4104  4104 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-06 19:17:37.151  4104  4104 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 19:17:37.152  4104  4117 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 19:17:37.159  4104  4117 D bt_stack_manager: event_clean_up_stack finished.
09-06 19:17:37.160  4104  4104 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:17:37.166  4104  4104 I art     : System.exit called, status: 0
,09-06 19:17:37.166  4104  4104 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:17:37.221   872  2004 I ActivityManager: Process com.android.bluetooth (pid 4104) has died
,09-06 19:17:38.011   872  1308 D ConnectivityService: handlePromptUnvalidated 101
,09-06 19:17:39.616  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:17:39.617  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:42.624  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:17:42.625  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a20f4b8 added. We now have 6 listener(s)
09-06 19:17:42.626  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:42.629  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:42.630  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8e87291 added. We now have 7 listener(s)
09-06 19:17:42.630  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:42.632  3827  3874 I System.out: IsBluetoothEnabled
,09-06 19:17:42.644  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:42.694   872   889 I ActivityManager: Start proc 4162:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 19:17:42.828  4162  4162 D AdapterServiceConfig: Adding HeadsetService
09-06 19:17:42.828  4162  4162 D AdapterServiceConfig: Adding A2dpService
09-06 19:17:42.829  4162  4162 D AdapterServiceConfig: Adding HidService
,09-06 19:17:42.829  4162  4162 D AdapterServiceConfig: Adding HealthService
09-06 19:17:42.829  4162  4162 D AdapterServiceConfig: Adding PanService
09-06 19:17:42.829  4162  4162 D AdapterServiceConfig: Adding GattService
09-06 19:17:42.829  4162  4162 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:17:42.842  4162  4162 D BluetoothAdapterState: make() - Creating AdapterState
09-06 19:17:42.842   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e87291:true
,09-06 19:17:42.848  4162  4162 I bt_bluedroid: init
,09-06 19:17:42.849  4162  4174 I BluetoothAdapterState: Entering OffState
,09-06 19:17:42.854  4162  4175 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:17:42.855  4162  4175 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:17:42.855  4162  4175 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:17:42.855  4162  4175 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:17:42.858  4162  4162 I bt_bluedroid: get_profile_interface socket
,09-06 19:17:42.860  4162  4178 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:17:42.862  4162  4178 D BluetoothAdapterProperties: Name is: Nexus 6
09-06 19:17:42.863  4162  4162 I bt_bluedroid: get_profile_interface sdp
,09-06 19:17:42.869  4162  4173 I bt_bluedroid: config_hci_snoop_log
,09-06 19:17:42.872   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:17:42.886  4162  4174 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:17:42.887  4162  4174 D BluetoothAdapterProperties: Setting state to 14
,09-06 19:17:42.889  4162  4174 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:17:42.894  4162  4174 D BluetoothBondStateMachine: make
,09-06 19:17:42.900  4162  4179 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:17:42.907  4162  4174 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:17:42.909  4162  4162 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:17:42.918  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:42.920  4162  4162 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:17:42.922  4162  4162 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:17:42.922  4162  4162 D BtGatt.GattService: start()
,09-06 19:17:42.923  4162  4162 I bt_bluedroid: get_profile_interface gatt
09-06 19:17:42.925  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:42.926  4162  4162 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:17:42.943  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:42.943  4162  4162 V BluetoothAdapterState: isTurningOn()=false
09-06 19:17:42.943  4162  4162 V BluetoothAdapterState: isBleTurningOn()=true
09-06 19:17:42.944  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:42.946  4162  4174 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 19:17:42.946  4162  4174 I bt_bluedroid: enable
09-06 19:17:42.947  4162  4175 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-06 19:17:42.948  4162  4175 I bt_hci  : start_up
,09-06 19:17:42.965  4162  4175 I bt_vendor: alloc value 0xb3a70189
,09-06 19:17:42.965  4162  4175 I bt_vendor: init
09-06 19:17:42.965  4162  4175 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:17:42.965  4162  4175 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:17:43.073  4162  4175 D bt_hci  : start_up starting async portion
,09-06 19:17:43.074  4162  4182 I bt_hci  : event_finish_startup
09-06 19:17:43.075  4162  4182 I bt_hci_h4: hal_open
09-06 19:17:43.075  4162  4182 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:17:43.086  4162  4182 I bt_userial_vendor: device fd = 51 open
,09-06 19:17:43.117  4162  4182 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:17:43.148  4162  4182 D bt_hwcfg: Chipset BCM4354A2
,09-06 19:17:43.148  4162  4182 D bt_hwcfg: Target name = [BCM4354A2]
09-06 19:17:43.149  4162  4182 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:17:44.043  4162  4182 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:17:44.045  4162  4182 D bt_hwcfg: Settlement delay -- 100 ms
09-06 19:17:44.045  4162  4182 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:17:44.163  4162  4182 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
09-06 19:17:44.165  4162  4182 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:17:44.193  4162  4182 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:17:44.193  4162  4182 I bt_vendor: firmware callback
09-06 19:17:44.193  4162  4182 I bt_hci  : firmware_config_callback
,09-06 19:17:44.205  4162  4184 I bt_btu  : btu_task pending for preload complete event
,09-06 19:17:44.206  4162  4184 I bt_btu_task: Bluetooth chip preload is complete
09-06 19:17:44.206  4162  4184 I bt_btu  : btu_task received preload complete event
,09-06 19:17:44.217  4162  4184 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:17:44.217  4162  4184 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:17:44.217  4162  4184 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:17:44.217  4162  4184 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:17:44.218  4162  4184 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:17:44.218  4162  4184 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:17:44.218  4162  4184 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:17:44.218  4162  4184 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:17:44.218  4162  4184 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:17:44.219  4162  4184 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:17:44.219  4162  4184 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:17:44.219  4162  4184 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:17:44.219  4162  4184 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:17:44.219  4162  4184 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:17:44.220  4162  4184 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:17:44.371  4162  4184 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,09-06 19:17:44.372  4162  4184 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,09-06 19:17:44.384  4162  4178 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:17:44.387  4162  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:17:44.388  4162  4178 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:17:44.392  4162  4178 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:17:44.396  4162  4178 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:17:44.396  4162  4178 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:17:44.397  4162  4178 D bt_hci  : do_postload posting postload work item
,09-06 19:17:44.397  4162  4182 I bt_hci  : event_postload
,09-06 19:17:44.397  4162  4182 I bt_vendor: sco_config_cb
,09-06 19:17:44.398  4162  4182 I bt_hci  : sco_config_callback postload finished.
,09-06 19:17:44.402  4162  4178 D bt_bte_conf: Device ID record 1 : primary
,09-06 19:17:44.403  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:44.403  4162  4178 D bt_bte_conf:   vendorId            = 000f
,09-06 19:17:44.403  4162  4178 D bt_bte_conf:   vendorIdSource      = 0001
09-06 19:17:44.404  4162  4178 D bt_bte_conf:   product             = 1200
09-06 19:17:44.405  4162  4178 D bt_bte_conf:   version             = 1436
,09-06 19:17:44.405  4162  4178 D bt_bte_conf:   clientExecutableURL = 
09-06 19:17:44.406  4162  4178 D bt_bte_conf:   serviceDescription  = 
,09-06 19:17:44.407  4162  4182 I bt_vendor: low_power_mode_cb
,09-06 19:17:44.406  4162  4178 D bt_bte_conf:   documentationURL    = 
09-06 19:17:44.408  4162  4178 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 19:17:44.409  4162  4175 D bt_stack_manager: event_start_up_stack finished
09-06 19:17:44.411  4162  4174 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 19:17:44.412  4162  4174 D BluetoothAdapterProperties: Setting state to 15
,09-06 19:17:44.412  4162  4174 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-06 19:17:44.413  4162  4174 I BluetoothAdapterState: Entering BleOnState
,09-06 19:17:44.420  4162  4174 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 19:17:44.420  4162  4174 D BluetoothAdapterProperties: Setting state to 11
09-06 19:17:44.421  4162  4174 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-06 19:17:44.429  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:44.434  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:44.435  4162  4162 D HeadsetService: Received start request. Starting profile...
09-06 19:17:44.438  4162  4162 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:17:44.438  4162  4162 D HeadsetStateMachine: make
,09-06 19:17:44.450  4162  4162 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:17:44.451  4162  4162 I bt_bluedroid: get_profile_interface handsfree
09-06 19:17:44.451  4162  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 19:17:44.452  4162  4178 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:17:44.454  4162  4174 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:17:44.456  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:44.457  4162  4162 D A2dpService: Received start request. Starting profile...
09-06 19:17:44.458  4162  4162 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:17:44.458  4162  4162 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:17:44.465  4162  4162 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:17:44.466  4162  4162 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:17:44.466  4162  4162 D A2dpStateMachine: make
,09-06 19:17:44.467  4162  4162 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:17:44.468  4162  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:17:44.470  4162  4162 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:17:44.471  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:44.471  4162  4193 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:17:44.471  4162  4162 D HidService: Received start request. Starting profile...
09-06 19:17:44.472  4162  4162 I bt_bluedroid: get_profile_interface hidhost
09-06 19:17:44.472  4162  4162 D HidService: setHidService(): set to: null
09-06 19:17:44.472  4162  4178 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
09-06 19:17:44.472  4162  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-06 19:17:44.472  4162  4162 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:17:44.473  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:44.474  4162  4162 D HealthService: Received start request. Starting profile...
,09-06 19:17:44.476  4162  4162 I bt_bluedroid: get_profile_interface health
,09-06 19:17:44.478  4162  4162 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:17:44.479  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:17:44.479  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
09-06 19:17:44.480  4162  4162 D PanService: Received start request. Starting profile...
09-06 19:17:44.480  4162  4162 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:17:44.480  4162  4162 I bt_bluedroid: get_profile_interface pan
,09-06 19:17:44.481  4162  4178 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:17:44.484  4162  4162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:44.485  4162  4162 D BluetoothMapService: Received start request. Starting profile...
09-06 19:17:44.485  4162  4162 D BluetoothMapService: start()
,09-06 19:17:44.487  4162  4162 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:17:44.488  4162  4162 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 19:17:44.488  4162  4162 D BluetoothMapAppObserver: createReceiver()
,09-06 19:17:44.489  4162  4162 D BluetoothMapAppObserver: initObservers()
09-06 19:17:44.489  4162  4162 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:17:44.495  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:44.496  4162  4162 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:44.496  4162  4162 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:44.496  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:44.498  4162  4191 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:44.498  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:44.499  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:44.499  4162  4162 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:17:44.499  4162  4162 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:44.499  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isTurningOn()=true
09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:17:44.500  4162  4162 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:17:44.501  4162  4174 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 19:17:44.501  4162  4174 D BluetoothAdapterProperties: ScanMode =  20
,09-06 19:17:44.501  4162  4174 D BluetoothAdapterProperties: State =  11
09-06 19:17:44.502  4162  4178 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:17:44.503  4162  4174 D BluetoothAdapterProperties: Setting state to 12,
09-06 19:17:44.503  4162  4174 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:17:44.503  4162  4178 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:17:44.503   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:17:44.504  4162  4174 I BluetoothAdapterState: Entering OnState
,09-06 19:17:44.504  3883  4154 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:44.508  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:44.508  1352  1375 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:17:44.510   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:17:44.511  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:44.511  3883  3893 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:17:44.511  1352  1352 D BluetoothMap: Proxy object connected
09-06 19:17:44.511  1352  1352 D MapProfile: Bluetooth service connected
09-06 19:17:44.512  1352  1352 D BluetoothMap: getConnectedDevices()
09-06 19:17:44.511   872   872 D BluetoothA2dp: Proxy object connected
,09-06 19:17:44.519  4162  4162 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 19:17:44.519  3883  3895 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:17:44.520  4162  4162 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 19:17:44.520  3883  3883 D BluetoothA2dp: Proxy object connected,
09-06 19:17:44.521  4162  4162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:44.523  1352  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:17:44.523  4162  4162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:44.525  4162  4162 D ObexServerSockets: Succeed to create listening sockets 
,09-06 19:17:44.525  4162  4162 D ObexServerSockets0: startAccept()
09-06 19:17:44.525  4162  4162 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:17:44.526  1969  2130 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:17:44.527  3883  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:17:44.529  3883  3883 D BluetoothMap: Proxy object connected
09-06 19:17:44.529  3883  3883 D MapProfile: Bluetooth service connected
09-06 19:17:44.529  1352  1375 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:17:44.529  3883  3883 D BluetoothMap: getConnectedDevices()
,09-06 19:17:44.530  4162  4162 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:17:44.530  4162  4162 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-06 19:17:44.531  4162  4199 D ObexServerSockets0: Accepting socket connection...
09-06 19:17:44.532  4162  4200 D ObexServerSockets0: Accepting socket connection...
09-06 19:17:44.532  3883  4154 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:17:44.532  1352  1352 D BluetoothInputDevice: Proxy object connected
09-06 19:17:44.532  1352  1352 D HidProfile: Bluetooth service connected
09-06 19:17:44.533  1352  1363 D BluetoothA2dp: onBluetoothStateChange: up=true,
09-06 19:17:44.535  3883  3883 D BluetoothInputDevice: Proxy object connected
09-06 19:17:44.535  3883  3883 D HidProfile: Bluetooth service connected
,09-06 19:17:44.535  1352  1352 D BluetoothA2dp: Proxy object connected
09-06 19:17:44.536  1352  1916 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:17:44.537   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:17:44.538  1352  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:17:44.539  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:17:44.539  1352  1352 D PanProfile: Bluetooth service connected
09-06 19:17:44.539   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:17:44.539  3883  3895 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:17:44.542  3883  3883 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:17:44.542  3883  3883 D PanProfile: Bluetooth service connected
09-06 19:17:44.543   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:17:44.544  4162  4162 D BluetoothMapService: onReceive
,09-06 19:17:44.544  4162  4162 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:17:44.544  4162  4162 D BluetoothMapService: STATE_ON
09-06 19:17:44.545  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:44.552  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:17:44.559  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:17:44.562  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:17:44.568  3883  3883 D BluetoothPbap: Proxy object connected
,09-06 19:17:44.568  3883  3883 D PbapServerProfile: Bluetooth service connected
,09-06 19:17:44.570  4162  4162 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:17:44.570  4162  4162 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:17:44.570  1352  1352 D BluetoothPbap: Proxy object connected
09-06 19:17:44.570  1352  1352 D PbapServerProfile: Bluetooth service connected
,09-06 19:17:44.576  4162  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:44.593  4162  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:17:44.594  4162  4208 I BtOppRfcommListener: Accept thread started.
,09-06 19:17:44.605  3883  3893 D BluetoothHeadset: Proxy object connected
,09-06 19:17:44.605  3883  3883 D HeadsetProfile: Bluetooth service connected
09-06 19:17:44.606  1969  1984 D BluetoothHeadset: Proxy object connected
09-06 19:17:44.606  1352  1375 D BluetoothHeadset: Proxy object connected
,09-06 19:17:44.607   872   872 D BluetoothHeadset: Proxy object connected
09-06 19:17:44.607   872   872 D BluetoothHeadset: Proxy object connected
09-06 19:17:44.607   872   872 D BluetoothHeadset: Proxy object connected
09-06 19:17:44.607  1352  1352 D HeadsetProfile: Bluetooth service connected
,09-06 19:17:44.627  1969  2290 D BluetoothHeadset: Proxy object connected
,09-06 19:17:44.634  3883  3895 D BluetoothHeadset: Proxy object connected
09-06 19:17:44.634  3883  3883 D HeadsetProfile: Bluetooth service connected
,09-06 19:17:44.637   872   889 D BluetoothHeadset: Proxy object connected
,09-06 19:17:44.641  1352  1916 D BluetoothHeadset: Proxy object connected
,09-06 19:17:44.642  1352  1352 D HeadsetProfile: Bluetooth service connected
09-06 19:17:44.644   872   889 D BluetoothHeadset: Proxy object connected
,09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:44.663  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:44.668  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:44.671  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:17:44.672  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0725f6 added. We now have 8 listener(s)
09-06 19:17:44.673  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:44.676   872  1961 D WifiService: setWifiEnabled: false pid=3827, uid=10000
09-06 19:17:44.676   872  1961 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:17:44.683  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:44.684   872   883 D WifiService: setWifiEnabled: true pid=3827, uid=10000
09-06 19:17:44.684   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:17:44.688   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:44.696  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:44.698  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:44.704   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:17:44.705   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-06 19:17:44.705   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 19:17:44.706   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:17:44.706   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-06 19:17:44.706   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 19:17:44.706   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:17:44.714   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:17:44.715   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:44.716   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-06 19:17:44.716   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:17:44.718   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:17:44.718   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-06 19:17:44.718   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:17:44.779   872  1306 E native  : do suspend true
,09-06 19:17:44.825   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.,
,09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:45.702  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:45.709  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:45.721  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:17:45.724  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:17:45.732  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@289763f Bundle[{}]
,09-06 19:17:45.733  3827  3874 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:17:45.733  3827  3874 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:17:45.734  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:17:45.734  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:17:45.735  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:17:45.737  3827  3874 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:17:45.741  3827  3874 I System.out: Running OutgoingSocketThread
,09-06 19:17:45.744  3827  4215 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,09-06 19:17:45.747  3827  4215 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43578
,09-06 19:17:45.747  3827  4215 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:17:46.100   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:17:46.238   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.12 rxSuccessRate=11.12 delta 1000 -> 994
,09-06 19:17:46.241   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:17:46.241   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:17:46.260   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:17:46.319   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:17:46.323  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:17:46.746  3827  3874 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
09-06 19:17:46.747  3827  3874 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
09-06 19:17:46.749  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:17:46.763  3827  3874 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
09-06 19:17:46.764  3827  3874 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 19:17:46.764  3827  3874 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,09-06 19:17:46.766  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:46.766  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e04df7 added. We now have 2 listener(s)
09-06 19:17:46.768  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:17:46.768  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:46.769  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:17:46.769  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.769  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ca464 added. We now have 9 listener(s)
09-06 19:17:46.769  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:46.770  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:17:46.777  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:46.785  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:46.788  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:46.788  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:17:46.788  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:46.788  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@577ab82 added. We now have 3 listener(s)
09-06 19:17:46.790  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:17:46.790  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:46.791  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:17:46.791  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.791  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1d293 added. We now have 10 listener(s)
,09-06 19:17:46.791  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:46.791  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:46.791  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:46.791  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:46.791  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:46.791  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:46.792  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:46.792  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:46.792  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:46.792  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e04df7 removed from the list
09-06 19:17:46.792  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:46.792  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ca464 removed from the list
09-06 19:17:46.794  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:46.794  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:17:46.794  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:46.795  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.795  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:46.797  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:46.798  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:46.798  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:46.798  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ca464 not in the list
,09-06 19:17:46.798  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.799  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:46.800  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:46.801  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:46.801  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:46.801  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1d293 removed from the list
,09-06 19:17:46.802  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:46.802  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.802  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:17:46.802  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:46.803  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@577ab82 removed from the list
,09-06 19:17:46.805  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:17:46.805  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b61a2d0 added. We now have 2 listener(s)
,09-06 19:17:46.808  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:17:46.808  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:17:46.812  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:17:46.812  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:17:46.812  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:17:46.813  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.813  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50de2c9 added. We now have 9 listener(s),
09-06 19:17:46.813  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:46.814  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:17:46.817   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:17:46.820  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:46.824  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:46.828  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:46.828  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:17:46.828   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-06 19:17:46.828  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:17:46.828   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:17:46.829   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:17:46.828  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62d04ef added. We now have 3 listener(s)
,09-06 19:17:46.831  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:46.831  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:17:46.831  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:46.831  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:17:46.832  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:17:46.832  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8861bfc added. We now have 10 listener(s)
,09-06 19:17:46.832  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:46.832  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:46.832  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:17:46.832  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:17:46.832  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:46.833  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:17:46.833  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:46.836  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 19:17:46.836  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:17:46.841  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:17:46.842  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:17:46.842  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:17:46.846   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:17:46.849  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:17:46.849  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:17:46.849  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:17:46.851  3827  3874 D BluetoothAdapter: STATE_ON
,09-06 19:17:46.855   371   870 D CommandListener: Setting iface cfg
,09-06 19:17:46.856   872  1306 D WifiStateMachine: Start Dhcp Watchdog 3
09-06 19:17:46.856  4162  4173 D BtGatt.GattService: registerClient() - UUID=8e879862-7de3-4000-912f-3a4a63159fcf
,09-06 19:17:46.857  4162  4178 D BtGatt.GattService: onClientRegistered() - UUID=8e879862-7de3-4000-912f-3a4a63159fcf, clientIf=5
09-06 19:17:46.858  3827  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:17:46.860  4162  4198 D BtGatt.GattService: start scan with filters
,09-06 19:17:46.864   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:17:46.865  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:17:46.865  4162  4181 D BtGatt.ScanManager: handling starting scan
,09-06 19:17:46.866  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:17:46.866  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:17:46.866  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:17:46.867  4162  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@402cee3
,09-06 19:17:46.872  4162  4178 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:17:46.872  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:46.872  4162  4181 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:17:46.874  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:17:46.875  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:46.875  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:17:46.879  4162  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:17:46.879  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.879  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:17:46.879  4162  4181 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:17:46.880  4162  4181 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:17:46.881   872  4218 D DhcpClient: Receive thread started
,09-06 19:17:46.885  3827  3874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:17:46.885  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:46.886  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:17:46.886  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:46.886  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:17:46.886  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:17:46.886  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:17:46.887  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:17:46.887  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:46.887  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:17:46.888  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:17:46.889  3827  3874 D BluetoothAdapter: STATE_ON
,09-06 19:17:46.890  4162  4198 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:17:46.891  4162  4172 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:17:46.891  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:17:46.891  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:17:46.891  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:17:46.892  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:17:46.892  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:17:46.892  4162  4178 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:17:46.892  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.893  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:46.893  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:17:46.893  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:17:46.893  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:17:46.894  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:17:46.896  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:46.896  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:17:46.896  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:17:46.898  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:46.898  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:46.898  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:46.898  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:46.898  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.898  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:46.898  4162  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:17:46.898  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:17:46.898  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.899  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b61a2d0 removed from the list
09-06 19:17:46.899  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:46.899  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50de2c9 removed from the list
09-06 19:17:46.899  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:46.899  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:46.900  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:46.900  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:46.901  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:46.901  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:46.901  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:46.901  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50de2c9 not in the list
09-06 19:17:46.901  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.901  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:46.902  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:46.902  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:46.902  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:46.903  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8861bfc removed from the list
09-06 19:17:46.903  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:46.903  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.903  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:46.903  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:46.903  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62d04ef removed from the list
09-06 19:17:46.904  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:46.904  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f16fbe8 added. We now have 2 listener(s)
,09-06 19:17:46.906  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:17:46.906  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:46.906  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:17:46.906  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.906  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afa2201 added. We now have 9 listener(s)
09-06 19:17:46.906  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:46.907  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:17:46.907  4162  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:17:46.907  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.907  4162  4181 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:17:46.910  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:46.913  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:46.915  4162  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:17:46.915  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.915  4162  4181 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:17:46.915  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:17:46.916  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:17:46.917  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:46.917  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:46.918  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38aa2e7 added. We now have 3 listener(s)
09-06 19:17:46.918  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:46.920  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:17:46.920  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:17:46.920  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:17:46.920  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.920  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@553ee94 added. We now have 10 listener(s)
,09-06 19:17:46.920  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:46.920  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:46.921  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:17:46.921  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:17:46.921  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:17:46.922  4162  4178 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:17:46.922  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:46.922  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:17:46.922  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.924  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 19:17:46.924  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:17:46.928  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:17:46.928  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:17:46.928  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:17:46.931  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:17:46.931  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:17:46.931  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:17:46.932  3827  3874 D BluetoothAdapter: STATE_ON
,09-06 19:17:46.934  4162  4172 D BtGatt.GattService: registerClient() - UUID=0b0cb991-290f-4304-9c7f-558ed01467c0
,09-06 19:17:46.934  4162  4178 D BtGatt.GattService: onClientRegistered() - UUID=0b0cb991-290f-4304-9c7f-558ed01467c0, clientIf=5
09-06 19:17:46.934  3827  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:17:46.935  4162  4190 D BtGatt.GattService: start scan with filters
,09-06 19:17:46.937  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:17:46.937  4162  4181 D BtGatt.ScanManager: handling starting scan
09-06 19:17:46.937  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:17:46.938  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:17:46.938  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:17:46.940  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:17:46.940  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:17:46.940  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:17:46.942  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:17:46.944  4162  4178 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:17:46.944  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:46.945  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:46.945  4162  4181 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:17:46.945  3827  3874 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:17:46.945  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:46.945  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:17:46.945  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:46.945  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:46.945  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:46.945  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:17:46.945  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:46.945  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f16fbe8 removed from the list
,09-06 19:17:46.945  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:46.946  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afa2201 removed from the list
09-06 19:17:46.946  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:17:46.946  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:46.946  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.946  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:17:46.946  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:46.947  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:17:46.948  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:46.948  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:46.948  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:46.948  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afa2201 not in the list
09-06 19:17:46.948  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:17:46.948  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:17:46.948  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:46.948  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:17:46.948  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:17:46.949  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:46.950  4162  4173 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:17:46.950  4162  4172 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 19:17:46.950  4162  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:17:46.951  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.951  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:17:46.951  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:17:46.951  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:17:46.951  4162  4181 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:17:46.951  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:17:46.951  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:17:46.951  4162  4181 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:17:46.952  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:46.952  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:17:46.952  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:17:46.952  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:17:46.953  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:46.954  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:46.954  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:46.954  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:46.954  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@553ee94 removed from the list
09-06 19:17:46.954  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:46.954  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:17:46.954  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:46.954  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:46.954  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:17:46.954  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:17:46.954  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38aa2e7 removed from the list
,09-06 19:17:46.955  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:46.955  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:17:46.955  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb6000 added. We now have 2 listener(s)
09-06 19:17:46.957  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:17:46.957  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:46.957  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:17:46.958  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.958  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d81039 added. We now have 9 listener(s)
,09-06 19:17:46.958  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:46.958  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:17:46.960  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:46.963  4162  4178 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:17:46.963  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:46.964  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:17:46.964   872  1306 E native  : do suspend false
,09-06 19:17:46.966  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:46.967  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:46.967  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:46.967  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f07df added. We now have 3 listener(s)
,09-06 19:17:46.968  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:46.970  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:17:46.970  4162  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:17:46.971  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.971  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:17:46.971  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:17:46.971  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:17:46.971  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:46.971  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b867c2c added. We now have 10 listener(s)
09-06 19:17:46.971  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:46.972  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:17:46.972  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:17:46.972  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:17:46.972  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:17:46.972  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:17:46.976  3827  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:17:46.976  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:17:46.979   872  1852 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:17:46.979  4162  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:17:46.980  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.980  4162  4181 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:17:46.981  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:17:46.982  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-06 19:17:46.982  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:17:46.985  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:17:46.986  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:17:46.986  3827  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:17:46.986  4162  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:17:46.986  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:46.986  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:46.986  4162  4181 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 19:17:46.988  4162  4172 D BtGatt.GattService: registerClient() - UUID=8ccb5353-9678-4114-b5bf-f90d5823fafa
09-06 19:17:46.989  4162  4178 D BtGatt.GattService: onClientRegistered() - UUID=8ccb5353-9678-4114-b5bf-f90d5823fafa, clientIf=5
09-06 19:17:46.990  3827  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:17:46.990  4162  4190 D BtGatt.GattService: start scan with filters
,09-06 19:17:46.993  4162  4178 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:17:46.993  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:46.993  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:17:46.993  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:17:46.994  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:17:46.994  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:17:46.994  4162  4181 D BtGatt.ScanManager: handling starting scan
,09-06 19:17:46.996  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:46.996  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:17:46.997  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:17:46.997   872  4218 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
09-06 19:17:46.998   872  1852 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
09-06 19:17:46.998  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:17:46.999   872  1852 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:17:47.001  4162  4178 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:17:47.001  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:47.002  4162  4181 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:17:47.003  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:17:47.003  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:47.003  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:47.003  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:17:47.003  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:47.004  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:17:47.004  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:17:47.004  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb6000 removed from the list
,09-06 19:17:47.004  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:47.004  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d81039 removed from the list
09-06 19:17:47.004  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:17:47.004  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:17:47.005  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:47.005  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:17:47.005  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:47.005  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:17:47.006  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:47.006  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:47.006  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:47.006  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d81039 not in the list
09-06 19:17:47.006  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:17:47.006  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:17:47.006  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:17:47.006  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:17:47.006  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:17:47.007  3827  3874 D BluetoothAdapter: STATE_ON
09-06 19:17:47.007  4162  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:17:47.007  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:47.008  4162  4181 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:17:47.008  4162  4198 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:17:47.008  4162  4181 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:17:47.008  4162  4173 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:17:47.008  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:17:47.009  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:17:47.009  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:17:47.009  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:17:47.009  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:17:47.009  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:17:47.010  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:17:47.010  3827  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:17:47.010  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:17:47.010  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:47.011  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:17:47.011  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:47.011  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:47.011   872  4218 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:17:47.011  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:17:47.011  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b867c2c removed from the list
09-06 19:17:47.011  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:47.011  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:17:47.011  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:47.011  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:47.012  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:47.012  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:17:47.012   872  1852 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:17:47.012  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f07df removed from the list
09-06 19:17:47.012  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:47.012  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f52f18 added. We now have 2 listener(s)
09-06 19:17:47.013   371   870 D CommandListener: Setting iface cfg
09-06 19:17:47.015  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:17:47.015  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:47.015  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:17:47.015  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:47.015  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4e8d71 added. We now have 9 listener(s)
09-06 19:17:47.015  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:17:47.016  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:17:47.016   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-06 19:17:47.017   872  1852 D DhcpClient: Scheduling renewal in 86399s
09-06 19:17:47.018  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:17:47.018  4162  4178 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:17:47.018  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:47.019   872  1306 E native  : do suspend true
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:17:47.021  3827  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:17:47.022  3827  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:17:47.023  3827  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:17:47.023  4162  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:17:47.023  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:47.023  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:17:47.023  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bac13d7 added. We now have 3 listener(s)
,09-06 19:17:47.024  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:47.025  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:17:47.025  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:17:47.025  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:17:47.025  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:17:47.026  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:17:47.026  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59a24c4 added. We now have 10 listener(s)
09-06 19:17:47.026  3827  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:17:47.026  3827  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:17:47.026  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:47.026  3827  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:17:47.026  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:47.026  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:17:47.026  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:17:47.026  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:17:47.026  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f52f18 removed from the list
09-06 19:17:47.026  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:17:47.027  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4e8d71 removed from the list
09-06 19:17:47.027  3827  3874 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:17:47.027  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:47.027  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:47.027  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:47.028  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:17:47.028  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:47.028  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:47.028  3827  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4e8d71 not in the list
09-06 19:17:47.028  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:47.028  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:17:47.029  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:17:47.029  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:17:47.029  3827  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:17:47.029  3827  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59a24c4 removed from the list
09-06 19:17:47.029  4162  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:17:47.029  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:47.029  3827  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:17:47.029  4162  4181 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:17:47.030  3827  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:17:47.030  3827  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:17:47.030  3827  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:17:47.030  3827  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bac13d7 removed from the list
09-06 19:17:47.031  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:17:47.031  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:17:47.031  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:17:47.031  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:17:47.031  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:17:47.031  3827  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:17:47.033   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-06 19:17:47.034   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-06 19:17:47.035   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:17:47.035   872  1308 D ConnectivityService: Adding iface wlan0 to network 102
09-06 19:17:47.037  4162  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:17:47.037  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:17:47.038  4162  4181 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:17:47.040   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:17:47.042  3827  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
09-06 19:17:47.042  3827  4220 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
09-06 19:17:47.042  3827  4220 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:17:47.043  4162  4178 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:17:47.043  4162  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:17:47.044  3827  4221 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
09-06 19:17:47.044  3827  4221 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
09-06 19:17:47.045  3827  4221 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:17:47.046  3827  3874 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:17:47.046  3827  3874 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-06 19:17:47.046  3827  3874 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:17:47.046  3827  3874 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:17:47.046  3827  3874 D com.test.thalitest.ThaliTestRunner: Total duration: 22842 ms
09-06 19:17:47.048  3827  3874 I jxcore-log: *Native tests were executed*
09-06 19:17:47.048  3827  3874 I jxcore-log: 
09-06 19:17:47.048  3827  3874 I jxcore-log: Total number of executed tests:  80
09-06 19:17:47.048  3827  3874 I jxcore-log: 
09-06 19:17:47.048  3827  3874 I jxcore-log: Number of passed tests:  80
09-06 19:17:47.048  3827  3874 I jxcore-log: 
,09-06 19:17:47.048  3827  3874 I jxcore-log: Number of failed tests:  0
09-06 19:17:47.048  3827  3874 I jxcore-log: 
09-06 19:17:47.049  3827  3874 I jxcore-log: Number of ignored tests:  0
09-06 19:17:47.049  3827  3874 I jxcore-log: 
09-06 19:17:47.049  3827  3874 I jxcore-log: Total duration:  22842
09-06 19:17:47.049  3827  3874 I jxcore-log: 
09-06 19:17:47.049  3827  3874 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:17:47.049  3827  3874 I jxcore-log: 
,09-06 19:17:47.052  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.052  3827  3874 I jxcore-log: 
09-06 19:17:47.054  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.054  3827  3874 I jxcore-log: 
09-06 19:17:47.056  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.056  3827  3874 I jxcore-log: 
09-06 19:17:47.057  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.057  3827  3874 I jxcore-log: 
09-06 19:17:47.058  3827  3827 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:17:47.058  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.058  3827  3874 I jxcore-log: 
09-06 19:17:47.060  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.060  3827  3874 I jxcore-log: 
09-06 19:17:47.062  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.062  3827  3874 I jxcore-log: 
09-06 19:17:47.064  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.064  3827  3874 I jxcore-log: 
09-06 19:17:47.065  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.065  3827  3874 I jxcore-log: 
09-06 19:17:47.065  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.065  3827  3874 I jxcore-log: 
09-06 19:17:47.066  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.066  3827  3874 I jxcore-log: 
09-06 19:17:47.066  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.066  3827  3874 I jxcore-log: 
09-06 19:17:47.067  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:17:47.067  3827  3874 I jxcore-log: 
09-06 19:17:47.067  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.067  3827  3874 I jxcore-log: 
,09-06 19:17:47.068  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.068  3827  3874 I jxcore-log: 
,09-06 19:17:47.068  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.068  3827  3874 I jxcore-log: 
09-06 19:17:47.069  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.069  3827  3874 I jxcore-log: 
09-06 19:17:47.069  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.069  3827  3874 I jxcore-log: 
09-06 19:17:47.070  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.070  3827  3874 I jxcore-log: 
09-06 19:17:47.070  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.070  3827  3874 I jxcore-log: 
09-06 19:17:47.071  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.071  3827  3874 I jxcore-log: 
,09-06 19:17:47.071  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.071  3827  3874 I jxcore-log: 
,09-06 19:17:47.072  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.072  3827  3874 I jxcore-log: 
09-06 19:17:47.072  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.072  3827  3874 I jxcore-log: 
,09-06 19:17:47.073  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.073  3827  3874 I jxcore-log: 
09-06 19:17:47.073  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.073  3827  3874 I jxcore-log: 
,09-06 19:17:47.074  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:17:47.074  3827  3874 I jxcore-log: 
,09-06 19:17:47.074  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.074  3827  3874 I jxcore-log: 
09-06 19:17:47.075  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.075  3827  3874 I jxcore-log: 
09-06 19:17:47.075  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.075  3827  3874 I jxcore-log: 
09-06 19:17:47.076  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.076  3827  3874 I jxcore-log: 
,09-06 19:17:47.076  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.076  3827  3874 I jxcore-log: 
,09-06 19:17:47.077  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.077  3827  3874 I jxcore-log: 
09-06 19:17:47.077  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:17:47.077  3827  3874 I jxcore-log: 
,09-06 19:17:47.086   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:17:47.086   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 19:17:47.087   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-06 19:17:47.088   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-06 19:17:47.089   872  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-06 19:17:47.098   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:17:47.102   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-06 19:17:47.102   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-06 19:17:47.102   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-06 19:17:47.102   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 19:17:47.102   872  1308 D ConnectivityService:    accepting network in place of null
09-06 19:17:47.103   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:17:47.103   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:17:47.112   872  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217911, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 19:17:47.132   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:17:47.165   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:17:47.173   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-06 19:17:47.173   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:47.182   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:17:47.187   872  4216 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:817::200e
09-06 19:17:47.191   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:17:47.195  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:17:47.197  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:17:47.201  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:17:47.201  3827  3874 I jxcore-log: 
,09-06 19:17:47.210  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:17:47.217  1725  1725 D SystemUpdateService: onCreate
,09-06 19:17:47.223  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:17:47.242  1725  4231 I SystemUpdateService: active receiver: enabled
,09-06 19:17:47.245  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:17:47.250  1725  2390 I iu.UploadsManager: num queued entries: 0
09-06 19:17:47.251  1725  2390 I iu.UploadsManager: num updated entries: 0
,09-06 19:17:47.254  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:17:47.256  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:17:47.258  3936  3936 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:17:47.267   872  4216 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:17:47 GMT], X-Android-Received-Millis=[1473182267266], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473182267238]}
,09-06 19:17:47.268   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 19:17:47.268   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed,
,09-06 19:17:47.268   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:17:47.269   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 19:17:47.272  3936  3936 D SprintDMHelper: simOperator: 
,09-06 19:17:47.273  3936  3936 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,09-06 19:17:47.281  1725  4233 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-06 19:17:47.281  1725  4233 W BaseAppContext: Using Auth Proxy for data requests.
,09-06 19:17:47.283  1725  4233 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:17:47.299  1725  4231 I SystemUpdateService: Already downloaded, skipping offpeak checks.,
,09-06 19:17:47.308  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:17:47.311  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:17:47.324  1725  4231 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 19:17:47.324  1725  4231 I SystemUpdateService: now status is 0 (complete)
,09-06 19:17:47.324  1725  4231 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:17:47.324  1725  4231 I SystemUpdateService: file has been verified
,09-06 19:17:47.338  1725  4231 I SystemUpdateService: OTA package size = 12249756
,09-06 19:17:47.326  1725  2390 I iu.SyncManager: NEXT; no task
,09-06 19:17:47.363  1725  4231 I SystemUpdateService: showing system update notification
,09-06 19:17:47.382  1725  1725 D SystemUpdateService: onDestroy
,09-06 19:17:47.387  1528  2418 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:17:47.390  1528  2418 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-06 19:17:47.390  1528  2418 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 19:17:47.390  1528  2418 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:17:47.397  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:17:47.400  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:17:47.400  3827  3874 I jxcore-log: 
,09-06 19:17:47.412  1725  4233 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-06 19:17:47.445  2277  4237 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:17:47.455  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:17:47.456  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:17:47.456  3827  3874 I jxcore-log: 
,09-06 19:17:47.512  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:17:47.515  3827  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:17:47.515  3827  3874 I jxcore-log: 
,09-06 19:17:47.705  4226  4226 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-06 19:17:47.710  4226  4226 D AndroidRuntime: CheckJNI is OFF
,09-06 19:17:47.752  4226  4226 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-06 19:17:47.798  4226  4226 I Radio-JNI: register_android_hardware_Radio DONE
,09-06 19:17:47.822  4226  4226 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:17:47.834   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-06 19:17:47.835   872   885 I ActivityManager: Killing 3827:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-06 19:17:47.936   872  1986 I WindowState: WIN DEATH: Window{2788c56 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:17:47.937   872  1961 D GraphicsStats: Buffer count: 2
09-06 19:17:47.937   872  1307 D WifiService: Client connection lost with reason: 4
,09-06 19:17:47.965   872   895 W PackageSettings: Skipping PackageSetting{78eb7c4 com.example.hello/10273} due to missing metadata
,09-06 19:17:47.991   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-06 19:17:47.991   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-06 19:17:47.991   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-06 19:17:47.991   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-06 19:17:47.991   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:47.991   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:47.991   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:17:47.991   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-06 19:17:47.992   872   885 I ActivityManager:   Force finishing activity ActivityRecord{39b7393 u0 com.test.thalitest/.MainActivity t2}
09-06 19:17:47.992   872   895 I art     : Starting a blocking GC Explicit
,09-06 19:17:48.002   872  1995 W ActivityManager: Spurious death for ProcessRecord{a3b8752 0:com.test.thalitest/u0a0}, curProc for 3827: null
,09-06 19:17:48.039   872   895 I art     : Explicit concurrent mark sweep GC freed 51981(3MB) AllocSpace objects, 9(220KB) LOS objects, 33% free, 29MB/43MB, paused 807us total 45.364ms
,09-06 19:17:48.082   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-06 19:17:48.086  4226  4226 I art     : System.exit called, status: 0
09-06 19:17:48.086  4226  4226 I AndroidRuntime: VM exiting with result code 0.
,09-06 19:17:48.091   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-06 19:17:48.105   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-06 19:17:48.120  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-06 19:17:48.124  1871  4253 I Keyboard.Facilitator.DecoderInitializer: run()
,09-06 19:17:48.127  4162  4162 D BluetoothMapAppObserver: onReceive
09-06 19:17:48.127  4162  4162 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-06 19:17:48.129  2046  2301 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:17:48.131  1871  4253 I Decoder : createOrResetDecoder
,09-06 19:17:48.133  3658  3658 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-06 19:17:48.134   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:17:48.172   872  1914 I ActivityManager: Start proc 4256:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-06 19:17:48.174  1969  1969 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-06 19:17:48.186  1528  1528 I ConfigService: onCreate
,09-06 19:17:48.206   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:17:48.221  1871  4253 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-06 19:17:48.239  1987  2095 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-06 19:17:48.240   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-06 19:17:48.242   872   884 E PackageManager: Failed to write settings, restoring backup
09-06 19:17:48.242   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-06 19:17:48.242   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-06 19:17:48.242   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-06 19:17:48.242   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-06 19:17:48.242   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-06 19:17:48.242   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.242   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.242   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:17:48.246   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-06 19:17:48.246   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 19:17:48.246   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:17:48.246   872   885 E DropBoxManagerService: 	... 13 more
,09-06 19:17:48.247   872  3964 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3827 uid 10000
,09-06 19:17:48.248  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-06 19:17:48.249  4256  4256 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-06 19:17:48.253   872  1384 I ActivityManager: Start proc 4270:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-06 19:17:48.253  1871  4253 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,--------- beginning of crash
09-06 19:17:48.254  1987  2095 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-06 19:17:48.254  1987  2095 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1987
09-06 19:17:48.254  1987  2095 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.254  1987  2095 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:17:48.256   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:17:48.259  1987  2095 I Process : Sending signal. PID: 1987 SIG: 9
09-06 19:17:48.259   872  4276 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:17:48.259   872  4276 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	,at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:17:48.259   872  4276 E DropBoxManagerService: 	... 5 more
,09-06 19:17:48.268  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-06 19:17:48.268  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-06 19:17:48.270  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-06 19:17:48.270  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-06 19:17:48.270  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-06 19:17:48.270  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-06 19:17:48.271  1871  4253 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-06 19:17:48.271  1871  4253 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-06 19:17:48.271  1871  4253 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-06 19:17:48.272  1871  4253 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-06 19:17:48.272  1871  4253 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-06 19:17:48.272  1871  4253 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-06 19:17:48.338   872   882 D GraphicsStats: Buffer count: 1
,09-06 19:17:48.338   872  1384 I WindowState: WIN DEATH: Window{4409796 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-06 19:17:48.349   872  1992 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1987) has died
,09-06 19:17:48.350   872  1992 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-06 19:17:48.352   872  1992 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:17:48.357  4256  4256 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-06 19:17:48.366   872   885 I ActivityManager: Start proc 4288:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:17:48.384   872  3964 I ActivityManager: Start proc 4301:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-06 19:17:48.414  4256  4299 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:17:48.423  4301  4301 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-06 19:17:48.423  4288  4288 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:48.423  4288  4288 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:17:48.423  4288  4288 D AndroidRuntime: Shutting down VM
,09-06 19:17:48.431  4288  4288 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:17:48.431  4288  4288 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4288
09-06 19:17:48.431  4288  4288 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:17:48.431  4288  4288 E AndroidRuntime: 	... 10 more
09-06 19:17:48.433   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-06 19:17:48.434  4288  4288 I Process : Sending signal. PID: 4288 SIG: 9
,09-06 19:17:48.437   872  4314 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:17:48.437   872  4314 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:17:48.437   872  4314 E DropBoxManagerService: 	... 5 more
,09-06 19:17:48.437  1725  4313 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 19:17:48.445  1725  4313 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 19:17:48.451  1725  4313 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 19:17:48.451  1725  4313 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 19:17:48.456   872  1918 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4288) has died
,09-06 19:17:48.458   872  1918 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:17:48.463  4256  4284 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.463  4256  4284 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.464  4256  4284 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:17:48.472   872   885 I ActivityManager: Start proc 4317:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:17:48.481   872  3964 I ActivityManager: Killing 3715:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-06 19:17:48.490  1528  1528 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-06 19:17:48.491  1528  1528 D AndroidRuntime: Shutting down VM
,09-06 19:17:48.492  1528  1528 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:17:48.492  1528  1528 E AndroidRuntime: Process: com.google.process.gapps, PID: 1528
09-06 19:17:48.492  1528  1528 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-06 19:17:48.492  1528  1528 E AndroidRuntime: 	... 8 more
,09-06 19:17:48.516  4256  4284 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-06 19:17:48.520  4256  4299 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.520  4256  4299 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:17:48.521  4256  4299 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 19:17:48.521  4256  4299 E AndroidRuntime: Process: android.process.acore, PID: 4256
09-06 19:17:48.521  4256  4299 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:17:48.521  4256  4299 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:17:48.522  4256  4284 I Process : Sending signal. PID: 4256 SIG: 9
,09-06 19:17:48.570   872  1377 I ActivityManager: Process android.process.acore (pid 4256) has died
,09-06 19:17:48.571   872  1377 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-06 19:17:48.571   872  4330 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:17:48.571   872  4330 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:17:48.571   872  4330 E DropBoxManagerService: 	... 5 more
,09-06 19:17:48.577   872  1995 W ActivityManager: Can't find mystery application for Crash from pid=4256 uid=10005: android.os.BinderProxy@e61fdc3
09-06 19:17:48.578  1528  1528 I Process : Sending signal. PID: 1528 SIG: 9
09-06 19:17:48.578   872  1995 E DropBoxManagerService: Can't write: system_server_crash
09-06 19:17:48.578   872  1995 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:17:48.578   872  1995 E DropBoxManagerService: 	... 11 more

```
